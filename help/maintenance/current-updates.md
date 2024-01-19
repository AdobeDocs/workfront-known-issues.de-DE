---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 83d675f4ddbdf031b6737cf3e1101afc07d2f841
workflow-type: tm+mt
source-wordcount: '945'
ht-degree: 81%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2024 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [Frühere Wartungs-Updates](#previous-maintenance-updates)

## Updates im Januar 2024

+++**Wartungs-Update vom Freitag, 18. Januar 2024**

### Wartungs-Update am Freitag, 18. Januar 2024

#### Pinnwände

**Es können keine Dokumente an eine Karte angehängt werden**

Beim Versuch, ein Dokument an eine verknüpfte Karte anzuhängen, lässt sich das Dokument auswählen, das angehängt werden soll, das Dokument wird jedoch nicht im Dokumentbereich der Karte angezeigt und ist nicht an das Objekt angehängt, mit dem die Karte verknüpft ist.

Dieser Vorfall wurde für Karten im Zusammenhang mit Problemen gemeldet.

**Karte erscheint bei mehreren Sprints**

Wenn Benutzende einen Sprint auf Pinnwänden anzeigen, werden Karten aus unterschiedlichen Sprints auf der Pinnwand angezeigt. Dieses Problem tritt vorübergehend auf.

**Die Karte wird nicht geschlossen, wenn die Pinnwandansicht in einem Projekt verwendet wird**

Wenn eine Benutzerin bzw. ein Benutzer die Ansicht „Pinnwände“ in einer Aufgabenliste in einem Projekt anzeigt und eine Karte erstellt, wird die Karte nicht geschlossen oder gespeichert. Dadurch wird verhindert, dass die Benutzerin bzw. der Benutzer zum Projekt zurückkehrt.

Um die Karte zu schließen, muss die Benutzerin bzw. der Benutzer die URL bearbeiten, um „Pinnwand“ und alles, was sich rechts neben „Pinnwand“ befindet, zu entfernen.

**Karten bleiben beim Wechseln der Iteration bestehen**

Wenn eine Benutzerin bzw. ein Benutzer eine Iteration auf einer Pinnwand anzeigt und dann die Iteration ändert, sind die für die neue Iteration angezeigten Karten die Karten aus einer Iteration, die die Benutzerin bzw. der Benutzer zuvor gesehen hat.

**Fehler in [!UICONTROL Kommentare] Kartenabschnitt**

Wenn jemand eine Karte aufruft und zum Abschnitt [!UICONTROL Kommentare] scrollt, werden nicht die Kommentare, sondern eine Fehlermeldung angezeigt:

„[!UICONTROL Etwas ist schiefgelaufen. Bitte versuchen Sie es später erneut.]&quot;

**Probleme beim Anzeigen von Unteraufgaben-Status**

Die folgenden Probleme wurden in Bezug auf die Anzeige des Status von Unteraufgaben auf einer Karte auf Pinnwänden gemeldet:

* Der Status wird auch dann als „Status auswählen“ angezeigt, wenn die Aufgabe bereits über einen Status verfügt. Dieser Status wird angezeigt, wenn die Aufgabe direkt angezeigt wird.
* Beim Versuch, einen Status auszuwählen, wird der Bildschirm leer angezeigt und muss aktualisiert werden.

**&quot;[!UICONTROL Sie haben keinen Zugriff]&quot; beim Anzeigen von Kommentaren auf einer Karte**

Wenn Benutzende versuchen, Kommentare auf einer Karte anzuzeigen, die nicht mit einem [!DNL Workfront]-Objekt verbunden ist, sehen sie die folgende Meldung:

„[!UICONTROL Sie haben keine Zugriffsberechtigung, um Kommentare zu diesem Objekt anzuzeigen]“

Dies kann auch auftreten, wenn die Benutzenden zuvor Kommentare auf der Karte sehen konnten.

#### Benutzerdefinierte Formulare in meiner Gruppe

**Benutzerdefinierte Formulare können nicht stapelweise zu Vorlagenaufgaben hinzugefügt oder daraus entfernt werden**

Wenn Benutzende versuchen, ein benutzerdefiniertes Formular in einer Vorlagenaufgabe stapelweise hinzuzufügen oder zu entfernen, wird das Formular nicht hinzugefügt bzw. entfernt und es wird der folgende Fehler angezeigt:

[!UICONTROL Versuchen Sie es erneut. Ungültiger Parameter: templateID-Wert „XXXXXXXXXXXXXXXX“]

Wenn Benutzende die Vorlage mit der angegebenen GUID lokalisieren und dann versuchen, benutzerdefinierte Formulare für die restlichen Vorlagenaufgaben hinzuzufügen oder zu entfernen, tritt der Fehler erneut mit einer anderen templateID auf.

Benutzerdefinierte Formulare können für eine einzelne Vorlagenaufgabe hinzugefügt oder entfernt werden. Dieser Fehler bezieht sich nur auf das stapelweise Hinzufügen oder Entfernen.

#### Portfolios

**Benutzerdefinierte Terminologie gilt nicht für Gruppenseite**

Wenn ein Benutzer benutzerdefinierte Terminologie auf der Ebene des Portfolios festlegt, gilt die Terminologie nicht für die Seite auf Gruppenebene.

#### Setup

**Optionale Status können nicht ausgeblendet werden**

Wenn ein Benutzer versucht, optionale Status auf System- und Gruppenebene auszublenden, wird der Status nicht ausgeblendet. Wenn der Benutzer den Status anzeigt, ist die Option zum Ausblenden des Status nicht aktiviert, obwohl der Benutzer ihn aktiviert und die Änderungen gespeichert hat.

**Standardmäßige Problemstatus fehlen in einigen Problemtypen in der Einrichtung**

Wenn jemand den Problemstatus im Setup anzeigt, zeigt sich, dass die standardmäßigen Status für Probleme (Neu, In Bearbeitung und Abgeschlossen) in einigen Problemtypen fehlen. Die standardmäßigen Status bieten keine Möglichkeit, den Problemtyp zu ändern. Daher lässt sich der Status für die Anzeige der betroffenen Problemtypen nicht neu konfigurieren.

#### Teams

**Probleme beim Festlegen des Teamstatus für [!UICONTROL Fertig] button**

Die folgenden Probleme wurden bezüglich des Status für die Schaltfläche [!UICONTROL Fertig] beim Bearbeiten oder Erstellen eines Teams gemeldet:

* Einige Status fehlen möglicherweise im Bereich der Schaltfläche „Fertig“ des Fensters [!UICONTROL Neues Team] oder im Bereich [!UICONTROL Team-Einstellungen] eines vorhandenen Teams.
* Wenn Benutzende versuchen, das Team zu speichern, wird ihnen möglicherweise der Fehler „In jeder Kategorie muss mindestens ein Status ausgewählt werden.“ angezeigt.

#### Vorlagen

**Fehler beim Anhängen der Vorlage an das Projekt**

Beim Versuch, eine Vorlage an ein Projekt anzuhängen, wird folgender Fehler angezeigt:

„Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.“

Dies tritt auf, wenn die Person nicht über die Berechtigung zum Anzeigen des an die Vorlage angehängten benutzerdefinierten Formulars verfügt.

#### Updates

**Kommentare übertragen nicht zwischen alten und neuen Erlebnissen**

Ein Kommentar, der im alten Kommentierungserlebnis abgegeben wurde, ist im neuen Kommentierungserlebnis möglicherweise nicht sichtbar. Das Gegenteil kann auch auftreten.

+++

+++**Wartungs-Update vom Donnerstag, 11. Januar 2023**

### Wartungs-Update am 11. Januar 2023

#### Pinnwände

**Abgeschlossene Karten werden auf dynamischen Pinnwänden nicht ordnungsgemäß geladen**

Zuvor bestand die einzige Möglichkeit, abgeschlossene Arbeiten auf einer dynamischen Pinnwand einzubeziehen, darin, die Karten als archivierte Karten zu laden. Andernfalls wurden die abgeschlossenen Karten überhaupt nicht auf die Pinnwand geladen. Dies führte zu Problemen bei der Suche nach Karten.

Beim Erstellen einer dynamischen Pinnwand werden abgeschlossene Karten standardmäßig als archivierte Karten geladen. Sie können jedoch die Option „Abgeschlossene Karten nicht archivieren“ auswählen, um alle abgeschlossenen Karten auf der Pinnwand als sichtbare Karten in der Spalte „Abgeschlossen“ zu laden.

+++

## Frühere Wartungs-Updates

Informationen zu früheren Wartungs-Updates finden Sie hier:

* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2023](2023-updates.md)
* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2022](2022-updates.md)
* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2021](2021-updates.md)
