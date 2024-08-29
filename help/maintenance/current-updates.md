---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: adfed546c37dc86b686598bb5b836838963e00e6
workflow-type: tm+mt
source-wordcount: '5326'
ht-degree: 89%

---

# Wartungs-Updates für [!DNL Workfront]

>[!NOTE]
>
>Informationen zu Wartungsausfällen für alle Adobe-Produkte, einschließlich Workfront, finden Sie auf der [Adobe-Statusseite](https://status.adobe.com/).

Auf dieser Seite werden die in den wöchentlichen Workfront-Updates behobenen Probleme beschrieben.

Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2024 durchgeführt wurden, finden Sie unter [Frühere Wartungs-Updates](#previous-maintenance-updates)

Die folgenden Wartungs-Updates wurden 2024 vorgenommen.

## Updates im August 2024

+++**Wartungs-Update vom Freitag, 29. August 2024**

### Wartungs-Update am 29. August 2024

#### Benutzerdefinierte Formulare

**Forms verwendet standardmäßig Projektformulare**

Wenn ein Benutzer ein benutzerdefiniertes Formular erstellt und einen Objekttyp für das Formular auswählt, wird der Objekttyp ignoriert und das Formular wird als benutzerdefiniertes Projekt-Formular erstellt.

#### Dokumente

**Durch Klicken auf einen Dokumentnamen wird eine leere Seite angezeigt**

Wenn ein Benutzer versucht, Dokumentdetails durch Klicken auf den Namen des Dokuments in einer Dokumentliste anzuzeigen, wird die Liste ausgeblendet und der Benutzer wird nicht zu den Dokumentdetails weitergeleitet.

#### Startseite

**Das Widget ausstehende Genehmigungen zeigt gelöschte Dokumente an**

Wenn ein Benutzer sein Widget &quot;Home Pending Approvals&quot;anzeigt, werden ihm Dokumente angezeigt, die gelöscht wurden. Wenn der Benutzer auf eines dieser Dokumente klickt, wird er auf eine leere Seite geleitet.

#### Benutzende

**Das Feld für das E-Mail-Gebietsschema des Benutzerprofils wurde deaktiviert**

Für Unternehmen mit IMS werden Sprachvoreinstellungen im Adobe Experience Cloud-Profil jedes Benutzers gespeichert. Das Feld E-Mail-Gebietsschema im Workfront-Benutzerprofil wurde deaktiviert (nur für IMS-Organisationen) und eine QuickInfo zu diesem Feld enthält Anweisungen zum Zugriff auf Spracheinstellungen im Adobe-Profil.

Dadurch wird ein Problem behoben, durch das ein Administrator, der versucht, die Einstellung für das E-Mail-Gebietsschema eines Benutzers zu ändern, auf Englisch zurückgesetzt wird.

+++

+++**Wartungs-Update vom Freitag, 22. August 2024**

### Wartungs-Update am 22. August 2024

#### Berichte

**Der Klick auf einen Bericht aus dem Bereich &quot;Benutzerdefinierte Felder&quot;der Einrichtung** ist nicht möglich.

Wenn ein Benutzer den Bereich Benutzerdefinierte Forms > Felder des Setups anzeigt und die Ansicht das Feld für native Berichte enthält, funktionieren die Links zu den Berichten nicht. Der Benutzer sollte auf den Namen eines Berichts klicken und zum Bericht weitergeleitet werden können, aber das Klicken auf den Namen des Berichts ist nicht effektiv.

+++

+++**Wartungs-Update vom Freitag, 15. August 2024**

### Wartungs-Update am 15. August 2024

#### Pinnwände

**Probleme mit doppelten Karten**

Die folgenden Probleme bezüglich doppelter Karten in Pinnwänden wurden gemeldet:

* Eine Karte wird zweimal angezeigt. Dies kann durch Aktualisieren der Seite behoben werden.
* Wenn Benutzende eine der duplizierten Karten löschen, werden alle Instanzen dieser duplizierten Karte gelöscht.

#### Benachrichtigungen

**Hopfenfehler beim Festlegen der Benachrichtigungseinstellungen**

Wenn ein Benutzer versucht, die Benachrichtigungseinstellungen anzuzeigen, wird der folgende Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies wurde in den folgenden Bereichen gemeldet:

* Benachrichtigungseinstellungen für ein Benutzerprofil
* Bereich &quot;Ereignisbenachrichtigungen&quot;in der Einrichtung

#### Projekte

**Währungssymbol ist beim Exportieren falsch**

Wenn ein Benutzer ein Problem exportiert, stimmt das Währungssymbol im Export nicht mit dem im Projekt oder im Problem festgelegten Währungssatz überein.

#### Korrekturabzüge

**Markups für den Testversand sind ungenau**

Testversand-Markups sind auf PDF-Ausdrucken, die per E-Mail von der Funktion &quot;Testdruck&quot;empfangen wurden, falsch ausgerichtet.


+++

+++**Wartungs-Update vom Freitag, 8. August 2024**

### Wartungs-Update am 8. August 2024

#### Pinnwände

**Karte enthält keine Unteraufgaben**

Wenn Benutzende eine Karte für eine Aufgabe anzeigen, die eine übergeordnete Aufgabe ist, werden die Unteraufgaben dieser übergeordneten Aufgabe nicht auf der Karte angezeigt. Stattdessen zeigt die Karte an, dass es 0 Unteraufgaben gibt.

### Berichte

**Berichtbereitstellungen sind verzögert oder fehlen**

Berichte mit geplanten Sendungen werden nicht erwartungsgemäß bereitgestellt. Sie können sich verspäten oder gar nicht zugestellt werden.

#### Setup

**&quot;Anmelden als&quot;führt zum leeren Bildschirm**

Wenn sich ein Administrator als ein anderer Benutzer anmeldet, wird dem Administrator kein Bildschirm angezeigt, anstatt das Konto dieses Benutzers zu sehen.

+++

+++**Wartungs-Update vom Freitag, 1. August 2024**

### Wartungs-Update am 1. August 2024

#### Dokumente

**Ansicht für Dokumentenliste kann nicht erstellt werden**

Wenn Benutzende versuchen, eine neue Ansicht einer Dokumentenliste zu erstellen, wird der Bildschirm leer und die Ansicht lässt sich nicht erstellen.

Bestehende Ansichten funktionieren erwartungsgemäß.

#### Integrationen

**Probleme mit der Dropbox-Integration**

Die folgenden Probleme wurden bezüglich der Dropbox-Integration gemeldet:

* Wenn Benutzende versuchen, in der Dropbox-Dateiauswahl nach einer Datei zu suchen, wird eine Fehlermeldung bezüglich der Autorisierung angezeigt und die Dateiauswahl ruft die Datei nicht von Dropbox ab.
* Wenn Benutzende versuchen, einen verknüpften Ordner zu öffnen, wird eine Fehlermeldung mit dem Hinweis angezeigt, dass die Dateien oder der Ordner nicht mehr in Dropbox vorhanden sind.

Diese Probleme sind auf Probleme mit Dropbox und nicht auf Workfront zurückzuführen.

+++

## Updates im Juli 2024

+++**Wartungs-Update vom Freitag, 25. Juli 2024**

### Wartungs-Update vom Freitag, 25. Juli 2024

#### Benutzerdefinierte Formulare

**Dropdown-Liste wird geschlossen, wenn mehrere Werte ausgewählt werden**

Wenn ein Benutzer versucht, mehrere Werte in einem benutzerdefinierten Formularfeld auszuwählen, wird die Dropdown-Liste geschlossen, nachdem der erste Wert ausgewählt wurde.

Dies tritt auf, wenn das Feld mit der Anzeigenlogik im benutzerdefinierten Formular verknüpft ist.

#### Benachrichtigungen

**In E-Mail-Benachrichtigungen nicht sichtbare Miniaturansichten**

Wenn Benutzende eine E-Mail-Benachrichtigung zu einer Dokumentgenehmigung anzeigen, wird die Miniaturansicht des Dokuments nicht in der E-Mail angezeigt.

Dies wurde in Gmail gemeldet.

+++

+++**Wartungs-Update vom Freitag, 18. Juli 2024**

### Wartungs-Update vom Freitag, 18. Juli 2024

#### Agile

**Die Meldungsfläche wird beim Hinzufügen einer Unteraufgabe leer gelassen**

Wenn Benutzende versuchen, einer Story-Pinnwand eine Unteraufgabe hinzuzufügen, während ein Filter ausgewählt ist, bleibt der Bildschirm leer und die Unteraufgabe lässt sich nicht hinzufügen.

#### Startseite

**Elemente aus [!UICONTROL Home Calendar] oder [!UICONTROL Work List]** können nicht geöffnet werden

Wenn Benutzende versuchen, ein Arbeitselement oder einen Korrekturabzug über den [!UICONTROL Startseitenkalender] oder die [!UICONTROL Arbeitsliste der Startseite] zu öffnen, wird das Element nicht geöffnet.

**Die eigene Startseite des Administrators wird angezeigt, wenn er als anderer Benutzer angemeldet ist**

Wenn ein Administrator als ein anderer Benutzer angemeldet ist und die Startseite dieses Benutzers anzeigt, wird die eigene Startseite des Administrators angezeigt.

#### Korrekturabzüge

**Das Schließen eines Testversands führt zur Seite &quot;Produktdokumente&quot;**

Wenn Benutzende einen Korrekturabzug anzeigen und diesen schließen, werden sie auf die Seite mit den Projektdokumenten geleitet, anstatt auf die Seite, von der aus der Korrekturabzug geöffnet wurde.

#### Workfront

**Benutzerdefinierte Terminologie wird nicht angewendet**

Die benutzerdefinierte Terminologie, die in der Layout-Vorlage festgelegt wurde, wird in einigen Bereichen von Workfront nicht angezeigt. Stattdessen wird die nicht benutzerdefinierte Standardterminologie angezeigt.

Dies wurde in den folgenden Bereichen gemeldet:

* Menüregisterkarten
* Seitenkopfzeilen
* Beschreibungen der aufgelisteten Projekte


+++

+++**Wartungs-Update vom Freitag, 11. Juli 2024**

### Wartungs-Update vom 11. Juli 2024

#### Probleme

**Probleme: Fehler bei der erweiterten Zuweisung zu einem Problem**

Wenn Benutzende versuchen, in Workfront eine erweiterte Zuweisung für ein Problem vorzunehmen, wird das Problem nicht zugewiesen und die Person erhält die folgende Fehlermeldung:

„[!UICONTROL APIModel INTERNAL unterstützt keine Felddauer (OpTask)]“

#### Berichte

**Fehler „Hoppla“ beim Festlegen von Matrixeinstellungen für den Stundenbericht**

Beim Versuch, die Matrixeinstellungen für einen Stundenbericht festzulegen, lassen sich die Einstellungen nicht festlegen. Folgende Fehlermeldung wird angezeigt:

* „[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“


+++

+++**Wartungs-Update vom Freitag, 4. Juli 2024**

### Wartungs-Update vom 4. Juli 2024

#### Startseite

**Das Menü mit den drei Punkten ist ineffektiv**

Wenn Benutzende auf das Menü „Mehr“ mit den drei Punkten in der veralteten Startseite-Arbeitsliste klicken, wird keine Aktion ausgelöst.

#### Berichte

**„Keine Daten zum Anzeigen vorhanden“, wenn der Gruppierungsname einen Schrägstrich oder einen umgekehrten Schrägstrich aufweist**

Wenn Benutzende ein Diagramm in einem Bericht anzeigen und auf eine Gruppierung im Diagramm klicken und diese Gruppierung einen Schrägstrich (/) oder einen umgekehrten Schrägstrich (\) im Namen aufweist, werden in den daraufhin angezeigten Details die Elemente in der Gruppierung nicht angezeigt und die Benutzenden erhalten die Meldung „Keine Daten zum Anzeigen vorhanden“.

#### Aufgaben

**Das Aufgabengebiet verschwindet nicht aus der Liste, wenn eine Benutzerin oder ein Benutzer einer Aufgabe zugewiesen wird**

Wenn einer Aufgabe ein Aufgabengebiet zugewiesen ist und diese Aufgabe einer Benutzerin oder einem Benutzer mit diesem Aufgabengebiet zugewiesen wird, verschwindet das Aufgabengebiet nicht aus der Zuweisungsliste.


+++

## Updates im Juni 2024

+++**Wartungs-Update am Freitag, 27. Juni 2024**

### Wartungs-Update am Freitag, 27. Juni 2024

#### Pinnwände

**Nur Pinnwandbesitzende können Konfigurationsfilter aktualisieren**

Aus Sicherheitsgründen können nur Pinnwandbesitzende die Pinnwandfilter im Panel „Konfigurieren“ ändern.

#### Berichte

**Bericht wird nicht geladen, wenn es sich bei der Standardwährung um USD handelt**

Wenn Benutzende versuchen, einen Bericht mit der Standardwährung USD anzuzeigen, wird der Bericht nicht geladen.

#### Updates

**Kopierter Link wird nicht ordnungsgemäß eingefügt**

Wenn Benutzende einen Link aus einer Aktualisierung kopieren, indem sie mit der rechten Maustaste klicken und „[!UICONTROL Link-Adresse kopieren]“ auswählen, und den Link dann in eine Aktualisierung einfügen, wird der Link nicht ordnungsgemäß eingefügt. Nur der erste Teil des Links ist ein Link und der Rest der URL wird ignoriert.

Wenn Sie den Link mit einer anderen Methode als „[!UICONTROL Link-Adresse kopieren]“ kopieren, können Sie den Link erwartungsgemäß einfügen.

+++

+++**Wartungs-Update am Freitag, 20. Juni 2024**

### Wartungs-Update am Freitag, 20. Juni 2024

#### Navigation

**Schaltfläche „Zurück“ geht nicht zur vorherigen Seite zurück**

Wenn jemand in Workfront auf die Schaltfläche „Zurück“ des Browsers klickt, kann eine der folgenden Situationen eintreten.

* Der Name der Browser-Registerkarte ändert sich, die Seite ändert sich jedoch nicht. Durch erneutes Klicken auf die Schaltfläche „Zurück“ kann das Problem behoben werden.
* Die Person wird zur Landingpage des Browsers weitergeleitet.

#### Korrekturabzüge

**Korrekturabzug-Viewer kann nicht geschlossen werden**

Wenn eine Benutzerin oder ein Benutzer einen Korrekturabzug im Korrekturabzug-Viewer betrachtet und versucht, den Korrekturabzug durch Klicken auf das X in der oberen rechten Ecke zu schließen, wird der Korrekturabzug nicht geschlossen.

+++

+++**Wartungs-Update am Freitag, 13. Juni 2024**

### **Wartungs-Update am Freitag, 13. Juni 2024**

#### Gruppen

**Untergruppe kann nicht hinzugefügt werden**

Wenn Benutzende versuchen, einer Gruppe eine vorhandene Untergruppe hinzuzufügen, funktioniert die Schaltfläche „Speichern“ nicht und die Untergruppe wird nicht hinzugefügt.

+++

+++ **Wartungs-Update am 6. Juni 2024**

### Wartungs-Update am 6. Juni 2024

#### Benutzerdefinierte Formulare

**Einschränkungen für native Felder im Formular-Designer**

Für benutzerdefinierte Formulare, die im Formular-Designer erstellt wurden, werden jetzt mehrere native Felder unterstützt. Zuvor galt ein Limit von einem nativen Feld pro Formular.

+++

## Updates im Mai 2024

+++ **Wartungs-Update am 30. Mai 2024**

### Wartungs-Update am 30. Mai 2024

#### Benutzerdefinierte Formulare

Fehler beim Bearbeiten beschreibender Textfelder

Wenn Benutzende versuchen, Änderungen an einem benutzerdefinierten Formular vorzunehmen, werden die Änderungen nicht gespeichert und die folgende Fehlermeldung wird angezeigt:

„Doppelte Schlüsselwerte verletzen die Eindeutigkeitsbeschränkung“

Dies wurde im alten Formular-Builder gemeldet.

#### Updates

**Beim Kopieren und Einfügen einer Erwähnung werden erwähnte Benutzende nicht benachrichtigt**

Wenn Benutzende einen Kommentar kopieren, der eine Erwähnung im @-Format enthält, und diesen Kommentar dann in den Bereich „Aktualisierungen“ eines anderen Objekts einfügen, wird die erwähnte Person nicht über den eingefügten Kommentar informiert.

+++

+++ **Wartungs-Update am 23. Mai 2024**

### Wartungs-Update am 23. Mai 2024

#### Berichte

Wenn Benutzende einen Bericht anzeigen und auf die Zurück-Schaltfläche des Browsers klicken, kann eine der folgenden Situationen eintreten:

* Die Person bleibt auf der Bericht-Seite.
* Die Person wird zur Landingpage des Browsers weitergeleitet.
* Die Person wird zur Anmeldeseite weitergeleitet.

Dies wurde beim Chrome-Browser gemeldet.

#### Updates

**Getaggte Benutzende können nicht sehen, wer sie getaggt hat**

Wenn eine Benutzende in einer Aktualisierung getaggt werden, können sie nicht sehen, wer sie getaggt hat. Dies geschieht, wenn die Einstellung „Personen in anderen Firmen sollten nur Benutzer anzeigen dürfen aus...“ auf „Ihrer Firma“ eingestellt ist.

**Das Tagging von Benutzenden mit „@“ im Bedienfeld „Zusammenfassung“ funktioniert nicht**

Wenn Benutzende versuchen, andere Benutzende im Bereich „Aktualisierungen“ eines Bedienfelds „Zusammenfassung“ mit einem „@“ zu versehen, passiert nichts, wenn auf den Namen der Person in der Dropdown-Liste geklickt wird. Der Versuch, Benutzende ein zweites Mal zu taggen, funktioniert erwartungsgemäß.

+++

+++**Wartungs-Update am 16. Mai 2024**

### Wartungs-Update am 16. Mai 2024

#### Setup

**Standardmäßige Problemstatus fehlen in einigen Problemtypen im Setup**

Wenn jemand den Problemstatus im Setup anzeigt, zeigt sich, dass die standardmäßigen Status für Probleme (Neu, In Bearbeitung und Abgeschlossen) in einigen Problemtypen fehlen. Die standardmäßigen Status bieten keine Möglichkeit, den Problemtyp zu ändern. Daher lässt sich der Status für die Anzeige der betroffenen Problemtypen nicht neu konfigurieren.

#### Benutzende

**Benutzende können nicht gelöscht werden**

Beim Versuch, Benutzende zu löschen, werden diese nicht gelöscht. Dies wurde von Organisationen berichtet, die zu Adobe Admin Console migriert sind.

+++

+++**Wartungs-Update am 9. Mai 2024**

### Wartungs-Update am 9. Mai 2024

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update am 2. Mai 2024**

### Wartungs-Update am 2. Mai 2024

#### Erfassen der Zeit

**Stunden für Aufgaben oder Probleme können nicht bearbeitet werden**

Beim Versuch, die Stunden für eine Aufgabe oder ein Problem zu bearbeiten, werden die Änderungen nicht gespeichert.

+++

## Updates im April 2024

+++**Wartungs-Update am 25. April 2024**

### Wartungs-Update am 25. April 2024

#### Updates

**Nummerierte Listen sind nicht korrekt nummeriert**

„Wenn eine Benutzerin bzw. ein Benutzer einen Kommentar sendet, der eine nummerierte Liste enthält, zeigt diese Liste in der Aktualisierung eine falsche Nummerierung an.

Dies wurde für die neue Kommentarerfahrung berichtet.

**Text bleibt beim Verlassen von und Zurückkehren zu Kommentaren nicht erhalten**

Wenn Benutzende einen Kommentar verfassen, der eine @Erwähnung enthält, dann den Kommentar vor dem Senden verlassen und wieder dorthin zurückkehren, fehlt im Kommentarentwurf jeglicher Text, der nach der @Erwähnung eingegeben wurde.

Dies wurde für die neue Kommentarerfahrung berichtet.

+++

+++**Wartungs-Update am 18. April 2024**

### Wartungs-Update am 18. April 2024

#### Agile

**Kanban-Karten zeigen keine benutzerdefinierten Felder an**

Wenn ein Kanban-Board angezeigt wird, das so konfiguriert wurde, dass es benutzerdefinierte Felder enthält, werden diese benutzerdefinierten Felder möglicherweise nicht angezeigt.

#### Kalender

**Fehler beim Aktualisieren des Kalenders**

Beim Anzeigen eines Kalenders und Aktualisieren der Seite wird ein Fehler „Hoppla“ angezeigt. Die Daten im Kalender werden wie erwartet angezeigt, sind aber möglicherweise durch die Fehlermeldung verdeckt.

#### Benutzerdefinierte Formulare

**Externe Suchfelder geben keine Ergebnisse zurück**

Wenn ein externes Suchfeld auf ein Mehrfachauswahlfeld verweist, in dem nur ein Wert ausgewählt ist, gibt das Feld den Wert nicht zurück.

Verweist ein externes Suchfeld beispielsweise auf ein Mehrfachauswahlfeld, in dem die Werte „Rot“ und „Blau“ ausgewählt sind, funktioniert das Feld wie erwartet. Wenn dagegen im Feld nur die Option „Rot“ ausgewählt ist, gibt das externe Suchfeld keinen Wert zurück.

#### Projekte

**Problem kann nicht in Projekt konvertiert werden, wenn ein Web-Korrekturabzug angefügt ist**

Wenn an ein Problem ein Web-Korrekturabzug angefügt ist (ein URL-Korrekturabzug mit einem Link eines externen Dokumentenanbieters wie SharePoint) und Benutzende versuchen, dieses Problem in ein Projekt zu konvertieren, schlägt die Konvertierung fehl und das Projekt wird nicht erstellt. Der folgende Fehler wird angezeigt:

„Fehler beim Kopieren der Datei (Datei-GUID). Entfernen Sie die Datei oder kontaktieren Sie den Support und versuchen Sie es erneut.“

+++

+++**Wartungs-Update am 11. April 2024**

### Wartungs-Update am 11. April 2024

#### Suchen

**Bearbeitung über Suche nicht möglich**

Wenn Benutzende die erweiterte Suche verwenden und versuchen, die Suchergebnisse zu bearbeiten oder eine Massenbearbeitung vorzunehmen, reagiert das Symbol „Bearbeiten“ nicht.

#### Updates

**Vorschau eines Bildes in Aktualisierungen ist unscharf**

Wenn sich Benutzende Aktualisierungen ansehen und auf die Lupe für ein Bild klicken, um eine Vorschau des Bildes zu öffnen, ist die Vorschau extrem pixelig und unscharf.

Wenn die Benutzenden das Bild herunterladen, wird es mit der erwarteten Auflösung angezeigt.

**Meldung „[!UICONTROL Ihr Kommentar kann nicht veröffentlicht werden]“ beim Beantworten**

Beim Versuch, im neuen Kommentierungserlebnis auf eine Nachricht zu antworten, wird die Antwort nicht gespeichert und es wird die folgende Meldung angezeigt:

„[!UICONTROL Ihr Kommentar kann derzeit nicht veröffentlicht werden. Bitte warten Sie einen Moment und versuchen Sie es dann erneut.]“

+++

+++**Wartungs-Update am 4. April 2024**

### Wartungs-Update am 4. April 2024

#### Suchen

**Bearbeitung über Suche nicht möglich**

Wenn Benutzende die erweiterte Suche verwenden und versuchen, die Suchergebnisse zu bearbeiten oder eine Massenbearbeitung vorzunehmen, reagiert das Symbol „Bearbeiten“ nicht.

#### Updates

**Vorschau eines Bildes in Aktualisierungen ist unscharf**

Wenn sich Benutzende Aktualisierungen ansehen und auf die Lupe für ein Bild klicken, um eine Vorschau des Bildes zu öffnen, ist die Vorschau extrem pixelig und unscharf.

Wenn die Benutzenden das Bild herunterladen, wird es mit der erwarteten Auflösung angezeigt.

**Meldung „[!UICONTROL Ihr Kommentar kann nicht veröffentlicht werden]“ beim Beantworten**

Beim Versuch, im neuen Kommentierungserlebnis auf eine Nachricht zu antworten, wird die Antwort nicht gespeichert und es wird die folgende Meldung angezeigt:

„[!UICONTROL Ihr Kommentar kann derzeit nicht veröffentlicht werden. Bitte warten Sie einen Moment und versuchen Sie es dann erneut.]“

+++

+++**Wartungs-Update am 4. April 2024**

### Wartungs-Update am 4. April 2024

#### Integrationen

**Dokumente werden beim Erstellen einer Anfrage von[!DNL Outlook]** nicht angehängt

Wenn Benutzende eine Anfrage von [!DNL Outlook] erstellen, werden die an die E-Mail angehängten Dokumente nicht an die Anfrage angehängt.

Dies wurde für die folgenden Anhangstypen gemeldet:

XLS
PDF

#### Erfassen der Zeit

**Benutzende können die Zeit für den aktuellen Tag nicht protokollieren**

Beim Versuch, die Zeit im Bereich „Updates“ zu protokollieren, ist der aktuelle Tag ausgegraut und Benutzende können die Zeit für den aktuellen Tag nicht protokollieren.

#### Updates

<!--no article-->

**Fehler beim Anzeigen von Kommentaren**

Beim Versuch, Kommentare im neuen Kommentierungserlebnis anzuzeigen, sind die Kommentare nicht zu sehen. Stattdessen wird die folgende Fehlermeldung angezeigt:

„Es ist ein Fehler aufgetreten. Bitte versuchen Sie es später erneut.“

Das alte Kommentierungserlebnis funktioniert wie erwartet.

+++

## Updates im März 2024

+++**Wartungs-Update am 28. März 2024**

### Wartungs-Update am 28. März 2024

#### Integrationen

**Dokumente werden beim Erstellen einer Anfrage von[!DNL Outlook]** nicht angehängt

Wenn Benutzende eine Anfrage von [!DNL Outlook] erstellen, werden die an die E-Mail angehängten Dokumente nicht an die Anfrage angehängt.

Dies wurde für die folgenden Anhangstypen gemeldet:

XLS
PDF

#### Korrekturabzüge

**Korrekturabzüge werden weiterhin im Widget „Meine Genehmigungen“ angezeigt**

Ein Korrekturabzug, der nicht mehr im Widget „Meine Genehmigungen“ angezeigt werden sollte, verbleibt im Widget. Dies kann vorkommen, wenn mehrere Personen gleichzeitig Entscheidungen über einen Korrekturabzug treffen oder eine Person eine Entscheidung trifft und diese schnell ändert.

#### Ressourcenverwaltung

**Diskrepanz bei budgetierten Stunden**

Die in einem der folgenden Bereiche angezeigten budgetierten Stunden stimmen möglicherweise nicht mit denen in einem der anderen folgenden Bereiche überein:

* Business Case
* Berichte
* Ressourcenbudgetierungs-Tool

#### Aufgaben

**QuickInfo des Vorgängers zeigt nicht den Aufgabennamen an**

Wenn Benutzende eine Aufgabenliste anzeigen und den Mauszeiger über das Symbol eines Vorgängers bewegen, um weitere Informationen zu erhalten, zeigt die angezeigte QuickInfo nicht den Namen der Vorgängeraufgabe an.

#### Updates

**Kommentare zu Dokumenten werden in Aktualisierungen des übergeordneten Objekts nicht angezeigt**

Wenn Benutzende einen Kommentar zu einem Dokument abgeben, wird dieser Kommentar nicht sofort im Bereich „Updates“ des übergeordneten Objekts des Dokuments angezeigt.

Dieses Problem wurde für die neue Kommentarerfahrung gemeldet. Kommentare werden in der alten Kommentarerfahrung wie erwartet angezeigt.

**Das Taggen von Benutzenden ist ineffektiv**

Wenn Benutzende in einem Kommentar getaggt werden, ist dieser Kommentar für die getaggten Benutzenden nicht sichtbar. Außerdem werden die getaggten Benutzenden nicht per E-Mail oder über eine In-App-Benachrichtigung über den Kommentar informiert.

Dies wurde für die alte Kommentarerfahrung gemeldet.

+++

+++**Wartungs-Update von Workfront Fusion am 28. März 2024**

### Wartungs-Update von Workfront Fusion am 28. März 2024

**RuntimeError mit Antwort 200 vom Workfront-Modul**

Ein Workfront-Modul kann die Antwort `RuntimeError [200]` zurückgeben. 200 bedeutet eine erfolgreiche Antwort, der Fehler zeigt jedoch, dass die Anfrage nicht erfolgreich war.

Dies kann vorkommen, wenn die Antwort extrem lang ist. Die Daten werden an Fusion zurückgegeben, können aber nicht von Fusion verarbeitet werden.

+++

+++**Wartungs-Update am 21. März 2024**

### Wartungs-Update am 21. März 2024

#### Updates

**Große Abstände zwischen Zeilen**

Wenn Benutzende eine Aktualisierung mit mehreren Zeilen eingeben und dafür die Eingabetaste verwenden oder wenn sie mehrere Zeilen in eine Aktualisierung einfügen, wird die Aktualisierung zwar wie erwartet angezeigt. Wird diese Aktualisierung dann jedoch in einem Bericht angezeigt, gibt es große Abstände zwischen den Zeilen.

Dies wurde für die neue Kommentarerfahrung berichtet.

**Das Taggen von Benutzenden mit „@“ ist ineffektiv**

Wenn Benutzende mit „@“ in einem Kommentar getaggt werden, werden sie nicht zum Bereich für getaggte Benutzende hinzugefügt und erhalten keine Benachrichtigung über den Kommentar.

Diese Fehlerbehebung gilt nur für die neue Kommentarerfahrung.

+++

+++**Wartungs-Update am 14. März 2024**

### Wartungs-Update am 14. März 2024

#### Korrekturabzüge

**Auf Korrekturabzüge, die aus verknüpften Dokumenten erstellt wurden, wird keine Korrekturabzugsvorlage angewendet**

Wenn Benutzende einen Korrekturabzug aus einem verknüpften Dokument erstellen, wird die Korrekturabzugsvorlage nicht korrekt angewendet und im Korrekturabzug fehlen möglicherweise Informationen wie der Workflow.

Dies gilt auch für Korrekturabzüge, die über die API und über Workfront Fusion erstellt wurden.

#### Benutzende

**Beim Erstellen von Benutzenden sind keine niedrigeren Zugriffsebenen verfügbar**

Wenn ein Benutzer bzw. eine Benutzerin einen anderen Benutzer oder eine andere Benutzerin erstellt, ist für die neu erstellten Benutzenden nur die Zugriffsebene der ersten Person verfügbar. Alle Zugriffsebenen mit niedrigeren Berechtigungen als die des Erstellers bzw. der Erstellerin sollten verfügbar sein, um sie der neuen Person zuzuweisen.

+++

+++**Wartungs-Update am 7. März 2024**

### Wartungs-Update am 7. März 2024

#### Pinnwände

**400-Fehler beim Hinzufügen einer Aufgabe zu einer Pinnwand**

Wenn Benutzende ein Projekt anzeigen und versuchen, einer Pinnwand eine Aufgabe hinzuzufügen, wird die Aufgabe nicht hinzugefügt und ein Fehler angezeigt:

Fehler: „400: undefined /boards-service/graphql“.

#### Startseite

**Fehler beim Inline-Bearbeiten einer Aufgabe im Widget „Meine Aufgaben“**

Beim Versuch, eine Aufgabe im Widget „Meine Aufgaben“ inline zu bearbeiten, wird der folgende Fehler angezeigt:

„Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browser-Seite, um mit Ihrer Arbeit fortzufahren.“


#### Workload Balancer

**Geplante Stunden werden im Workload Balancer nicht aktualisiert**

Wenn die geplanten Stunden in einem Projekt aktualisiert werden, werden sie im Workload Balancer nicht aktualisiert. Dies kann auch dann passieren, wenn die Änderung im Projekt korrekt widergespiegelt wird.

+++

+++**Wartungs-Update von Workfront Fusion am 7. März 2024

**Workfront-Korrekturabzug > Zeitüberschreitung des Moduls zur Überwachung des Korrekturabzugs**

Szenarien, in denen Workfront-Korrekturabzug > Modul zur Überwachung des Korrekturabzugs verwendet wird, werden möglicherweise aufgrund der Zeitüberschreitung des Moduls zur Überwachung des Korrekturabzugs deaktiviert.

+++

## Updates im Februar 2024

+++**Wartungs-Update am 29. Februar 2024**

### Wartungs-Update am 29. Februar 2024

#### Updates

**Aktualisierungen: Bildschirm wird leer, wenn einer Person eines anderen Unternehmens geantwortet wird**

Beim Versuch, auf einen Kommentar einer Person von einem anderen Unternehmen zu antworten, wird der Bildschirm leer.

Dies liegt daran, dass Benutzende nicht über die Berechtigung zum Anzeigen von Personen aus anderen Unternehmen verfügen.

+++

+++**Wartungs-Update am 22. Februar 2024**

### Wartungs-Update am 22. Februar 2024

#### Startseite

**[!UICONTROL Startseite]: [!UICONTROL Arbeitsbereich] und Pins werden nicht geladen**

Wenn sich Benutzende anmelden, können Probleme auftreten:

* Die neue [!UICONTROL Startseite] wird nicht geladen und ihnen wird der folgende Fehler angezeigt: „[!UICONTROL Ihre Arbeitsbereich-Informationen können nicht geladen werden. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“
* Die Pins der Benutzenden werden nicht geladen und der folgende Fehler wird angezeigt: „[!UICONTROL Ihre Pins sind aufgrund eines Systemfehlers nicht verfügbar. Versuchen Sie, Ihren Browser zu aktualisieren, um das Problem zu beheben.]“

#### Benutzende

**Gruppenadmins können die Zugriffsebene von Benutzenden nicht festlegen oder ändern**

<!--no article-->

Wenn Gruppenadmins versuchen, die Zugriffsebene von Benutzenden zu ändern, kann eine der folgenden Situationen eintreten:

* Das Feld für die Zugriffsebene ist deaktiviert.
* Die Gruppenadmins können keine niedrigere Zugriffsebene wählen.

#### Workload Balancer

**Beschriftung für arbeitsfreie Stunden**

Der Workload Balancer und der Kalender für persönliche Ausfallzeiten zeigen jetzt „[!UICONTROL Arbeitsfreie Stunden]“ für die Zeit an, in der sich eine Person freinimmt. Zuvor wurde in der Anzeige die Beschriftung „[!UICONTROL Arbeitszeiten]“ für arbeitsfreie Stunden angezeigt.

+++

+++**Wartungs-Update am 15. Februar 2024**

### Wartungs-Update am 15. Februar 2024

#### Probleme

**In Zeitfeldern wird bei der Massenbearbeitung von Problemen eine falsche Uhrzeit gespeichert**

Wenn jemand bei der Massenbearbeitung von Problemen ein Datum und eine Uhrzeit für ein Datumsfeld auswählt und speichert, ist die in diesem Feld gespeicherte Zeit nicht die ausgewählte Zeit. Stattdessen scheint die Zeit beim Speichern in UTC konvertiert zu werden.

#### Aufgaben

**Die Zuweisung einer Person zu einer oder mehreren Aufgaben wird aufgehoben**

Die Zuweisung einer Person zu einer Aufgabe kann automatisch aufgehoben werden. Dies kann bei einer oder mehreren Aufgaben der Fall sein. Die Aufhebung der Zuweisung wird nicht im Bereich „Systemaktualisierungen“ der Aufgaben angezeigt, obwohl sie im Abschnitt „Feeds aktualisieren“ des Setup-Menüs angezeigt wird.

#### Updates

**Deaktivierte Option für Bild ist beim Bearbeiten eines Kommentars verfügbar**

Nachdem ein[!DNL Workfront]-Administrator die Option zum Hinzufügen von Bildern zu Kommentaren deaktiviert hat, ist diese Option beim Erstellen eines Kommentars nicht verfügbar. Beim Bearbeiten eines vorhandenen Kommentars ist die Bildoption jedoch verfügbar.

+++

+++**Wartungs-Update am 8. Februar 2024**

### Wartungs-Update am 8. Februar 2024

#### Pinnwände

**Eine Karte kann nicht mithilfe der Optionen zum [!UICONTROL Verschieben] in einer Spalte verschoben werden**

Wenn versucht wird, eine Karte in einer Spalte mithilfe der Optionen [!UICONTROL Spaltenanfang] oder [!UICONTROL Spaltenende] im Menü mit den drei Punkten zu verschieben, wird die Karte nicht verschoben.

**Karten bleiben bei Iterationsänderungen bestehen**

Wenn eine Benutzerin bzw. ein Benutzer eine Iteration auf einer Pinnwand anzeigt und dann die Iteration ändert, sind die für die neue Iteration angezeigten Karten die Karten aus einer Iteration, die die Benutzerin bzw. der Benutzer zuvor gesehen hat.

#### Berichte

**Spalte „Kein Wert“ zeigt keine Ergebnisse an**

Wenn ein Diagrammbericht über die Spalte „[!DNL No value]“ verfügt, zeigt die Spalte keine Daten an, auch wenn Daten vorhanden sein sollten.

#### Ressourcenverwaltung

**Fehlerhafte Finanzberechnungen aufgrund von Problemen mit dem Aufgabengebiet**

Stunden- und Finanzberechnungen können falsch sein und Kosten von 0 anzeigen, obwohl Stunden in einem Aufgabengebiet protokolliert werden, das über einen Kostensatz verfügt.

Dies liegt daran, dass Aufgabengebiete automatisch doppelte Raten ohne Start- oder Enddatum erstellen. Da sie kein Start- oder Enddatum haben, werden sie bei der Ausführung von Finanzberechnungen als Wert von 0 behandelt.

+++

+++**Wartungs-Update am 1. Februar 2024**

### Wartungs-Update am 1. Februar 2024

#### Anmeldung

**Benutzende, die SSO verwenden, werden beim Anmelden nicht zum ursprünglichen Standort weitergeleitet**

Wenn sich Benutzende auf einer Seite in [!DNL Workfront] befinden und sich mit SSO anmelden, wenn die Anmeldung abgeschlossen ist, werden sie an die [!UICONTROL Startseite] weitergeleitet, anstelle der Seite, auf der sie sich vor der Anmeldung befanden.

#### Vorlagen

**Fehler beim Kopieren von Vorlagen**

Beim Versuch, eine neue oder vorhandene Vorlage zu kopieren, wird die Vorlage nicht kopiert und der folgende Fehler wird angezeigt:

„[!UICONTROL ID kann nicht null sein.]“

+++

## Updates im Januar 2024

+++**Wartungs-Update (Hotfix) am 30. Januar 2024**

### Wartungs-Update (Hotfix) am 30. Januar 2024

#### Berichte

**Im Feld „Externe API“ werden nicht alle verfügbaren Werte in Listen und Berichten angezeigt.**

Zuvor konnten Benutzende den ausgewählten Wert für ein externes Suchfeld in Listen und Berichten sehen (und bearbeiten), aber die Dropdown-Liste mit den Optionen aus der API wurde nicht angezeigt.

Wenn jetzt ein benutzerdefiniertes externes Suchfeld in einer Liste oder einem Bericht verwendet wird, ist die Dropdown-Liste mit allen Optionen aus der externen API verfügbar.

+++

+++**Wartungs-Update am 25. Januar 2024**

### Wartungs-Update am 25. Januar 2024

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

+++**Wartungs-Update am 18. Januar 2024**

### Wartungs-Update am 18. Januar 2024

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

#### Benutzerdefinierte Formulare

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

+++**Wartungs-Update am 11. Januar 2024**

### Wartungs-Update am 11. Januar 2024

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
