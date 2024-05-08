---
title: "Timesheets: Pinned timesheet geht an leere Seite"
description: '"Wenn ein Benutzer in Workfront auf eine Pin klickt, die zum Timesheet hinzugefügt werden soll, wird die Pin stattdessen auf eine leere Seite verschoben. Eine Problemumgehung ist verfügbar.“'
hidefromtoc: true
feature: Timesheets
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# Timesheets: Das angeheftete Timesheet wird auf eine leere Seite verschoben

Wenn ein Benutzer in Workfront auf eine Pin klickt, die zum Timesheet hinzugefügt werden soll, wird die Pin stattdessen auf eine leere Seite verschoben.

Dies liegt daran, dass sich die URL des Timesheets geändert hat. Die `/own` am Ende der URL ist nicht mehr die richtige URL. Wenn der Benutzer eine URL mit `/own`, führt dieser Pin zu einer leeren Seite.

**Problemumgehung**

1. Heben Sie die Zeitleiste auf.
1. Entfernen `/own` vom Ende der URL
1. Passen Sie das Zeitblatt erneut an.

_Erste Meldung am Mittwoch, 7. Mai 2024._

