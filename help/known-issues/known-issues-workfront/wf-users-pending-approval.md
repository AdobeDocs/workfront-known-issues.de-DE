---
title: 'Benutzende: Bei neuen Benutzenden wird das Badge „Ausstehende Genehmigung“ angezeigt'
description: Neue Benutzende in Workfront werden möglicherweise in der Benutzerliste mit dem Badge „Ausstehende Genehmigung“ angezeigt. Das Badge wird länger als einige Minuten angezeigt und ist beim Aktualisieren der Seite weiterhin vorhanden.
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: 254442ca-6997-5cfa-963e-f420870aea53
    internal-label: People Teams and Groups
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%
---
# Benutzende: Bei neuen Benutzenden wird das Badge „Ausstehende Genehmigung“ angezeigt

>[!NOTE]
>
>Dieses Problem kann in Organisationen auftreten, die auf die Adobe Admin Console migriert wurden.

Neue Benutzende in Workfront werden möglicherweise mit dem Badge „Ausstehende Genehmigung“ in der Benutzerliste angezeigt. Das Badge wird länger als einige Minuten angezeigt und ist beim Aktualisieren der Seite weiterhin vorhanden.

Dieses Problem wird noch verschärft, wenn Benutzende in großer Anzahl hochgeladen werden, z. B. aus einer Tabelle oder einem Workfront-Kickstart.

Das erwartete Verhalten ist, dass das Badge nach einigen Minuten ausgeblendet wird und beim Aktualisieren der Seite nicht erscheint.

## Umgehungslösungen

Dies tritt auf, wenn zu Workfront hinzugefügte Benutzende nicht mit Adobe Admin Console synchronisiert sind.

Wir empfehlen Folgendes:

### Probleme bei einzelnen Benutzenden lösen

In der Benutzerliste können Sie Probleme bei einzelnen Benutzenden lösen.

1. Wählen Sie die Benutzenden in der Benutzerliste aus.
1. Klicken Sie auf das Dreipunkt-Menü in der Listenüberschrift.
1. Wählen Sie **Genehmigen** aus.
1. Aktualisieren Sie die Seite nach einigen Minuten.

### Lösen Sie Probleme bei Benutzenden, die in großer Anzahl hinzugefügt wurden

Um Probleme bei Benutzenden zu lösen, die in großer Anzahl hinzugefügt wurden, können Sie den Batch von Benutzenden direkt in der Adobe Admin Console hinzufügen.

Anweisungen finden Sie unter [Verwalten mehrerer Benutzender | CSV-Massen-Upload](https://helpx.adobe.com/de/enterprise/using/bulk-upload-users.html) in der Adobe-Dokumentation.


_Erste Meldung am Freitag, 8. Mai 2025._
