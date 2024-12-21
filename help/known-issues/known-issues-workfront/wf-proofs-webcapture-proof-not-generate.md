---
title: 'Korrekturabzüge: WebCapture-Korrekturabzüge werden nicht generiert'
description: Wenn ein(e) Benutzende(r) versucht, einen WebCapture-Korrekturabzug zu erstellen, wird der Korrekturabzug nicht erfolgreich generiert.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 16%

---

# Korrekturabzüge: WebCapture-Korrekturabzüge werden nicht generiert

>[!NOTE]
>
>Dieses Problem wurde abgeschlossen, da es ordnungsgemäß funktioniert. Siehe Problemumgehung unten.

Wenn ein(e) Benutzende(r) versucht, einen WebCapture-Korrekturabzug zu erstellen, wird der Korrekturabzug nicht erfolgreich generiert.

**Problemumgehung**

Dieses Problem wird durch lange Korrekturabzugsgenerierungszeiten für bestimmte PDF-Dateien verursacht. Um den Timeout für die Generierung von den standardmäßigen 30 Sekunden zu erhöhen, bearbeiten Sie die folgende Eigenschaft in den Verarbeitungseinstellungen auf Kontoebene in der Admin für Korrekturabzüge:

`WebCaptureNavigationTimeout -> 120`

_Erste Meldung am Freitag, 3. Oktober 2024._
