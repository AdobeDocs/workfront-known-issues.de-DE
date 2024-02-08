---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '1518'
ht-degree: 86%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2024 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [Frühere Wartungs-Updates](#previous-maintenance-updates)

## Updates im Februar 2024

+++**Wartungs-Update vom Freitag, 8. Februar 2024**

### Wartungs-Update am 8. Februar 2024

#### Pinnwände

**Karte kann nicht in einer Spalte mit [!UICONTROL Verschieben] options**

Wenn ein Benutzer versucht, eine Karte in einer Spalte mithilfe der[!UICONTROL Spaltenanfang]&quot; oder &quot;[!UICONTROL Spaltenende]&quot;im Menü mit drei Punkten aus, die Karte wird nicht verschoben.

**Karten bleiben bei Iterationsänderungen bestehen**

Wenn eine Benutzerin bzw. ein Benutzer eine Iteration auf einer Pinnwand anzeigt und dann die Iteration ändert, sind die für die neue Iteration angezeigten Karten die Karten aus einer Iteration, die die Benutzerin bzw. der Benutzer zuvor gesehen hat.

#### Berichte

**Spalte &quot;Kein Wert&quot;zeigt keine Ergebnisse an**

Wenn ein Diagrammbericht einen &quot;[!DNL No value]&quot;, zeigt die Spalte keine Daten an, auch wenn Daten vorhanden sein sollten.

#### Ressourcenverwaltung

**Falsche Finanzberechnungen aufgrund von Problemen mit der Auftragsrolle**

Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.

Dies liegt daran, dass Aufgabengebiete automatisch doppelte Raten ohne Start- oder Enddatum erstellen. Da sie kein Start- oder Enddatum haben, werden sie bei der Ausführung von Finanzberechnungen als Wert von 0 behandelt.

+++

+++**Wartungs-Update vom Freitag, 1. Februar 2024**

### Wartungs-Update am 1. Februar 2024

#### Anmeldung

**Benutzer, die SSO verwenden, werden beim Anmelden nicht zum ursprünglichen Speicherort weitergeleitet**

Wenn sich ein Benutzer auf einer Seite in [!DNL Workfront] und melden sich mit SSO an, wenn die Anmeldung abgeschlossen ist, werden sie an [!UICONTROL Startseite] anstelle der Seite, auf der sie sich vor der Anmeldung befanden.

#### Vorlagen

**Fehler beim Kopieren von Vorlagen**

Beim Versuch, eine neue oder vorhandene Vorlage zu kopieren, wird die Vorlage nicht kopiert und der folgende Fehler wird angezeigt:

„[!UICONTROL ID kann nicht null sein.]“

+++

## Updates im Januar 2024

+++**Wartungs-Update (Hotfix) vom Mittwoch, 30. Januar 2024**

### Wartungs-Update (Hotfix) am 30. Januar 2024

#### Berichte

**Im Feld Externe API werden nicht alle verfügbaren Werte in Listen und Berichten angezeigt.**

Zuvor konnten Benutzer den ausgewählten Wert (und den Wert) für ein externes Suchfeld in Listen und Berichten sehen, aber das Dropdown-Menü mit den Optionen aus der API wurde nicht angezeigt.

Wenn jetzt ein benutzerdefiniertes externes Lookup-Feld in einer Liste oder einem Bericht verwendet wird, ist das Dropdown-Menü mit allen Optionen aus der externen API verfügbar.

+++

+++**Wartungs-Update vom Freitag, 25. Januar 2024**

### Wartungs-Update am Freitag, 25. Januar 2024

#### Pinnwände

**Karten werden beim Ändern des Status nicht in die entsprechende Spalte verschoben**

Wenn der Status des verknüpften Objekts einer verbundenen Karte direkt auf dem Objekt geändert wird, wird die Karte nicht in die entsprechende Spalte verschoben. Wenn der Objektstatus auf der Karte geändert wird oder die Karte in die neue Spalte gezogen wird, verhält sich die Karte erwartungsgemäß.

#### Benachrichtigungen

**Kennzeichnungs-Benachrichtigungen wie angezeigt bleiben nicht bestehen**

Wenn eine Person ihre Benachrichtigungen als angezeigt markiert und dann zu einer anderen Seite innerhalb von [!DNL Workfront] wechselt, zeigt das Benachrichtigungssymbol weiterhin die Anzahl der ungelesenen Benachrichtigungen an, die vorhanden waren, bevor sie als angezeigt markiert wurden, und die Benachrichtigungen werden auch weiterhin angezeigt, wenn auf das Symbol geklickt wird. Dies ändert sich nicht, wenn sie als angezeigt markiert werden und zu einer anderen Seite oder zurück zur ursprünglichen Seite navigiert wird.

#### Updates

**Probleme mit dem Tagging von alten Kommentaren**

Wenn Benutzende in einem Kommentar im alten Kommentar-Erlebnis getaggt werden, treten die folgenden Probleme auf:

* Im Kommentar ist nur der Vorname der Person enthalten
* Der Name der Benutzenden ist nicht mit einem @-Symbol gekennzeichnet
* Der Name der Benutzenden ist nicht blau
* Der Name der Benutzenden ist kein Link zum Profil dieser Benutzenden.

Die Benutzenden erhalten wie erwartet eine E-Mail-Benachrichtigung zum Tag.

+++

+++**Wartungs-Update vom Freitag, 18. Januar 2024**

### Wartungs-Update am Freitag, 18. Januar 2024

#### Pinnwände

**Es können keine Dokumente an eine Karte angehängt werden**

Beim Versuch, ein Dokument an eine verknüpfte Karte anzuhängen, lässt sich das Dokument auswählen, das angehängt werden soll, das Dokument wird jedoch nicht im Dokumentbereich der Karte angezeigt und ist nicht an das Objekt angehängt, mit dem die Karte verknüpft ist.

Dieser Vorfall wurde für Karten im Zusammenhang mit Problemen gemeldet.

**Karte wird in mehreren Sprints angezeigt**

Wenn Benutzende einen Sprint auf Pinnwänden anzeigen, werden Karten aus unterschiedlichen Sprints auf der Pinnwand angezeigt. Dieses Problem tritt vorübergehend auf.

**Karte wird bei Verwendung der Ansicht „Pinnwände“ in einem Projekt nicht geschlossen**

Wenn eine Benutzerin bzw. ein Benutzer die Ansicht „Pinnwände“ in einer Aufgabenliste in einem Projekt anzeigt und eine Karte erstellt, wird die Karte nicht geschlossen oder gespeichert. Dadurch wird verhindert, dass die Benutzerin bzw. der Benutzer zum Projekt zurückkehrt.

Um die Karte zu schließen, muss die Benutzerin bzw. der Benutzer die URL bearbeiten, um „Pinnwand“ und alles, was sich rechts neben „Pinnwand“ befindet, zu entfernen.

**Karten bleiben bei Iterationsänderungen bestehen**

Wenn eine Benutzerin bzw. ein Benutzer eine Iteration auf einer Pinnwand anzeigt und dann die Iteration ändert, sind die für die neue Iteration angezeigten Karten die Karten aus einer Iteration, die die Benutzerin bzw. der Benutzer zuvor gesehen hat.

**Fehler im Kartenabschnitt [!UICONTROL Kommentare]**

Wenn jemand eine Karte aufruft und zum Abschnitt [!UICONTROL Kommentare] scrollt, werden nicht die Kommentare, sondern eine Fehlermeldung angezeigt:

„[!UICONTROL Etwas ist schiefgelaufen. Bitte versuchen Sie es später erneut.]&quot;

**Probleme beim Anzeigen von Unteraufgaben-Status**

Die folgenden Probleme wurden in Bezug auf die Anzeige des Status von Unteraufgaben auf einer Karte auf Pinnwänden gemeldet:

* Der Status wird auch dann als „Status auswählen“ angezeigt, wenn die Aufgabe bereits über einen Status verfügt. Dieser Status wird angezeigt, wenn die Aufgabe direkt angezeigt wird.
* Beim Versuch, einen Status auszuwählen, wird der Bildschirm leer angezeigt und muss aktualisiert werden.

**„[!UICONTROL Sie haben keinen Zugriff]“ beim Anzeigen von Kommentaren auf einer Karte**

Wenn Benutzende versuchen, Kommentare auf einer Karte anzuzeigen, die nicht mit einem [!DNL Workfront]-Objekt verbunden ist, sehen sie die folgende Meldung:

„[!UICONTROL Sie haben keine Zugriffsberechtigung, um Kommentare zu diesem Objekt anzuzeigen]“

Dies kann auch auftreten, wenn die Benutzenden zuvor Kommentare auf der Karte sehen konnten.

#### Benutzerdefinierte Formulare in meiner Gruppe

**Benutzerdefinierte Formulare können nicht stapelweise zu Vorlagenaufgaben hinzugefügt oder aus diesen entfernt werden**

Wenn Benutzende versuchen, ein benutzerdefiniertes Formular in einer Vorlagenaufgabe stapelweise hinzuzufügen oder zu entfernen, wird das Formular nicht hinzugefügt bzw. entfernt und es wird der folgende Fehler angezeigt:

[!UICONTROL Versuchen Sie es erneut. Ungültiger Parameter: templateID-Wert „XXXXXXXXXXXXXXXX“]

Wenn Benutzende die Vorlage mit der angegebenen GUID lokalisieren und dann versuchen, benutzerdefinierte Formulare für die restlichen Vorlagenaufgaben hinzuzufügen oder zu entfernen, tritt der Fehler erneut mit einer anderen templateID auf.

Benutzerdefinierte Formulare können für eine einzelne Vorlagenaufgabe hinzugefügt oder entfernt werden. Dieser Fehler bezieht sich nur auf das stapelweise Hinzufügen oder Entfernen.

#### Portfolios

**Benutzerdefinierte Terminologie gilt nicht für Gruppenseite**

Bei der Festlegung benutzerdefinierter Terminologie auf der Ebene des Portfolios gilt die Terminologie nicht für die Seite auf Gruppenebene.

#### Setup

**Optionale Status können nicht ausgeblendet werden**

Beim Versuch, optionale Status auf System- und Gruppenebene auszublenden, wird der Status nicht ausgeblendet. Beim Anzeigen des Status ist die Option zum Ausblenden des Status nicht aktiviert, obwohl Benutzende ihn aktiviert und die Änderungen gespeichert haben.

**Standardmäßige Problemstatus fehlen in einigen Problemtypen im Setup**

Wenn jemand den Problemstatus im Setup anzeigt, zeigt sich, dass die standardmäßigen Status für Probleme (Neu, In Bearbeitung und Abgeschlossen) in einigen Problemtypen fehlen. Die standardmäßigen Status bieten keine Möglichkeit, den Problemtyp zu ändern. Daher lässt sich der Status für die Anzeige der betroffenen Problemtypen nicht neu konfigurieren.

#### Teams

**Probleme beim Festlegen von Team-Status für die Schaltfläche [!UICONTROL Fertig]**.

Die folgenden Probleme wurden bezüglich des Status für die Schaltfläche [!UICONTROL Fertig] beim Bearbeiten oder Erstellen eines Teams gemeldet:

* Einige Status fehlen möglicherweise im Bereich der Schaltfläche „Fertig“ des Fensters [!UICONTROL Neues Team] oder im Bereich [!UICONTROL Team-Einstellungen] eines vorhandenen Teams.
* Wenn Benutzende versuchen, das Team zu speichern, wird ihnen möglicherweise der Fehler „In jeder Kategorie muss mindestens ein Status ausgewählt werden.“ angezeigt.

#### Vorlagen

**Fehler beim Anhängen von Vorlagen an ein Projekt**

Beim Versuch, eine Vorlage an ein Projekt anzuhängen, wird folgender Fehler angezeigt:

„Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.“

Dies tritt auf, wenn die Person nicht über die Berechtigung zum Anzeigen des an die Vorlage angehängten benutzerdefinierten Formulars verfügt.

#### Updates

**Kommentare werden nicht vom alten zum neuen Erlebnis übertragen**

Ein Kommentar, der im alten Kommentierungserlebnis abgegeben wurde, ist im neuen Kommentierungserlebnis möglicherweise nicht sichtbar. Das Gegenteil kann ebenfalls auftreten.

+++

+++**Wartungs-Update vom Freitag, 11. Januar 2024**

### Wartungs-Update am Freitag, 11. Januar 2024

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
