---
title: '"Resource Management: Falsche Finanzberechnungen aufgrund von Problemen mit der Rolle "Job"'
description: "Stunden- und Finanzberechnungen können falsch sein, was Kosten von 0 anzeigt, obwohl Stunden in einer Stellenaufgabe protokolliert werden, die über eine Kostenstelle verfügt."
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# Ressourcenverwaltung: Fehlerhafte Finanzberechnungen aufgrund von Problemen mit der Rolle &quot;Auftrag&quot;

Stunden- und Finanzberechnungen können falsch sein, was Kosten von 0 anzeigt, obwohl Stunden in einer Job-Rolle protokolliert werden, die über eine Kostensenkung verfügt.

Dies liegt daran, dass Auftragsrollen automatisch doppelte Raten ohne Start- oder Enddatum erstellen. Da sie kein Start- oder Enddatum haben, werden sie bei Ausführung von Finanzberechnungen als Wert von 0 behandelt.

**Problemumgehung**

1. Vergewissern Sie sich, dass Ihre bisherigen korrekten Daten gespeichert wurden.
1. Löschen Sie die doppelten Raten ohne Start- oder Enddatum.
1. Neuberechnung der Finanzen.

_Erste Meldung am 18. Januar 2023._
