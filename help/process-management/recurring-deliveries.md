---
title: Configuration de campagnes email récurrentes et continues
description: Découvrez comment configurer une diffusion récurrente et continue et comprendre les différences entre les deux approches.
feature: Workflows
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 21%

---


# Configuration de campagnes email récurrentes et continues

Ce tutoriel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches.

## Suivi des diffusions récurrentes et continues {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et continues diffèrent dans la façon dont les données de contact sont gérées :

* La **diffusion continue** permet d&#39;ajouter de nouveaux destinataires à une diffusion existante et d&#39;éviter d&#39;avoir à créer une diffusion chaque fois qu&#39;un nouveau destinataire est ajouté. Vous pouvez mettre à jour le contenu créatif directement dans le workflow de l&#39;opération et le mettre à jour dans le dossier des ressources du modèle de diffusion.

   Une diffusion au fil de l’eau crée une diffusion et des logs de diffusion UNIQUES (broadLog) et des logs de tracking, qui font référence à une diffusion, sont ajoutés à chaque exécution.

![Diffusion (au fil de l’eau)](/help/assets/delivery_continuous.jpg)

* Une **diffusion récurrente** crée une instance de diffusion à chaque exécution. Par exemple, si le workflow est planifié pour s’exécuter une fois par semaine, 52 diffusions seront créées en une année. Cela signifie également que le broadlog et les logs de tracking sont séparés par une instance de diffusion.

![Diffusion récurrente](/help/assets/delivery_recurring.jpg)

## Configuration d’une diffusion récurrente {#how-to-set-up-a-recurring-delivery}

La vidéo explique comment configurer une diffusion récurrente et une activité Planificateur.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Comment configurer une diffusion (au fil de l’eau){#how-to-set-up-a-continuous-delivery}

Cette vidéo montre comment configurer une diffusion (au fil de l’eau) avec une requête incrémentale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
