---
title: Créer un workflow d'export (Partie 1) - Rechercher la date de dernière modification pour une liste de destinataires
description: Dans cette première partie du tutoriel Créer un workflow d’exportation , apprenez à créer un workflow qui recherche la date de dernière modification pour une liste de destinataires créée à partir d’un segment Experience Platform.
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
source-git-commit: c685927a01d08ae6533399ad2466967c6cd3f9fd
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Créer un workflow d&#39;export (Partie 1) - Rechercher la date de dernière modification pour une liste de destinataires

Dans cette première partie du tutoriel Créer un workflow d’exportation , apprenez à créer un workflow qui recherche la date de dernière modification pour une liste de destinataires créée à partir d’un segment Experience Platform.

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12)

## Assets

JavaScript pour établir des plages de dates :

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## Vidéo suivante

[Créer un workflow d&#39;export (Partie 2) - Extraction, formatage et enregistrement des données dans un compte externe](extract-format-save-data-to-external-account.md)
