---
title: 'Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann'
description: Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall definiert werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 44%

---

# Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann

<!--Requested article-->

Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall festgelegt werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.). Daher kann der neue Benutzer nicht zu einem Schritt hinzugefügt werden, dessen Frist auf :15 oder :45 endet, da die Fristen nicht aufeinander abgestimmt werden können. Stattdessen wird der/die neue Benutzende zu einem neuen Schritt hinzugefügt, dessen Frist in Intervallen von 30 Minuten festgelegt wird.

**Problemumgehung**:

* Wenn Sie eine Frist für einen neuen Korrekturabzug auswählen, setzen Sie die Frist auf einen Zeitpunkt, der auf :00 oder :30 endet (:00, 10:30, 11 :00 usw.).
* Wenn die Frist zum Zeitpunkt der Korrekturabzugs-Erstellung automatisch festgelegt wird, legen Sie die Frist für den Korrekturabzug manuell auf einen Zeitpunkt fest, der auf :00 oder :30 endet (:00, 10:30, 11 :00 usw.).
