---
title: 'Berichte: Berichtfilter gibt nicht die erwarteten Ergebnisse zurück'
description: Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück. Eine Problemumgehung ist verfügbar.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
source-git-commit: 9457b520c469c729f8727b1efd21bbde117b9546
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 100%

---

# Berichte: Berichtfilter gibt nicht die erwarteten Ergebnisse zurück

>[!NOTE]
>
>Dieses Problem wurde geschlossen.

Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück.

Dies kann vorkommen, wenn der Filter so konfiguriert ist, dass er Ergebnisse mit bestimmten Kriterien zurückgibt, und außerdem eine ODER-Regel enthält, die Ergebnisse zurückgibt, die eine Teilmenge derselben Kriterien sind.

**Problemumgehung**

Stellen Sie sicher, dass die ODER-Blöcke des Filters keine identischen Auswertungskriterien enthalten.

_Erste Meldung am Dienstag, 11. März 2024._
