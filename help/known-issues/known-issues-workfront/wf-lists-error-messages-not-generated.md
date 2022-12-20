---
title: '„Listen: Fehler bei der Inline-Bearbeitung durch den/die Benutzende(n) verursachen keine Fehlermeldungen“'
description: „Wenn ein(e) Benutzende(r) ein Objekt inline bearbeitet und einen Fehler macht, durch den eine Fehlermeldung ausgelöst werden sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch verwirrend sein.“
hidefromtoc: true
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: ht
source-wordcount: '171'
ht-degree: 100%

---


# Listen: Fehler bei der Inline-Bearbeitung durch den/die Benutzende(n) verursachen keine Fehlermeldungen

>[!NOTE]
>
>Dieses Problem wurde am 1. Dezember 2022 behoben.

Wenn ein(e) Benutzende(r) ein Objekt inline bearbeitet und einen Fehler macht, durch den eine Fehlermeldung ausgelöst werden sollte, wird keine Fehlermeldung angezeigt. Der Fehler selbst wird nicht in Workfront gespeichert, sodass die Daten nicht betroffen sind. Das Fehlen einer Fehlermeldung kann jedoch verwirrend sein.

Dies wurde in den folgenden Situationen gemeldet:

* Vorgänger: Es wird eine Vorgängerschleife erstellt, z. B. das Zuweisen einer Aufgabe zu sich selbst
* Datumsangaben: Es wird ein unmögliches Datum eingegeben, z. B. ein Fertigstellungsdatum, das vor dem Startdatum liegt oder das über das Fertigstellungsdatum des Projekts hinausgeht

_Erste Meldung am 26. Oktober 2022._

