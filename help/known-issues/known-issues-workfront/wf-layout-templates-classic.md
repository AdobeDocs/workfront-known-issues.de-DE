---
title: '„Layout-Vorlagen: Layout-Vorlagen verursachen Inkonsistenzen in Berichten“'
description: „Layout-Vorlagen aus dem klassischen Workfront-Erlebnis sind nicht mehr in der Workfront-Benutzeroberfläche verfügbar, können sich aber dennoch auf Workfront-Daten auswirken. Dies kann zu Inkonsistenzen in Feldern führen, die von Layout-Vorlagen (z. B. ‚Freigegeben für‘) in Berichten oder Dashboards betroffen sind.“
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 3845794a0b1b610d821f5653c06d0cce77d58f2e
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 81%

---


# Layout-Vorlagen: Layout-Vorlagen verursachen Inkonsistenzen in Berichten

Layout-Vorlagen aus Classic [!DNL Workfront] Erlebnis ist nicht mehr in der [!DNL Workfront] -Schnittstelle, kann sich aber dennoch auf [!DNL Workfront] Daten. Dies kann zu Inkonsistenzen in Feldern führen, die von Layoutvorlagen betroffen sind (z. B. [!UICONTROL Freigegeben für]) in Berichten oder Dashboards.

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

