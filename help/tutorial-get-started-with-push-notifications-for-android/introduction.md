---
title: Prise en main des notifications push pour Android - Introduction
description: Ce tutoriel vous guide tout au long des étapes nécessaires à l'envoi de notifications push depuis Adobe Campaign et à la réception de ces notifications dans votre application Android™.
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
TQID: https://experienceleague.adobe.com/llhU9-u6ri1njd6wSTE1CTZTmYerQDz7-R2WY4ahWzs
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bdid: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2: id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 331
ht-degree: 100%

---

# Prise en main des notifications push pour Android - Introduction

Adobe Campaign vous permet d&#39;envoyer des notifications personnalisées et segmentés [!DNL push] aux appareils mobiles [!DNL iOS] et [!DNL Android™]. Ce tutoriel vous guide tout au long des étapes nécessaires à l&#39;envoi des notifications [!DNL push] d&#39;Adobe Campaign à une application [!DNL Android™].

## Conditions préalables requises

Avant de pouvoir commencer, vous devez disposer des éléments suivants :

1) **Application mobile Android™**

   Ce tutoriel ne décrit pas les étapes détaillées requises pour configurer l&#39;application mobile. Vous devez disposer d&#39;une application mobile **[!DNL Android™]avec le [!DNL Campaign SDK] intégré**.

   Vous trouverez une description détaillée des étapes requises dans la documentation du produit :

   [Intégrer le SDK Campaign dans l’application mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=fr)

2) Package **[!DNL Mobile App channel]installé**

   Le package [!DNL Mobile App channel] doit être installé sur votre instance [!DNL Campaign]. La vidéo suivante explique comment vérifier si [!DNL Mobile App channel] est installé sur votre instance et, dans le cas contraire, comment l’installer.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## Présentation du tutoriel

L&#39;objectif consiste à envoyer une notification promotionnelle personnalisée [!DNL push] aux abonnés de l&#39;application mobile [!DNL Neotrip] [!DNL Android™]. L&#39;application [!DNL Neotrip] est configurée avec la balise [!DNL Campaign SDK] et la balise [!DNL Mobile App channel] est activée sur l&#39;instance [!DNL Campaign].

Les étapes de configuration suivantes sont requises :

### Étape 1 : étendre le schéma d&#39;abonnement de l&#39;application pour personnaliser les notifications [!DNL push].

Pour pouvoir personnaliser la notification [!DNL push], vous devez d&#39;abord [étendre le schéma d&#39;abonnement de l&#39;application](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Cela permet au système de stocker les valeurs de personnalisation reçues de l&#39;application lorsque l&#39;utilisateur s&#39;abonne au service.

### Étape 2 : configurer le service Android™ et créer l&#39;application mobile dans Campaign

Ensuite, [le service Android™ doit être configuré et l&#39;application mobile créée dans Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). Au cours de cette étape, l&#39;application [!DNL Neotrip] est définie comme cible de la notification push.

### Étape 3 : configurer et envoyer la notification push

Désormais, la notification push est prête à être [configurée et envoyée](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Commencer le tutoriel

Étape 1 : [étendre le schéma d&#39;abonnement de l&#39;application](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
