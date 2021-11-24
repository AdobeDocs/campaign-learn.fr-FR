---
title: Création de workflows de validation - Introduction
description: Découvrez comment configurer différents workflows de validation.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: f25e3e7553d23aacf96c0f05e1ad78ee783192ff
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 68%

---

# Création de workflows de validation - Introduction

Adobe Campaign offre plusieurs options aux spécialistes marketing pour examiner et fournir le contenu des diffusions, la cible des campagnes, l&#39;extraction des données et les validations de budget.

## Prérequis {#prerequisite}

Avant d&#39;activer les étapes de validation, l&#39;équipe marketing doit définir les différents validants :

* Le rôle de validant Adobe Campaign dans une activité de validation peut être soit un seul validant (opérateur), soit un groupe de validants (rôle opérateur).
* Pour permettre aux développeurs de campagnes de sélectionner les validants dans une campagne ou une diffusion, les validants et groupes de validants doivent être configurés dans Adobe Campaign par un administrateur.

## Paramétrer les validations {#configuring-approvals}

Campaign propose trois niveaux de validations différents :

1. [Configurer les validations pour les campagnes](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Si vous disposez du même ensemble de validants pour toutes les diffusions de votre workflow d&#39;opération, appliquez la fonctionnalité de validation de l&#39;opération, en configurant les validations et les validants au niveau de l&#39;opération. Les tâches de validation et les validants sont redirigés vers chaque activité de diffusion de votre workflow une fois celui-ci exécuté.
2. [Configurer les validations des diffusions](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): Vous pouvez également configurer les validations au niveau de la diffusion. Si les étapes de validation des diffusions et les validants diffèrent des étapes de validation de le la campagne et des validants, les paramètres de la diffusion remplacent les paramètres de la campagne.
3. [Créer un processus d’approbation dans un workflow](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): L&#39;activité Validation permet la création d&#39;un processus de validation au sein d&#39;un workflow. Ainsi, la logique de sélection du ciblage peut être validée avant le lancement de la diffusion. Cela permet également la validation à plusieurs niveaux dans le workflow, si nécessaire.

Pour plus d&#39;informations, consultez la [documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=fr).
