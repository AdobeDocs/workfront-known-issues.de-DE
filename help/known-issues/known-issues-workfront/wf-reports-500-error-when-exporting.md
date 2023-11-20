---
title: "Berichte: 500-Fehler beim Export eines Berichts"
description: "Wenn ein Benutzer versucht, einen Bericht zu exportieren, schlägt der Export mit einem 500-Fehler fehl."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Berichte: 500-Fehler beim Export eines Berichts

Wenn ein Benutzer versucht, einen Bericht zu exportieren, schlägt der Export mit dem folgenden Fehler fehl:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Dies wurde in Berichten berichtet, die eine `valueexpression` auf die `lastNote` Text.

_Erste Meldung am 8. November 2023._
