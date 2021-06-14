---
title: Prise en main des notifications push pour Android - Introduction
description: Ce tutoriel vous guide tout au long des étapes nécessaires à l'envoi de notifications push depuis Adobe Campaign et à la réception de ces notifications dans votre application Android™.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 100%

---

# Prise en main des notifications push pour Android - Introduction

Adobe Campaign vous permet d&#39;envoyer des notifications personnalisées et segmentés [!DNL push] aux appareils mobiles [!DNL iOS] et [!DNL Android™]. Ce tutoriel vous guide tout au long des étapes nécessaires à l&#39;envoi des notifications [!DNL push] d&#39;Adobe Campaign à une application [!DNL Android™].

## Conditions préalables requises

Avant de pouvoir commencer, vous devez disposer des éléments suivants :

1) **Application mobile Android™**

   Ce tutoriel ne décrit pas les étapes détaillées requises pour configurer l&#39;application mobile. Vous devez disposer d&#39;une application mobile **[!DNL Android™]avec le [!DNL Campaign SDK] intégré**.

   Vous trouverez une description détaillée des étapes requises dans la documentation du produit :

   [Intégrer le SDK Campaign dans l&#39;application mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=fr)

2) Package **[!DNL Mobile App channel]installé**

   Le package [!DNL Mobile App channel] doit être installé sur votre instance [!DNL Campaign]. La vidéo suivante explique comment vérifier si [!DNL Mobile App channel] est installé sur votre instance et, dans le cas contraire, comment l&#39;installer.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

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
