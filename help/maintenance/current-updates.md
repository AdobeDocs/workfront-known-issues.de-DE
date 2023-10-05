---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: f55aca778701e1319eaa7a7eb6ce8f3d0cd2b8c5
workflow-type: tm+mt
source-wordcount: '5929'
ht-degree: 89%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2023 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [früheren Wartungs-Updates](#previous-maintenance-updates)

## Updates im Oktober 2023

+++**Wartungs-Update vom 5. Oktober 2023**

**Das Board lädt langsam**

_Pinnwände_

Wenn ein Benutzer eine Pinnwand lädt, wird die Pinnwand extrem langsam geladen. Dies kann auch auftreten, wenn die Pinnwand eine kleine Anzahl von Karten hat.

Archivierte Karten, selbst wenn sie nicht angezeigt wurden, wirkten sich auf die Ladezeit der Pinnwand aus.

**Karten können nicht zwischen Spalten verschoben werden**

_Pinnwände_

Wenn ein Benutzer versucht, eine Karte auf einer Pinnwand zu verschieben, wird die Karte nicht verschoben. Dies geschieht unter den folgenden Umständen:

* Drag &amp; Drop
* Option &quot;Verschieben&quot;auf Karte
* Bearbeiten der Karte

**Karten können nicht aus der Annahmespalte verschoben werden**

_Pinnwände_

Der Benutzer kann eine Karte aus der Ansauspalte in eine andere Spalte auf der Pinnwand ziehen, nachfolgende Karten können jedoch nicht aus der Ansauspalte verschoben werden.

**Gruppe nach Auswirkung auf die Leistung der Pinnwand**

_Pinnwände_

Wenn der Benutzer versucht, die Karten nach Bevollmächtigten oder Tags zu gruppieren, wird die Leistung der Pinnwand sehr langsam.

**Automatische Erinnerungsmail wird nicht gesendet**

_Benachrichtigungen_

Automatische E-Mail-Erinnerungen werden nicht gesendet. Dies begann am 14. September 2023.

+++

## Updates im September 2023

+++**Wartungs-Update vom 28. September 2023**

**Benutzerdefiniertes Feld kann nicht gelöscht werden**

_Benutzerdefinierte Formulare_

„Wenn eine Benutzerin bzw. ein Benutzer versucht, ein benutzerdefiniertes Feld zu löschen, kann es nicht gelöscht werden und es wird die Meldung angezeigt: [!UICONTROL Datenbankfehler aufgrund einer Einschränkungsverletzung].“

**In neuen Kommentaren vorgenommene Kommentare sind im alten Erlebnis nicht sichtbar**

_Updates_

Wenn ein Benutzer im neuen Kommentarerlebnis einen Kommentar abgibt und dieser Kommentar im Kommentarbereich des neuen Erlebnisses angezeigt wird, wird derselbe Kommentar möglicherweise nicht im alten Kommentarerlebnis angezeigt. Dies kann dazu führen, dass Benutzer, die das alte Erlebnis verwenden, Kommentare verpassen.

**Objektseite fehlt Elemente**

_Workfront_

Wenn ein Benutzer zu einem benutzerdefinierten Abschnitt auf einem Objekt in [!DNL Workfront], auf der Seite, die geladen wird, fehlen möglicherweise einige Elemente. Diese Elemente können Folgendes umfassen:

* Das linke Navigationsfenster
* Der Name des Objekts, zu dem der benutzerdefinierte Abschnitt gehört
* Felder und Informationen in der Kopfzeile

+++

+++**Wartungs-Update vom 21. September 2023**

**Benutzer kann auf einer Pinnwand eines Workflows nicht zugewiesen werden**

_Pinnwände_

Wenn ein Benutzer versucht, einen anderen Benutzer einer Aufgabe aus einer Pinnwand zuzuweisen, die Teil eines Workflows ist, und beginnt, den Namen des Benutzers einzugeben, wird der Benutzer nicht in der Dropdown-Liste der verfügbaren Benutzer angezeigt. Dies tritt auch dann auf, wenn der Benutzer aktiv ist und sowohl Mitglied der Pinnwand als auch des Workflows ist.

Der Benutzer kann auch bemerken, dass deaktivierte Benutzer in der Dropdown-Liste angezeigt werden.

**Checklisten-Element kann nicht gelöscht werden**

_Pinnwände_

Wenn ein Benutzer versucht, ein Checklisten-Element aus einer Karte auf einer Pinnwand zu löschen, wird die [!UICONTROL Löschen] -Schaltfläche reagiert nicht und das Element wird nicht gelöscht.

**Benutzerdefinierte Formulare werden langsam geladen**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer versucht, ein benutzerdefiniertes Formular zu laden, wird das benutzerdefinierte Formular langsam geladen.

**Dokument kann nicht in einen anderen Ordner verschoben werden**

_Dokumente_

Wenn ein Benutzer ein Dokument in einen Objektordner verschiebt, kann er das Objekt dann nicht in einen anderen Ordner verschieben.

**XML-Fehler beim Herunterladen**

_Dokumente_

Wenn Benutzende versuchen, ein Dokument herunterzuladen, wird das Dokument nicht heruntergeladen, den Benutzenden wird eine Seite mit der folgenden Meldung gefolgt von XML-Text angezeigt.

&quot;[!UICONTROL Der XML-Datei sind anscheinend keine Stilinformationen zugeordnet. Die Dokumentstruktur befindet sich unten.]&quot;

**Dokumente können nicht aus Vorschau-/Sandbox-Umgebungen heruntergeladen werden**

_Dokumente_

Wenn ein Benutzer versucht, ein Dokument aus einer anderen Umgebung als der Produktionsumgebung herunterzuladen, wird das Dokument nicht heruntergeladen, und der Benutzer sieht den folgenden Fehler:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

**Testsendungen erscheinen desaturiert oder zugeschnitten**

_Korrekturabzüge_

Beim Erstellen eines Testversands über eine URL wurden die folgenden Probleme gemeldet:

* Der Beweis scheint entsättigt oder ausgespült zu sein.
* Der Testversand ist zugeschnitten.

Dies kann dazu führen, dass Testversandentscheidungen schwierig sind, da der Testversand nicht korrekt dargestellt wird.

**Die Erstellung von Testsendungen dauert zu lange**

_Korrekturabzüge_

Wenn ein Benutzer versucht, einen Testversand zu erzeugen, dauert die Erstellung des Testversands übermäßig lange. Die Erstellung eines Testversands kann mehrere Tage in Anspruch nehmen.

+++

+++**Wartungs-Update vom 14. September 2023**

**&quot;[!UICONTROL Keine Fabrik]&quot;-Fehler beim Hinzufügen eines Dokuments**

_Dokumente_

Wenn ein Benutzer versucht, ein Dokument aus einer externen Quelle hinzuzufügen, [!DNL Workfront] kann nicht auf die Quelle zugreifen, und dem Benutzer wird der folgende Fehler angezeigt:

&quot;[!UICONTROL Der folgende Fehler ist aufgetreten: Keine Factory für den Authentifizierungstyp null]&quot;

**Fehler „Hoppla“ in Matrix-Berichten**

_Berichte_

Beim Versuch, einen Matrix-Bericht zu öffnen, wird dieser nicht geladen und der folgende Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies geschieht bei der Gruppierung eines Berichts nach Datumsbereichen.

+++

+++**Wartungs-Update vom 11. September 2023**

**Persönliche Aufgaben werden nicht in Timesheets angezeigt**

_Arbeitszeittabellen_

Persönliche Aufgaben werden nicht mehr standardmäßig auf dem Timesheet angezeigt. Persönliche Aufgaben werden auf dem Timesheet angezeigt, wenn sie veröffentlicht werden oder Stunden protokolliert werden. Vor dieser Änderung werden persönliche Aufgaben standardmäßig auf Timesheets angezeigt.

+++

+++**Wartungs-Update vom 7. September 2023**

**Das Projekt ist leer, wenn es aus dem neuen [!UICONTROL Startseitenerlebnis] geladen wird**

_Projekte_

Wenn eine Benutzerin bzw. ein Benutzer auf der [!UICONTROL Startseite] im neuen Startseitenerlebnis auf ein Projekt klickt, wird die Seite des Projekts nicht geladen.

Dies tritt auf, wenn sich die Benutzerin bzw. der Benutzer sich als jemand anderes angemeldet und wieder abgemeldet hat und dann zur eigenen [!UICONTROL Startseite] zurückgekehrt ist.

+++

## Updates im August 2023

+++**Wartungs-Update vom 31. August 2023**

**Startseite: Filter funktionieren im neuen [!UICONTROL Startseitenerlebnis] nicht für Widgets**

_[!UICONTROL Startseite]_

Beim Anwenden eines Filters auf ein Widget im neuen [!UICONTROL Startseitenerlebnis] zeigt das Widget Elemente an, die eigentlich vom Filter ausgeschlossen werden sollten.

Dies wurde in der Umgebung einer benutzerdefinierten Sandbox gemeldet. In der Vorschau- und Produktionsumgebung werden dieselben Widgets wie erwartet gefiltert.

**Probleme beim Laden von Matrix-Berichten**

_Berichte_

Wenn eine Benutzerin bzw. ein Benutzer versucht, einen Matrix-Bericht als Diagramm zu laden, kann eine der folgenden Situationen auftreten:

* Einige Informationen im Bericht werden nicht geladen
* Der Bericht gibt den Fehler an „[!UICONTROL Inhalt kann nicht vom Server geladen werden]“

**Der Planer wird nicht geladen, wenn ein Filter angewendet wird**

_[!UICONTROL Ressourcenplaner]_

Beim Versuch, den [!UICONTROL Ressourcenplaner] zu laden, wird der Planer nicht geladen und es wird die folgende Fehlermeldung angezeigt:

„[!UICONTROL Folgender Fehler ist aufgetreten: Fehler beim Herstellen einer Verbindung zum WorkPerDay-Dienst]“

+++

+++**Wartungs-Update vom 24. August 2023**

**In Listen oder Aufzählungspunkten kann kein Text ausgewählt werden**

_Korrekturabzüge_

Wenn ein Korrekturabzug im Korrekturabzug-Viewer angezeigt wird und versucht wird, Text auszuwählen, der sich in einer Liste oder einem Aufzählungspunkt befindet, ist das Textauswahlwerkzeug nicht wirksam und der Text kann nicht ausgewählt werden.

**Beim Erstellen einer neuen Korrekturabzugsversion werden alle Versionen des Korrekturabzugs gelöscht**

_Korrekturabzüge_

Beim Erstellen eines Korrekturabzugs aus einem Dokument wird der Korrekturabzug zwar erstellt. Wenn jedoch eine andere Version des Korrekturabzugs erstellt wird, werden sowohl die alte als auch die neue Version gelöscht. Es gibt die Option [!UICONTROL Korrekturversand erstellen] für das Originaldokument, und die Korrekturabzugsversion findet sich im [!UICONTROL Papierkorb] des Bereichs [!UICONTROL Proofing] in [!DNL Workfront].

+++

+++**Wartungs-Update vom 17. August 2023**

**Es ist nicht möglich, zu einem Projekt mit einer URL zu navigieren, die eine [!UICONTROL Referenz-ID]** verwendet

_Projekte_

Wenn eine Benutzerin bzw. ein Benutzer versucht, mithilfe einer URL, die eine [!UICONTROL Referenz-ID] enthält, zu einem Projekt zu navigieren, wird sie bzw. er zu einer Seite mit einer Fehlermeldung umgeleitet. Die Navigation zu einer Aufgabe mithilfe eines URI mit einer [!UICONTROL Referenz-ID] funktioniert erwartungsgemäß.

**Die Einstellung „[!UICONTROL E-Mail-Benachrichtigungen für Korrekturabzug deaktivieren]“ wird ungenau angezeigt**

_Korrekturabzüge_

Wenn eine Benutzerin bzw. ein Benutzer in [!DNL Workfront] die Einstellungen für Korrekturabzüge anzeigt, zeigt das Kontrollkästchen „[!UICONTROL E-Mail-Benachrichtigungen für Korrekturabzug deaktivieren]“ nicht die richtige aktuelle Einstellung an. Wenn das Kästchen aktiviert ist und dadurch angibt, dass E-Mail-Benachrichtigungen für einen Korrekturabzug deaktiviert sind, sind Benachrichtigungen trotzdem aktiviert. Umgekehrt ist dies ebenso der Fall.

**Korrekturabzugsmarkierungen können nicht angepasst werden**

_Korrekturabzüge_

Wenn jemand im Korrekturabzug-Viewer einen Kommentar abgibt, eine Markierung auf dem Korrekturabzug vornimmt und dann wegklickt, kann die Markierung nicht mehr angepasst werden.

+++

+++**Wartungs-Update vom 10. August 2023**

**Löschen eines [!UICONTROL Aufgabenelements] im neuen [!UICONTROL Startseitenerlebnis] nicht möglich**

_Startseite_

Beim Versuch, im neuen [!UICONTROL Startseitenerlebnis] ein Element aus dem [!UICONTROL Aufgaben]-Widget zu löschen, wird das Element nicht gelöscht und es wird der folgende Fehler angezeigt:

„[!UICONTROL Beim Entfernen Ihrer Aufgabe ist ein Fehler aufgetreten. Warten Sie kurz und versuchen Sie es dann nochmals.]“

Dies kann vorkommen, wenn im [!UICONTROL Aufgabenelement] Stunden protokolliert sind.

**Angeheftetes Projekt zeigt in einigen Spalten keine Informationen an**

_Projekte_

Beim Navigieren zu einem angehefteten Projekt mithilfe des Pins können in den Objektlisten (z. B. der Aufgabenliste) leere Spalten angezeigt werden. Zum Beispiel kann es vorkommen, dass eine Spalte [!UICONTROL Zuweisungen] keine Zuweisungen anzeigt, auch wenn Zuweisungen vorgenommen wurden.

**Schlafmodul verursacht Hängen in Szenarien**

_[!DNL Workfront Fusion]_

Das Modul [!UICONTROL Tools] > [!UICONTROL Schlafen] in einem Szenario kann dazu führen, dass die Ausführung eines Szenarios hängen bleibt. Diese Ausführungen zeigen den Status „Wird ausgeführt“ im [!UICONTROL Szenarioverlauf] an und werden nicht beendet.

+++

+++**Wartungs-Update vom 3. August 2023**

**Schwierigkeiten beim Auffinden von Elementen in der Aufnahmespalte**

_Pinnwände_

Die Aufnahmespalte auf einer Pinnwand wurde zuvor nach der für Aufgaben und Probleme definierten Priorität sortiert, was die Suche nach bestimmten Elementen erschwerte.

Die Standardreihenfolge lautet nun wie folgt:

Aufgaben:

* Primäre Reihenfolge: Projektname
* Sekundäre Reihenfolge: Struktur für Auffächerung des Arbeitsaufwands

Probleme

* Primäre Reihenfolge: Projektname
* Sekundäre Reihenfolge: Referenznummer

**Projekt löst Problem nicht korrekt**

_Projekte/Probleme_

Wenn Benutzende den Status eines Projekts ändern, das das Lösungsobjekt für ein Problem ist, wird der Problemstatus in einen Status geändert, der nicht demselben Schlüssel entspricht wie der Status des Projekts.

**Fehler „Hoppla“ in Matrix-Berichten**

_Berichte_

Beim Versuch, einen Matrix-Bericht zu öffnen, wird dieser nicht geladen und der folgende Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies wurde für Benutzerinnen und Benutzer in EMEA berichtet.

+++

## Updates im Juli 2023

+++**Wartungs-Update vom 27. Juli 2023**

**Tags und Checklisten-Elemente funktionieren in der Pinnwandansicht des Projekts nicht ordnungsgemäß**

_Pinnwände_

Tags und Checklisten-Elemente wurden aus der Pinnwandansicht von Projekten entfernt, da sie nicht zu Workfront-Aufgaben gehören und nicht von Benutzenden gemeinsam genutzt werden können.

**„[!UICONTROL Systemweit aktivieren]“ und „[!UICONTROL Systemweit anzeigen]“ stellen verschiedene Funktionen dar**

_Filter_

Wenn eine Benutzerin bzw. ein Benutzer einen Filter freigibt und die Option „[!UICONTROL Systemweit anzeigen]“ aktiviert, wird der Filter für jede Benutzerin bzw. jeden Benutzer im System freigegeben. Wenn eine Administratorin bzw. ein Administrator diesen Filter jedoch im [!UICONTROL Setup] anzeigt, sieht sie bzw. er, dass dieser Filter „[!UICONTROL false]“ in der Spalte „[!UICONTROL Systemweit sichtbar]“ anzeigt. Damit dieser Filter zu einer Standardeinstellung des Systems wird, muss die Administratorin bzw. der Administrator die Option „[!UICONTROL Systemweit aktivieren]“ im [!UICONTROL Setup] aktivieren. Dies kann aufgrund der Ähnlichkeit der Formulierung zu Verwirrung führen.

+++

+++**Wartungs-Update vom 20. Juli 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 13. Juli 2023**

**Zeitleiste wird nicht neu berechnet**

_Projekte/Aufgaben/Probleme_

Wenn ein Ereignis auftritt, das eine Timeline-Berechnung auslösen sollte, wird die Timeline nicht neu berechnet. Dies wirkt sich auf Neuberechnungen bei Änderungen sowie auf geplante Neuberechnungen aus. Dies kann die Genauigkeit des Workload Balancers beeinträchtigen.

**Gesperrte Genehmigungen von Korrekturabzügen werden weiterhin in der Arbeitsliste angezeigt**

_Korrekturabzüge_

Genehmigungen von Korrekturabzügen, deren Termin überschritten ist und die gesperrt sind, werden weiterhin in der Arbeitsliste der Startseite der genehmigenden Person angezeigt, anstatt nach Ablauf des Termins aus der Liste gelöscht zu werden.

**Auslastungsbericht wird nicht geladen**

_Berichte_

Wenn eine Kundin bzw. ein Kunde versucht, einen Auslastungsbericht anzuzeigen, wird ein rotierendes Ladesymbol angezeigt, doch der Bericht wird nicht geladen. Der Bericht gibt einen 500-Fehler zurück, doch es ist nicht zu erkennen, dass der Bericht fehlgeschlagen ist.

**Seite „Benutzer bearbeiten“ ist leer**

<!--no article-->

_Benutzende_

Wenn eine Benutzerin oder ein Benutzer versucht, andere Benutzende zu bearbeiten, ist die Seite „Benutzer bearbeiten“ leer und er oder sie kann andere Benutzende nicht bearbeiten.

+++

## Updates im Juni 2023

+++**Wartungs-Update vom 29. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 22. Juni 2023**

**Fehler beim Anzeigen des Matrixberichts**

_Berichte_

Wenn eine Benutzerin oder ein Benutzer einen Matrixbericht anzeigt, wird der folgende Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies wurde gemeldet, wenn der Bericht nach Datum sortiert wird und die Option „[!UICONTROL Wochen ohne Ergebnisse anzeigen]“ aktiviert ist.

**Datumsangaben werden in Matrixberichten falsch angezeigt**

_Berichte_

Wenn ein Diagramm oder Matrixbericht nach Datum gruppiert ist, können Datumsangaben in der Nähe der Gruppierungsränder in der richtigen Gruppierung, der vorherigen/nächsten Gruppierung oder in beiden erscheinen.

+++

+++**Wartungs-Update vom 15. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 8. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update vom 8. Juni 2023**

[!DNL Fusion] hat eine Fehlerbehebung implementiert, die verhindert, dass die Verbindungen einer Benutzerin oder eines Benutzers entfernt werden, wenn sie oder er in der [!UICONTROL Adobe Admin Console] deaktiviert ist.

[!DNL Fusion]-Team-Admins können weiterhin nicht benötigte Verbindungen von der Seite [!UICONTROL Verbindungen] in [!DNL Fusion] entfernen.

+++

+++**Wartungs-Update vom 1. Juni 2023**

**Keine Fehlermeldung bei Neuanordnung der Aufgabe im Status [!UICONTROL Ausstehende Genehmigung]**

_Aufgaben_

Wenn Benutzende versuchen, eine Aufgabe in einer Aufgabenliste neu anzuordnen und sich die Aufgabe im Status [!UICONTROL Ausstehende Genehmigung] befindet, wird die Aufgabe scheinbar in die Aufgabenliste verschoben. Nach der Aktualisierung wird jedoch angezeigt, dass das Element nicht verschoben wurde. Das Element kann nicht verschoben werden, da es sich im Status [!UICONTROL Ausstehende Genehmigung] befindet, doch es gibt keine Meldung, die darauf hinweist, dass das Element nicht verschoben werden kann, was zu Verwirrung führen kann.

**Keine Fehlermeldung beim Verschieben einer Vorgängeraufgabe unter eine abhängige Aufgabe**

_Aufgaben_

Wenn Benutzende versuchen, eine Aufgabe in einer Aufgabenliste neu anzuordnen und sich die Aufgabe im Status [!UICONTROL Ausstehende Genehmigung] befindet, wird die Aufgabe scheinbar in die Aufgabenliste verschoben. Nach der Aktualisierung wird jedoch angezeigt, dass das Element nicht verschoben wurde. Das Element kann nicht verschoben werden, da eine Vorgängeraufgabe nicht unter eine Aufgabe verschoben werden kann, deren Vorgänger sie ist. Es gibt jedoch keine Meldung, die der Benutzerin oder dem Benutzer mitteilt, dass das Element nicht verschoben werden kann, was zu Verwirrung führen kann.

+++

## Updates im Mai 2023

+++**Wartungs-Update vom 25. Mai 2023**

**[!UICONTROL Kanban]-Pinnwand beim Bearbeiten von Karten leer**

_Agile_

Wenn eine Benutzerin oder ein Benutzer etwas an einer Karte auf der [!UICONTROL Kanban]-Pinnwand ändert, dann wird die [!UICONTROL Kanban]-Pinnwand leer, anstatt mit der Änderung aktualisiert zu werden. Wenn die Benutzerin oder der Benutzer die Seite manuell aktualisiert, wird die [!UICONTROL Kanban]-Pinnwand wieder angezeigt, mit der korrekten Änderung.

Dies wurde unter den folgenden Umständen gemeldet:

* Bearbeiten einer Karte
* Verschieben einer Karte


+++

+++**Wartungs-Update vom 22. Mai 2023**

**Die Größe des beschreibenden Texts kann nicht angepasst werden**

_Benutzerdefinierte Formulare_

Als der Designer für benutzerdefinierte Formulare in der Beta-Version veröffentlicht wurde, war die Funktion zum Anpassen der Größe von beschreibendem Text nicht verfügbar. Dieses Problem wurde behoben, und Benutzerinnen und Benutzer können jetzt die Größe des beschreibenden Texts anpassen.

+++

+++**Wartungs-Update vom 18. Mai 2023**

**Bericht wird beim Sortieren nach benutzerdefiniertem Feld nicht korrekt sortiert**

_Berichte_
Wenn eine Benutzerin oder ein Benutzer einen Aufgabenbericht ausführt, wird der Bericht beim Laden scheinbar korrekt sortiert, doch nach Abschluss des Ladevorgangs ist ersichtlich, dass der Bericht nicht korrekt sortiert wurde.

Dies scheint der Fall zu sein, wenn alle folgenden Bedingungen erfüllt sind:

* Der Bericht ist ein Aufgabenbericht
* Der Bericht wird nach einem benutzerdefinierten Feld sortiert
* Auf den Bericht wird eine Gruppierung angewendet

+++

+++**Wartungs-Update am 11. Mai 2023**

**Korrekturabzugsversion kann bei der Ansicht des Korrekturstatus nicht gewechselt werden**

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug im [!UICONTROL Proofing Viewer] anzeigen und zu einer anderen Version wechseln, wird das Dropdown-Menü für die Version deaktiviert, und die Benutzenden können nicht zur Originalversion, die sie angezeigt haben, oder zu einer anderen Version des Korrekturabzugs zurückkehren.

Zeitüberschreitung bei **[!DNL Workfront]-Suche**

_Suche_

[!DNL Workfront]-Suche überschreitet gleich die Zeit. Die Suche gibt möglicherweise wenige oder gar keine Ergebnisse zurück.

Dieses Problem betrifft auch die Funktionalität des Moduls [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Suche].

+++

+++**[!DNL Adobe Workfront Fusion]-Wartungs-Update vom 11. Mai 2023**

**Zeitüberschreitungsfehler in[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Wenn ein Szenario ausgeführt wird, kann ein Zeitüberschreitungsfehler angezeigt werden. Die vom Modul mit dem Fehler stammenden Informationen erreichen ihr Ziel nicht.

Zeitüberschreitung bei **[!DNL Workfront]-Suche**

_Suche_

[!DNL Workfront]-Suche überschreitet gleich die Zeit. Die Suche gibt möglicherweise wenige oder gar keine Ergebnisse zurück.

Dieses Problem betrifft auch die Funktionalität des Moduls [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Suche].

+++

+++**Wartungs-Update vom 9. Mai 2023**

**Gespeicherte Filter, die in der Aufnahmespalte der Pinnwand verfügbar sind**

_Pinnwände_

Sie können jetzt in Workfront vorhandene Aufgaben- und Problemfilter beim Konfigurieren der Aufnahmspalte für eine Pinnwand verwenden. Vorhandene Aufnahmespaltenfilter sind jetzt jedoch im Konfigurationsbereich schreibgeschützt. Die vorhandenen Filter werden weiterhin auf die Aufnahmespalte angewendet, doch müssen die Filter neu erstellt werden, um sie bearbeiten zu können.

+++

+++**Wartungs-Update vom 4. Mai 2023**

**Vorlage kann nicht aus den [!UICONTROL Favoritenvorlagen]** ausgewählt werden

_Vorlagen_

Wenn Benutzende versuchen, eine Vorlage aus dem Menü „Aktionen“ (drei Punkte) auszuwählen, wird die Liste der Vorlagen ausgeblendet, sobald die Maus zur Liste bewegt wird, und es kann keine Vorlage ausgewählt werden. Dies liegt daran, dass sich die Bildlaufleiste zwischen dem Menü und der Liste der Vorlagen befindet und der Fokus der Maus auf die Bildlaufleiste gelegt wird, wenn sie zur Liste der Vorlagen bewegt wird.

+++

## Updates im April 2023

+++**Wartungs-Update vom 27. April 2023**

**Kann im [!UICONTROL Korrekturabzüge-Viewer]** nicht zwischen Korrekturabzügen wechseln

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug im [!UICONTROL Korrekturabzüge-Viewer] anzeigen und zu einem anderen Korrekturabzug wechseln, reagiert die Schaltfläche „Korrekturabzug wechseln“ nicht mehr. Die Benutzenden können nicht zum ursprünglichen Korrekturabzug, den sie angesehen haben, oder zu einem anderen Korrekturabzug zurückkehren.

**Bearbeiten von angehängten Bildern beim Bearbeiten eines Kommentars**

_Updates_

Sie können jetzt das Bild bearbeiten, das an einen Kommentar angehängt ist, wenn Sie einen Kommentar bearbeiten. Dies ist im Abschnitt „Aktualisierungen“ für Workfront-Ziele und im Abschnitt „Probleme“ bei der Aktivierung des Beta-Kommentierungserlebnisses verfügbar.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update vom 25. April 2023**

In-App-Hilfe-Links in **[!DNL Fusion]führen nicht zu den jeweiligen Hilfeseiten**

_[!DNL Workfront Fusion]_

Wenn Benutzende einen Korrekturabzug im [!UICONTROL Korrekturabzüge-Viewer] anzeigen und zu einem anderen Korrekturabzug wechseln, reagiert die Schaltfläche „Korrekturabzug wechseln“ nicht mehr. Die Benutzenden können nicht zum ursprünglichen Korrekturabzug, den sie angesehen haben, oder zu einem anderen Korrekturabzug zurückkehren.

+++

+++**Wartungs-Update vom 20. April 2023**

**Probleme in benutzerdefinierten Dropdown-Feldern**

_Benutzerdefinierte Formulare_

Benutzerdefinierte Dropdown-Felder, die als Mehrfachauswahlfelder aktiviert sind, können die folgenden Probleme anzeigen:

* Die Schaltfläche „+[!UICONTROL Hinzufügen]“ ist nicht vorhanden, wenn sich das Formular nicht im Bearbeitungsmodus befindet.
* Felder ohne Werte zeigen eine Option „--[!UICONTROL keine Beschriftung]--“ an.

**Mehrzeilenwerkzeug kann nicht für einen Kommentar zu einem Korrekturabzug verwendet werden**

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug im Proofing Viewer anzeigen und versuchen, mit dem Mehrzeilenwerkzeug einen Kommentar abzugeben, markiert das Werkzeug den Korrekturabzug nicht.

**Feld mit Textoptionen zeigt „textAnnotations“**

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug anzeigen, einen Kommentar verfassen und das Textwerkzeug öffnen, wird neben den Optionen im Werkzeug das Wort „textAnnotation“ angezeigt. Das Textwerkzeug funktioniert dennoch wie erwartet und „textAnnotation“ verschwindet, nachdem der Kommentar veröffentlicht wurde.

**Bilder werden als Entwurf beibehalten, wenn Sie mit der Beta-Kommentar-Funktion von einer Aktualisierung wegnavigieren**

>[!NOTE]
>
>Diese Funktion wurde am 19. April 2023 in der Vorschau veröffentlicht und am 20. April 2023 für die Produktion freigegeben.

_Updates_

Wenn Sie jetzt von der Seite „Updates“ wegnavigieren, während Sie eine Nachricht erstellen, an die Sie ein Bild angefügt haben, bleiben die Nachricht und das Bild erhalten, bis Sie wieder zu der Seite zurückkehren. Vor diesem Update wurde der nicht übermittelte Kommentar beibehalten, aber das Bild wurde gelöscht. Dies ist im Abschnitt „Aktualisierungen“ für Ziele und für Probleme bei der Aktivierung der Beta-Kommentar-Funktion verfügbar.

**Echtzeit-Updates und gelöschte Kommentare im Abschnitt „Aktualisierungen“**

>[!NOTE]
>
>Diese Funktion wurde am 19. April 2023 in der Vorschau veröffentlicht und am 20. April 2023 für die Produktion freigegeben.

_Aktualisierungen_

Wenn jetzt jemand einen Kommentar oder eine Antwort hinzufügt oder einen Kommentar aus dem Bereich „Aktualisierungen“ löscht, können Sie den neuen Kommentar oder einen Hinweis sehen, dass der Kommentar verzögerungsfrei (in Echtzeit) entfernt wurde. Dies ist im Abschnitt „Aktualisierungen“ für Ziele und für Probleme bei der Aktivierung der Beta-Kommentar-Funktion verfügbar.

**Zugriffsebene wird durch das System ohne Aufzeichnung einer solchen Änderung geändert**

_Benutzende_

Die Zugriffsebene von Benutzenden kann vom System unvorhersehbar geändert werden. In diesem Fall gibt es keine sichtbare Aktualisierung, und die Änderung wird nicht im Administratorprotokoll angezeigt.

+++

+++**Wartungs-Update vom 17. April 2023**

**Anzeige neuer Kommentare außerhalb des sichtbaren Bildschirmbereichs im Abschnitt [!UICONTROL Aktualisierungen] von Problemen (neue Beta-Kommentar-Funktion) und im Abschnitt [!UICONTROL Ziele]**

_Aktualisierungen_

Wir haben ein Benachrichtigungs-Banner für den Abschnitt [!UICONTROL Aktualisierungen] hinzugefügt, um Benutzende darüber zu informieren, wenn neue Kommentare zu einem Element vorhanden sind, das sich außerhalb des sichtbaren Bereichs des Bildschirms befindet. Dieses Update ist derzeit im Abschnitt [!UICONTROL Aktualisierung] von Zielen und Problemen verfügbar, nachdem die neue Beta-Kommentar-Funktion für Probleme aktiviert wurde.

+++

+++**Wartungs-Update vom 13. April 2023**

**Filter werden nicht auf die Anfragenliste angewendet**

_Anfragen_

Wenn eine Liste von Anfragen angezeigt wird, auf die ein Filter angewendet wurde, enthält die Liste Anfragen, die vom Filter ausgeschlossen werden sollten.

**Auswahl von [!UICONTROL Standardstundentyp] oder [!UICONTROL Verfügbare Stundentypen]** ist nicht möglich

_Benutzende_

Wenn Admins eine Benutzerin oder einen Benutzer bearbeiten und versuchen, einen Wert für [!UICONTROL Standardstundentyp] oder [!UICONTROL Verfügbarer Stundentyp] auszuwählen, sind die Dropdown-Listen für diese Felder deaktiviert, sodass keine Stundentypen ausgewählt werden können.

+++

+++**Wartungs-Update vom 6. April 2023**

**Dropdown-Listen werden nicht geöffnet, wenn Benutzende zu einem Korrekturabzug hinzugefügt werden**

_Korrekturabzüge_

Wenn Benutzende andere Benutzende zu einem Korrekturabzug im [!UICONTROL Proofing Viewer] hinzufügen, können die Dropdown-Listen „[!UICONTROL Rolle des Korrekturabzugs]“ und „[!UICONTROL E-Mail-Warnungen]“ nicht geöffnet werden. Die Benutzenden können keine Korrekturabzugsrolle oder E-Mail-Warnung zuweisen. Dies kann vorkommen, wenn Benutzende über einen Kommentar hinzugefügt werden oder der Korrekturabzug für die Benutzenden freigegeben wird.

+++

## Updates im März 2023

+++**Wartungs-Update vom 30. März 2023**

**Korrekturabzugsversion kann bei der Ansicht des Korrekturstatus nicht gewechselt werden**

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug im [!UICONTROL Proofing Viewer] anzeigen und zu einer anderen Version wechseln, wird das Dropdown-Menü für die Version deaktiviert, und die Benutzenden können nicht zur Originalversion, die sie angezeigt haben, oder zu einer anderen Version des Korrekturabzugs zurückkehren.

**504-Fehler beim Exportieren von Berichten**

_Berichte_

Wenn Benutzende versuchen, einen Bericht mit einer hohen Anzahl von Elementen zu exportieren, wird ein 504-Fehler angezeigt und der Bericht kann nicht exportiert werden.

**Im Auftrag von Benutzenden vorgenommene Aktualisierungen werden als direkt von den Benutzenden angezeigt**

_Updates_

Wenn Administrierende als Benutzende angemeldet sind und einen Kommentar abgeben, wird dieser Kommentar als direkt von Benutzenden und nicht als von Administrierenden im Namen der Benutzenden angezeigt.

+++

+++**Wartungs-Update vom 23. März 2023**

Inhalte des Bedienfelds **[!UICONTROL Zusammenfassung] sind zu breit für das Bedienfeld**

_Dokumente_

Wenn eine Benutzerin bzw. ein Benutzer das Bedienfeld [!UICONTROL Zusammenfassung] für ein Dokument ansieht, sind die Inhalte zu breit, um im Bedienfeld sichtbar zu sein. Das Bedienfeld verfügt nun über eine horizontale Bildlaufleiste und Benutzende müssen horizontal scrollen, um die Inhalte des Bedienfelds [!UICONTROL Zusammenfassung] zu sehen. Dies geschieht, weil der Dateiname des Dokuments nicht umgebrochen wird. Dieses Problem ist auf Dateien beschränkt, bei welchen der Dateiname eine HTML-Dateierweiterung aufweist.

**Neue [!UICONTROL Desktop Proofing Viewer]-Version**

_Proofing_

Um ein Kommentierproblem im [!UICONTROL Desktop Proofing Viewer] zu beheben, haben wir eine neue Version des Desktop Proofing Viewers bereitgestellt.

Benutzende, die den [!UICONTROL Desktop Proofing Viewer] bereits installiert haben, erhalten dieses Update automatisch.

Benutzende können die neueste Version auch manuell herunterladen. Weitere Informationen finden Sie unter [[!UICONTROL Installieren des Desktop Proofing Viewers]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=de).

* Frühere Version: 2.1.22
* Neue Version: 2.1.23

+++

+++**Wartungs-Update vom 16. März 2023**

**Beim Kopieren einer Karte werden Checklisten-Elemente nicht kopiert**

_Pinnwände_

Beim Kopieren einer Ad-hoc-Karte (verbundene Karten können nicht kopiert werden) werden Checklisten-Elemente nicht auf die neue Karte kopiert.

**Benutzerdefiniertes Feld fehlt, wenn Problem in ein Projekt konvertiert wird**

_Projekte_

Wenn ein Problem mithilfe einer Vorlage in ein Projekt konvertiert wird, wird ein benutzerdefiniertes Feld, das zum Problem gehörte, nicht im Projekt angezeigt. Dieses Problem betrifft nur Nicht-Admins.

**Benutzerdefinierte Nachrichten werden nicht in E-Mail-Benachrichtigungen angezeigt**

_Korrekturabzüge_

Wenn ein Korrekturabzug freigegeben und ihm eine benutzerdefinierte Nachricht hinzufügt wird, wird diese benutzerdefinierte Nachricht nicht in der Benachrichtigungs-E-Mail an die Empfängerin bzw. den Empfänger angezeigt. Der Betreff ist der Name des Korrekturabzugs, und die Nachricht wird nicht in der E-Mail angezeigt.

+++

+++**Wartungs-Update vom 9. März 2023**

**Zugriffsebene wird beim Reaktivieren der bzw. des Benutzenden nicht zugewiesen**

_Benutzende_

Wenn ein(e) Benutzende(r) eine(n) deaktivierte(n) Benutzende(r) erneut aktiviert und versucht, ihm/ihr im Fenster [!UICONTROL Benutzer erneut aktivieren] eine Zugriffsebene zuzuweisen, wird das Zugriffsebenen-Dropdown-Menü nicht entsprechend der Eingabe der/des Benutzenden angezeigt und der/die Benutzende kann keine Zugriffsebene auswählen. Wenn der/die Benutzende die Zugriffsebene eingibt und speichert, wird diese Zugriffsebene dem/der erneut aktivierten Benutzenden nicht zugewiesen.

**Speichern eines Kommentarentwurfs im Bereich [!DNL Goals]**

_[!DNL Workfront Goals]_

Wenn Sie jetzt von der Seite [!UICONTROL Updates] eines Ziels während der Erstellung einer Nachricht wegnavigieren, wird die Nachricht beim Zurücknavigieren beibehalten. Vor dieser Aktualisierung wäre der nicht übermittelte Kommentar gelöscht worden.

+++

+++**Wartungs-Update vom 2. März 2023**

**Bei angewendeter Gruppierung können keine Karten hinzugefügt werden**

_Pinnwände_

Wenn Benutzende eine Pinnwand mit angewendeter Gruppierung anzeigen und versuchen, eine Karte hinzuzufügen, können sie nur den Namen der Karte eingeben. Die übrigen Kartenfelder sind deaktiviert, einschließlich der Schaltfläche [!UICONTROL Speichern].

Wenn Benutzende die Gruppierung in [!UICONTROL Keine] ändern, bleibt das Problem bestehen. Benutzende müssen die Gruppierung in [!UICONTROL Keine] ändern und die Seite aktualisieren, um die Möglichkeit zum Hinzufügen einer Karte wiederherzustellen.

**Verbundene Karten werden nicht nach Status zu Spalten hinzugefügt**

_Pinnwände_

Obwohl Spaltenrichtlinien auf den Status angewendet werden, erscheinen neue verbundene Karten in der Spalte ganz links und nicht in der Spalte, die ihrem Status entspricht.


**Link zu einem Kommentar leitet auf die Seite [!UICONTROL Details] um**

_Updates_

Wenn ein(e) Benutzende(r) einem Link zu einem Kommentar folgt, der sich auf ein Objekt in Workfront bezieht, wird der Aktualisierungsstrom kurz geladen und der/die Benutzende wird dann zum Bereich [!UICONTROL Details] des Objekts weitergeleitet. Dies kann vorkommen, wenn der/die Benutzende in einer E-Mail auf den Link klickt oder den Link in den Browser einfügt.

Dies betrifft derzeit nur Dokumentobjekte.

**Druckzusammenfassung wird nicht geladen**

_[!UICONTROL Workfront-Korrekturabzug]_

Wenn eine Benutzerin bzw. ein Benutzer versucht, die Seite „Druckzusammenfassung“ zu laden, scheint die Seite zu laden, sie wird jedoch nie geladen.

+++

## Updates im Februar 2023

+++**Wartungs-Update vom 23. Februar 2023**

**Link zu einem Kommentar leitet auf die Seite [!UICONTROL Details] um**

_Updates_

Wenn ein(e) Benutzende(r) einem Link zu einem Kommentar folgt, der sich auf ein Objekt in Workfront bezieht, wird der Aktualisierungsstrom kurz geladen und der/die Benutzende wird dann zum Bereich [!UICONTROL Details] des Objekts weitergeleitet. Dies kann vorkommen, wenn der/die Benutzende in einer E-Mail auf den Link klickt oder den Link in den Browser einfügt.

Dies betrifft derzeit nur Dokumentobjekte.

**Benutzende können ihre eigenen Benachrichtigungseinstellungen nicht bearbeiten**

_Benutzende_

Wenn Benutzende mit der Lizenz [!UICONTROL Arbeitskraft] versuchten, ihre eigenen Benachrichtigungseinstellungen zu bearbeiten, werden die [!UICONTROL Benachrichtigungsoptionen] im Fenster [!UICONTROL Bearbeiten] nicht angezeigt und die Benutzenden können die Einstellungen nicht bearbeiten.

+++

+++**Wartungs-Update vom 16. Februar 2023**

**Mehrere Team-Zuweisungen auf Pinnwänden**

_Pinnwände_

Sie können jetzt mehrere Teams einer Aufgabe oder einem Problem auf einer Pinnwand und der Pinnwand selbst zuweisen.

**Erhöhung des Limits für die Verringerung von Karten**

_Pinnwände_

Die Limits für die Verringerung von Karten wurden von 4 Wochen/30 Tage auf 8 Wochen/60 Tage erhöht.

**Die geplante Deaktivierung deaktiviert Benutzende nicht**

_Benutzende_

Wenn die Deaktivierung von Benutzenden geplant ist und das geplante Datum und die geplante Uhrzeit vergehen, werden Benutzende nicht deaktiviert.

+++

+++**Wartungs-Update vom 9. Februar 2023**

Das Feld **[!UICONTROL Story-Punkte] wurde zu Aufgaben- und Problemlisten und Berichten hinzugefügt**

_Berichte_

Das Feld [!UICONTROL Story-Punkte] kann jetzt zu Listen und Berichten für Aufgaben oder Probleme hinzugefügt werden. Es handelt sich dabei um ein editierbares, Freiform-Feld, das nicht an geplante Stunden oder Team-Arbeitsaufträge gebunden ist.

+++

+++**Wartungs-Update vom 8. Februar 2023**

**Filterschaltfläche in Aufnahmespalte**

_Pinnwände_

Wenn die Aufnahmespalte leer ist und keine Filter erstellt wurden, enthält die Aufnahmespalte auf einer Pinnwand jetzt die Schaltfläche **[!UICONTROL Filter hinzufügen]**. Die Schaltfläche öffnet den Konfigurationsbereich, in dem Sie Filter hinzufügen können, um Aufgaben und Probleme in die Aufnahmespalte zu übernehmen.

+++

+++**Wartungs-Update vom 2. Februar 2023**

Das Symbol **[!UICONTROL Pinnwände] wird standardmäßig im [!UICONTROL Hauptmenü] angezeigt**

_Pinnwände_

Für Benutzende, die keine Layout-Vorlage haben, wird das Symbol [!UICONTROL Pinnwände] jetzt im [!UICONTROL Hauptmenü] angezeigt. Pinnwände sind auch im Hauptmenü für alle neu erstellten Layout-Vorlagen standardmäßig enthalten. Bestehende Layout-Vorlagen wurden nicht geändert.

**E-Mail-Vorlagen können nicht gespeichert werden**

_Setup_

Wenn Benutzende versuchen, eine E-Mail-Vorlage zu erstellen oder zu bearbeiten, reagiert die Schaltfläche [!UICONTROL Speichern] nicht, und sie können die Vorlage nicht speichern.

+++

## Updates im Januar 2023

+++**Wartungs-Update vom 30. Januar 2023**

**Tastaturbefehle für häufige Aktionen in der Arbeitszeittabelle hinzugefügt**

_Arbeitszeittabellen_

Wir haben für die folgenden häufig durchgeführten Aktionen in einer Arbeitszeittabelle die unten stehenden Tastaturbefehle eingeführt:

* Zeile hinzufügen (Befehl+Option++/Strg+Option++)
* Zeile löschen (Befehl+Option+-/Strg+Option+-)
* Ein Arbeitselement anheften oder loslösen (Option+P/Option+P)
* Kommentar öffnen (Umschalt+F2/Umschalt+F2)
* Kommentar speichern (Befehl+Eingabetaste/Strg+Eingabetaste)
* Erweitern (Umschalt+Option+Nach-oben-Taste/Umschalt+Alt+Nach-oben-Taste)
* Reduzieren (Umschalt+Option+Nach-unten-Taste/Umschalt+Alt+Nach-unten-Taste)

Der Bereich, an dem diese Aktionen ausgeführt werden, muss hervorgehoben werden, damit sie angewendet werden können.

**Neue Informationssymbole für Arbeitszeittabellen, Arbeitszeittabellenprofile und Arbeitszeittabellen-Voreinstellungen**

_Arbeitszeittabellen_

>[!NOTE]
>
>Dieses Update wurde am 3. November 2022 nur in der Vorschau-Umgebung veröffentlicht und ist jetzt in der Produktionsumgebung verfügbar.

Wir haben zu den folgenden Einstellungen mehrere Informationssymbole hinzugefügt:

* Wenn das Kontrollkästchen „[!UICONTROL Kann die Zeit bearbeiten]“ bei der Erstellung oder Bearbeitung einer Arbeitszeittabelle oder eines Arbeitszeittabellenprofils aktiviert wird, bedeutet dies, dass die genehmigenden Personen auch die Arbeitszeittabelle senden, erneut öffnen oder bearbeiten können, es sei denn, der Administrierende beschränkt diese Aktionen im Bereich „[!UICONTROL Arbeitszeittabellen-Voreinstellungen]“ im [!UICONTROL Setup].
* Wenn die Option „[!UICONTROL Bearbeitung von Arbeitszeittabellen auf Inhaber und Administrierende beschränken]“ im Bereich [!UICONTROL Arbeitszeittabellen- und Stunden-Voreinstellungen] von „[!UICONTROL Setup]“ deaktiviert ist, können auch die folgenden Benutzenden die Arbeitszeittabellen bearbeiten: Benutzende mit administrativem Zugriff auf Arbeitszeittabellen und Stunden, Arbeitszeittabellen-Genehmiger, die die Zeit bearbeiten dürfen, und Arbeitszeittabellen-Besitzer und -Besitzerinnen mit Verwaltungsrechten.

Beachten Sie, dass sich die Funktionalität dieser Einstellungen nicht geändert hat und nur die Informationssymbole hinzugefügt wurden, um den Umfang der Einstellungen zu verdeutlichen.

+++

+++**Wartungs-Update vom 26. Januar 2023**

**Fehler beim Senden einer Anfrage über [!DNL Outlook]**

_Integrationen_

Wenn ein(e) Benutzende(r) versucht, eine Anfrage mit Anhängen über eine [!DNL Outlook]-E-Mail-Adresse zu senden, werden ein oder mehrere Anhänge nicht hochgeladen und der folgende Fehler wird angezeigt.

„[!UICONTROL Der folgende Fehler ist aufgetreten: Datei mit Handle xxxx ist nicht vorhanden.]“

Dies tritt nur auf, wenn bei der neuen Anfrage entweder über die Anfrage-Warteschlange oder beim manuellen Erstellen der Anfrage ein Arbeitsauftrag erteilt wird.

**Neue Desktop Proofing Viewer-Version**

_Proofing_

Um ein Einfrieren im Desktop Proofing Viewer zu beheben, haben wir eine neue Version des Desktop Proofing Viewers bereitgestellt. Benutzende, die bereits den Desktop Proofing Viewer installiert haben, erhalten dieses Update automatisch.

Benutzende können die neueste Version auch manuell herunterladen. Weitere Informationen finden Sie unter [Installieren des Desktop Proofing Viewers](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=de).

* Frühere Version: 2.1.19
* Neue Version: 2.1.20

**Benutzende können ihre eigenen Benutzereinstellungen nicht bearbeiten**

_Benutzende_

Wenn Benutzende mit einer Lizenz für Arbeit, Überprüfung oder Anfrage versuchen, ihre eigenen Benutzereinstellungen zu bearbeiten, ist das Popup leer und die Benutzenden können keine Änderungen vornehmen. Um das Popup zu schließen, muss die Seite aktualisiert werden.

+++

+++**Wartungs-Update vom 19. Januar 2023**

**Spaltenfilter für die Aufnahme können jetzt geteilt werden**

_Pinnwände_

Als die Aufnahmespaltenfunktion in Pinnwänden veröffentlicht wurde, konnten die Filter zur Einrichtung der Aufnahmespalte nur von der Person gesehen werden, die diese Filter erstellt hatte. Jetzt kann die erstellende Person die Filter mit anderen Benutzenden oder Teams teilen.

**PIN-Funktion verfügbar im Menü [!UICONTROL Mehr]**

_Navigation_

Die folgenden Funktionen sind jetzt im Menü [!UICONTROL Mehr] für Pins in der Produktionsumgebung verfügbar:

* Pins umbenennen
* Pins innerhalb des Menüs [!UICONTROL Mehr] neu anordnen
* Pin aus dem Menü [!UICONTROL Mehr] entfernen (dabei wird der letzte Pin in der oberen Navigationsleiste in das Menü [!UICONTROL Mehr] verschoben)

+++

+++**Wartungs-Update vom 18. Januar 2023**

**Ausdrücke mit Platzhaltern sind in benutzerdefinierten Feldern nicht gültig**

_Benutzerdefinierte Formulare_

Wenn Benutzende einen Platzhalter wie \$$TODAY oder $$NOW zusammen mit einem Modifikator (z. B. „-30d“) in einem benutzerdefinierten Feld verwenden, akzeptiert der Validator den Platzhalter nicht als gültig. Platzhalter ohne Modifikatoren werden als gültig betrachtet.

**[!UICONTROL Lastenausgleich] zeigt Stunden an, die mit keinem Projekt/keiner Aufgabe/keinem Problem verknüpft sind**

_[!UICONTROL Workload-Balancer]_

Wenn Benutzende den [!UICONTROL Lastenausgleich] betrachten, sehen sie Stunden, die für Benutzende protokolliert wurden und keinem Projekt, keiner Aufgabe sowie keinem Problem zugeordnet sind und auch nicht als [!UICONTROL Allgemeine] Stunden eingetragen sind. Diese Stunden werden möglicherweise nur in der 4- oder 6-Wochen-Ansicht angezeigt.

+++

+++Wartungs-Update für **[!DNL Adobe Workfront Fusion] (Hotfix) vom 12. Januar 2023**

**404-Fehler bei [!DNL Workfront]-Modulen**

_Workfront Fusion_

Beim Ausführen eines Szenarios, wird von einem [!DNL Workfront]-Modul ein 404-Fehler zurückgegeben.

Dies wurde in den folgenden Modulen gemeldet:

* [!UICONTROL Datensatz lesen]

+++

+++**Wartungs-Update (Hotfix) vom 12. Januar 2023**

**„[!UICONTROL Hoppla]“-Fehler beim Einrichten eines berechneten Felds**

_Benutzerdefinierte Formulare_

Wenn ein(e) Benutzende(r) ein berechnetes Feld in einem benutzerdefinierten Formular erstellt oder bearbeitet und ein benutzerdefiniertes Feld in den Ausdruck des berechneten Felds einbezieht, wird der Ausdruck als ungültig erachtet. Die Schaltfläche [!UICONTROL Speichern] ist deaktiviert und der Benutzer kann das benutzerdefinierte Feld nicht verlassen. Zusätzlich wird unter dem Feld folgende angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Wenn Sie das benutzerdefinierte Feld aus dem Ausdruck entfernen, können Sie das Feld speichern und verlassen.

**Zugriffsebenen können nicht festgelegt werden**

_Benutzer_

Wenn Benutzende versuchen, die Zugriffsebene anderer Benutzender zu ändern, sind die Zugriffsebenen grau ausgeblendet, und die Benutzenden können sie nicht ändern. Dies ist auch dann der Fall, wenn die Person, die die Änderung durchführt, eine Systemadministratorin oder ein Systemadministrator ist.

+++

+++**Wartungs-Update vom 12. Januar 2023**

**Strg+F bzw. Befehl+F funktioniert in Dropdown-Feldern nicht wie erwartet**

_Benutzerdefinierte Formulare_

Wenn ein(e) Benutzende(r) ein benutzerdefiniertes Formular ausfüllt und mithilfe von Strg+F oder Befehl+F eine Dropdown-Liste durchsucht und dann versucht, zur nächsten Instanz dieser Suche zu springen, kehrt die Dropdown-Liste zum Anfang der Liste zurück, anstatt zur nächsten Instanz der Suche zu springen. Dies tritt auf, wenn ein Dropdown-Menü so eingerichtet ist, dass mehrere Auswahlmöglichkeiten zulässig sind.

**[!UICONTROL Berichtbearbeitungsbildschirm] ist leer**

_Berichte_

Wenn ein(e) Benutzende(r) einen Bericht betrachtet und versucht, den Bericht zu bearbeiten, wird er/sie auf einen leeren Bildschirm weitergeleitet und kann den Bericht nicht bearbeiten.

**Eingerückte Aufgaben bleiben nicht eingerückt**

_Aufgaben_

Wenn ein(e) Benutzende(r) eine Aufgabenliste anzeigt und eine Aufgabe einrückt, kehrt die Aufgabe sofort an die ursprüngliche (ausgerückten) Position zurück.

+++

+++**Wartungs-Update vom 5. Januar 2023**

**PIN-Funktion verfügbar im Menü [!UICONTROL Mehr]**

_Navigation_

Die folgenden Funktionen sind jetzt für Pins im Menü [!UICONTROL Mehr] verfügbar; nur in der Vorschau-Umgebung:

* Pins umbenennen
* Pins innerhalb des Menüs [!UICONTROL Mehr] neu anordnen
* Pin aus dem Menü [!UICONTROL Mehr] entfernen (dabei wird der letzte Pin in der oberen Navigationsleiste in das Menü [!UICONTROL Mehr] verschoben)

**Die Einschränkung für Projektgruppen wurde entfernt, sodass Benutzende zum Projektteam hinzugefügt werden können**

_Teams_

Wir haben die Einschränkung entfernt, die erforderlich machte, dass die einem Projektteam hinzuzufügenden Benutzenden in der mit dem Projekt verknüpften Gruppe sein müssen. Jetzt können Sie einem Projektteam jeden aktiven Benutzenden hinzufügen, unabhängig davon, zu welchen Gruppen er gehört.

**Neue Informationssymbole für Arbeitszeittabellen, Arbeitszeittabellenprofile und Arbeitszeittabellen-Voreinstellungen**

>[!NOTE]
>
>Dieses Update wurde am 3. November 2022 in der Vorschau-Umgebung veröffentlicht und ist jetzt in der Produktionsumgebung verfügbar.

_Workfront_

Wir haben zu den folgenden Einstellungen mehrere Informationssymbole hinzugefügt:

* Wenn das Kontrollkästchen „Kann die Zeit bearbeiten“ bei der Erstellung oder Bearbeitung einer Arbeitszeittabelle oder eines Arbeitszeittabellenprofils aktiviert wird, bedeutet dies, dass die genehmigenden Personen auch die Arbeitszeittabelle senden, erneut öffnen oder bearbeiten können, es sei denn, der Administrierende beschränkt diese Aktionen im Bereich „Arbeitszeittabellen-Voreinstellungen“ im Setup.
* Wenn die Option „Bearbeitung von Arbeitszeittabellen auf Inhaber und Administrierende beschränken“ im Bereich „Setup“ deaktiviert ist, können auch die folgenden Benutzenden die Arbeitszeittabellen bearbeiten: Benutzende mit administrativem Zugriff auf Arbeitszeittabellen und Stunden, Arbeitszeittabellen-Genehmiger, die die Zeit bearbeiten dürfen, und Arbeitszeittabellen-Besitzer mit Verwaltungsrechten.

Beachten Sie, dass sich die Funktionalität dieser Einstellungen nicht geändert hat und nur die Informationssymbole hinzugefügt wurden, um den Umfang der Einstellungen zu verdeutlichen.

+++

## Frühere Wartungs-Updates

Informationen zu früheren Wartungs-Updates finden Sie hier:

* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2022](2022-updates.md)
* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2021](2021-updates.md)
