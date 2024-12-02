---
title: 'Startseite: Aufgaben in Projekten mit dem Status „Genehmigt“ oder „Planung“ sind nicht in der Arbeitsliste von „Meine Aufgaben“ oder der Startseite enthalten'
description: Aufgaben aus Projekten mit dem Status „Genehmigt“ oder „Planung“ werden nicht auf der Startseite angezeigt. Eine Problemumgehung ist verfügbar.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 100%

---

# Startseite: Aufgaben in Projekten mit dem Status „Genehmigt“ oder „Planung“ sind nicht in der Arbeitsliste von „Meine Aufgaben“ oder der Startseite enthalten

>[!NOTE]
>
>Das Produkt-Team arbeitet derzeit an der Problemlösung. Wenn dieses Problem behoben ist, wird dies in den Produktankündigungen und nicht mit den Wartungs-Updates kommuniziert.

Aufgaben aus Projekten mit dem Status „Genehmigt“ oder „Planung“ werden nicht in den folgenden Bereichen angezeigt.

* Klassische Startseite: Arbeitsliste
* Neue Startseite: Widget „Meine Aufgaben“

Dies liegt daran, dass Aufgaben aus Projekten mit diesem Status derzeit in der Abfragebegrenzung von 2000 Elementen enthalten sind, aber nicht in „Meine Aufgaben“ oder der Arbeitsliste der Startseite angezeigt werden. Dies kann dazu führen, dass Benutzende mit weniger als 2000 Aufgaben diese Aufgaben nicht sehen können.

**Problemumgehung**

Erstellen Sie einen benutzerspezifischen Zuweisungsbericht, der die folgenden Textmodusfilter enthält:

Wenn die Zuweisung den Status AWAITING_ACCEPTANCE hat, schließen Sie Projekte mit dem Status CURRENT|APPROVED ein:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Wenn die Zuweisung den Status ACCEPTED hat, schließen Sie Projekte mit dem Status CURRENT|APPROVED|PLANNING ein:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Erste Meldung am 6. November 2023._
