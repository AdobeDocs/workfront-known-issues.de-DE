---
title: 'Berichte: Berichtfilter gibt nicht die erwarteten Ergebnisse zurück'
description: Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück. Eine Umgehungslösung ist verfügbar.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# Berichte: Berichtfilter gibt nicht die erwarteten Ergebnisse zurück

>[!NOTE]
>
>Dieses Problem wurde geschlossen.

Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück.

Dies kann vorkommen, wenn der Filter so konfiguriert ist, dass er Ergebnisse mit bestimmten Kriterien zurückgibt, und außerdem eine ODER-Regel enthält, die Ergebnisse zurückgibt, die eine Teilmenge derselben Kriterien sind.

**Umgehungslösung**

Stellen Sie sicher, dass die ODER-Blöcke des Filters keine identischen Auswertungskriterien enthalten.

_Erste Meldung am Dienstag, 11. März 2024._
