---
title: Créer des diffusions par e-mail récurrentes et continues
description: Découvrez comment configurer une diffusion récurrente et continue et comprendre les différences entre les deux approches.
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: 05b49ca012d0d505b117a2fb6b12ff41b51be63e
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Créer des diffusions par e-mail récurrentes et continues

Ce tutoriel explique comment configurer une diffusion récurrente et continue et les différences entre les deux approches.

## Suivi des diffusions récurrentes et au fil de l&#39;eau {#recurring-and-continuous-delivery-tracking}

Les diffusions récurrentes et au fil de l&#39;eau diffèrent dans la façon dont les données de contact sont gérées :

* Une **diffusion au fil de l&#39;eau** permet d&#39;ajouter de nouveaux destinataires à une diffusion existante, ce qui évite d&#39;avoir à créer une diffusion chaque fois qu&#39;un nouveau destinataire est ajouté. Vous pouvez mettre à jour le contenu créatif directement dans le workflow de campagne et le modèle sera mis à jour dans le dossier Ressource du modèle de diffusion.

  Une diffusion au fil de l&#39;eau crée une diffusion et des logs de diffusion UNIQUES (broadLog) et des logs de tracking qui font référence à l&#39;ajout d&#39;une diffusion chaque fois qu&#39;elle s&#39;exécute.

![Diffusion au fil de l&#39;eau](/help/assets/delivery_continuous.jpg)

* Une **diffusion récurrente** crée une instance de diffusion chaque fois qu&#39;elle s&#39;exécute. Par exemple, si le workflow est planifié pour s&#39;exécuter une fois par semaine, 52 diffusions seront créées en une année. Cela signifie également que le broadlog et les logs de tracking sont séparés par instance de diffusion.

![Diffusion récurrente](/help/assets/delivery_recurring.jpg)

## Configuration d’une diffusion récurrente {#how-to-set-up-a-recurring-delivery}

La vidéo explique comment configurer une diffusion récurrente et une activité Planificateur.

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## Comment configurer une diffusion au fil de l’eau {#how-to-set-up-a-continuous-delivery}

Cette vidéo montre comment configurer une diffusion au fil de l&#39;eau avec une requête incrémentale.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
