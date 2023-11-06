---
title: '"Startseite: Aufgaben in Projekten mit dem Status "Genehmigt"oder "Planung"sind nicht in der Liste "Meine Aufgaben"oder "Hausarbeit"enthalten.'
description: "Aufgaben aus Projekten mit dem Status Genehmigt oder Planung werden nicht auf der Startseite angezeigt. Eine Problemumgehung ist verfügbar."
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# Startseite: Aufgaben in Projekten mit dem Status &quot;Genehmigt&quot;oder &quot;Planung&quot;sind nicht in der Liste &quot;Meine Aufgaben&quot;oder &quot;Hausarbeit&quot;enthalten

Aufgaben aus Projekten mit dem Status Genehmigt oder Planung werden in den folgenden Bereichen nicht angezeigt:

* Klassische Startseite: Arbeitsliste
* Neue Startseite: Widget &quot;My Tasks&quot;

Dies liegt daran, dass Aufgaben aus Projekten mit diesem Status derzeit in der Elementabfragebegrenzung von 2000 enthalten sind, aber nicht in My Tasks oder der Home Work List angezeigt werden. Dies kann dazu führen, dass Benutzer mit weniger als 2000 Aufgaben diese Aufgaben nicht sehen können.

**Problemumgehung**

Erstellen Sie einen benutzerspezifischen Zuweisungsbericht, der die folgenden Textmodusfilter enthält:

Wenn die Zuweisung AWARITING_ACCEPTANCE lautet, schließen Sie die Projekte CURRENT|APPROVED ein:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Wenn die Zuweisung AKZEPTIERT ist, schließen Sie CURRENT|APPROVED|PLANING -Projekte ein:

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
