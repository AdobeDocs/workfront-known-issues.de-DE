---
title: 'Workfront Fusion: Das Jira-Suchmodul gibt einen Fehler zurück'
description: Das vom alten Jira-Connector verwendete Suchmodul kann zu einem Fehler führen. Eine Umgehungslösung ist verfügbar.
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 4%

---


# Workfront Fusion: Das Jira-Suchmodul gibt einen Fehler zurück

>[!NOTE]
>
>Dieses Problem ist auf eine Änderung zurückzuführen, die Jira an seinem Produkt vorgenommen hat.

Das vom alten Jira-Connector verwendete Suchmodul kann zu folgendem Fehler führen:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Dies ist auf eine Einstellung auf der Jira-Seite zurückzuführen.

Beachten Sie Folgendes:

* Nur das Suchmodul ist betroffen. Derzeit sind andere vom Fusion-Connector verwendete Jira-API-Endpunkte von dieser Einstellung nicht betroffen.

* Der geografische Rollout kann zu Inkonsistenzen führen. Atlassian führt diese Änderung regional ein, was bedeutet, dass einige Jira-Cloud-Instanzen möglicherweise noch vorübergehend ältere Endpunkte unterstützen. Dies kann zu inkonsistentem Verhalten in allen Umgebungen führen.

**Umgehungslösung**

Wenn dieser Fehler auftritt, können Sie das Suchmodul des alten Jira-Connectors durch das Suchmodul des neuen Connectors ersetzen. Beachten Sie, dass Sie mit dem neuen Connector die verwendete API-Version auswählen können. Wählen Sie beim Erstellen **Verbindung unbedingt** V3 **im Feld API-Version** aus.

_Erste Meldung am Dienstag, 15. September 2025._

