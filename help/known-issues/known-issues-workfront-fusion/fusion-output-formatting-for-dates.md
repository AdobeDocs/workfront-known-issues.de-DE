---
title: 'Workfront Fusion: Ausgabeformatierung für Datumsangaben'
description: Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik innerhalb eines Zuordnungsbereichs ab.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%

---

# Workfront Fusion: Ausgabeformatierung für Datumsangaben

Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik im Zuordnungsbedienfeld ab.

* Wenn ein Datum in einer Funktion mit einer Zeichenfolge verknüpft ist, wird die Zeichenfolge im **UTC**-Format ausgegeben.
* Wenn das Datum nicht in einer Funktion verknüpft ist, wird es als **ISO-Zeichenfolge** ausgegeben.

Kunden sollten die Funktionen `toString` (für ISO) oder `formatDate` verwenden, um sicherzustellen, dass die Ausgaben dem benötigten Format entsprechen.
