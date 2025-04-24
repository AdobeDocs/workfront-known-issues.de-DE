---
title: 'Korrekturabzüge: WebCapture-Korrekturabzüge werden nicht generiert'
description: Beim Versuch, einen WebCapture-Korrekturabzug zu erstellen, wird der Korrekturabzug nicht erfolgreich generiert.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# Korrekturabzüge: WebCapture-Korrekturabzüge werden nicht generiert

>[!NOTE]
>
>Dieser Problemfall wurde geschlossen, da die Funktion ordnungsgemäß funktioniert. Siehe die Umgehungslösung unten.

Beim Versuch, einen WebCapture-Korrekturabzug zu erstellen, wird der Korrekturabzug nicht erfolgreich generiert.

**Umgehungslösung**

Dieses Problem wird durch lange Generierungszeiten für Korrekturabzüge bei bestimmten PDF-Dateien verursacht. Um die standardmäßigen 30 Sekunden des Timeouts für die Generierung zu erhöhen, bearbeiten Sie die folgende Eigenschaft in den Verarbeitungseinstellungen auf Kontoebene unter „Admin für Korrekturabzüge“:

`WebCaptureNavigationTimeout -> 120`

_Erste Meldung am 3. Oktober 2024._
