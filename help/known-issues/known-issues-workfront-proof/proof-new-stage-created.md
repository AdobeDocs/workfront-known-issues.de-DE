---
title: 'Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann'
description: Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall definiert werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '243'
ht-degree: 64%
---
# Korrekturabzüge: Neuer Schritt erstellt, weil Frist nicht mit der Frist des bestehenden Schritts abgestimmt werden kann

<!--Requested article-->

Wenn ein neuer Korrekturabzug erstellt wird, kann die Frist im 15-Minuten-Intervall definiert werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein(e) Benutzende(r) jedoch nach der Erstellung des Korrekturabzugs zu einem Korrekturabzug hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.). Daher kann der neue Benutzer nicht zu einem Schritt hinzugefügt werden, dessen Frist auf :15 oder :45 endet, da die Fristen nicht aufeinander abgestimmt werden können. Stattdessen wird der/die neue Benutzende zu einem neuen Schritt hinzugefügt, dessen Frist in Intervallen von 30 Minuten festgelegt wird.

**Problemumgehung**:

* Wenn Sie eine Frist für einen neuen Korrekturabzug auswählen, setzen Sie die Frist auf einen Zeitpunkt, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
* Wenn die Frist zum Zeitpunkt der Korrekturabzugs-Erstellung automatisch festgelegt wird, legen Sie die Frist für den Korrekturabzug manuell auf einen Zeitpunkt fest, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
