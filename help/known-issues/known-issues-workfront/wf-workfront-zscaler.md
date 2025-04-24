---
title: 'Workfront: ZScaler-Einstellungen können die Leistung beeinträchtigen'
description: Der Web-Dienst von ZScaler verwendet standardmäßig http/1.1, was zu Leistungseinbußen in Workfront führen kann.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: ht
source-wordcount: '81'
ht-degree: 100%

---

# Workfront: ZScaler-Einstellungen können die Leistung beeinträchtigen

>[!NOTE]
>
>Dies ist ein Problem mit ZScaler und wird von Workfront nicht behoben.

Der Web-Dienst von ZScaler verwendet standardmäßig `http/1.1`, was zu Leistungseinbußen in Workfront führen kann.

**Problemumgehung**

Konfigurieren Sie Ihre ZScaler-Software für die Verwendung von `http/2`. Dies kann nicht in Workfront konfiguriert werden.

Informationen zu `http/2` finden Sie in der Dokumentation zu ZScaler.

_Erste Meldung am 18. November 2024._
