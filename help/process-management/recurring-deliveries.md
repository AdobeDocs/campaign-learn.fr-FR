---
title: Configuration de campagnes e-mail récurrentes et au fil de l'eau
description: Découvrez comment configurer une diffusion récurrente et au fil de l'eau et comprendre les différences entre les deux approches.
feature: Workflows
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: ht
source-wordcount: '239'
ht-degree: 100%

---


# Configuration de campagnes e-mail récurrentes et au fil de l&#39;eau

Ce tutoriel explique comment configurer une diffusion récurrente et au fil de l&#39;eau et les différences entre les deux approches.

## Suivi des diffusions récurrentes et au fil de l&#39;eau {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et au fil de l&#39;eau diffèrent dans la façon dont les données de contact sont gérées :

* Une **diffusion au fil de l&#39;eau** permet d&#39;ajouter de nouveaux destinataires à une diffusion existante, ce qui évite d&#39;avoir à créer une diffusion chaque fois qu&#39;un nouveau destinataire est ajouté. Vous pouvez mettre à jour le contenu créatif directement dans le workflow de campagne et le modèle sera mis à jour dans le dossier Ressource du modèle de diffusion.

   Une diffusion au fil de l&#39;eau crée une diffusion et des logs de diffusion UNIQUES (broadLog) et des logs de tracking qui font référence à l&#39;ajout d&#39;une diffusion chaque fois qu&#39;elle s&#39;exécute.

![Diffusion au fil de l&#39;eau](/help/assets/delivery_continuous.jpg)

* Une **diffusion récurrente** crée une instance de diffusion chaque fois qu&#39;elle s&#39;exécute. Par exemple, si le workflow est planifié pour s&#39;exécuter une fois par semaine, 52 diffusions seront créées en une année. Cela signifie également que le broadlog et les logs de tracking sont séparés par instance de diffusion.

![Diffusion récurrente](/help/assets/delivery_recurring.jpg)

## Configuration d&#39;une diffusion récurrente {#how-to-set-up-a-recurring-delivery}

La vidéo explique comment configurer une diffusion récurrente et une activité Planificateur.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Comment configurer une diffusion au fil de l&#39;eau{#how-to-set-up-a-continuous-delivery}

Cette vidéo montre comment configurer une diffusion au fil de l&#39;eau avec une requête incrémentale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
