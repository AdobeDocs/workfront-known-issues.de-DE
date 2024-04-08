---
title: '„Berichte: 500-Fehler beim Exportieren eines Berichts“'
description: Wenn ein Benutzer versucht, einen Bericht zu exportieren, wird der Bericht nicht exportiert und dem Benutzer wird ein Fehler angezeigt. Eine Problemumgehung ist verfügbar.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 27%

---

# Berichte: 500-Fehler beim Export eines Berichts

>[!NOTE]
>
>Dieses Problem wurde am Samstag, 5. April 2024 behoben.

Wenn ein Benutzer versucht, einen Bericht zu exportieren, wird der Bericht nicht exportiert und der Benutzer sieht den folgenden Fehler:

500: &quot;com.attask.biz.Parameter.getDisplayType()&quot;kann nicht aufgerufen werden, da &quot;parameter&quot;null ist /attask/api-internal/report/export

Dies tritt auf, wenn der Bericht auf ein Feld mit benutzerdefinierter Währung auf Projektebene verweist.

**Problemumgehung**

Entfernen Sie die Spalte, die auf das Feld für die benutzerdefinierte Währung verweist, und exportieren Sie den Bericht erneut.

_Erste Meldung am Freitag, 4. April 2024._
