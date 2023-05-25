---
title: "Workfront-Testversand: 500-Fehler beim Zugriff auf Workfront Testversand über API oder Workfront Fusion"
description: '"Wenn ein Benutzer auf die Aktion "Proof API getAllProofs"zugreift, gibt der Workfront Testserver die folgende Meldung zurück: 500 Interner Server-Fehler"'
hidefromtoc: true
source-git-commit: ef82f9a12925f2fc70a20f91f9278240fcee92fb
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 31%

---


# [!DNL Workfront Proof]: 500-Fehler beim Zugriff [!DNL Workfront Proof] über API oder [!DNL Workfront Fusion]

>[!NOTE]
>
>Das Produkt-Team bewertet derzeit diese Problemlösung, die möglicherweise eine Produktverbesserung erfordert. Produktverbesserungen werden in den Produktankündigungen und nicht in den Wartungs-Updates kommuniziert.

<!--This article is on Proof and Fusion TOCs-->

Wenn ein Benutzer auf die [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] -Aktion verwenden, gibt der Server die folgende Meldung zurück:

[!UICONTROL 500 Interner Server-Fehler]

weil [!DNL Workfront Fusion] verwendet die [!DNL Workfront Proof] API für [!DNL Workfront Proof] -Modulen, kann dieser Fehler an ein Modul zurückgegeben werden, wodurch ein Szenario angehalten wird.

_Erste Meldung am 28. April 2023._

