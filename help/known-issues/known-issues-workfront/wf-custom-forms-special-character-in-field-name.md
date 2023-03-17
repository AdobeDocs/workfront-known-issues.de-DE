---
title: '„Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn der Feldname Apostrophe oder Anführungszeichen enthält“'
description: '„Wenn ein(e) Benutzende(r) einen berechneten Feldausdruck erstellt und versucht, ein Feld mit automatischer Textvervollständigung einzubeziehen, das einen Namen mit einem Apostroph oder Anführungszeichen enthält, wird die Berechnung nicht akzeptiert und folgende Fehlermeldung wird angezeigt: Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut.“'
hidefromtoc: true
source-git-commit: 3307a9be28555d0b9561e8ae96e3667cb1fee711
workflow-type: ht
source-wordcount: '154'
ht-degree: 100%

---


# Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn der Feldname Apostrophe oder Anführungszeichen enthält

>[!NOTE]
>
>Dieses Problem wurde am 2. März 2023 behoben.

Wenn ein(e) Benutzende(r) einen berechneten Feldausdruck erstellt und versucht, ein Feld mit automatischer Textvervollständigung einzubeziehen, das einen Namen mit einem `'` oder `"` enthält, wird die Berechnung nicht akzeptiert und folgende Fehlermeldung wird angezeigt: „[!UICONTROL Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut.]“

Dieses Problem tritt nur bei Feldern mit automatischer Textvervollständigung auf. Textfelder, die `'` oder `"` im Namen enthalten, können problemlos in berechneten Feldausdrücken verwendet werden.

_Erste Meldung am 10. November 2022._

