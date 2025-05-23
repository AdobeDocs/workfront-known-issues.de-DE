---
title: 'Benutzende: Bei neuen Benutzenden wird das Abzeichen für ausstehende Genehmigungen angezeigt'
description: Neue Benutzende in Workfront werden möglicherweise in der Benutzerliste mit dem Badge Ausstehende Genehmigung angezeigt. Das Badge bleibt länger als einige Minuten bestehen und ist beim Aktualisieren der Seite weiterhin vorhanden.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# Benutzende: Bei neuen Benutzenden wird das Badge „Ausstehende Genehmigung“ angezeigt

>[!NOTE]
>
>Dieses Problem kann in Organisationen auftreten, die in die Adobe Admin Console migriert wurden.

Neue Benutzende in Workfront werden möglicherweise mit dem Badge „Ausstehende Genehmigung“ in der Benutzerliste angezeigt. Das Badge bleibt länger als einige Minuten bestehen und ist beim Aktualisieren der Seite weiterhin vorhanden.

Dieses Problem wird noch verschärft, wenn Benutzende in großen Batches hochgeladen werden, z. B. aus einer Tabelle oder einem Workfront-Kickstart.

Erwartet wird, dass das Badge nach einigen Minuten ausgeblendet wird und beim Aktualisieren der Seite nicht vorhanden ist.

## Problemumgehungen

Dies tritt auf, wenn zu Workfront hinzugefügte Benutzende nicht mit Adobe Admin Console synchronisiert werden.

Wir empfehlen die folgenden Problemumgehungen:

### Einzelne Benutzer auflösen

Sie können einzelne Benutzer in der Benutzerliste auflösen.

1. Wählen Sie den oder die Benutzer in der Benutzerliste aus.
1. Klicken Sie auf das Dreipunkt-Menü in der Listenüberschrift.
1. Wählen Sie **Genehmigen** aus.
1. Aktualisieren Sie die Seite nach einigen Minuten.

### Auflösen von in einem großen Batch hinzugefügten Benutzern

Um Benutzende aufzulösen, die in einem großen Batch hinzugefügt wurden, können Sie den Batch von Benutzenden direkt zur Adobe Admin Console hinzufügen.

Anweisungen finden Sie unter [Mehrere Benutzer verwalten | CSV-Massen-Upload](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html) in der Dokumentation zu Adobe.


_Erste Meldung am Freitag, 8. Mai 2025._
