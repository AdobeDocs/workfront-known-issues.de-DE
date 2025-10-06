---
title: 'Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook'
description: Wenn Benutzende die Workfront for Outlook-Integration verwenden, wird möglicherweise ein Fehler angezeigt.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 87%

---

# Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook

>[!NOTE]
>
>Die Integration von Workfront für Outlook ist nicht mehr verfügbar. Dieser Artikel wird in naher Zukunft entfernt.

Wenn Benutzende die Workfront for Outlook-Integration verwenden, wird möglicherweise der folgende Fehler angezeigt:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Umgehungslösung**


Um diesen Fehler zu beheben, müssen Sie Microsoft 365-Legacytoken für Ihr Unternehmen aktivieren. Da dies in Microsoft 365 erfolgen muss, kann Workfront diese Token nicht für Ihr Unternehmen aktivieren.

Anweisungen zum Aktivieren von Microsoft 365-Legacytoken finden Sie unter [Aktivieren oder Deaktivieren von Legacytoken](https://learn.microsoft.com/de-de/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) in der Dokumentation zu Microsoft.

Weitere Informationen zu Legacytoken finden Sie unter [Kann ich Exchange Online Legacytoken wieder aktivieren?](https://learn.microsoft.com/de-de/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) in der Dokumentation zu Microsoft.


_Erste Meldung am 3. März 2025, 2024._
