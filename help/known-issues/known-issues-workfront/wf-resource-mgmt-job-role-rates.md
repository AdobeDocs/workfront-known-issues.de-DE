---
title: '„Ressourcen-Management: Falsche Finanzberechnungen aufgrund von Problemen mit dem Aufgabengebiet“'
description: „Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.“
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---


# Ressourcen-Management: Fehlerhafte Finanzberechnungen aufgrund von Problemen mit dem Aufgabengebiet

>[!NOTE]
>
>Dieses Problem wurde am Freitag, 8. Februar 2024 behoben.

Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.

Dies liegt daran, dass Aufgabengebiete automatisch doppelte Raten ohne Start- oder Enddatum erstellen. Da sie kein Start- oder Enddatum haben, werden sie bei der Ausführung von Finanzberechnungen als Wert von 0 behandelt.

**Problemumgehung**

1. Vergewissern Sie sich, dass Ihre bisherigen korrekten Daten gespeichert wurden.
1. Löschen Sie die doppelten Raten ohne Start- oder Enddatum.
1. Berechen Sie die Finanzen neu.

_Erste Meldung am 18. Januar 2023._
