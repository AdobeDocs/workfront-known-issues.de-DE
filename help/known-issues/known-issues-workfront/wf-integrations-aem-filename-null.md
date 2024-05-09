---
title: '„Integrationen: Dateiname ist ‚null‘, wenn eine Datei über eine Integration an AEM gesendet wird“'
description: „Wenn eine große Datei (über 100 MB) über die Workfront-Integration an Adobe Experience Manager gesendet wird, ist der Dateiname in AEM ‚null‘. '
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: e24d266002a913e5c6e2d5e40e9dad36deff541a
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 52%

---

# Integrationen: Dateiname ist &quot;null&quot;, wenn an die Dokumentintegration gesendet

>[!NOTE]
>
>Dieses Problem wurde am Donnerstag, 8. Mai 2024 behoben.

Wenn eine große Datei (über 100 MB) über eine Workfront-Integration an einen Dokumentanbieter gesendet wird, lautet der Dateiname im Dokumentenanbieter &quot;null&quot;.

Dies wurde sowohl bei ZIP- als auch bei TIF-Dateien gemeldet.

**Problemumgehung**

Führen Sie einen der folgenden Schritte aus:

* Weisen Sie den Dokumentnamen dem Titel im Dokumentanbieter zu.
* Geben Sie den Dateinamen direkt im Dokumentanbieter ein.

_Erste Meldung am Mittwoch, 23. April 2024._

