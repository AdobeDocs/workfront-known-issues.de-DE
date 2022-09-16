---
title: '"Genehmigungen: Die Validierungsdelegierung wird für die falsche Anzahl von Tagen festgelegt.'
description: Wenn ein Benutzer die Zeitüberschreitung für die persönliche Zeit plant und seine Genehmigungen für diese Zeit delegiert, kann die Validierungsdelegierung Tage vor oder nach der geplanten Zeitüberschreitung umfassen.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
hidefromtoc: true
source-git-commit: de7f66f7acba1a0ac32a1257b2e643a767eae7fb
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Genehmigungen: Die Validierungsdelegierung ist für die falsche Anzahl von Tagen festgelegt.

>[!NOTE]
>
>Dieses Problem wurde behoben, da es kein Problem darstellt.

Wenn ein Benutzer die Zeitüberschreitung für die Person plant und seine Genehmigungen für diesen Zeitpunkt delegiert, kann die Validierungsdelegierung Tage vor oder nach der geplanten Zeitüberschreitung umfassen.

**Problemumgehung**

Diese Diskrepanz resultiert aus einem Unterschied zwischen der Zeitzone im Profil eines Benutzers und der Zeitzone des zugewiesenen Zeitplans des Benutzers.

Es wird empfohlen, für jede Zeitzone, aus der Benutzer arbeiten, einen eindeutigen Zeitplan zu erstellen und jeden Benutzer dem Zeitplan zuzuweisen, der der Zeitzone in ihrem Benutzerprofil entspricht.

_Erste Meldung am 24. März 2022._
