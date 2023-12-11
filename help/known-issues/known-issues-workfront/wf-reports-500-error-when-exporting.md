---
title: '„Berichte: 500-Fehler beim Exportieren eines Berichts“'
description: Wenn Benutzende versuchen, einen Bericht zu exportieren, schlägt der Export mit einem 500-Fehler fehl.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: ht
source-wordcount: '70'
ht-degree: 100%

---

# Berichte: 500-Fehler beim Export eines Berichts

>[!NOTE]
>
>Dieses Problem wurde am Freitag, 30. November 2023 behoben.

Wenn Benutzende versuchen, einen Bericht zu exportieren, schlägt der Export mit dem folgenden Fehler fehl:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Dies wurde in Berichten gemeldet, die einen `valueexpression` verwenden, um auf den `lastNote`-Notiztext zu verweisen.

_Erste Meldung am 8. November 2023._
