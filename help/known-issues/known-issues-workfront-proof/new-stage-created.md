---
title: '„Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann.“'
description: Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall definiert werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: ht
source-wordcount: '197'
ht-degree: 100%

---

# Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann.

>[!NOTE]
>
>Dieses Problem wurde behoben.

Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall definiert werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.). Ein(e) neue Benutzende kann nicht zu einem Schritt hinzugefügt werden, dessen Frist auf :15 oder :45 endet, da die Fristen nicht aufeinander abgestimmt werden können. Stattdessen wird der/die neue Benutzende zu einem neuen Schritt hinzugefügt, dessen Frist in Intervallen von 30 Minuten festgelegt wird.

**Problemumgehung**:

* Wenn Sie eine Frist für einen neuen Korrekturabzug auswählen, legen Sie die Frist auf einen Zeitpunkt fest, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
* Wenn die Frist zum Zeitpunkt der Korrekturabzugs-Erstellung automatisch festgelegt wird, wählen Sie für die Frist des Korrekturabzugs manuell einen Zeitpunkt, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
