---
title: Créer un workflow d'export (Partie 2) - Extraction, formatage et enregistrement des données dans un compte externe
description: Dans cette deuxième partie du tutoriel Créer un workflow d’exportation , vous apprenez à formater les données à exporter et à enregistrer les données dans un compte externe.
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: 85a32e0415c02ccfff9a22021ed77872ad726bf7
workflow-type: tm+mt
source-wordcount: '92'
ht-degree: 1%

---

# Créer un workflow d&#39;export (partie 2) : Extraction, formatage et enregistrement de données dans un compte externe

Dans cette deuxième partie du tutoriel Créer un workflow d’exportation , vous apprenez à formater les données à exporter et à enregistrer les données dans un compte externe.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12)

## Assets

JavaScript : Enregistrer la date

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
