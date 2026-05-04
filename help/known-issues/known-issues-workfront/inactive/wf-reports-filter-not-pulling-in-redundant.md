---
title: 'Berichte: Berichtfilter gibt nicht die erwarteten Ergebnisse zurück'
description: Ein Filter in einem Bericht gibt möglicherweise nicht alle erwarteten Ergebnisse zurück. Eine Umgehungslösung ist verfügbar.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
