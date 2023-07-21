---
title: '"Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn Feldname Anführungszeichen oder ein Apostroph enthält'
description: Wenn ein Benutzer einen berechneten Feldausdruck erstellt und versucht, ein typeahead-Feld mit einem Namen mit einem Apostroph oder Anführungszeichen einzuschließen, wird die Berechnung nicht akzeptiert. Der Benutzer sieht die Meldung Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut.
hidefromtoc: true
feature: Custom Forms
exl-id: 7caa6b7a-87ab-40e8-aea2-05b41583a375
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 59%

---

# Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn der Feldname Apostrophe oder Anführungszeichen enthält

>[!NOTE]
>
>Dieses Problem wurde am 2. März 2023 behoben.

Wenn ein(e) Benutzende(r) einen berechneten Feldausdruck erstellt und versucht, ein Feld mit automatischer Textvervollständigung einzubeziehen, das einen Namen mit einem `'` oder `"` enthält, wird die Berechnung nicht akzeptiert und folgende Fehlermeldung wird angezeigt: „[!UICONTROL Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut.]“

Dieses Problem tritt nur bei Feldern mit automatischer Textvervollständigung auf. Textfelder, die `'` oder `"` im Namen enthalten, können problemlos in berechneten Feldausdrücken verwendet werden.

_Erste Meldung am 10. November 2022._
