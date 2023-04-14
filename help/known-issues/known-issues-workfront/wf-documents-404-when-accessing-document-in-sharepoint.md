---
title: '„Dokumente: 404-Fehler beim Zugriff auf über SharePoint verknüpfte Dokumente“'
description: „Wenn Benutzende versuchen, auf ein über SharePoint verknüpftes Dokument zuzugreifen, werden sie zu einer Seite mit einem 404-Fehler geleitet.“
hidefromtoc: true
source-git-commit: c95d478b78e26e4f0243e9b9ae69ecfbc016d696
workflow-type: ht
source-wordcount: '104'
ht-degree: 100%

---


# Dokumente: 404-Fehler beim Zugriff auf ein über [!DNL SharePoint] verknüpftes Dokument

<!--This issue is on the WF and WFP TOCs-->

Wenn Benutzende versuchen, auf ein Dokument zuzugreifen, das über [!DNL SharePoint] verknüpft ist, werden sie zu einer Seite mit folgendem Fehler weitergeleitet:

„[!UICONTROL Fehler 404: Seite nicht gefunden. Diese Seite ist nicht verfügbar. Bitte die URL überprüfen oder eine andere Seite besuchen.]“

Dies ist ein bekanntes [!DNL SharePoint]-Problem, das auftritt, wenn die Site ein „@“-Symbol im Link enthält.

**Problemumgehung**

[!DNL SharePoint] empfiehlt, eine kurze URL zu generieren und diese für den Link zu verwenden.

_Erste Meldung am 14. März 2023._

