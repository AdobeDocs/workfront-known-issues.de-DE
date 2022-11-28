---
title: "Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn Feldname Anführungszeichen oder ein Apostroph enthält."
description: "Wenn ein Benutzer einen berechneten Feldausdruck erstellt und versucht, ein typeahead-Feld mit einem Namen mit einem Apostroph oder Anführungszeichen einzuschließen, wird die Berechnung nicht akzeptiert und der Benutzer sieht die Meldung Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut."
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 2%

---


# Benutzerdefinierte Formulare: Feld kann nicht in der Berechnung verwendet werden, wenn Feldname Apostrophe oder Anführungszeichen enthält

Wenn ein Benutzer einen Ausdruck für ein berechnetes Feld erstellt und versucht, ein typeahead -Feld einzuschließen, das einen Namen mit einem `'` oder `"`, wird die Berechnung nicht akzeptiert und der Benutzer sieht die Nachricht &quot;[!UICONTROL Dies ist ein ungültiger benutzerdefinierter Ausdruck. Versuchen Sie es erneut.]&quot;

Dieses Problem tritt nur bei Typeahead-Feldern auf. Textfelder mit `'` oder `"` im Namen kann in berechneten Feldausdrücken ohne Probleme verwendet werden.

_Erste Meldung am 10. November 2022._

