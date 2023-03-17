---
title: "Dokumente: 404-Fehler beim Zugriff auf von SharePoint verknüpfte Dokumente"
description: "Wenn ein Benutzer versucht, auf ein über SharePoint verknüpftes Dokument zuzugreifen, wird er zu einer Seite mit dem Fehler 404 geleitet."
hidefromtoc: true
source-git-commit: c95d478b78e26e4f0243e9b9ae69ecfbc016d696
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Dokumente: 404-Fehler beim Zugriff auf ein verknüpftes Dokument aus [!DNL SharePoint]

<!--This issue is on the WF and WFP TOCs-->

Wenn ein Benutzer versucht, auf ein Dokument zuzugreifen, das über [!DNL SharePoint], werden sie zu einer Seite mit folgendem Fehler weitergeleitet:

&quot;[!UICONTROL Fehler 404: Seite nicht gefunden. Diese Seite ist nicht verfügbar. Versuchen Sie, die URL zu überprüfen oder eine andere Seite zu besuchen.]&quot;

Dies ist bekannt [!DNL SharePoint] Problem, das auftritt, wenn die Site ein &quot;@&quot;-Symbol im Link enthält.

**Problemumgehung**

[!DNL SharePoint] empfiehlt, eine kurze URL zu generieren und diese für den Link zu verwenden.

_Erste Meldung am 14. März 2023._

