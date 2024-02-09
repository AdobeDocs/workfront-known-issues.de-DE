---
title: "Workfront Fusion: Ausgabeformatierung für Datumsangaben"
description: "Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik im Zuordnungsbedienfeld ab."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion: Ausgabeformatierung für Datumsangaben

Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik im Zuordnungsbedienfeld ab.

* Wenn ein Datum in einer Funktion mit einer Zeichenfolge verknüpft ist, wird die Zeichenfolge im **UTC**-Format ausgegeben.
* Wenn das Datum nicht in einer Funktion verknüpft ist, wird es als **ISO-Zeichenfolge** ausgegeben.

Kunden sollten die Funktionen `toString` (für ISO) oder `formatDate` verwenden, um sicherzustellen, dass die Ausgaben dem benötigten Format entsprechen.
