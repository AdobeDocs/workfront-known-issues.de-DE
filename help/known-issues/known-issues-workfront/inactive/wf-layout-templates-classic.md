---
title: '„Layout-Vorlagen: Layout-Vorlagen verursachen Inkonsistenzen in Berichten“'
description: Layout-Vorlagen aus dem klassischen Workfront-Erlebnis sind nicht mehr in der Workfront-Benutzeroberfläche verfügbar, können sich aber dennoch auf Workfront-Daten auswirken. Dies kann zu Inkonsistenzen in Feldern führen, die von Layout-Vorlagen (z. B. „Freigegeben für“) in Berichten oder Dashboards betroffen sind.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 100%

---

# Layout-Vorlagen: Layout-Vorlagen verursachen Inkonsistenzen in Berichten

<!--Can delete after 9/24/2024-->

>[!NOTE]
>
>Dieses Problem wurde behoben.

Layout-Vorlagen aus dem klassischen [!DNL Workfront]-Erlebnis sind nicht mehr in der [!DNL Workfront]-Benutzeroberfläche verfügbar, können sich aber dennoch auf [!DNL Workfront]-Daten auswirken. Dies kann zu Unstimmigkeiten in Feldern führen, die von Layout-Vorlagen (z. B. [!UICONTROL Freigegeben für]) in Berichten und Pinnwänden betroffen sind.

**Problemumgehung**

Löschen Sie die klassischen Layout-Vorlagen mithilfe eines API-Aufrufs. Sie müssen bei Workfront angemeldet sein.

>[!NOTE]
>
>Vorlagen für globale und System-Layouts können nicht gelöscht werden.

1. Suchen Sie die Layout-Vorlage, die Sie löschen möchten, mithilfe des folgenden API-Aufrufs:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Notieren Sie sich die ID der Layout-Vorlage, die Sie löschen möchten.
1. Suchen Sie Ihre Sitzungs-ID mithilfe des folgenden API-Aufrufs:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Geben Sie Ihre Sitzungs-ID niemals an andere weiter.

1. Fügen Sie die Layout-Vorlagen-ID und die Sitzungs-ID in den folgenden API-Aufruf ein:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Fügen Sie den API-Aufruf aus Schritt 4 in die URL-Leiste Ihres Browsers ein und drücken Sie die Eingabetaste.

   Dadurch wird die Layout-Vorlage gelöscht.
