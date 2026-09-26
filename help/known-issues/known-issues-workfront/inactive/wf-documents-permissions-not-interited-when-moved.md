---
title: 'Dokumente: Berechtigungen werden nicht vererbt, wenn ein Dokument in ein neues Projekt verschoben wird'
description: 'Wenn ein(e) Benutzende(r) ein Dokument in ein anderes Projekt verschiebt, erbt das Dokument die Freigabeberechtigungen vom neuen Projekt nicht. Das Dokument wird nicht für die Benutzenden freigegeben, für die das Projekt freigegeben ist. '
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
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
source-wordcount: '182'
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

_Erste Meldung am Samstag, 6. Januar 2023._



<!--CHECK ME - 1 VIEW APRIL-JUNE 2025 (June 11 and 27)-->
