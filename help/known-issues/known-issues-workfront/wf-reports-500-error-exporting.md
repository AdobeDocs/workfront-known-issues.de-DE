---
title: "Berichte: 500-Fehler beim Export eines Berichts"
description: '"Wenn ein Benutzer versucht, einen Bericht zu exportieren, wird der Bericht nicht exportiert und dem Benutzer wird ein Fehler angezeigt. Eine Problemumgehung ist verfügbar.“'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# Berichte: 500-Fehler beim Export eines Berichts

Wenn ein Benutzer versucht, einen Bericht zu exportieren, wird der Bericht nicht exportiert und der Benutzer sieht den folgenden Fehler:

500: &quot;com.attask.biz.Parameter.getDisplayType()&quot;kann nicht aufgerufen werden, da &quot;parameter&quot;null ist /attask/api-internal/report/export

Dies tritt auf, wenn der Bericht auf ein Feld mit benutzerdefinierter Währung auf Projektebene verweist.

**Problemumgehung**

Entfernen Sie die Spalte, die auf das Feld für die benutzerdefinierte Währung verweist, und exportieren Sie den Bericht erneut.

_Erste Meldung am Freitag, 4. April 2024._

