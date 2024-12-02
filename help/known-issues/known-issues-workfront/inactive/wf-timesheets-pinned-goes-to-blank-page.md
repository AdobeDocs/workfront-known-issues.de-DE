---
title: 'Arbeitszeittabellen: Angeheftete Arbeitszeittabelle führt zu leerer Seite.'
description: '"Wenn Benutzende in Workfront auf einen Pin klicken, der zur Arbeitszeittabelle führen soll, führt der Pin stattdessen auf eine leere Seite. Eine Problemumgehung ist verfügbar.'
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 100%

---

# Arbeitszeittabellen: Angeheftete Arbeitszeittabelle führt zu leerer Seite.

<!--article live for workaround-->

Wenn Benutzende in Workfront auf einen Pin klicken, der zur Arbeitszeittabelle führen soll, führt der Pin stattdessen auf eine leere Seite.

Das liegt daran, dass sich die URL der Arbeitszeittabelle geändert hat. Aufgrund von `/own` am Ende der URL ist diese nicht mehr die richtige URL. Wenn Benutzende eine URL mit `/own` angeheftet haben, führt dieser Pin zu einer leeren Seite.

**Problemumgehung**

1. Heben Sie die Anheftung der Arbeitszeittabelle auf.
1. Entfernen Sie `/own` vom Ende der URL.
1. Heften Sie die Arbeitszeittabelle erneut an.

_Erste Meldung am Mittwoch, 7. Mai 2024._
