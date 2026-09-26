---
title: 'Arbeitszeittabellen: Angeheftete Arbeitszeittabelle führt zu leerer Seite'
description: Wenn Benutzende in Workfront auf einen Pin klicken, der zur Arbeitszeittabelle führen soll, führt der Pin stattdessen auf eine leere Seite. Eine Umgehungslösung ist verfügbar.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
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
