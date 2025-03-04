---
title: 'Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook'
description: Wenn ein(e) Benutzende(r) die Workfront for Outlook-Integration verwendet, wird möglicherweise ein Fehler angezeigt.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook

Wenn ein(e) Benutzende(r) die Workfront for Outlook-Integration verwendet, wird möglicherweise der folgende Fehler angezeigt:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Problemumgehung**


Um diesen Fehler zu beheben, müssen Sie ältere Microsoft 365-Token für Ihr Unternehmen aktivieren. Da dies in Microsoft 365 erfolgen muss, kann Workfront diese Token für Ihr Unternehmen nicht aktivieren.

Anweisungen zur Aktivierung veralteter Microsoft 365-Token finden Sie unter [Aktivieren oder Deaktivieren veralteter Exchange Online-Token](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) in der Dokumentation zu Microsoft.

Weitere Informationen zu älteren Token finden Sie unter [Kann ich ältere Exchange Online-Token wieder aktivieren?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) in der Dokumentation zu Microsoft.


_Erste Meldung am 3. März 2025, 2024._
