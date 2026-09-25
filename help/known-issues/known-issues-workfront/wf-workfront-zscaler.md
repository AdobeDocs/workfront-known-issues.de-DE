---
title: 'Workfront: ZScaler-Einstellungen können die Leistung beeinträchtigen'
description: Der Web-Dienst von ZScaler verwendet standardmäßig http/1.1, was zu Leistungseinbußen in Workfront führen kann.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront: ZScaler-Einstellungen können die Leistung beeinträchtigen

>[!NOTE]
>
>Dies ist ein Problem mit ZScaler und wird von Workfront nicht behoben.

Der Web-Dienst von ZScaler verwendet standardmäßig `http/1.1`, was zu Leistungseinbußen in Workfront führen kann.

**Umgehungslösung**

Konfigurieren Sie Ihre ZScaler-Software für die Verwendung von `http/2`. Dies kann nicht in Workfront konfiguriert werden.

Informationen zu `http/2` finden Sie in der Dokumentation zu ZScaler.

_Erste Meldung am Dienstag, 18. November 2024._
