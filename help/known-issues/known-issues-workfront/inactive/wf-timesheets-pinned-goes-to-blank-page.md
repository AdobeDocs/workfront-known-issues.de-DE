---
title: 'Arbeitszeittabellen: Angeheftete Arbeitszeittabelle führt zu leerer Seite'
description: Wenn Benutzende in Workfront auf einen Pin klicken, der zur Arbeitszeittabelle führen soll, führt der Pin stattdessen auf eine leere Seite. Eine Umgehungslösung ist verfügbar.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%

---

# Arbeitszeittabellen: Angeheftete Arbeitszeittabelle führt zu leerer Seite

<!--article live for workaround-->

&quot;Wenn Benutzende in Workfront auf einen Pin klicken, der zur Arbeitszeittabelle führen soll, führt der Pin stattdessen auf eine leere Seite.

Das liegt daran, dass sich die URL der Arbeitszeittabelle geändert hat. Aufgrund von `/own` am Ende der URL ist diese nicht mehr die richtige URL. Wenn Benutzende eine URL mit `/own` angeheftet haben, führt dieser Pin zu einer leeren Seite.

**Umgehungslösung**

1. Heben Sie die Anheftung der Arbeitszeittabelle auf.
1. Entfernen Sie `/own` vom Ende der URL.
1. Heften Sie die Arbeitszeittabelle erneut an.

_Erste Meldung am Mittwoch, 7. Mai 2024._
