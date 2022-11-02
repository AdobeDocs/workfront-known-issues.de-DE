---
title: "Listen: Fehler bei der Inline-Bearbeitung durch den Benutzer werden nicht zu Fehlermeldungen geführt"
description: "Wenn ein Benutzer ein Objekt inline bearbeitet und einen Fehler auslöst, der eine Fehlermeldung erzeugen sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch zu Verwirrung führen."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 2%

---


# Listen: Fehler bei der Inline-Bearbeitung durch den Benutzer verursachen keine Fehlermeldungen

Wenn ein Benutzer ein Objekt inline bearbeitet und einen Fehler auslöst, der eine Fehlermeldung erzeugen sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch zu Verwirrung führen.

Dies wurde für die folgenden Situationen gemeldet:

* Vorgänger: Es wird eine Vorläuferschleife erstellt, z. B. das Zuweisen einer Aufgabe zu sich selbst
* Daten: Es wird ein unmögliches Datum festgelegt, z. B. ein Abschlussdatum, das vor dem Startdatum liegt oder das über das Projektzulassungsdatum hinausgeht

_Erste Meldung am 26. Oktober 2022._

