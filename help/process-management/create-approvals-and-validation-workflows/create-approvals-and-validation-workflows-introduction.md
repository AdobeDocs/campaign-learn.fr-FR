---
title: Création de validations et de workflows de validation - Introduction
description: Découvrez comment configurer différents workflows de validation.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: ca13bdbd7d95e6646aff88af595e866bd3666bb2
workflow-type: ht
source-wordcount: '262'
ht-degree: 100%

---

# Création de validations et de workflows de validation - Introduction

Adobe Campaign offre plusieurs options aux spécialistes marketing pour examiner et fournir le contenu des diffusions, la cible des campagnes, l’extraction des données et les validations de budget. Découvrez comment [gérer les validations](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Prérequis {#prerequisite}

Avant d&#39;activer les étapes de validation, l&#39;équipe marketing doit définir les différents validants :

* Le rôle de validant Adobe Campaign dans une activité de validation peut être soit un seul validant (opérateur), soit un groupe de validants (rôle opérateur).
* Pour permettre aux développeurs de campagnes de sélectionner les validants dans une campagne ou une diffusion, les validants et groupes de validants doivent être configurés dans Adobe Campaign par un administrateur.

## Configuration des validations {#configuring-approvals}

1. [Configuration des validations pour les campagnes](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md) :
Si vous disposez du même jeu de validants pour toutes les diffusions de votre workflow de campagne, appliquez la fonctionnalité de validation de la campagne, en configurant les validations et les validants au niveau de la campagne. Les tâches de validation et les validants sont redirigés vers chaque activité de diffusion de votre workflow une fois celui-ci exécuté.
2. [Configuration des validations pour les diffusions](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md) :
Vous pouvez également configurer les validations au niveau de la diffusion. Si les étapes de validation et les validants des diffusions diffèrent de ceux de la campagne, les paramètres de la diffusion remplacent ceux de la campagne.
3. [Création d’un processus de validation dans un workflow](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md) :
L’activité Validation permet la création d’un processus de validation au sein d’un workflow. Ainsi, la logique de sélection du ciblage peut être validée avant le lancement de la diffusion. Cela permet également la validation à plusieurs niveaux dans le workflow, si nécessaire.

Pour plus d’informations, consultez la [documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=fr).
