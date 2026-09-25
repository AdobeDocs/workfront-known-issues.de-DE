---
title: 'Layout-Vorlagen: Benutzerdefinierte Datenfelder werden nicht angezeigt, wenn sie über die Layout-Vorlage zur Aufgabenübersicht hinzugefügt werden'
description: Wenn Admins ein benutzerdefiniertes Datenfeld über eine Layout-Vorlage zum Abschnitt „Aufgabenübersicht“ hinzufügen, wird das Feld für Benutzende, die den Abschnitt „Aufgabenübersicht“ einer Aufgabe betrachten, als leer angezeigt.
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 100%
---
# Layout-Vorlagen: Benutzerdefinierte Datenfelder werden nicht angezeigt, wenn sie über die Layout-Vorlage zur Aufgabenübersicht hinzugefügt werden

>[!NOTE]
>
>Dieser Problemfall wurde geschlossen, da die Funktion ordnungsgemäß funktioniert. Siehe die Umgehungslösung unten.

Wenn Admins ein benutzerdefiniertes Datenfeld über eine Layout-Vorlage zum Abschnitt „Aufgabenübersicht“ hinzufügen, wird das Feld für Benutzende, die den Abschnitt „Aufgabenübersicht“ einer Aufgabe betrachten, als leer angezeigt.

**Umgehungslösung**

Verwendem Sie keine Punkte „.“ in den Namen benutzerdefinierter Felder, um dieses Problem zu vermeiden. Sie können das benutzerdefinierte Feld im Abschnitt der Übersicht neu benennen und bei Bedarf einen Punkt einfügen.

_Erste Meldung am Donnerstag, 2. Oktober 2024._
