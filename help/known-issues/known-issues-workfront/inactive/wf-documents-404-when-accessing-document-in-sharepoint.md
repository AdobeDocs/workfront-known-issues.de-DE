---
title: 'Dokumente: 404-Fehler beim Zugriff auf ein über SharePoint verknüpftes Dokument'
description: Wenn Benutzende versuchen, auf ein über SharePoint verknüpftes Dokument zuzugreifen, werden sie zu einer Seite mit einem 404-Fehler geleitet.
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '110'
ht-degree: 91%
---
# Dokumente: 404-Fehler beim Zugriff auf ein über [!DNL SharePoint] verknüpftes Dokument

<!--Requested article. This issue is on the WF and WFP TOCs.-->

Wenn Benutzende versuchen, auf ein Dokument zuzugreifen, das über [!DNL SharePoint] verknüpft ist, werden sie zu einer Seite mit folgendem Fehler weitergeleitet:

„[!UICONTROL Fehler 404: Seite nicht gefunden. Diese Seite ist nicht verfügbar. Bitte die URL überprüfen oder eine andere Seite besuchen.]“

Dies ist ein bekanntes [!DNL SharePoint]-Problem, das auftritt, wenn die Site ein „@“-Symbol im Link enthält.

**Umgehungslösung**

[!DNL SharePoint] empfiehlt, eine kurze URL zu generieren und diese für den Link zu verwenden.

_Erste Meldung am Mittwoch, 14. März 2023._
