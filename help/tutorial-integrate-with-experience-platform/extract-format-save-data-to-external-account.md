---
title: Créer un workflow d’exportation (Partie 2) - Extraction, formatage et enregistrement des données dans un compte externe
description: Dans cette deuxième partie du tutoriel Créer un workflow d’exportation, vous allez apprendre à formater les données à exporter et à les enregistrer dans un compte externe.
feature: Data Management, Workflows
jira: KT-8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 100%

---

# Créer un workflow d’exportation (Partie 2) : Extraction, formatage et enregistrement de données dans un compte externe

Dans cette deuxième partie du tutoriel Créer un workflow d’exportation, vous allez apprendre à formater les données à exporter et à les enregistrer dans un compte externe.

>[!VIDEO](https://video.tv.adobe.com/v/3449901?quality=12&learn=on&captions=fre_fr){transcript=true}

## Assets

JavaScript : Enregistrer la date

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
