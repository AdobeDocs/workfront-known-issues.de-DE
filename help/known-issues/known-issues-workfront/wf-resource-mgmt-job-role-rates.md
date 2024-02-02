---
title: '„Ressourcen-Management: Falsche Finanzberechnungen aufgrund von Problemen mit dem Aufgabengebiet“'
description: „Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.“
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: ht
source-wordcount: '135'
ht-degree: 100%

---


# Ressourcen-Management: Fehlerhafte Finanzberechnungen aufgrund von Problemen mit dem Aufgabengebiet

Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.

Dies liegt daran, dass Aufgabengebiete automatisch doppelte Raten ohne Start- oder Enddatum erstellen. Da sie kein Start- oder Enddatum haben, werden sie bei der Ausführung von Finanzberechnungen als Wert von 0 behandelt.

**Problemumgehung**

1. Vergewissern Sie sich, dass Ihre bisherigen korrekten Daten gespeichert wurden.
1. Löschen Sie die doppelten Raten ohne Start- oder Enddatum.
1. Berechen Sie die Finanzen neu.

_Erste Meldung am 18. Januar 2023._
