---
title: "Workfront Fusion: Ausgabeformatierung für Datumsangaben"
description: "Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik in einem Zuordnungsbereich ab."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: Ausgabeformatierung für Datumsangaben

Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik in einem Zuordnungsbereich ab:

* Wenn ein Datum in einer Funktion mit einer Zeichenfolge verknüpft ist, wird die Zeichenfolge in **UTC** Format.
* Wenn das Datum nicht in einer Funktion verbunden ist, wird es als **ISO-Zeichenfolge**.

Kunden sollten die `toString` (für ISO) oder `formatDate` Funktionen, um sicherzustellen, dass die Ausgaben dem Format entsprechen, das sie benötigen.
