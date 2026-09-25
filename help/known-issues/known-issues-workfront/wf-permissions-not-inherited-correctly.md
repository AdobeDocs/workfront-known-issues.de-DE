---
title: 'Berechtigungen: Objektberechtigungen werden nicht korrekt übernommen'
description: Vererbte Berechtigungen werden nicht korrekt auf Objekte angewendet. Dies kann aufgrund der Komplexität der geerbten Berechtigungen auftreten.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# Berechtigungen: Objektberechtigungen werden nicht korrekt übernommen

>[!NOTE]
>
>Das Produkt-Team bewertet derzeit diese Problemlösung, die möglicherweise eine Produktverbesserung erfordert. Produktverbesserungen werden in den Produktankündigungen und nicht in den Wartungs-Updates kommuniziert.

Vererbte Berechtigungen werden nicht korrekt auf Objekte angewendet. Dies kann aufgrund der Komplexität der geerbten Berechtigungen auftreten, die durch Folgendes beeinträchtigt werden können:

* Das Objekt wird mit einer großen Anzahl von Personen geteilt.
* Eine große Anzahl von Objekten ist von einer Änderung der geerbten Berechtigung betroffen.

**Umgehungslösung**

Eine Begrenzung der Größe oder Komplexität der Objekte kann dazu beitragen, dieses Problem zu vermeiden. Es wird empfohlen, unter keinem übergeordneten Objekt mehr als 10.000 untergeordnete Objekte zu verwenden.

_Erste Meldung am Samstag, 21. März 2025._
