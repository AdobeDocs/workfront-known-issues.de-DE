---
title: 'Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook'
description: Wenn Benutzende die Workfront for Outlook-Integration verwenden, wird möglicherweise ein Fehler angezeigt.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: fff5428fd0c9a50f20ded044bf0ab251dfde5a6e
workflow-type: ht
source-wordcount: '127'
ht-degree: 100%

---

# Integrationen: OutlookIdentityToken-Fehler bei Verwendung von Workfront für Outlook

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
