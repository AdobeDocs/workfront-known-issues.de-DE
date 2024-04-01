---
title: "Berichte: Berichtsfilter gibt keine erwarteten Ergebnisse zurück"
description: '"Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück. Eine Problemumgehung ist verfügbar.“'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: e28899711b95aea10ef43c45498db7aa73f7a784
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 14%

---


# Berichte: Berichtsfilter gibt keine erwarteten Ergebnisse zurück

>[!NOTE]
>
>Dieses Problem wurde geschlossen.

Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück.

Dies kann vorkommen, wenn der Filter so konfiguriert ist, dass er Ergebnisse mit bestimmten Kriterien zurückgibt, und eine ODER-Regel enthält, die Ergebnisse zurückgibt, die eine Untergruppe derselben Kriterien sind.

**Problemumgehung**

Stellen Sie sicher, dass die ODER-Blöcke Ihres Filters keine identischen Bewertungskriterien enthalten.

_Erste Meldung am Dienstag, 11. März 2024._
