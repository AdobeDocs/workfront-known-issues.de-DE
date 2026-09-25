---
title: 'Workfront Fusion: Ausgabeformatierung für Datumsangaben'
description: Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik innerhalb eines Zuordnungsbereichs ab.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion: Ausgabeformatierung für Datumsangaben

Wenn Datumsangaben als Zeichenfolgen ausgegeben werden, kann das Datum als UTC- oder ISO-Zeichenfolge ausgegeben werden. Dies hängt von der Logik im Zuordnungsbedienfeld ab.

* Wenn ein Datum in einer Funktion mit einer Zeichenfolge verknüpft ist, wird die Zeichenfolge im **UTC**-Format ausgegeben.
* Wenn das Datum nicht in einer Funktion verknüpft ist, wird es als **ISO-Zeichenfolge** ausgegeben.

Kunden sollten die Funktionen `toString` (für ISO) oder `formatDate` verwenden, um sicherzustellen, dass die Ausgaben dem benötigten Format entsprechen.
