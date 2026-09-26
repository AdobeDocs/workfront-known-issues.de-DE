---
title: 'Workfront Fusion: Das Jira-Suchmodul gibt einen Fehler zurück'
description: Das vom alten Jira-Connector verwendete Suchmodul kann zu einem Fehler führen. Eine Umgehungslösung ist verfügbar.
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%
---
# Workfront Fusion: Das Jira-Suchmodul gibt einen Fehler zurück

>[!NOTE]
>
>Dieses Problem ist auf eine Änderung zurückzuführen, die Jira an seinem Produkt vorgenommen hat.

Das vom alten Jira-Connector verwendete Suchmodul kann zu folgendem Fehler führen:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Dies ist auf eine Funktionseinstellung aufseiten von Jira zurückzuführen.

Hinweis:

* Betroffen ist nur das Suchmodul. Derzeit sind andere vom Fusion-Connector verwendete Jira-API-Endpunkte hiervon nicht betroffen.

* Der geografische Rollout kann zu Inkonsistenzen führen. Atlassian führt diese Änderung regional ein, was bedeutet, dass einige Jira-Cloud-Instanzen ggf. noch vorübergehend ältere Endpunkte unterstützen. Dies kann in allen Umgebungen zu inkonsistentem Verhalten führen.

**Umgehungslösung**

Wenn dieser Fehler auftritt, können Sie das Suchmodul des alten Jira-Connectors durch das Suchmodul des neuen Connectors ersetzen. Beachten Sie, dass Sie beim neuen Connector die verwendete API-Version auswählen können. Wählen Sie beim Einrichten der Verbindung unbedingt **V3** im Feld **API-Version**.

_Erste Meldung am Dienstag, 15. September 2025._
