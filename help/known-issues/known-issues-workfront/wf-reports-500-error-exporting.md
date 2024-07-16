---
title: '„Berichte: 500-Fehler beim Exportieren eines Berichts“'
description: Beim Versuch, einen Bericht zu exportieren, wird der Bericht nicht exportiert und es wird ein Fehler angezeigt. Eine Problemumgehung ist verfügbar.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# Berichte: 500-Fehler beim Export eines Berichts

>[!NOTE]
>
>Dieses Problem wurde am Samstag, 5. April 2024 behoben.

Beim Versuch, einen Bericht zu exportieren, wird der Bericht nicht exportiert und es wird der folgende Fehler angezeigt:

500: „com.attask.biz.Parameter.getDisplayType()“ kann nicht aufgerufen werden, da „Parameter“ null ist /attask/api-internal/report/export

Dies tritt auf, wenn der Bericht auf ein benutzerdefiniertes Währungsfeld auf Projektebene verweist.

**Problemumgehung**

Entfernen Sie die Spalte, die auf das benutzerdefinierte Währungsfeld verweist, und exportieren Sie den Bericht erneut.

_Erste Meldung am Freitag, 4. April 2024._
