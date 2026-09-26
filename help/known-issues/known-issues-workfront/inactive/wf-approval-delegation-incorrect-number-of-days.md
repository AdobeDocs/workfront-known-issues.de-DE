---
title: 'Genehmigungen: Für die Delegierung von Genehmigungen erscheint die falsche Anzahl von Tagen'
description: Wenn ein(e) Benutzende(r) Urlaubstage eingibt und die entsprechenden Genehmigungen für diese Zeit delegiert, kann es passieren, dass in dieser Genehmigungsdelegierung Tage vor oder nach der geplanten Urlaubsdauer enthalten sind.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# Genehmigungen: Für die Delegierung von Genehmigungen erscheint die falsche Anzahl von Tagen

<!--Live for workaround-->

>[!NOTE]
>
>Dieses Problem wurde geschlossen, da es sich hierbei um kein Problem handelt.

Wenn ein(e) Benutzende(r) Urlaubstage eingibt und die entsprechenden Genehmigungen für diese Zeit delegiert, kann es passieren, dass in dieser Genehmigungsdelegierung Tage vor oder nach der geplanten Urlaubsdauer enthalten sind.

**Umgehungslösung**

Diese Diskrepanz kommt durch den Unterschied zwischen der Zeitzone des Profils eines/r Benutzenden und der Zeitzone des zugewiesenen Zeitplans des/r Benutzenden zustande.

Es wird empfohlen, für jede Zeitzone, in der ein(e) Benutzende(r) arbeitet, einen eigenen Zeitplan zu erstellen und jede(n) Benutzende(n) dem Zeitplan zuzuweisen, der der Zeitzone im Benutzerprofil entspricht.

_Erste Meldung am Freitag, 24. März 2022._
