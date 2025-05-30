---
title: 'Benutzende: Bei neuen Benutzenden wird das Badge „Ausstehende Genehmigung“ angezeigt'
description: Neue Benutzende in Workfront werden möglicherweise in der Benutzerliste mit dem Badge „Ausstehende Genehmigung“ angezeigt. Das Badge wird länger als einige Minuten angezeigt und ist beim Aktualisieren der Seite weiterhin vorhanden.
hidefromtoc: true
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 39a085b629d6d2afc5a198e47ca639d2bb431b0d
workflow-type: ht
source-wordcount: '245'
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


_Erste Meldung am 8. Mai 2025._
