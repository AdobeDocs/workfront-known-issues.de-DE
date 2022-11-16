---
title: '„Listen: Fehler bei der Inline-Bearbeitung durch den/die Benutzende(n) verursachen keine Fehlermeldungen“'
description: „Wenn ein(e) Benutzende(r) ein Objekt inline bearbeitet und einen Fehler macht, durch den eine Fehlermeldung ausgelöst werden sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch verwirrend sein.“
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: ht
source-wordcount: '165'
ht-degree: 100%

---


# Listen: Fehler bei der Inline-Bearbeitung durch den/die Benutzende(n) verursachen keine Fehlermeldungen

Wenn ein(e) Benutzende(r) ein Objekt inline bearbeitet und einen Fehler macht, durch den eine Fehlermeldung ausgelöst werden sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch verwirrend sein.

Dies wurde in den folgenden Situationen gemeldet:

* Vorgänger: Es wird eine Vorgängerschleife erstellt, z. B. das Zuweisen einer Aufgabe zu sich selbst
* Datumsangaben: Es wird ein unmögliches Datum eingegeben, z. B. ein Fertigstellungsdatum, das vor dem Startdatum liegt oder das über das Fertigstellungsdatum des Projekts hinausgeht

_Erste Meldung am 26. Oktober 2022._

