---
title: "Testsendungen: Neue Phase erstellt, weil der Termin nicht mit dem Termin der bestehenden Phase übereinstimmen kann."
description: Wenn ein neuer Testversand erstellt wird, kann die Frist um 15 Minuten erhöht werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein Benutzer jedoch nach der Erstellung des Testversands zu einem Testversand hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Testsendungen: Neue Phase erstellt, weil der Termin nicht mit dem Termin für die bestehende Phase übereinstimmen kann

>[!NOTE]
>
>Dieses Problem wurde behoben.

Wenn ein neuer Testversand erstellt wird, kann die Frist um 15 Minuten erhöht werden (10:00, 10:15, 10:30, 20:45 usw.). Wenn ein Benutzer jedoch nach der Erstellung des Testversands zu einem Testversand hinzugefügt wird, kann die Frist nur in Schritten von 30 Minuten festgelegt werden (10:00, 10:30, 11:00 usw.). Daher kann der neue Benutzer nicht zu einer Phase hinzugefügt werden, deren Termin auf :15 oder :45 endet, da die Termine nicht übereinstimmen können. Stattdessen wird der neue Benutzer zu einer neuen Phase hinzugefügt, wobei der Termin in Schritten von 30 Minuten festgelegt wird.

**Problemumgehung**:

* Wenn Sie einen Termin für einen neuen Testversand auswählen, legen Sie den Termin auf einen Zeitpunkt fest, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
* Wenn der Termin zum Zeitpunkt der Testversand-Erstellung automatisch festgelegt wird, legen Sie den Testversand manuell auf einen Zeitpunkt fest, der auf :00 oder :30 endet (10:00, 10:30, 11:00 usw.).
