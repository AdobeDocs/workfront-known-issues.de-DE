---
title: 'Workfront Proof: 500-Fehler beim Zugriff auf Workfront Proof über API oder Workfront Fusion'
description: 'Wenn eine Benutzerin oder ein Benutzer auf die Aktion getAllProofs der Korrekturabzugs-API zugreift, gibt der Workfront Proof-Server die folgende Meldung zurück: 500 Interner Server-Fehler'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]: 500-Fehler beim Zugriff auf [!DNL Workfront Proof] über API oder [!DNL Workfront Fusion]

>[!NOTE]
>
>Das Produkt-Team bewertet derzeit diese Problemlösung, die möglicherweise eine Produktverbesserung erfordert. Produktverbesserungen werden in den Produktankündigungen und nicht in den Wartungs-Updates kommuniziert.

<!--This article is on Proof and Fusion TOCs-->

Wenn eine Benutzerin oder ein Benutzer auf die [!DNL Workfront Proof]API[!UICONTROL `getAllProofs`]-Aktion zugreift, gibt der Server die folgende Nachricht zurück:

[!UICONTROL 500 Interner Server-Fehler]

Da [!DNL Workfront Fusion] die [!DNL Workfront Proof]-API für [!DNL Workfront Proof]-Module verwendet, kann dieser Fehler an ein Modul zurückgegeben werden, wodurch ein Szenario angehalten wird.

_Erste Meldung am Samstag, 28. April 2023._
