---
title: '„Workfront Fusion: Es kann keine Verbindung zu Google hergestellt werden“'
description: Wenn ein(e) Benutzende(r) versucht, eine Verbindung in einem der Google-Connectoren (z. B. Google Tabellen oder Google Drive) herzustellen, wird die Verbindung nicht erstellt und verschiedene Fehlermeldungen werden angezeigt.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '109'
ht-degree: 94%

---

# [!DNL Workfront Fusion]: Es kann keine Verbindung zu [!DNL Google] hergestellt werden

>[!NOTE]
>
>Dieses Problem wurde am 9. Januar 2023 behoben.

Wenn ein(e) Benutzende(r) versucht, eine Verbindung in einem der [!DNL Google]-Connectoren (z. B. [!DNL Google Sheets] oder [!DNL Google Drive]) herzustellen, wird ein Fenster mit der folgenden Fehlermeldung angezeigt:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Wenn der/die Benutzende dieses Fenster schließt, schlägt die Verbindung fehl und in [!DNL Fusion] wird die folgende Fehlermeldung angezeigt:

„[!UICONTROL Fehler: Die Anfrage schlug aufgrund des Fehlens einer früheren Anfrage fehl. Kein Zugriffs-Token angegeben.]“

_Erste Meldung am 21. November 2022._
