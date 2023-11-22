---
title: '„Aktualisierungen: Zusätzliche Zeilen in Kommentaren, die über API oder Workfront Fusion erstellt wurden“'
description: „Wenn eine Benutzerin bzw. ein Benutzer einen Kommentar über die API oder über Workfront Fusion sendet, werden im Bereich „Aktualisierungen“ zusätzliche Zeilen angezeigt. Manchmal sind so viele Zeilen vorhanden, dass nach unten gescrollt werden muss, um den Kommentarinhalt anzuzeigen.“
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: ht
source-wordcount: '173'
ht-degree: 100%

---


# Aktualisierungen: Zusätzliche Zeilen in Kommentaren, die über API oder [!DNL Workfront Fusion] erstellt wurden

>[!NOTE]
>
>Dieses Problem wurde am 16. November 2023 behoben.

Wenn eine Benutzerin bzw. ein Benutzer einen Kommentar über die API oder über [!DNL Workfront Fusion] eingibt, werden im Bereich „Aktualisierungen“ zusätzliche Zeilen angezeigt. Manchmal sind so viele Zeilen vorhanden, dass nach unten gescrollt werden muss, um den Kommentarinhalt anzuzeigen.

Dies wurde für die neue Kommentarerfahrung berichtet.

**Problemumgehung**

Dieses Problem wird durch Leerzeichen oder Zeilenumbrüche in der HTML verursacht, die im Kommentar eingereicht wird.

Um dieses Problem zu vermeiden, stellen Sie sicher, dass sich die gesamte HTML auf einer Zeile befindet, ohne Leerzeichen oder Zeilenumbrüche zwischen den HTML-Elementen.

Um die betroffenen Kommentare ohne die zusätzlichen Zeilen anzuzeigen, wechseln Sie zum klassischen Kommentarerlebnis.

_Erste Meldung am 27. Oktober 2023._
