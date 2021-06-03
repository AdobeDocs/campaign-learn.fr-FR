---
title: Création de workflows de validation
description: Découvrez comment configurer différents workflows de validation d’approbation.
feature: Workflows, approbations
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Création de workflows de validation

Adobe Campaign offre plusieurs options aux marketeurs pour examiner et fournir le contenu des diffusions, la cible des campagnes, l’extraction des données et les validations de budget.

Ce tutoriel explique comment configurer différents workflows de validation d’approbation.

## Prérequis {#prerequisite}

Avant d&#39;activer les étapes de validation, l&#39;équipe marketing doit définir les différents opérateurs validants :

* Le rôle de réviseur Adobe Campaign dans une activité de validation peut être soit un seul réviseur (opérateur), soit un groupe de réviseurs (rôle opérateur).
* Pour permettre aux développeurs d&#39;opérations de sélectionner les opérateurs validants dans une opération ou une diffusion, les opérateurs validants et validants doivent être paramétrés dans Adobe Campaign par un administrateur.

## Configuration des validations pour les campagnes {#configuring-approvals-for-campaigns}

Si vous disposez du même ensemble de validants pour toutes les diffusions de votre workflow d&#39;opération, appliquez la fonctionnalité de validation de l&#39;opération, en configurant les validations et les validants au niveau de l&#39;opération. Les tâches de validation et les validants sont redirigés vers chaque activité de diffusion de votre workflow une fois le workflow exécuté.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configuration des validations pour les diffusions {#configuring-approvals-for-deliveries}

Vous pouvez également configurer les validations au niveau de la diffusion. Si les étapes de validation des diffusions et les opérateurs validants diffèrent des étapes de validation de l&#39;opération et des opérateurs validants, les paramètres de la diffusion remplacent les paramètres de l&#39;opération.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Paramétrer une activité de validation {#configuring-an-approval-activity}

Contrairement à la diffusion ou aux validations de campagne, l&#39;activité de validation permet de créer un processus de validation au sein d&#39;un workflow. Ainsi, la logique de sélection du ciblage peut être validée avant le lancement de la diffusion. Il permet également l’approbation à plusieurs niveaux dans le workflow, si nécessaire.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Pour plus d’informations, voir la [Documentation sur l’approbation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
