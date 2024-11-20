---
title: "Workfront: ZScalar-Einstellungen können zu Leistungseinbußen führen"
description: "Der Webdienst von ZScalar verwendet standardmäßig http/1.1, was zu Leistungseinbußen in Workfront führen kann."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront: ZScalar-Einstellungen können zu Leistungseinbußen führen

>[!NOTE]
>
>Dies ist ein Problem mit ZScalar und wird von Workfront nicht behoben.

Der Webdienst von ZScalar verwendet standardmäßig `http/1.1`, was zu Leistungseinbußen in Workfront führen kann.

**Problemumgehung**

Konfigurieren Sie Ihre ZScalar-Software für die Verwendung von `http/2`. Dies kann nicht in Workfront konfiguriert werden.

Informationen zu `http/2` finden Sie in der ZScalar-Dokumentation.

_Erste Meldung am Dienstag, 18. November 2024._
