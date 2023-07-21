---
title: '„Dokumente: Berechtigungen werden nicht vererbt, wenn ein Dokument in ein neues Projekt verschoben wird“'
description: Wenn ein Dokument in ein anderes Projekt verschoben wird, erbt das Dokument nicht die Freigabeberechtigungen vom neuen Projekt. Das Dokument wird nicht für die Benutzenden freigegeben, für die das Projekt freigegeben ist. „
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 100%

---

# Dokumente: Berechtigungen werden nicht vererbt, wenn ein Dokument in ein neues Projekt verschoben wird

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

Wenn ein(e) Benutzende(r) ein Dokument in ein anderes Projekt verschiebt, erbt das Dokument die Freigabeberechtigungen vom neuen Projekt nicht. Das Dokument wird nicht für die Benutzenden freigegeben, für die das Projekt freigegeben ist.

**Problemumgehung:**

1. Navigieren Sie zum übergeordneten Objekt des Dokuments, z. B. Projekt, Aufgabe oder Problem.

1. Entfernen Sie geerbte Berechtigungen aus der Freigabeliste des übergeordneten Objekts, indem Sie auf das „x“ neben den geerbten Berechtigungen und dann auf **[!UICONTROL Speichern]** klicken.

1. Fügen Sie geerbte Berechtigungen erneut hinzu, indem Sie zurück zur Freigabeliste des übergeordneten Objekts navigieren, auf **[!UICONTROL Rückgängig]** neben den geerbten Berechtigungen und dann auf **[!UICONTROL Speichern]** klicken.

Alternativ können Sie die ID des Dokuments (aus der URL der [!UICONTROL Dokumentdetailseite]) notieren und sich an den [!DNL Workfront]-Support wenden.

_Erste Meldung am 6. Januar 2023._
