---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: fdf641bd38d05d6b8abac133daa3118d2c0fff3a
workflow-type: tm+mt
source-wordcount: '15397'
ht-degree: 99%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2022 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Informationen zu Wartungs-Updates, die vor 2022 durchgeführt wurden, finden Sie unter [früheren Wartungs-Updates](#previous-maintenance-updates)

## Updates im November 2022

+++**Wartungs-Update vom 17. November 2022**

**Dokumente, die in der [!UICONTROL Papierkorb] wenn beim Verschieben einer Aufgabe oder eines Problems nicht ausgewählt**

*Dokumente*

Wenn Sie jetzt die Option [!UICONTROL Dokumente] -Option beim Verschieben einer Aufgabe oder eines Problems, der Dokumente, die an die Aufgabe angehängt sind, oder des Problems wird in der [!UICONTROL Papierkorb] für 30 Tage. Ein Administrator kann sie bei Bedarf wiederherstellen. Der Benutzer, der die Auswahl von Dokumenten im verschiebenden Prozess aufhebt, erhält eine Warnung zu diesem Verhalten in der [!UICONTROL Aufgabe verschieben] oder [!UICONTROL Problem verschieben] ankreuzen. Vor dieser Verbesserung wurden die Dokumente dauerhaft gelöscht.

**Beim Ausblenden eines Elements wird das falsche Element ausgeblendet**

*Layout-Vorlagen*

Wenn ein(e) Benutzende(r) verändert, ob ein Element ausgeblendet oder angezeigt werden soll, werden diese Änderungen in der Layout-Vorlage von einem anderen Element übernommen.


+++

+++**Wartungs-Update vom 10. November 2022**

**Durch Massenbearbeitung werden Aufgabenzuweisungen geändert**

*Aufgaben*

Wenn ein(e) Benutzende(r) ein Feld für mehrere Aufgaben gleichzeitig bearbeitet, werden die Arbeitsaufträge der ersten Aufgabe auf alle Aufgaben angewendet. Dadurch werden frühere Arbeitsaufträge gelöscht.

**Interaktiver Korrekturabzug kann nicht geöffnet werden**

*Workfront-Korrekturabzug*

Wenn ein(e) Benutzende(r) versucht, einen interaktiven Korrekturabzug zu öffnen, wird er nicht geöffnet und die folgende Fehlermeldung wird angezeigt:

„[!UICONTROL Korrekturabzug nicht geladen (501); versuchen Sie es erneut]“

+++

+++**Wartungs-Update (Hot Fix) vom 4. November 2022**

**Probleme mit Aufgaben, die einer Iteration hinzugefügt werden**

*Agile*

Die folgenden Probleme wurden beim Hinzufügen von Aufgaben zu einer Iteration gemeldet:

* Manche Unteraufgaben einer Aufgabe, die einer Iteration hinzugefügt wurden, werden nicht auf der Seite [!UICONTROL Iteration] angezeigt.
* Wenn ein(e) Benutzende(r) versucht, der Iteration eine fehlende Aufgabe hinzuzufügen, wird die Aufgabe nicht hinzugefügt und die folgende Meldung wird angezeigt:

   „[!UICONTROL Folgender Fehler ist aufgetreten: Keines der ausgewählten Objekte konnte verschoben werden, da sie keinem agilen Team zugewiesen sind oder keine agilen Elemente sind]“

**Aufgaben, die durch Massenbearbeitung zugewiesen werden, werden nicht in der Rückstandsanzeige des Teams angezeigt**

*Agile*

Wenn ein(e) Benutzende(r) einem Scrum-Team Aufgaben mithilfe der Massenbearbeitung zuweist, werden diese Aufgaben nicht in der Rückstandsanzeige des Teams angezeigt.

Kanban-Teams sind von diesem Problem nicht betroffen.

**Das Textfeld „[!UICONTROL Neue Korrekturabzugsempfänger]“ ist zu klein**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) einen Korrekturabzug betrachtet und versucht, ihn über die Registerkarte [!UICONTROL Freigabe] freizugeben, ist das Textfeld „[!UICONTROL Neue Testversand-Empfänger]“ sehr klein. Der/die Benutzende kann zwar einen Namen eingeben, doch das Feld ist so klein, dass der Text so umgebrochen wird, dass er schwer lesbar ist.

**Berichtverwendungsinformationen werden nicht aktualisiert**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht öffnet, werden Informationen zur letzten Ansicht des Berichts, wie etwa ‚Zuletzt angezeigt am‘ und ‚Zuletzt angezeigt von‘, nicht aktualisiert. Dies bedeutet, dass alle Nutzungsinformationen falsch sein können.

Dieses Verhalten wurde gemeldet, wenn über folgende Tools auf einen Bericht zugegriffen wird:

* Suchen
* Nadeln
* Favoriten
* Letzte

Beim Zugriff auf Berichte über ein Dashboard werden die Informationen zur letzten Anzeige eines Berichts aktualisiert.

**[!DNL Workfront]: 500-Fehler bei Änderungen an einem [!DNL Workfront]-Objekt**

*[!DNL Workfront]*

Wenn ein(e) Benutzende(r) versucht, Änderungen an einem [!DNL Workfront]-Objekt vorzunehmen, werden die Änderungen nicht gespeichert und der folgende Fehler wird angezeigt:

„[!UICONTROL 500: Datenbankfehler aufgrund von ungültigem SQL-Befehl.]“

Dies wurde in den folgenden Situationen gemeldet:

* Änderung des Status eines Objekts
* Neuberechnung der Timeline
* Anhängen einer Vorlage
* Erfassen der Zeit

+++

+++**[!DNL Workfront Fusion]Wartungs-Update vom 3. November 2022**

**Fehler bezüglich [!UICONTROL apiKey] in [!DNL Workfront] > Modul [!UICONTROL Ereignisse beobachten]**

*[!DNL Workfront Fusion]*

Wenn ein(e) Benutzende(r) versucht, einen Webhook zum Modul [!DNL Workfront] > [!UICONTROL Ereignisse beobachten] hinzuzufügen, wird der folgende Fehler angezeigt:

„[!UICONTROL Der bereitgestellte apiKey war leer oder ungültig.]“

+++

+++**Wartungs-Update vom 3. November 2022**

**Umbenennung der Abschnitte „Zeitplan“ und „Planung“ für Teams und Projekte in der Layout-Vorlage**

*Layout-Vorlagen*

Die Registerkarten „Zeitplan“ und „Planung“, die in einer Layout-Vorlage zum linken Bedienfeld eines Teams oder Projekts hinzugefügt werden können, wurden in „Workload Balancer“ umbenannt.

**Fehler beim Zugriff auf E-Mail-Benachrichtigungseinstellungen**

*Benachrichtigungen*

>[!NOTE]
>
>Dieses Problem tritt sowohl in der Produktions- als auch in der Vorschau-Umgebung auf.

Wenn Ein(e) Benutzende(r) versucht, die Einstellungen für E-Mail-Benachrichtigungen zu ändern, wird möglicherweise einer der folgenden Fehler angezeigt:

* „[!UICONTROL Versuchen Sie es erneut. Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

* „[!UICONTROL E-Mail-Benachrichtigung konnte nicht abgerufen werden]“

Dies wurde in den folgenden Bereichen gemeldet:

* [!UICONTROL Setup] > [!UICONTROL E-Mail-Benachrichtigungen]
* [!UICONTROL Benutzer] > [!UICONTROL Benutzer bearbeiten]
* [!UICONTROL Gruppen]

+++

## Updates im Oktober 2022

+++**Wartungs-Update vom 27. Oktober 2022**

**[!UICONTROL STUNDE]-Funktion in berechneten Feldern verwendet UTC**

*Benutzerdefinierte Formulare*

Wenn ein berechnetes Feld die Funktion [!UICONTROL STUNDE] enthält, gibt die Funktion Werte basierend auf UTC und nicht auf der erwarteten Zeitzone zurück. Daher sind alle Berechnungen, die auf dem Wert STUNDE basieren, falsch.

**[!UICONTROL Schnellfilter] gibt bei der Suche nach Teams keine Ergebnisse aus**

*Listen*

Wenn ein(e) Benutzende(r) versucht, mithilfe des [!UICONTROL Schnellfilters] in einer Liste nach einem Team zu suchen, werden durch die Eingabe des Team-Namens keine Ergebnisse zurückgegeben, selbst wenn das gesuchte Team in der Liste sichtbar ist (z. B. im Feld [!UICONTROL Zugewiesen an]). Auch die Suche nach dem Wort „[!UICONTROL Team]“ liefert keine Ergebnisse.

**Eine Seite kann nicht erneut angeheftet werden, nachdem ihre Nadel entfernt wurde**

*Navigation*

>[!NOTE]
>
>Dieses Problem wurde am 13. Oktober 2022 in der Vorschau-Umgebung behoben. Am 27. Oktober 2022 wurde es in der Produktionsumgebung behoben.

Wenn ein(e) Benutzende(r) auf einer Nadel die Option „[!UICONTROL Nadel entfernen]“ auswählt, eine Meldung über die Entfernung erhält und versucht, die Nadel durch Klicken auf „[!UICONTROL Rückgängig]“ in der Nachricht wiederherzustellen, wird die Nadel in der oberen Navigationsleiste nicht wiederhergestellt und auch nicht zur Liste der Nadeln in [!UICONTROL Weitere Nadeln] hinzugefügt (das Dreipunkt-Menü im Bereich [!UICONTROL Nadeln]).

Wenn ein(e) Benutzende(r) versucht, die Seite erneut anzuheften, indem er/sie die Seite aufruft und anheftet, wird die Nadel nicht erstellt und der/die Benutzende kann die Seite nicht anheften.

**Im [!UICONTROL Workload Balancer] werden alle Benutzenden aufgelistet, wenn im [!DNL Safari]-Browser ein Freigabe-Link verwendet wird**

*[!UICONTROL Workload Balancer]*

Wenn ein(e) Benutzende(r) im [!DNL Safari]-Browser auf einen Freigabe-Link zum [!UICONTROL Workload Balancer] klickt, werden alle Benutzenden und nicht nur die aufgelisteten Team-Mitglieder angezeigt.

+++

+++**Wartungs-Update vom 20. Oktober 2022**

**Fehler bei der Massenzuweisung eines Teams**

*Arbeitsaufträge*

Wenn ein(e) Benutzende(r) mehrere Aufgaben oder Probleme gleichzeitig bearbeitet und ein Team zuweist, nachdem eine einzelne Person zugewiesen wurde, werden die Arbeitsaufträge nicht gespeichert und die folgende Fehlermeldung wird angezeigt:

„[!UICONTROL Versuchen Sie es erneut. Der folgende Fehler ist aufgetreten: Team-Arbeitsaufträge müssen entweder eine Liste von Objekten oder eine Liste von IDs sein]“

**Fehlermeldung „[!UICONTROL Fehler beim Hochladen der Datei]“**

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, eine Datei in den Bereich [!UICONTROL Dokumente] hochzuladen, wird die Datei nicht hochgeladen und die folgende Fehlermeldung wird angezeigt: „[!UICONTROL Fehler beim Hochladen der Datei]“.

Dieser Fehler wurde beim Versuch gemeldet, MP4-Dateien hochzuladen.

**Falsche Anzahl von Problemen im linken Navigationsbereich bei Aufgaben**

*Probleme*

Wenn ein(e) Benutzende(r) eine Aufgabe aufruft, stellt die Zahl der [!UICONTROL Probleme] im linken Navigationsbereich nicht die korrekte Anzahl der mit der Aufgabe verbundenen Probleme dar.


Symbol **[!UICONTROL Vorgänger] fehlt in der Aufgabenkopfzeile**

*Aufgaben*

Wenn ein(e) Benutzende(r) eine Aufgabe betrachtet, fehlt das Vorgänger-Symbol der Aufgabe in der Kopfzeile.

+++

+++**Wartungs-Update vom 13. Oktober 2022**

**Eine Seite kann nicht erneut angeheftet werden, nachdem ihre Nadel entfernt wurde**

*Navigation*

>[!NOTE]
>
>Dieses Problem wird am 13. Oktober 2022 in der Vorschau-Umgebung behoben. Am 27. Oktober 2022 wird es in der Produktionsumgebung behoben.

Wenn ein(e) Benutzende(r) auf einer Nadel die Option „[!UICONTROL Nadel entfernen]“ auswählt, eine Meldung über die Entfernung erhält und versucht, die Nadel durch Klicken auf „[!UICONTROL Rückgängig]“ in der Nachricht wiederherzustellen, wird die Nadel in der oberen Navigationsleiste nicht wiederhergestellt und auch nicht zur Liste der Nadeln in [!UICONTROL Weitere Nadeln] hinzugefügt (das Dreipunkt-Menü im Bereich [!UICONTROL Nadeln]).

Wenn ein(e) Benutzende(r) versucht, die Seite erneut anzuheften, indem er/sie die Seite aufruft und anheftet, wird die Nadel nicht erstellt und der/die Benutzende kann die Seite nicht anheften.

**Neu erstellte Filter können nicht benannt oder gespeichert werden**

*[!UICONTROL Ressourcenplaner]*

Wenn ein(e) Benutzende(r) versucht, einen neuen Filter im [!UICONTROL Ressourcenplaner] zu benennen, bleibt das Namensfeld leer. Wenn der/die Benutzende die Leertaste gedrückt hat, wird die Schaltfläche [!UICONTROL Speichern] deaktiviert.

**Name oder „Prozent abgeschlossen“ einer Aufgabe oder eines Problems kann nicht bearbeitet werden**

*Aufgaben und Probleme*

Benutzende mit der Zugriffsberechtigung [!UICONTROL Beitragen] für eine Aufgabe oder ein Problem können den Namen der Aufgabe oder des Problems in der Kopfzeile nicht bearbeiten. Darüber hinaus können Benutzende mit der Zugriffsberechtigung [!UICONTROL Beitragen] den Bereich „Prozent abgeschlossen“ einer Aufgabe oder eines Problems nicht bearbeiten.

**Anfordernde und Prüfende werden bei der Lizenzanzahl eines Unternehmens mitgezählt**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einem Korrekturabzug als Prüfende(r) oder Anfragende(r) hinzugefügt wird, erhält er/sie das Berechtigungsprofil „[!UICONTROL Besucher]“, für das keine [!DNL Workfront Proof]-Lizenz erforderlich ist. Wenn der/die Benutzende hinzugefügt wird, steigt aber die Anzahl der verwendeten [!DNL Workfront Proof]-Lizenzen.

+++

+++**Wartungs-Update vom 11. Oktober 2022**

**Eine Seite kann nicht erneut angeheftet werden, nachdem ihre Nadel entfernt wurde**

*Navigation*

>[!NOTE]
>
>Dieses Problem wurde am 13. Oktober 2022 in der Vorschau-Umgebung behoben. Am 27. Oktober 2022 wird es in der Produktionsumgebung behoben.

Wenn ein(e) Benutzende(r) auf einer Nadel die Option „[!UICONTROL Nadel entfernen]“ auswählt, eine Meldung über die Entfernung erhält und versucht, die Nadel durch Klicken auf „[!UICONTROL Rückgängig]“ in der Nachricht wiederherzustellen, wird die Nadel in der oberen Navigationsleiste nicht wiederhergestellt und auch nicht zur Liste der Nadeln in [!UICONTROL Weitere Nadeln] hinzugefügt (das Dreipunkt-Menü im Bereich [!UICONTROL Nadeln]).

Wenn ein(e) Benutzende(r) versucht, die Seite erneut anzuheften, indem er/sie die Seite aufruft und anheftet, wird die Nadel nicht erstellt und der/die Benutzende kann die Seite nicht anheften.

+++

+++**Wartungs-Update vom 6. Oktober 2022**

**Neuer Blueprint-Typ**

*Blueprints*

Dem Blueprint-Katalog wurde der Blueprint-Typ „Dashboard“ hinzugefügt. Zuvor waren nur Blueprints zu Projektvorlagen und zur Organisationsstruktur verfügbar.

**Elemente überschneiden sich im linken Bedienfeld**

*Benutzerdefinierte Formulare*

Wenn ein(e) Benutzende(r) im Formular-Builder arbeitet und das Formular mehr als 100 Felder enthält, führt die Meldung, die den/die Benutzende(n) über die Feldbegrenzung informiert, zu einer Überschneidung der Elemente im linken Bereich.

**Die Datumsauswahl wird nicht mehr automatisch beim Eingabefokus oder Klicken geöffnet**

*Navigation*

Wenn ein(e) Benutzende(r) die Tastatur zur Navigation verwendet, wird die Datumsauswahl bei der Datumseingabe, bei der der Eingabefokus ist, nicht mehr automatisch geöffnet. Stattdessen sollten Tastaturbenutzende das Symbol zur Datumsauswahl verwenden und die Eingabetaste drücken, um die Datumsauswahl zu öffnen. Wenn ein(e) Benutzende(r) mit der Maus navigiert, wird die Datumsauswahl beim Anklicken der Datumseingabe nicht mehr automatisch geöffnet. Stattdessen sollten Mausbenutzende auf das Symbol zur Datumsauswahl klicken, um die Datumsauswahl zu öffnen.

Diese Änderung wurde vorgenommen, um eine konsistente Nutzung analog der Standard-Datumsauswahl zu ermöglichen und Benutzenden von Tastatur- und Bildschirmlesehilfen einen barrierefreien Zugriff bereitzustellen.

**Das Zuweisen mehrerer Teams führt dazu, dass nur ein Team zugewiesen ist**

*Teams*

>[!NOTE]
>
>Dieses Problem tritt nur in der Vorschau-Umgebung auf.

Wenn ein(e) Benutzende(r) einer Aufgabe oder einem Problem mehrere Teams zuweist, wird in der Arbeitsauftragsliste nur ein Team angezeigt. Dieses Problem betrifft auch das Reporting. Berichte, die Team-Arbeitsaufträge enthalten, sind nicht korrekt, da nur ein Team als der Aufgabe oder dem Problem zugewiesen angezeigt wird.

**Bei der automatischen Speicherung von Änderungen in einer Arbeitszeittabelle tritt der Fehler „[!UICONTROL Ihre letzten Änderungen wurden nicht gespeichert]“ auf**

*Arbeitszeittabellen*

Wenn ein(e) Benutzende(r) versucht, eine Arbeitszeittabelle so zu bearbeiten, dass die automatische Speicherung der Änderungen ausgelöst wird, werden die Änderungen nicht gespeichert und der/die Benutzende sieht die folgende Meldung:

„[!UICONTROL Ihre letzten Änderungen wurden nicht gespeichert. Aktualisieren Sie die Seite, um die Änderungen anzuzeigen]“.

Dies wurde beim Bearbeiten der folgenden Elemente gemeldet:

* Stunden
* Aufgaben

**E-Mail-Benachrichtigungen sind verzögert**

*Workfront-Korrekturabzug*

Wenn ein Ereignis in [!DNL Workfront Proof] stattfindet, durch das eine E-Mail-Benachrichtigung ausgelöst wird, erhält der/die Benutzende die Benachrichtigung nicht sofort. Die Benachrichtigung kann um mehrere Stunden verzögert ankommen.

+++

+++**Wartungs-Update vom 3. Oktober 2022**

**Speichern Sie Ihre Arbeitszeittabelle manuell, wenn sich die vorherigen Aufgabengebiete geändert haben.**

*Arbeitszeittabellen*

Wenn sich ein Aufgabengebiet, für das Sie die Zeit erfasst haben, geändert hat und die Einstellung [!UICONTROL Aufgabengebiet zu Stundeneinträgen manuell hinzufügen] deaktiviert wurde, müssen Sie Ihre Zeiteinträge manuell speichern, bis für das geänderte Aufgabengebiet keine Stunden mehr erfasst werden.

+++

## Updates im September 2022

+++**Wartungs-Update vom 29. September 2022**

**Benutzende(r) kehrt beim Schließen des Korrekturabzugs nicht zur vorherigen Seite zurück**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) in [!DNL Workfront] einen Korrekturabzug betrachtet und dann schließt, kehrt er/sie nicht zur Seite zurück, auf der er/sie sich vor dem Öffnen des Korrekturabzugs befand. Stattdessen gelangt er/sie auf eine andere Seite in [!DNL Workfront].

**Der Korrekturabzug kann in[!DNL Workfront]** nicht geöffnet werden

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) ein Dokument in [!DNL Workfront] betrachtet und versucht, den Korrekturabzug zu öffnen, wird er nicht geöffnet und der/die Benutzende gelangt wieder auf die Seite [!UICONTROL Dokumentdetails].

**Bei Verwendung der [!UICONTROL Tabulatortaste] werden die Stunden nicht gespeichert**

*Arbeitszeittabellen*

Wenn ein(e) Benutzende(r) eine Arbeitszeittabelle ausfüllt und mit der [!UICONTROL Tabulatortaste] zwischen Zellen navigiert, werden die Stunden nicht gespeichert. Die Benachrichtigung zum [!UICONTROL automatischen Speichern] wird nicht unten am Bildschirm angezeigt. Wenn der/die Benutzende die Seite aktualisiert, kann er/sie sehen, das die Stunden nicht gespeichert wurden.

**Leere Seiten, wenn ein Korrekturabzug mit mehreren Seiten aufgerufen wird**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einen Korrekturabzug mit mehreren Seiten aufruft, kann er/sie zwar die Miniaturansichten der Seiten sehen, die Seiten werden jedoch nicht im Hauptansichtsfenster geöffnet.



+++

+++**Wartungs-Update vom 22. September 2022**

**Benutzerkarte wird in Aktualisierungen nicht geschlossen**

*Updates*

Wenn sich ein(e) Benutzende(r) Aktualisierungen ansieht und den Mauszeiger über einen Namen bewegt, wird eine Karte mit Details zum/r entsprechenden Benutzenden geöffnet und nicht automatisch wieder geschlossen. Die Seite reagiert nicht mehr, bis die Karte manuell geschlossen wird, indem auf das X in der oberen rechten Ecke geklickt wird.

+++

+++**Wartungs-Update vom 15. September 2022**

**Beim Eingeben von Stunden erscheint der Fehler „[!UICONTROL Eine andere Person hat versucht, dieses Projekt zu speichern]“**

*Arbeitszeit- tabellen*

Wenn ein(e) Benutzende(r) versucht, einer Aufgabe auf seiner/ihrer Arbeitszeittabelle Stunden hinzuzufügen, werden die Stunden nicht automatisch gespeichert und die folgende Fehlermeldung erscheint:

„[!UICONTROL Hinweis: Das Speichern ist fehlgeschlagen, da ein anderer Benutzer gleichzeitig versucht hat, dieses Projekt zu speichern. Versuchen Sie erneut, das Projekt zu speichern.]“

**Benutzerkarte wird in Aktualisierungen nicht geschlossen**

*Updates*

Wenn sich ein(e) Benutzende(r) Aktualisierungen ansieht und den Mauszeiger über einen Namen bewegt, wird eine Karte mit Details zum/r entsprechenden Benutzenden geöffnet und nicht automatisch wieder geschlossen. Die Seite reagiert nicht mehr, bis die Karte manuell geschlossen wird, indem auf das X in der oberen rechten Ecke geklickt wird.

**Das Feld „[!UICONTROL Aufgabenrollenzuweisung]“ wurde in „[!UICONTROL Rollenzuweisung]“ umbenannt, um zum Ausdruck zu bringen, dass gleichzeitig mehrere Arbeitsaufgaben über den [!UICONTROL Workload Balancer]** zugewiesen werden können

*[!UICONTROL Lastenausgleich]*

Um die neue Funktionalität besser zum Ausdruck zu bringen, mit der eine größere Anzahl von sowohl Aufgaben als auch Problemen im Bereich [!UICONTROL Nicht zugewiesene Arbeit] zugewiesen werden können, wurde im [!UICONTROL Workload Balancer] das Feld „[!UICONTROL Aufgabenrollenzuweisung]“ in „[!UICONTROL Rollenzuweisung]“ umbenannt. Das Feld bezieht sich auf Aufgabengebiete, die entweder Aufgaben oder Problemen zugewiesen wurden, und es wird angezeigt, wenn im Feld [!UICONTROL Massenzuweisungen] Benutzende Elementen zugewiesen werden.

+++

+++**[!DNL Workfront Scenario Planner]Wartungs-Update vom 15. September 2022**

**Ein für eine Gruppe freigegebener Filter wird nun für Mitglieder aller Untergruppen im [!DNL Scenario Planner] in der Liste [!UICONTROL Projekte importieren] angezeigt**

*[!DNL Workfront Scenario Planner]*

Wenn Sie nun einen Projektfilter für eine Gruppe mit zusätzlichen Untergruppen freigeben, ist der Filter für alle Gruppen- und Untergruppenmitglieder sichtbar, die Projekte im Feld [!UICONTROL Projekte importieren] eines Plans im [!DNL Scenario Planner] betrachten.

+++

+++**Wartungs-Update vom 8. September 2022**

**Aktualisierte Feldernamen zur Zuweisung von Benutzenden und Aufgabengebieten wurden wieder zurückgesetzt**

*Zuweisungen*

Die in der letzten Woche vorübergehend umbenannten Arbeitsauftragsfelder wurden auf ihre ursprünglichen Namen zurückgesetzt:

* [!UICONTROL Arbeitsauftrag – Benutzer]
* [!UICONTROL Arbeitsauftrag – Aufgabengebiete]

**Fehler beim Entfernen des Projektbesitzers aus der Kopfzeile**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, eine(n) [!UICONTROL Projektbesitzer(in)] aus der Kopfzeile eines Projekts zu entfernen, wird der/die [!UICONTROL Projektbesitzer(in)] nicht entfernt und der/die Benutzende erhält folgende Fehlermeldung:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Geänderte Größe des Fensters [!UICONTROL Beschreibung] wird auf die Originalgröße** zurückgesetzt

*Projekte, Aufgaben und Probleme*

Wenn ein(e) Benutzende das Fenster [!UICONTROL Beschreibung] im Detailbereich eines Arbeitselements vergrößert und dann Text in das Feld tippt, wird die Originalgröße des Feldes wiederhergestellt. Der/die Benutzende kann dennoch Text in das Feld eingeben und der Inhalt wird wie erwartet gespeichert.

**Unbeabsichtigtes Beenden beim Erstellen von Aufgaben oder Problemen**

*Aufgaben und Probleme*

Wenn ein(e) Benutzende(r) eine Aufgabe oder ein Problem in einem Projekt erstellt und außerhalb des Erstellungsfensters klickt, wird das Fenster ohne Warnung geschlossen und alle eingegebenen Informationen gehen verloren.

**Die Möglichkeit, einen Korrekturabzug per E-Mail an einen Ablagebereich zu senden, wurde entfernt**

*[!DNL Workfront Proof]*

Am 8. September 2022 haben wir die Möglichkeit entfernt, im Standalone-[!DNL Workfront Proof]-Produkt einen Korrekturabzug per E-Mail an einen Ablagebereich zu senden.

Sie können Ablagebereiche weiterhin auf andere Weise verwenden, um neue Korrekturabzüge und neue Versionen von Korrekturabzügen an Ihr Konto zu senden, ohne sich bei Ihrem Konto anmelden zu müssen. Siehe [Der Ablagebereich](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=de) für weitere Informationen.

+++

+++**Wartungs-Update vom 6. September 2022**

**Zur Felderliste für anpassbare Projekt-Kopfzeilen wurden ein voraussichtliches Datum hinzugefügt**

*Projekte*

Wir haben zur Liste der Felder für anpassbare Projekt-Kopfzeilen bei der Verwendung einer Layout-Vorlage das [!UICONTROL voraussichtliche Startdatum] und das [!UICONTROL voraussichtliche Abschlussdatum] hinzugefügt.

**Neues Limit bei einer Bestätigungsnachricht, bei der die Anzahl der zu einer Arbeitszeittabelle hinzugefügten Elemente angezeigt wird**

*Arbeitszeit- tabellen*

Wenn Sie zum Hinzufügen an eine Arbeitszeittabelle mehr als 50 Elemente auswählen, erhalten Sie jetzt eine Bestätigungsnachricht mit der Anzahl dieser Elemente und einer Möglichkeit, nicht alle Elemente hinzuzufügen. Alle hinzugefügten Elemente werden automatisch in die Arbeitszeittabelle angeheftet und müssen gegebenenfalls manuell aus allen aktuellen und zukünftigen Arbeitszeittabellen wieder entfernt werden.

+++

+++**Wartungs-Update vom 2. September 2022**

Das Feld [!UICONTROL Integrationen] kann zur benutzerdefinierten Kopfzeile eines Projekts hinzugefügt werden

*Integrationen*

Sie können bei der Verwendung einer Layout-Vorlage jetzt das Feld [!UICONTROL Integrationen] zur benutzerdefinierten Kopfzeile eines Projekts hinzufügen. Nach dem Hinzufügen wird im Feld ein Link zu einem externen Element angezeigt, das mit dem Projekt verknüpft ist, das sich je nach Integration in [!DNL Salesforce] oder [!DNL Anaplan] befindet.

>[!NOTE]
>
>Dieses Wartungs-Update wurde am 25. August 2022 in der Vorschau-Umgebung veröffentlicht und befindet sich jetzt in der Produktionsumgebung.

+++

+++**Wartungs-Update vom 1. September 2022**

**Erledigte Elemente aus der Delegierung entfernt**

*Delegierungen*

Jetzt werden beim Beginn einer Delegierung von Arbeitselementen nur mehr noch nicht erledigte Elemente, deren Daten mit den Daten einer Delegierung übereinstimmen, an andere Benutzende delegiert. Wenn Elemente vor dem Beginn der Delegierung erledigt wurden, werden sie nicht mehr delegiert. Elemente, die innerhalb des Zeitrahmens der Delegierung erledigt werden, bleiben für den/die Beauftragte(n) und den/die Zuweisende(n) zwei Wochen lang auf der Arbeitsliste des Startseiten-Bereichs, bevor sie automatisch entfernt werden, sofern die Delegierung in diesen Wochen nicht beendet wurde.

**Metadaten-Updates für [!DNL Adobe Workfront] für [!DNL Experience Manager Assets]- und [!DNL Assets Essentials]-Integrationen**

*Integrationen*

Metadaten werden automatisch übergeben, wenn Sie ein Asset zu einem verknüpften Ordner hinzufügen.

Zuvor wurden Metadaten nur übergeben, wenn Sie ein Asset mit dem Dropdown-Menü [!UICONTROL Neu hinzufügen] hinzugefügt haben.

**Stunden in Verbindung mit einem Problem können nicht genehmigt oder abgelehnt werden**

*Anfragen*

Ein(e) Benutzende(r) versucht, Stunden in Bezug auf ein Problem in der Registerkarte [!UICONTROL Stunden] zu genehmigen oder abzulehnen, doch die Schaltflächen [!UICONTROL Genehmigen] und [!UICONTROL Ablehnen] fehlen.

**Wenn ein Problem mithilfe einer Vorlage in ein Projekt konvertiert wird, wird eine falsche Fehlermeldung angezeigt**

*Anfragen*

Wenn ein Problem mithilfe einer Vorlage in ein Projekt konvertiert wird und ein Fehler auftritt, wird eine Seite mit der Mitteilung „[!UICONTROL Das Projekt existiert nicht mehr]“ anstelle der korrekten Fehlermeldung angezeigt, in der die Ursache der fehlgeschlagenen Konvertierung erklärt wird.

**Korrekturabzug für Dateien mit mehr als 1,5 GB kann nicht erstellt werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) beim Erstellen eines neuen Korrekturabzugs eine Datei mit mehr als 1,5 GB hochlädt, wird der Dateiname rot dargestellt und der Korrekturabzug kann nicht erstellt werden.

+++

## Updates im August 2022

+++**Wartungs-Update vom 25. August 2022**

**Links zum Workload Balancer werden in Dashboards falsch angezeigt**

*Dashboards*

Workload Balancer-Links zur gemeinsamen Nutzung werden falsch angezeigt, wenn sie als externe Seite zu einem Dashboard hinzugefügt werden. Anstatt die Ansicht/die Filter zu verwenden, die mit dem Link verknüpft sind, verwendet das Dashboard die jüngste Ansicht/die jüngsten Filter, die auf den Work Balancer angewendet wurden.

**Feld [!UICONTROL Integrationen] zur benutzerdefinierten Kopfzeile des Projekts kann hinzugefügt werden**

*Projekte*

Sie können bei der Verwendung einer Layout-Vorlage jetzt das Feld [!UICONTROL Integrationen] zur benutzerdefinierten Kopfzeile eines Projekts hinzufügen. Nach dem Hinzufügen wird im Feld ein Link zu einem externen Element angezeigt, das mit dem Projekt verknüpft ist, das sich je nach Integration in [!DNL Salesforce] oder [!DNL Anaplan] befindet.

>[!NOTE]
>
>Dieses Wartungs-Update befindet sich derzeit nur in der Vorschau-Umgebung. Es wird eine Woche nach der Vorschau-Veröffentlichung für die Produktion freigegeben.

**Benutzerdefinierte Daten werden beim Konvertieren eines Problems in ein leeres Projekt nicht beibehalten**

*Projekte*

Wenn ein(e) Benutzende(r) ein Problem in ein leeres Projekt konvertiert (ohne Vorlage), werden Daten in berechneten Feldern nicht an das neue Projekt übertragen.

**Fehler „Timeline-Planungsmodus“ beim Ändern eines Datums in einem Projekt**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein Datum in einem Projekt zu ändern, in dem der [!UICONTROL Planungsmodus] auf [!UICONTROL Manuelles Speichern] > [!UICONTROL Timeline-Planung] festgelegt ist, ändert sich das Datum nicht und ein Fehler wird angezeigt.

[!UICONTROL Der Timeline-Planungsmodus ist nur verfügbar, wenn „timelineDate“ geladen wird. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

**Konsistenz beim Öffnen des Workload Balancer mithilfe der Monatsansicht**

*Lastenausgleich*

Jetzt zeigt der Workload Balancer in der Ansicht [!UICONTROL Tag], [!UICONTROL Woche] oder [!UICONTROL Monat] die den Benutzenden zugewiesenen Elemente maximiert an. Vor diesem Update wurden die zugewiesenen Elemente für die [!UICONTROL Tag]- und [!UICONTROL Wochen]-Ansicht maximiert, aber für die [!UICONTROL Monats]-Ansicht reduziert angezeigt.


+++

+++**Wartungs-Update vom 18. August 2022**

Die Optionen **„[!UICONTROL Zu Iteration hinzufügen]“ und „[!UICONTROL Zu Kanban-Board hinzufügen]“ sind nicht verfügbar, wenn Aufgaben in einem Bericht inline bearbeitet werden**

*Berichte*

Wenn ein(e) Benutzende(r) eine Liste von Aufgaben in einem Bericht aufruft und das Menü [!UICONTROL Mehr] (drei Punkte) öffnet, sind die Optionen „[!UICONTROL Zu Iteration hinzufügen]“ und „[!UICONTROL Zu Kanban-Board hinzufügen]“ in der Dropdown-Liste nicht verfügbar. Wenn der Bericht in einem Dashboard angezeigt wird, sind die Optionen „[!UICONTROL Zu Iteration hinzufügen]“ und „[!UICONTROL Zu Kanban-Board hinzufügen]“ in der Dropdown-Liste verfügbar.

**Matrix-Berichte werden beim Scrollen falsch angezeigt**

*Berichte*

Wenn ein(e) Benutzende(r) einen Matrix-Bericht öffnet und scrollt, können sich einige visuelle Elemente des Berichts überschneiden oder doppelt angezeigt werden.

Ansicht **[!UICONTROL Meilenstein] aus der Arbeitszeittabellen-Projektliste entfernt**

*Arbeitszeit- tabellen*

Die Ansicht [!UICONTROL Meilenstein] wurde aus der Arbeitszeittabellen-Projektliste entfernt, wenn ein Projekt hinzugefügt wird.

**Hyperlinks in einem interaktiven Korrekturabzug sind nicht aktiv**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einen interaktiven Korrekturabzug öffnet und auf einen Link oder eine Schaltfläche klickt, die einen Link enthält, wird der/die Benutzende nicht zu der Seite weitergeleitet, auf die der Link oder die Schaltfläche verweist.

**Auf der Seite „Neuer Korrekturabzug“ fehlen Textfelder**

*[!DNL Workfront Proof]*

Auf der Seite [!DNL New Proof] werden viele Textfelder nicht angezeigt (einschließlich Feldbezeichnungen, Dropdown-Optionen und Checkbox-Namen).

**Benutzende erhalten keine Benachrichtigungen, wenn sie in einem Korrekturabzug getaggt werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) in einem Korrekturabzugskommentar getaggt wird, erhält er/sie keine E-Mail-Benachrichtigung über den Kommentar.

+++

+++**Wartungs-Update vom 12. August 2022**

**Neues anpassbares Kopfzeilenfeld am Anfang der Kopfzeile hinzugefügt**

*Kopfzeilen*

Wenn Sie ein neues Feld zu einer anpassbaren Kopfzeile hinzufügen, wird das Feld jetzt als erstes Feld links in der Kopfzeile oder direkt nach dem Feld [!UICONTROL Suche] in der Layout-Vorlage hinzugefügt. Vor dieser Änderung wurde das Feld als letztes Feld in der Kopfzeile hinzugefügt.

+++

+++**Wartungs-Update vom 11. August 2022**

**Benutzerdefinierte Formulare können aufgrund einer falschen Zeichenbeschränkung für beschreibende Textfelder nicht bearbeitet werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) versucht, ein benutzerdefiniertes Formular zu bearbeiten, und dieses [!UICONTROL ein beschreibendes Textfeld] beinhaltet, das mehr als 512 Zeichen enthält, können die Änderungen nicht im benutzerdefinierten Formular gespeichert werden und der folgende Fehler wird angezeigt:

„Die folgenden Felder sind ungültig: (Feld) ist zu lang, max. 512“

Dies betrifft [!UICONTROL beschreibende Textfelder], die zuvor gut funktioniert haben, obwohl sie mehr als 512 Zeichen enthielten.

**Daten in Feldern, die durch einen Abschnittsumbruch ausgeblendet werden, bleiben beim Konvertieren eines Problems in ein Projekt nicht erhalten**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) ein Problem in ein Projekt konvertiert und das Problem ein benutzerdefiniertes Formular mit Daten in einem Abschnittsumbruch enthält, der mithilfe der Anzeigelogik ausgeblendet werden kann, werden die Daten in diesem Abschnitt nicht an das neue Projekt übertragen.

**Daten in Feldern, die durch einen Abschnittsumbruch ausgeblendet werden, bleiben beim Konvertieren einer Anfrage in ein Projekt nicht erhalten**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) eine Anfrage in ein Projekt konvertiert und die Anfrage ein benutzerdefiniertes Formular mit Daten in einem Abschnittsumbruch enthält, der mithilfe der Anzeigelogik ausgeblendet werden kann, werden die Daten in diesem Abschnitt nicht an das neue Projekt übertragen.

**Benutzerdefinierte Formulare können aufgrund eines beschreibenden Textfelds nicht bearbeitet werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) versucht, ein benutzerdefiniertes Formular zu bearbeiten, das ein beschreibendes Textfeld enthält, wird der Feldtitel nicht befüllt. Der/die Benutzende sieht unter dem Titelfeld den Fehler „[!UICONTROL Dies ist ein Pflichtfeld]“ und kann das benutzerdefinierte Formular aufgrund dieses Fehlers nicht bearbeiten.

**Anweisungen können nicht aus einem benutzerdefinierten Feld im Formular-Builder entfernt werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer ein benutzerdefiniertes Feld bearbeitet und versucht, vorhandenen Text im Bereich [!UICONTROL Anweisungen] zu entfernen, wird der Text beim Speichern des Felds nicht entfernt. Der/die Benutzende kann Text bearbeiten, ihn aber nicht vollständig entfernen.

**Team-Arbeitsauftrag erscheint beim Erstellen einer Anfrage nicht in der neuen Anfrage**

*Anforde- rungen*

Wenn ein(e) Benutzende(r) eine Anfrage erstellt und ihr ein Team zuweist und dann die Anfrage absendet, wird das Team der erstellten Anfrage nicht zugewiesen. Dies betrifft nur Arbeitsaufträge an Teams. Arbeitsaufträge an Benutzende funktionieren erwartungsgemäß.

+++

+++**Wartungs-Update vom 4. August 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben.

Alle Funktionen von [!DNL Workfront Classic] wurden am 14. Juli 2022 entfernt.

**Fehler beim Ändern des geplanten Abschlussdatums in der Kopfzeile einer Aufgabe oder eines Problems**

*Aufgaben und Probleme*

Wenn ein(e) Benutzende(r) versucht, das [!UICONTROL geplante Abschlussdatum] in der Kopfzeile einer Aufgabe oder eines Problems zu ändern, wird das Datum nicht geändert und dem/r Benutzenden wird ein Fehler angezeigt, der in etwa folgendermaßen lautet:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Updates im Juli 2022

+++**Wartungs-Update vom 28. Juli 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben.

Alle Funktionen von [!DNL Workfront Classic] wurden am 14. Juli 2022 entfernt.

**Fehler beim Öffnen eines Elements in der [!UICONTROL Startseiten-Arbeitsliste]**

*[!UICONTROL Startseite]*

Wenn ein(e) Benutzende(r) versucht, ein Element in seiner/ihrer [!UICONTROL Startseiten-Arbeitsliste] zu öffnen, wird das Element nicht geöffnet und die folgende Fehlermeldung wird angezeigt:

„[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browser-Seite, um mit Ihrer Arbeit fortzufahren.]“

**Aufgaben und Probleme, die einem/r Benutzenden zugewiesen wurden, werden nicht in der Startseiten-Arbeitsliste des/r Benutzenden angezeigt**

*[!UICONTROL Startseite]*

Wenn ein(e) Benutzende(r) die [!UICONTROL Startseiten-Arbeitsliste] aufruft, werden dem/r Benutzenden zugewiesenen Aufgaben oder Probleme nicht in der Liste aufgeführt und dem/r Benutzenden sind die Delegationen möglicherweise nicht bekannt.

**Terminierte Berichte werden nicht an alle Empfangenden gesendet**

*Berichte*

Wenn ein terminierter Bericht gesendet wird, wird er nicht an alle Benutzenden im Bereich „[!UICONTROL Senden an]“ übermittelt. Die Auswahl der übergangenen Benutzenden ist zufällig und kann bei jedem Versand des Berichts anders sein.

**[!UICONTROL Die Auswahl von Aufgaben kann nicht aufgehoben werden, wenn eine Vorlage angehängt wird]**

*Vorlagen*

Wenn ein(e) Benutzende(r) eine Vorlage anhängt und anpasst, wird er/sie aufgefordert, die Auswahl der Aufgaben aufzuheben, die nicht einbezogen werden sollen. Keine der Aufgaben wird jedoch als ausgewählt angezeigt und der/die Benutzende kann die Auswahl nicht aufheben.

**Felder vom Typ „Gebietsschema“ haben jetzt spezifischere Bezeichnungen**

*Terminologie*

Um die Funktion der Felder unter „[!UICONTROL Gebietsschema]“ zu verdeutlichen, wurden ihre Titel überarbeitet.

* Das Feld „[!UICONTROL Gebietsschema]“ im Benutzerprofil heißt jetzt „[!UICONTROL E-Mail-Gebietsschema]“
* Das Feld „[!UICONTROL Gebietsschema]“ im Bereich [!UICONTROL Setup] > [!UICONTROL System] > [!UICONTROL Kundeninformationen] heißt jetzt „[!UICONTROL Standard-E-Mail-Gebietsschema]“

Die Funktionalität dieser Felder hat sich nicht geändert.

**Probleme beim Erstellen von Arbeitszeittabellen**

*Arbeitszeit- tabellen*

Die folgenden Probleme wurden bei der Erstellung von Arbeitszeittabellen gemeldet:

* Wenn ein(e) Benutzende(r) versucht, eine Arbeitszeittabelle für eine Rolle zu erstellen, wird die Arbeitszeittabelle nicht erstellt und der folgende Fehler angezeigt: „[!UICONTROL Benutzer mit Primärschlüsselwerten ‚XXXXXXXXXXX‘ nicht gefunden].“
* Wenn ein(e) Benutzende(r) versucht, eine Arbeitszeittabelle für ein Team zu erstellen, wird das Feld [!UICONTROL mit automatischer Textvervollständigung] nicht mit Teams befüllt und die Schaltfläche [!UICONTROL Arbeitszeittabelle erstellen] ist deaktiviert.


**Manche Bereiche von [!DNL Workfront Proof] werden nicht aktualisiert, wenn ein Korrekturabzug erstellt, verschoben oder archiviert wird**

*[!DNL Workfront]Korrekturabzug*

Beim Korrekturabzug treten derzeit Indexierungsverzögerungen auf. Dies kann sich auf das Benutzererlebnis auswirken, beispielsweise:

* In Dashboards wird nicht die richtige Anzahl von Korrekturabzügen angezeigt
* Ordner werden beim Erstellen oder Verschieben eines Korrekturabzugs nicht aktualisiert
* Archivierte Korrekturabzüge bleiben auf der Liste der aktiven Korrekturabzüge.

+++

+++**Wartungs-Update (Hotfix) vom 26. Juli 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben.

Alle Funktionen von [!DNL Workfront Classic] wurden am 14. Juli 2022 entfernt.

**Die auf der Arbeitszeittabelle angezeigten Stunden unterscheiden sich von denen auf der Arbeitszeittabellenliste**

*Arbeitszeit- tabellen*

Wenn ein(e) Benutzende(r) eine Arbeitszeittabelle öffnet, unterscheiden sich die angezeigten Stunden von denen, die in der entsprechenden Arbeitszeittabellenliste anzeigt werden.


**Wenn eine Anfrage mithilfe einer Vorlage in ein Projekt konvertiert wird, wird eine Gruppe in der Anfragewarteschlange anstelle einer Gruppe in der Vorlage angezeigt**

*Anforde- rungen*

Wenn ein(e) Benutzende(r) eine Anfrage mithilfe einer Vorlage in ein Projekt konvertiert, wird das neu erstellte Projekt der in der Anfragewarteschlange befindlichen Gruppe zugeordnet und nicht der Gruppe, die in der Vorlage zugewiesen wird. Dies ist auch dann der Fall, wenn bei der Erstellung des Projekts die mit der Vorlage verknüpfte Gruppe im Feld [!UICONTROL Gruppe] angezeigt wird.

+++

+++**Wartungs-Update vom 21. Juli 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben.

Alle Funktionen von [!DNL Workfront Classic] wurden am 14. Juli 2022 entfernt.

**Der mit einer Genehmigung verknüpfte Ablehnungsstatus berücksichtigt den Genehmigungs-Workflow**

**HINWEIS: Diese Funktion wurde am 22. Juli 2022 veröffentlicht.**

*Genehmigungen*

Wenn Sie einen mit einem Genehmigungsprozess verknüpften Status als Ablehnungsstatus für einen Genehmigungspfad auswählen, wechselt das abgelehnte Objekt in den ausgewählten Status und erhält die Kennzeichnung „[!UICONTROL Genehmigung ausstehend]“. Wenn Sie beispielsweise für den Ablehnungsstatus [!UICONTROL Halten] auswählen und der [!UICONTROL Halten]-Status mit einem Genehmigungsprozess verknüpft ist, wird das abgelehnte Objekt in den Status „[!UICONTROL Wird gehalten – Genehmigung ausstehend]“ versetzt, was eine Genehmigung erfordert.

Vor diesem Update umging das Objekt den Genehmigungsprozess für den Ablehnungsstatus und wurde in den Status [!UICONTROL Halten] versetzt.

**Konfigurieren einer benutzerdefinierten Hilfe-URL**

*[!UICONTROL Hauptmenü]*

Wenn Ihr Unternehmen über eine benutzerdefinierte interne Hilfeseite verfügt, können Sie im [!UICONTROL Hauptmenü] das [!UICONTROL Hilfe]-Symbol so konfigurieren, dass es auf diese Seite verweist. Dies ist nützlich, wenn die Hilfeseite Informationen darüber enthält, wie Ihr Unternehmen [!DNL Workfront] nutzt.
Diese benutzerdefinierte URL hat keine Auswirkungen auf den Haupt-Hilfe-Link im oberen Bereich von [!DNL Workfront] noch auf die kontextsensitiven Hilfelinks in [!DNL Workfront], über die Benutzende zur [!DNL Workfront]-Hilfeseite gelangen.

**Verstrichene Zeit kann nicht ausgewählt werden, wenn die [!UICONTROL Aufgabendauer]** inline bearbeitet wird

*Aufgaben*

Wenn ein(e) Benutzende(r) eine Aufgabenliste öffnet und versucht, die [!UICONTROL Aufgabendauer] zu bearbeiten, sind die folgenden Einheiten nicht verfügbar:

* [!UICONTROL Verstrichene Minuten]
* [!UICONTROL Verstrichene Stunden]
* [!UICONTROL Verstrichene Tage]
* [!UICONTROL Verstrichene Wochen]
* [!UICONTROL Verstrichene Monate]

Seite **[!UICONTROL Meine Aktualisierungen] ist leer**

*Updates*

Wenn ein(e) Benutzende(r) versucht, die Seite [!UICONTROL Meine Aktualisierungen] aufzurufen, wird die Seite nicht geladen. Der/die Benutzende kann nur die [!DNL Workfront]-Navigationskopfzeile sehen.

**Einstellung „[!UICONTROL Nur SAML 2.0-Authentifizierung zulassen]“ fehlt, wenn ein(e) Benutzende(r) kopiert wird**

*Benutzer*

Wenn ein(e) Gruppen-Administrator(in) eine(n) Benutzende(n) kopiert und die Option „[!UICONTROL Einladungs-E-Mail an diese Person senden]“ deaktiviert, wird das Kontrollkästchen „[!UICONTROL Nur SAML 2.0-Authentifizierung zulassen]“ nicht wie erwartet angezeigt. Dies kann auch dann vorkommen, wenn alle Zugriffs- und Berechtigungsanforderungen für diese Aktion erfüllt sind.

+++

+++**Wartungs-Update vom 14. Juli 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben.

Alle Funktionen von [!DNL Workfront Classic] wurden am 14. Juli 2022 entfernt.

**Fehler beim Zurücksetzen des Passworts**

*Anmeldung*

Wenn ein(e) Benutzende(r) versucht, sein/ihr Passwort zurückzusetzen, gelingt dies nicht und eine Meldung informiert darüber, dass er/sie keinen Zugriff hat. Der/die Benutzende kann sich nicht bei Workfront anmelden.

**Es kann kein weiterer Zugriff auf einen Bericht angefordert werden**

*Berichte*

Wenn ein(e) Benutzende(r) mit eingeschränktem Zugriff auf einen Bericht versucht, mehr Zugriffsberechtigungen anzufordern, ist die entsprechende Option nicht im Menü [!UICONTROL Berichtsaktionen] verfügbar.

**Bestätigungsnachricht beim Löschen eines Anfrageentwurfs wurde aktualisiert**

*Anforde- rungen*

Wenn Sie eine entworfene Anfrage verwerfen, wird in der Bestätigungsmeldung nach dem Klicken auf „[!UICONTROL Entwurf verwerfen]“ Folgendes angezeigt:

* [!UICONTROL Entwurf wurde verworfen] (Dies ist eine Benachrichtigung, die Sie darüber informiert, dass Ihr Entwurf verworfen wurde)
* [!UICONTROL Rückgängig] (Dies ist ein Link, auf den Sie klicken können, um das Löschen des Entwurfs rückgängig zu machen. Dadurch wird der Entwurf beibehalten und nicht gelöscht.)

Vor dieser Änderung waren folgende Optionen verfügbar:

* [!UICONTROL Entwurf wird verworfen]
* [!UICONTROL Abbrechen]

**Datumswerte für Tagebucheintragsfelder sind falsch, wenn über die API zugegriffen wird**

*Updates*

Wenn ein(e) Benutzende(r) ein Datum für ein Objekt ändert und dann über die API auf den Tagebucheintrag zugegriffen wird, in dem diese Datumsänderung dargestellt wird, sind die Datumswerte für [!UICONTROL oldDateVal] und [!UICONTROL newDateVal], die von der API zurückgegeben werden, falsch.

**Fehler beim Versuch, einen Kommentar rückgängig zu machen**

*Updates*

Wenn ein(e) Benutzende(r) versucht, einen Kommentar rückgängig zu machen, gelingt dies nicht und die folgende Fehlermeldung wird angezeigt:

[!UICONTROL Fehler 403: Sie verfügen nicht über ausreichende Zugriffsberechtigungen, um die Anmerkung unter /attask/api-internal/NOTE zu löschen]

**Neue Begrenzung der Zeichenanzahl in einer Aktualisierung in der Vorschau**

*Updates*

Um die Leistung des Bereichs [!UICONTROL Aktualisierungen] zu verbessern, haben wir eine neue Begrenzung für die Anzahl der Zeichen eingeführt, die Sie bei einer Aktualisierung oder einer Antwort auf eine vorhandene Aktualisierung eingeben können. Die neue Beschränkung beträgt 15.000 Zeichen. Durch dieses Update wurde die zulässige Zeichenanzahl bei Verwendung der API nicht geändert. Die API-Zeichenbeschränkung für Aktualisierungen beträgt 4.000.

**Fehler beim Hochladen eines Anhangs über die [!DNL Workfront] für Outlook-Integration**

*Workfront-Integrationen*

Wenn ein(e) Benutzende(r) versucht, eine Anlage über die [!DNL Workfront for Outlook]-Integration hochzuladen, gelingt dies nicht und die folgende Nachricht wird angezeigt:

[!UICONTROL Einige Anlagen wurden nicht hochgeladen. Grund: Beim Hochladen von Anhängen ist etwas schiefgelaufen.]

**Update für die E-Mail-Benachrichtigung für den Korrekturabzug**

*[!DNL Workfront]Korrekturabzug*

Anfang dieses Monats haben wir im Zuge eines Patches für die [!DNL Workfront]-Produktionsumgebung einige Fehlerbehebungen im Benachrichtigungssystem für Korrekturabzug-E-Mails durchgeführt. Diese Änderung wurde nicht im Wartungs-Update zum Zeitpunkt seiner Veröffentlichung mitgeteilt. Wir haben die folgenden Informationen zum [Wartungs-Update vom 2. Juni 2022](#maintenance-update-on-june-2-2022) hinzugefügt:

Infolge dieser Fehlerkorrekturen hat sich die E-Mail-Adresse geändert, die zum Senden von Korrekturabzugs-Benachrichtigungen verwendet wird.

Zuvor enthielten Korrekturabzugs-E-Mail-Adressen die Subdomain Ihres Unternehmens. Beispiel: notifications@[Unternehmensdomain].my.workfront.com

Jetzt enthalten die Korrekturabzugs-E-Mail-Adressen keine Unternehmens-Subdomain mehr. Alle E-Mail-Benachrichtigungen zu Korrekturabzügen werden von der folgenden Adresse gesendet: notification@my.workfront.com

Daher empfehlen wir, die folgenden Aktionen durchzuführen, falls Sie dies noch nicht getan haben:

* Aktualisieren Sie Ihre Spam-Filter, um E-Mails von notification@my.workfront.com zuzulassen.
* Aktualisieren Sie Ihre Zulassungslisten, um E-Mails von notification@my.workfront.com zuzulassen.

**Benutzeroptionen können nach der erstmaligen Konfiguration in Workflow-Vorlagen nicht mehr geändert werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) eine(n) andere(n) Benutzende(n) zu einer Workflow-Vorlage hinzufügt, können Optionen konfiguriert werden. Nach Abschluss der erstmaligen Konfiguration kann der/die Benutzende jedoch Folgendes nicht mehr ändern:

* Die Funktion zum „[!UICONTROL Auflösen von Kommentaren und Anwenden von Aktionen]“
* Die Funktion zum „[!UICONTROL Freigeben des Korrekturabzugs durch Taggen]“
* Korrekturabzugs-Rolle ([!UICONTROL Prüfende Person], [!UICONTROL genehmigende Person] usw.)

Der Filter **„[!UICONTROL Die Arbeitselemente dieses Projekts]“ wurde im Projekt-[!UICONTROL Workload Balancer]** wiederhergestellt

*[!UICONTROL Lastenausgleich]*

Der Filter „Arbeitselemente dieses Projekts“ ist wieder im Bereich [!UICONTROL Zugeordnet] verfügbar, wenn Sie über ein Projekt auf den [!UICONTROL Workload Balancer] zugreifen.

Dieser Filter befindet sich jetzt im [!UICONTROL Workload Balancer] eines Projekts in den Filtern für den Bereich [!UICONTROL Zugewiesene Arbeit] unter dem Abschnitt „[!UICONTROL Vorgeschlagen]“.

+++

## Updates im Juni 2022

+++**Wartungs-Update vom 30. Juni 2022**

**Anzeigen des [!UICONTROL Workload Balancer] für eine Woche**

*[!UICONTROL Lastenausgleich]*

Aufgrund des Feedbacks, das wir von vielen Kunden erhalten haben, haben wir nun eine Option hinzugefügt, durch die der [!UICONTROL Workload Balancer] eine Woche lang angezeigt werden kann. Vor diesem Update konnten Sie den [!UICONTROL Workload Balancer] 4, 6 und 12 Wochen lang anzeigen. Mit diesem Update haben wir auch die 12-Wochen-Option in 3 Monate geändert.

**Das Bedienfeld „Delegieren“ ist jetzt über den Workload Balancer verfügbar.**

*[!UICONTROL Lastenausgleich]*

HINWEIS: Dieses Update ist nur in der Vorschau-Umgebung verfügbar. Die mit diesem Update verknüpfte Funktionalität wird ab Version 22.3 in der Produktionsumgebung verfügbar sein.

Sie können jetzt die Beauftragten einer Aufgabe oder eines Problems über den Workload Balancer aufrufen. Beim Zuweisen einer Aufgabe oder eines Problems über den Workload Balancer können Sie eine Liste der Zuweisungen sowie eine Liste der Beauftragten für die Aufgabe oder das Problem aufrufen, sofern diese gerade zugewiesen sind.

**Endpunktinformationen in API Explorer können nicht geöffnet werden**

*API*

Wenn ein(e) Benutzende(r) [!DNL API Explorer] aufruft und auf einen Endpunkt klickt, werden die Endpunktinformationen nicht angezeigt.

**Probleme mit der Schaltfläche [!UICONTROL Details] bei Verwendung des [!UICONTROL Startseiten-Kalenders]**

*Startseite*

Wenn ein(e) Benutzende(r) den [!UICONTROL Startseiten-Kalender] verwendet und auf eine Aufgabe klickt, kann eines der folgenden Szenarien eintreten:

* Die Schaltfläche [!UICONTROL Details] wird kurz angezeigt und verschwindet wieder. Der/die Benutzende kann nicht auf die Details zugreifen.
* Die Schaltfläche [!UICONTROL Details] wird nicht angezeigt. Der/die Benutzende kann nicht auf die Details zugreifen.
* Die Schaltfläche [!UICONTROL Details] wird angezeigt, befindet sich jedoch nicht an der richtigen Stelle. Der/die Benutzende kann auf die Schaltfläche klicken, um auf die Details zuzugreifen.

+++

+++**Wartungs-Update (Hotfix) vom 24. Juni 2022**

**Datumsauswahl wird beim Bearbeiten eines benutzerdefinierten Formulars nicht geschlossen**

*Benutzerdefinierte Formulare*

Wenn ein(e) Benutzende(r) ein benutzerdefiniertes Formular bearbeitet und versucht, ein Datum zu ändern, wird die Datumsauswahl bei Auswahl des Datums nicht geschlossen. Der/die Benutzende kann die Datumsauswahl nicht durch Speichern, Abbrechen oder Anklicken einer anderen Stelle schließen.

Dies wurde in den folgenden Bereichen gemeldet:

* Bereich [!UICONTROL Aktualisierungen]
* [!UICONTROL Startseite]

**Benutzende können sich nicht in einen anderen Korrekturabzugsschritt verschieben**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) den [!UICONTROL Korrekturabzug-Workflow] eines Korrekturabzugs anzeigt und versucht, sich selbst in einen anderen Korrekturabzugsschritt zu ziehen, springt der Name des/r Benutzenden an die ursprüngliche Stelle zurück und wird nicht zum gewünschten Schritt hinzugefügt.

+++

+++**Wartungs-Update vom 23. Juni 2022**

**[!UICONTROL Neue Anfrage kann nicht über das Dashboard hinzugefügt werden]**

*Dashboards*

Wenn ein(e) Benutzende(r) ein Dashboard zu einem Projekt öffnet und versucht, eine neue Anfrage hinzuzufügen, indem er/sie auf [!UICONTROL +Neue Anfrage] klickt, reagiert die Schaltfläche nicht und der/die Benutzende kann keine neue Anfrage hinzufügen.

**Fehler beim Anzeigen von Elementen in der Startseiten-Arbeitsliste**

*[!UICONTROL Startseite]*

Wenn ein(e) Benutzende(r) seine/ihre [!UICONTROL Startseiten-Arbeitsliste] öffnet und auf ein Element im Bereich [!UICONTROL Von mir gesendete Genehmigungen] klickt, wird der folgende Fehler angezeigt:

„[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]“

Wenn der/die Benutzende die Seite aktualisiert und dann auf ein Element in der [!UICONTROL Arbeitsliste] klickt, wird der Fehler angezeigt. Das Problem betrifft nicht mehr nur Elemente im Abschnitt [!UICONTROL Gesendete Genehmigungen].

**Benutzerdefinierter Abschnitt eines Objekts enthält Ergebnisse, die nicht in diesem Objekt enthalten sind**

*Objekte*

Wenn ein(e) Benutzende(r) einen [!UICONTROL benutzerdefinierten] Abschnitt eines Objekts öffnet, zeigt der benutzerdefinierte Abschnitt Elemente an, die nicht zu diesem Objekt gehören. Dies wurde gemeldet, wenn der benutzerdefinierte Abschnitt direkt zum Objekt oder über eine Layout-Vorlage hinzugefügt wird.

**Aufgaben werden in ein falsches Projekt verschoben**

*Aufgaben*

Wenn ein(e) Benutzende(r) Aufgaben von Projekt A zu Projekt B verschiebt und dann weitere Aufgaben von Projekt A zu Projekt C verschiebt, werden die ursprünglich in Projekt B verschoben Aufgaben in Projekt C angezeigt.

**Einige Schaltflächen/Symbole funktionieren nicht beim Zugriff auf den [!UICONTROL Workload Balancer] über einen freigegebenen Link oder ein freigegebenes Dashboard**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) auf den [!UICONTROL Workload Balancer] über einen freigegebenen Link oder einen Link in einem Dashboard zugreift und versucht, die Elemente oben im Bildschirm zu verwenden, funktionieren sie nicht. Dies wurde für die folgenden Elemente gemeldet:

* [!UICONTROL Heute]
* Vorwärts- und Rückwärtspfeile
* [!UICONTROL Wochen]
* Kalendersymbol (Datumsauswahl)

+++

+++**[!DNL Workfront]Wartungs-Update von Workfront Scenario Planner vom 23. Juni 2022**

**Benutzende mit der Berechtigung [!UICONTROL Verwalten] für einen Plan können ihn für andere freigeben**

Benutzende mit der Genehmigung [!UICONTROL Verwalten] für einen Plan im [!DNL Scenario Planner] können den Plan jetzt für andere Benutzende freigeben. Vor diesem Update konnte nur der/die Erstellende des Plans diesen für andere freigeben.

+++

+++**Wartungs-Update vom 16. Juni 2022**

**Gruppenadministrator bzw. -administratorin kann keine Mitglieder zu Gruppe hinzufügen**

*Gruppen*

Wenn ein Gruppenadministrator bzw. eine Gruppenadministratorin versucht, eine(n) Benutzende(n) zu einer Gruppe hinzuzufügen, wird das Dropdown-Menü zur Auswahl des/der Benutzenden nicht vorab befüllt. Der Gruppenadministrator bzw. die Gruppenadministratorin kann keine Benutzenden auswählen und daher keine Benutzenden zur Gruppe hinzufügen.

**Benutzerdefinierte Quartale werden beim Festlegen eines Filters nicht angezeigt**

*Filter*

Wenn ein(e) Benutzende(r) einen Filter erstellt und eine Filterung nach einem Datumsfeld durchführt, enthält die Dropdown-Liste der verfügbaren Operatoren für das Datumsfeld keine kürzlich hinzugefügten benutzerdefinierten Quartale.

**„Hoppla“-Fehler beim Konvertieren eines Problems in ein Projekt über eine Vorlage**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein Problem über eine Vorlage in ein Projekt zu konvertieren, und das Problem ein benutzerdefiniertes Formular hat, das einen Abschnitt nur für Administratoren bzw. Administratorinnen enthält, wird das Problem nicht konvertiert und der folgende Fehler erscheint:

„[!UICONTROL Versuchen Sie es erneut. Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

**Anfragen werden gesendet, ohne dass die erforderlichen Felder ausgefüllt sind**

*Anforde- rungen*

Wenn ein(e) Benutzende(r) eine Anfrage erstellt und die erforderlichen Felder nicht ausfüllt und dann die Anfrage sendet, wird die Anfrage ohne Angaben in den Pflichtfeldern gesendet. Erwartet wird, dass die Anfrage nicht gesendet wird und der/die Benutzende benachrichtigt wird, dass er/sie die Pflichtfelder ausfüllen muss, bevor er/sie die Anfrage sendet.

**Neue benutzerdefinierte Quartale werden anscheinend nicht gespeichert**

*Setup*

Wenn ein(e) Benutzende(r) ein neues benutzerdefiniertes Quartal im Bereich „Projekte“ unter Setup hinzufügt und auf [!UICONTROL Speichern] klickt, gibt es keinen visuellen Hinweis auf die Speicherung. Dem/der Benutzenden wird keine Erfolgsmeldung angezeigt und die Schaltfläche [!UICONTROL Speichern] in noch vorhanden und aktiv. Wenn der/die Benutzende die Seite jedoch aktualisiert, kann er/sie sehen, dass die neuen Quartale in der Liste der benutzerdefinierten Quartale angezeigt werden.

Wenn der/die Benutzende ein neues Quartal hinzufügt, auf [!UICONTROL Speichern] klickt, keine Speicherbestätigung erhält, ein weiteres Quartal hinzufügt, ohne die Seite zu aktualisieren, und erneut auf [!UICONTROL Speichern] klickt, wird das zweite hinzugefügte Quartal möglicherweise nicht gespeichert.

**[!UICONTROL Team-Arbeitsanfragen]-Seite ist leer**

*Teams*

HINWEIS: Dieses Problem tritt nur in der Vorschau-Umgebung auf.

Wenn ein(e) Benutzende(r) den Abschnitt [!UICONTROL Arbeitsanfragen] auf einer Team-Seite öffnet, ist die Seite leer. Der/die Benutzende kann die obere Navigationsleiste sehen, jedoch keinen Seiteninhalt.

+++

+++**Wartungs-Update vom 9. Juni 2022**

**Objekte, die in den Voreinstellungen von [!UICONTROL Portfolio-Optimizer] gefiltert werden sollen, können nicht ausgewählt werden**

*Portfolios*

Wenn sich ein(e) Benutzende(r) im [!UICONTROL Portfolio-Optimizer] befindet und die Registerkarte [!UICONTROL Projektfilter] im Bereich [!UICONTROL Voreinstellungen] öffnet, fehlen die Kontrollkästchen neben den Objekten. Der/die Benutzende kann die Kontrollkästchen nicht aktivieren oder deaktivieren und daher keine zu filternden Objekte auswählen.

**[!UICONTROL Geplantes Startdatum] oder [!UICONTROL Geplantes Abschlussdatum] kann nicht geändert werden, wenn „[!UICONTROL Zeitplan ab]“ nicht markiert ist**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, das [!UICONTROL geplante Startdatum] oder das [!UICONTROL geplante Abschlussdatum] eines Projekts zu bearbeiten und die Option „[!UICONTROL Zeitplan ab]“ nicht aktiviert ist, sind die Bereiche [!UICONTROL Geplantes Startdatum] und [!UICONTROL Geplantes Abschlussdatum] deaktiviert und der/die Benutzende diese Daten nicht bearbeiten.

**Zugriffsebene von Benutzenden kann nicht bearbeitet werden**

*Benutzer*

Wenn ein(e) Benutzende(r) mit Planerzugriff, der/die auch Administratorrechte für Gruppenbenutzende besitzt, versucht, Benutzende in der Gruppe zu bearbeiten, die von ihm/ihr administriert wird, ist das Feld [!UICONTROL Zugriffsebene] deaktiviert und der/die Benutzende kann die Zugriffsebene nicht bearbeiten.

+++

+++**[!DNL Workfront Scenario Planner]Wartungs-Update vom 9. Juni 2022**

**Anpassbares linkes Bedienfeld im [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Sie können jetzt im [!DNL Scenario Planner] die Größe des linken Bedienfelds in einem Plan ändern. Dadurch können längere Namen vollständig angezeigt werden. Vor diesem Update wurden längere Namen abgeschnitten.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update vom 9. Juni 2022**

**Daten aus benutzerdefinierten Formularen sind nicht in [!DNL Workfront Fusion] [!DNL Workfront]-Modulen verfügbar**

*[!DNL Workfront Fusion]*

Wenn ein(e) Benutzende(r) ein [!DNL Workfront]-Modul in [!DNL Workfront Fusion] konfiguriert und versucht, Ausgaben für das Modul auszuwählen, sind die Felder von benutzerdefinierten Formularen nicht sichtbar. Dies tritt auf, wenn ein benutzerdefiniertes Formular für einen Typ eines [!DNL Workfront]-Objekts erstellt wurde und anschließend ein anderer Typ hinzugefügt wurde. In [!DNL Workfront Fusion] werden nur Felder von benutzerdefinierten Formularen angezeigt, die ursprünglich für den ausgewählten Objekttyp erstellt wurden.

**Es kann nicht gescrollt werden, um alle Szenario-Ausführungen anzuzeigen**

*[!DNL Workfront Fusion]*

Wenn ein(e) Benutzende(r) den Ausführungsverlauf eines Szenarios anzeigt und versucht, nach unten zu scrollen, um weitere Ausführungen anzuzeigen, werden keine Ausführungen mehr geladen und der/die Benutzende kann sie nicht anzeigen. Zusätzlich kann der/die Benutzende auch nicht mehr zu den letzten Ausführungen hinaufscrollen.

+++

+++**Wartungs-Update vom 2. Juni 2022**

**[!UICONTROL Portfolio-Optimizer] zeigt den Score 0 an, wenn eine andere Sprache als Englisch verwendet wird**

*Portfolios*

Wenn ein(e) Benutzende(r) [!DNL Workfront] in einer anderen Sprache als Englisch anzeigt und den [!UICONTROL Portfolio-Optimizer] öffnet, wird der Score als 0 dargestellt. Dies kann auch auftreten, wenn der Business-Case noch nicht abgeschlossen ist.

**Berechnete Feldwerte sind bei der Erstellung eines Projekts aus einer Vorlage falsch**

*Projekte*

Wenn ein(e) Benutzende(r) ein Projekt aus einer Vorlage erstellt, die berechnete Felder enthält, sind die im neuen Projekt angezeigten Feldwerte falsch.

**[!UICONTROL Bedingungen] im Abschnitt [!UICONTROL Projektvoreinstellungen] von [!UICONTROL Setup]** können nicht bearbeitet werden

*[!UICONTROL Einrichtung]*

Wenn ein(e) Benutzende(r) versucht, [!UICONTROL Bedingungen] im Abschnitt [!UICONTROL Projektvoreinstellungen] von [!UICONTROL Setup] zu bearbeiten, ist die Seite leer.

**Neue Begrenzung der Zeichenanzahl in einer Aktualisierung in der Vorschau**

*[!UICONTROL Lastenausgleich]*

>[!NOTE]
>
>Dieses Update gilt nur für die Vorschau-Umgebung.

Um die Leistung des Bereichs „Aktualisierungen“ zu verbessern, haben wir eine neue Begrenzung für die Anzahl der Zeichen eingeführt, die Sie bei einer Aktualisierung oder einer Antwort auf eine vorhandene Aktualisierung eingeben können. Die neue Beschränkung beträgt 15.000 Zeichen. Durch dieses Update wurde die zulässige Zeichenanzahl bei Verwendung der API nicht geändert. Die API-Zeichenbeschränkung für Aktualisierungen beträgt 4.000. Aktualisierungen
Unterstützung für benutzerdefinierte Felder mit automatischer Textvervollständigung in den Workload Balancer-Filtern

Wir unterstützen im Workload Balancer nun Filter, die auf benutzerdefinierten Feldern [!UICONTROL mit automatischer Textvervollständigung] basieren. Vor diesem Patch war das Filtern nach diesem Typ von benutzerdefinierten Feldern im Workload Balancer nicht möglich.

**Berechtigungen für Benutzerrollen können nicht bearbeitet werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) versucht, die Rollenberechtigungen „[!UICONTROL Kommentare auflösen und Aktionen anwenden]“ oder „[!UICONTROL Korrekturabzug durch Tagging freigeben]“ in [!DNL Workfront Proof] zu bearbeiten, werden die Änderungen nicht gespeichert. Der/die Benutzende erhält eine Benachrichtigung, dass die Vorlage aktualisiert wurde. Wenn der/die Benutzende die Rollenberechtigungen jedoch erneut öffnet, kann er/sie sehen, dass die Änderungen nicht gespeichert wurden.

+++


## Updates im Mai 2022

+++**Wartungs-Update vom 26. Mai 2022**

Diese Probleme wurden in der neuen [!DNL Workfront]-Version behoben. [!DNL Adobe Workfront Classic] wird nicht mehr unterstützt.

Alle Funktionen von [!DNL Workfront Classic] werden im Juli 2022 entfernt. Bitte wechseln Sie so bald wie möglich zur neuen Version.

**Aktualisierte Breadcrumb-Trennzeichen**

*[!DNL Workfront]*

HINWEIS: Dieses Update wurde am 24. Mai 2022 veröffentlicht.

Wir haben die Breadcrumb-Trennzeichen in allen Bereichen aktualisiert, in denen Breadcrumbs verfügbar sind. Jetzt werden die Objekte in den Breadcrumbs durch senkrechte Striche (|) getrennt. Vor dieser Aktualisierung wurden sie durch Schrägstriche (/) getrennt.

**Benutzerdefinierte Formulare mit Abschnittsumbrüchen können nicht bearbeitet werden**

*Benutzerdefinierte Formulare*

Wenn ein(e) Benutzende(r) versucht, ein benutzerdefiniertes Formular mit einem Abschnittsumbruch zu bearbeiten, kann er/sie das Formular nicht bearbeiten und die folgende Meldung erscheint:

[!UICONTROL Der angegebene Schutz für den Abschnittsumbruch kann nicht auf alle Objekttypen angewendet werden]

**Probleme beim Drucken von Dashboards im PDF-Format**

*Dashboards*

Beim Drucken eines Dashboards im PDF-Format wurden die folgenden Probleme gemeldet: Im PDF-Format wird nicht jede Zeile des Berichts ausgedruckt. Wenn Zeilen fehlen, wird nur Leerraum angezeigt.
Die PDF-Datei enthält Leerzeichen zwischen den Spaltenüberschriften und der ersten Zeile des Berichts.

**[!DNL Portfolio Optimizer] zeigt den Score 0 an, wenn eine andere Sprache als Englisch verwendet wird**

*Portfolios*

Wenn ein(e) Benutzende(r) [!DNL Workfront] in einer anderen Sprache als Englisch anzeigt und den [!UICONTROL Portfolio-Optimizer] öffnet, wird der Score als 0 dargestellt. Dies kann auch auftreten, wenn der Business-Case noch nicht abgeschlossen ist.

**Beim Bearbeiten einer Vorlage werden einige benutzerdefinierte Formulare nicht angezeigt**

*Vorlagen*

Wenn ein(e) Benutzende(r) versucht, die an eine Vorlage angehängten benutzerdefinierten Formulare zu bearbeiten, indem er/sie in der Kopfzeile der Vorlage auf [!UICONTROL Bearbeiten] klickt, wird im Feld [!UICONTROL Vorlage bearbeiten] nur eines der benutzerdefinierten Formulare angezeigt, die an die Vorlage angehängt sind.

**Freigegebener Link zum Workload Balancer zeigt zugewiesene Arbeit falsch an**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) den [!UICONTROL Workload Balancer] über einen freigegebenen Link öffnet, wird im [!DNL Workload Balancer] [!UICONTROL zugewiesene Arbeit] im Abschnitt [!UICONTROL Nicht zugewiesene Arbeit] angezeigt. [!UICONTROL Zugewiesene Arbeit] hat keinen separaten Abschnitt. Wenn der/die Benutzende den [!UICONTROL Workload Balancer] ohne den freigegebenen Link öffnet, wird die [!UICONTROL zugewiesene Arbeit] korrekt angezeigt.

+++

+++**Wartungs-Update vom 19. Mai 2022**

**Aus einer [!DNL PowerPoint]**-Datei kann kein Korrekturabzug erstellt werden

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) versucht, einen Korrekturabzug aus einer [!DNL PowerPoint]-Datei zu erstellen, die ein Diagramm enthält, schlägt die Erstellung des Korrekturabzugs fehl.

**Aus einem [!UICONTROL Word]-Dokument kann kein Korrekturabzug erstellt werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) versucht, einen Korrekturabzug aus einem [!DNL Word]-Dokument zu erstellen, das ein Diagramm enthält, schlägt die Erstellung des Korrekturabzugs fehl.

**Benutzerdefinierte Nachricht kann nicht hinzugefügt werden, wenn ein Korrekturabzug freigegeben wird**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einen Korrekturabzug aufruft, den Abschnitt [!UICONTROL Korrekturabzug freigeben] öffnet und die Schaltfläche [!UICONTROL Benutzerdefinierte Nachricht hinzufügen] wählt, kann der/die Benutzende nichts in das sich öffnende Textfeld eingeben. Wenn der/die Benutzende versucht, Text in dieses Feld einzugeben, wird das Feld sofort ausgeblendet.

**Korrekturabzug kann nicht geschlossen werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einen Korrekturabzug aufruft und versucht, ihn zu schließen, fehlt das X zum Schließen des Korrekturabzugs in der oberen rechten Ecke des Korrekturabzugs.

**Gruppenadministrator bzw. -administratorin kann nicht hinzugefügt oder entfernt werden**

*Gruppen*

Wenn ein(e) Benutzende(r) die Seite [!UICONTROL Gruppe] aufruft und versucht, einen Gruppenadministrator bzw. eine Gruppenadministratorin über den Abschnitt [!UICONTROL Gruppenadministratoren] in der Kopfzeile hinzuzufügen oder zu entfernen, werden die Änderungen nicht gespeichert und die folgende Fehlermeldung wird angezeigt:

[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]

**Horizontaler Bildlaufbalken blockiert Element am Ende der Liste**

*Projekte*

Wenn ein(e) Benutzende(r) eine Liste mithilfe einer Ansicht anzeigt, die sich über die Bildschirmseite hinaus erstreckt, blockiert die horizontale Bildlaufleiste die Anzeige des letzten Elements auf der Liste für den/die Benutzende(n).

**„[!UICONTROL Unerwarteter Fehler]“ beim Konvertieren eines Problems in ein Projekt mithilfe einer Vorlage**

*Listen*

Wenn ein(e) Benutzende(r) versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, wird das Problem nicht konvertiert, und der/die Benutzende sieht die folgende Meldung:

[!UICONTROL Unerwarteter Fehler]

**Das Feld [!UICONTROL Status] in einer Arbeitszeittabellen-Ansicht ist jetzt schreibgeschützt**

*Arbeitszeit- tabellen*

Wir haben das Feld [!UICONTROL Status] in der Arbeitszeittabellen-Ansicht geändert, sodass es jetzt schreibgeschützt ist. Vor dieser Änderung konnten Benutzende den Status einer Arbeitszeittabelle inline bearbeiten, wodurch sie die Entscheidung der Arbeitszeittabellen-Genehmiger überschreiben konnten.

+++

+++**Wartungs-Update vom 12. Mai 2022**

**[!UICONTROL Speichern]-Schaltfläche lädt beim Bearbeiten eines Projekts unentwegt**

*Projekte*

Wenn ein(e) Benutzende(r) ein Projekt bearbeitet und versucht, es zu speichern, wird in der Schaltfläche [!UICONTROL Speichern] „[!UICONTROL Wird geladen]“ angezeigt. Wenn der/die Benutzende auf diese Schaltfläche klickt, um die Änderungen am Projekt zu speichern, reagiert die Schaltfläche nicht und die Änderungen werden nicht gespeichert.

**Feldbeschriftungen werden beim Öffnen eines Objekts in der [!UICONTROL Startseite]** nicht angezeigt

*Startseite*

Wenn ein(e) Benutzende(r) ein Objekt in der [!UICONTROL Startseiten-Arbeitsliste] auswählt, sind in Bereich rechts neben der [!UICONTROL Startseiten-Arbeitsliste], wo sich das Objekt befindet, keine Feldtitel vorhanden. Die Feldwerte dagegen sind vorhanden.

**Fokus des Schnellfilters wechselt nicht automatisch zur Suchleiste**

*Listen*

Wenn sich ein(e) Benutzende(r) in einer Liste befindet und auf die Lupe klickt, um schnell zu filtern, und dann mit der Eingabe von Text beginnt, wird der Text nicht angezeigt. Der Grund dafür ist, dass der Fokus auf dem Lupensymbol bleibt anstatt zur Suchleiste zu wechseln.

Durch Klicken auf die Suchleiste wird der Fokus übertragen und der/die Benutzende kann den Suchtext eingeben.

**Benutzende können Felder in einem Bericht nicht inline bearbeiten**

*Berichte*

Wenn ein(e) Benutzende(r) versucht, ein Feld in einem Bericht zu bearbeiten und dieses Feld aus einem benutzerdefinierten Formular abgerufen wird, kann er/sie das Feld nicht bearbeiten. Dies tritt auf, wenn das benutzerdefinierte Formular ursprünglich für einen anderen Objekttyp als das Objekt erstellt wurde, an das es angehängt ist.

**Titel und Schaltflächentext werden beim Erstellen eines Korrekturabzugs nicht angezeigt**

*[!DNL Workfront Proof]*

HINWEIS: Dieses Problem tritt nur in der Vorschau-Umgebung auf.

Wenn ein(e) Benutzende(r) versucht, einen Korrekturabzug zu erstellen, ist der Text für Optionen oder Schaltflächen nicht sichtbar. Daher weiß der/die Benutzende nicht, was die einzelnen Optionen oder Schaltflächen darstellen, und kann den Korrekturabzug nicht konfigurieren.

+++

+++**Wartungs-Update vom 5. Mai 2022**

**Neuer Rechnungs-Datensatz kann nicht hinzugefügt werden**

*Projekte*

Wenn sich ein(e) Benutzende(r) im Bereich [!UICONTROL Abrechnungs-Datensätze] eines Projekts befindet und die Ansicht [!UICONTROL Neuer Abrechnungs-Datensatz] geöffnet hat und versucht, einen neuen Abrechnungs-Datensatz hinzuzufügen, werden die Felder für den neuen Abrechnungs-Datensatz nicht angezeigt und der Abrechnungs-Datensatz kann nicht erstellt werden.

**Fehler bei der Massenzuweisung im [!UICONTROL Workload Balancer]**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) versucht, Zuweisungen im [!DNL Workload Balancer] eines Projekts durchzuführen, wird der/die Benutzende zu einer Seite mit der folgenden Meldung umgeleitet:

„[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]“

Der/die Benutzende kann diese Seite nicht verlassen, bis er/sie die Seite aktualisiert.

**Die Navigation zum Öffnen des Bedienfelds [!UICONTROL Zusammenfassung] für Aufgaben und Probleme im [!UICONTROL Workload Balancer]** wurde aktualisiert

*[!UICONTROL Lastenausgleich]*

Klicken kann einfach durch Klicken auf eine Aufgaben- oder eine Problemleiste im [!UICONTROL Workload Balancer] das Bedienfeld „Zusammenfassung“ geöffnet werden. Vor diesem Update mussten Sie auf das Symbol [!UICONTROL Zusammenfassung öffnen] in der Symbolleiste und dann auf die Aufgabe oder das Problem klicken. Dies war verwirrend und wurde nun korrigiert. Alternativ können Sie auf das Menü [!UICONTROL Mehr] neben dem Namen der Aufgabe oder des Problems und danach auf [!UICONTROL Zusammenfassung öffnen] klicken.

**Gruppen-Administrator bzw. -Administratorin kann keine Details zu Benutzenden in der Gruppe sehen**

*Benutzer*

Wenn ein(e) Benutzende(r), der/die einer Zugriffsebene zugewiesen ist, die die Zugriffseinstellung [!UICONTROL Benutzeradministration (Gruppenbenutzende)] enthält, versucht, Details eines/r Benutzenden in der Gruppe aufzurufen, erscheint der folgende Fehler:

„[!UICONTROL Versuchen Sie es erneut. Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

**Benutzerdefinierter Gruppenstatus kann nicht gelöscht werden**

*Gruppen*

Wenn ein(e) Benutzende(r) versucht, einen benutzerspezifischen Gruppenstatus aus der Seite [!UICONTROL Gruppe] zu löschen, wird eine leere Seite angezeigt und der Status wird nicht gelöscht.

**E-Mail-Warnhinweiseinstellungen im Bereich „Kontakte“ und in den Benutzerdetails stimmen nicht überein**

*[!DNL Workfront Proof]*

Die Einstellungen für den E-Mail-Warnhinweis im Bereich [!UICONTROL Kontakte] von [!DNL Workfront Proof] für einen Benutzer unterscheiden sich von der E-Mail-Warnhinweiseinstellung in den [!UICONTROL Benutzerdetails].

**Text-Tool kann nicht für einen Kommentar zu einem Korrekturabzug verwendet werden**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) einen Kommentar zu einem Korrekturabzug hinzufügt und versucht, das [!UICONTROL Text]-Tool zu öffnen, kann das Tool nicht geöffnet werden und die folgende Nachricht wird angezeigt:

„[!UICONTROL Textdaten für diese Seite werden noch heruntergeladen. Bitte warten Sie.]“

**Korrekturabzugs-E-Mails werden an die primäre E-Mail des Benutzenden gesendet**

*[!DNL Workfront Proof]*

Wir passen die Art und Weise an, wie Korrekturabzugs-E-Mail-Benachrichtigungen gesendet werden. Derzeit werden Benachrichtigungen an die primäre E-Mail-Adresse des/der Benutzenden gesendet und nicht an die vom System generierte Alias-E-Mail-Adresse.

Weitere Informationen dazu, warum das System Alias-E-Mail-Adressen generiert, finden Sie unter Benutzersynchronisierung zwischen Adobe [!DNL Workfront] und [!DNL Workfront Proof].

+++

## Updates im April 2022

+++**Wartungs-Update vom 28. April 2022**

**Scrollen zur Schaltfläche [!UICONTROL Speichern] beim Bearbeiten einer Arbeitszeittabelle nicht möglich**

*Arbeitszeit- tabellen*

Wenn ein(e) Benutzende(r) eine Arbeitszeittabelle bearbeitet, kann er/sie nicht weit genug scrollen, um die Schaltfläche [!UICONTROL Speichern] anzuzeigen und kann daher die Arbeitszeittabelle nicht bearbeiten.

**Elektronische Signatur überprüft jetzt die Federation ID**

*Korrekturabzüge*

Beim elektronischen Signieren eines Korrekturabzugs prüft das System jetzt die Federation ID, wenn Sie SSO in [!DNL Workfront Proof] zusätzlich zu Ihrer E-Mail in [!DNL Workfront] eingerichtet haben.

Zuvor hat das System nur Ihre E-Mail in Workfront überprüft.

+++

+++**Wartungs-Update (Hotfix) vom 25. April 2022**

**[!UICONTROL Workload Balancer] wird nicht geladen**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) versucht, den [!UICONTROL Workload Balancer] zu öffnen, wird die Kopfzeile und die linke Navigation geladen, aber der Inhalt des Workload-Balancer wird nicht geladen. Der/die Benutzende sieht blinkende graue Quadrate anstelle von Daten. Gelegentlich wird ein Teil des Inhalts geladen, aber der/die Benutzende sieht immer noch blinkende graue Quadrate, wo die fehlenden Daten wären.

+++

+++**Wartungs-Update vom 21. April 2022**

**Beim Hinzufügen einer Aufgabe springt die Seite nach unten**

*Aufgaben*

Wenn ein(e) Benutzende(r) eine Aufgabe unterhalb einer vorhandenen Aufgabe in einer Liste hinzufügt, wird die Seite in der Liste nach unten verschoben. Obwohl sich die neue Aufgabe an der richtigen Stelle befindet, muss der/die Benutzende nach oben scrollen, um sie zu finden.

**Benutzende, die zu einem Korrekturabzug hinzugefügt wurden, können nicht auf das Arbeitselement des Korrekturabzugs in [!DNL Workfront]** zugreifen

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) zu einem Schritt im Workflow eines Korrekturabzugs hinzugefügt wird, wird er/sie nicht zur Freigabe des Dokuments hinzugefügt und erhält keine Berechtigungen für das Arbeitselement des Korrekturabzugs in [!DNL Workfront]. Wenn der/die Benutzende in [!DNL Workfront] ist und versucht, das Arbeitselement zu öffnen, an das der Korrekturabzug angehängt ist, wird die folgende Meldung angezeigt:

„[!UICONTROL Sie verfügen nicht über die erforderliche Zugriffsberechtigung, um (dieses Objekt) anzuzeigen]“

Dieses Problem betrifft nur Korrekturabzüge, die bereits erstellt wurden und denen danach Benutzer hinzugefügt wurden. Das Hinzufügen von Benutzern zum Workflow vor der Erstellung eines Korrekturabzugs funktioniert ordnungsgemäß.

**Die E-Mail zum Zurücksetzen des Passworts kann in [!DNL Workfront]** nicht gesendet werden

*Benutzer*

Wenn ein(e) Benutzende(r) versucht, eine E-Mail zum Zurücksetzen des Passworts über eine Benutzerliste in [!DNL Workfront] zu senden, ist die Option zum Senden der E-Mail nicht verfügbar.

**Die Schaltfläche „[!UICONTROL Problem starten]“ wird anstelle von „[!UICONTROL Anfrage starten]“ angezeigt**

*Anforde- rungen*

Wenn ein(e) Benutzende(r) eine seinem/ihrem Team zugewiesene Anfrage aufruft, wird in der Kopfzeile die Schaltfläche „[!UICONTROL Problem starten]“ statt „[!UICONTROL Anfrage starten]“ angezeigt.

**„[!UICONTROL Kommentar rückgängig machen]“ entfernt getaggte Benutzende**

*Updates*

Wenn ein(e) Benutzende(r) eine(n) andere(n) Benutzende(n) in einem Kommentar taggt, den Kommentar postet und dann die Option „[!UICONTROL Kommentar rückgängig machen]“ auswählt, wird der Kommentar wie üblich in einem Aktualisierungsfeld angezeigt, aber der/die getaggte Benutzende ist nicht im Fenster [!UICONTROL Getaggte Benutzende] zu sehen.

**Bei Verwendung der [!UICONTROL Meilenstein]-Ansicht in einem Bericht kann nicht gescrollt werden**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht aufruft und die Ansicht [!UICONTROL Meilenstein] auswählt, wird auf der Seite die Meilensteinansicht angezeigt, der Bildlauf funktioniert aber nicht mehr. Außerdem kann der/die Benutzende keine Meilensteine anzeigen, die weiter unten auf der Seite stehen.

**Falsche Währung bei Anzeige eines Berichts im Dashboard**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht in einem Dashboard anzeigt, ist die im Bericht verwendete Währung falsch. Wenn der/die Benutzende den Bericht außerhalb des Dashboards anzeigt, ist die Währung korrekt.

**Abgeschlossener Filter zeigt kein abgeschlossenes Arbeitselement an**&#x200B;

*[!UICONTROL Startseite]*

Wenn ein(e) Benutzende(r) seine/ihre [!UICONTROL Homepage-Arbeitsliste] aufruft und der Filter [!UICONTROL Abgeschlossen] ausgewählt ist, werden abgeschlossene Arbeitselemente nicht in der Liste angezeigt. Wenn der Filter [!UICONTROL Alle] ausgewählt ist, werden die abgeschlossenen Elemente in die Liste aufgenommen, wodurch erkennbar wird, dass die abgeschlossenen Elemente vorhanden sind.

**[!DNL Workfront]wird nicht geladen**

*[!DNL Workfront]*

Wenn ein(e) Benutzende(r) versucht, sich bei [!DNL Workfront] anzumelden, scheint die Seite in einer Schleife aus Umleitungen oder Aktualisierungen festzustecken und wird nicht geladen.

+++

+++**Wartungs-Update vom 14. April 2022**

**Aufgabe kann nicht aus einem Bericht über einen benutzerdefinierten Abschnitt zu einer Aufgabe hinzugefügt werden**

*Aufgaben*

Wenn ein(e) Benutzende(r) einen benutzerdefinierten Abschnitt in einer Aufgabe aufruft und der Abschnitt einen Aufgabenbericht enthält, kann der/die Benutzende in diesem Bericht keine Aufgabe hinzufügen. Die Schaltfläche [!UICONTROL Aufgabe hinzufügen] ist im Bericht zwar vorhanden, durch Anklicken kann der/die Benutzende jedoch kein Fenster öffnen, um eine Aufgabe hinzuzufügen.

**Schaltfläche „Fertig“ ist beim Bearbeiten einer Ansicht an der falschen Stelle**

*Ansichten*

Wenn ein(e) Benutzende(r) eine Ansicht bearbeitet, wird die Schaltfläche [!UICONTROL Fertig] etwas höher am Bildschirm angezeigt und sich mit Text überschneiden.

Der/die Benutzende kann die Ansicht wie gewohnt bearbeiten. Die Funktionalität ist nicht beeinträchtigt.

**Bei Verwendung der [!UICONTROL Meilenstein]-Ansicht in einem Bericht kann nicht gescrollt werden**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht aufruft und die Ansicht [!UICONTROL Meilenstein] auswählt, wird auf der Seite die Meilensteinansicht angezeigt, der Bildlauf funktioniert aber nicht mehr. Außerdem kann der/die Benutzende keine Meilensteine anzeigen, die weiter unten auf der Seite stehen.

**Leerer Bildschirm beim Anzeigen von Aktualisierungen**

*Updates*

Wenn ein(e) Benutzende(r) Aktualisierungen aufruft und scrollt, um Aktualisierungen weiter unten anzuzeigen, wird der Bildschirm leer, und der/die Benutzende kann keine Aktualisierungen sehen.

**Fehler bei der Massenzuweisung von Benutzenden zu Aufgaben, die nicht der Rolle des/der Benutzenden zugewiesen sind**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) in [!UICONTROL Workload Balancer] versucht, einem/r Benutzenden Aufgaben zuzuweisen, dessen/deren Aufgabengebiet nicht mit dem Aufgabengebiet übereinstimmt, das der Aufgabe zugewiesen wurde, wird eine Meldung angezeigt, in der steht, dass die Aufgabe anhand des primären Aufgabengebiets des/r jeweiligen Benutzenden zugewiesen wird. Wenn der/die Benutzende jedoch auf „[!UICONTROL Zuweisen]“ klickt, werden die Aufgaben nicht zugewiesen und der folgende Fehler erscheint:

„[!UICONTROL Fehler. Unbekannter Server-Fehler.]“

+++

+++**Wartungs-Update vom 7. April 2022**

**Benutzende, die zu Korrekturabzüge hinzugefügt wurden, haben falsche Rollen**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) eine(n) andere(n) Benutzende(n) zu einem Korrekturabzug hinzufügt, wird die Rolle dieses/r Benutzenden im Korrekturabzug als „[!UICONTROL Schreibgeschützt]“ festgelegt trotz der tatsächlichen Korrekturabzugsrolle des/r Benutzenden.

**Die E-Mail zum Zurücksetzen des Passworts kann nicht an eine(n) Benutzende(n) gesendet werden**

*Benutzer*

Wenn ein(e) Benutzende(r) versucht, eine E-Mail zum Zurücksetzen des Passworts an eine(n) andere(n) Benutzende(n) zu senden, ist die Option [!UICONTROL E-Mail für vergessenes Passwort senden] im Menü [!UICONTROL Mehr] nicht verfügbar.

**[!UICONTROL Alle aktualisieren] sendet Aktualisierungen an Benutzerprofile und nicht an das Projekt**

*Updates*

Wenn ein(e) Benutzende(r) den Bereich [!UICONTROL Personen] eines Projekts aufruft, die Option [!UICONTROL Alle aktualisieren] auswählt und dann eine Aktualisierung eingibt, wird die Aktualisierung nicht im Projekt selbst veröffentlicht. Stattdessen wird sie an die einzelnen Profile jedes/r Benutzenden im Projekt gesendet.

**Zu viele Seiten beim Drucken von Aktualisierungen**

*Updates*

Wenn ein(e) Benutzende(r) einen Aktualisierungsverlauf aufruft, der länger als eine gedruckte Seite ist, und versucht, die Seite zu drucken, wird auf dem Druckbildschirm eine Seitenzahl angezeigt, die weit über der tatsächlichen Anzahl der Seiten liegt, die zum Drucken der Aktualisierungen erforderlich ist. Wenn der/die Benutzende dann versucht, im PDF-Format zu drucken, schlägt die Erstellung der PDF-Datei fehl.

**Benutzende können nicht die gesamte Liste der für einen Bericht freigegebenen Entitäten anzeigen, wenn die Einstellung „[!UICONTROL Systemweit sichtbar]“ aktiviert ist**

*Berichte*

Beim Freigeben von Berichten für mehrere Entitäten, die im Fenster [!UICONTROL Zugriff auf Berichte] angezeigt werden, können Benutzende nicht zum unteren Rand der Liste scrollen, um die gesamte Liste anzuzeigen, wenn die Einstellung „[!UICONTROL Systemweit sichtbar]“ aktiviert ist.

**Falsche Währung in Berichten**

*Berichte*

Wenn ein(e) Benutzende(r) für ein Projekt eine andere Währung als die Standardwährung festlegt und dann einen Bericht zu diesem Projekt aufruft, wird die Standardwährung anstelle der Projektwährung angezeigt.

**Information „Zuletzt angezeigt“ Berichten zur [!UICONTROL Nutzung von Berichten] wird nicht angezeigt**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht öffnet, der Informationen zum letzten Aufruf des Berichts enthält, können diese Informationen leer oder veraltet sein. Dieses Problem betrifft u. a. folgende Felder:

* [!UICONTROL Zuletzt angezeigt von]
* [!UICONTROL Zuletzt angezeigte Daten]
* [!UICONTROL Letzte X Betrachter]
* [!UICONTROL Anzeigen in diesem Monat/Quartal/Jahr]

**Abgeschlossene Aufgaben werden in der [!UICONTROL Startseiten-Arbeitsliste angezeigt]**

*[!UICONTROL Startseite]*

Wenn ein(e) Benutzende(r) seine/ihre [!UICONTROL Startseiten-Arbeitsliste] aufruft, werden in der Liste abgeschlossene Aufgaben angezeigt, selbst wenn die Option zum Anzeigen abgeschlossener Aufgaben nicht ausgewählt ist.

**Schaltfläche „Zeitplan“ ist nicht sichtbar, um die Sandbox-Aktualisierung zu planen**

*Sandbox-Umgebung*

Die Schaltfläche [!UICONTROL Zeitplan] zum Planen einer Sandbox-Aktualisierung wird nicht im oberen Banner der Sandbox-Umgebung angezeigt.

**Änderungen an einem berechneten Feld wirken sich auf alle berechneten Felder in einem Formular aus**

*Benutzerdefinierte Formulare*

Wenn sich ein(e) Benutzende(r) im benutzerdefinierten Formular-Builder befindet und den Wert eines berechneten Formulars ändert, wird der neue Wert in allen berechneten Feldern des Formulars angezeigt. Dies kann sowohl neue als auch bereits vorhandene berechnete Felder betreffen.

**Farben im benutzerdefinierten Formular-Builder flackern**

*Benutzerdefinierte Formulare*

Wenn ein(e) Benutzende(r) im benutzerdefinierten Formular-Builder berechnete Felder verwendet, flackern die Farben der Felder und Ausdrücke.

**[!UICONTROL Genehmigungen können nicht abgelehnt werden]**

*Genehmigungen*

Wenn ein(e) Benutzende(r) versucht, eine Genehmigung abzulehnen, reagiert die Schaltfläche [!UICONTROL Ablehnen] nicht und die Genehmigung wird nicht abgelehnt.

Bei der Auswahl der Registerkarte **[!UICONTROL Projekte] wird eine Seite im Bereich „Alle Projekte“ geöffnet**

*Projekte*

Wenn ein(e) Benutzende(r) über eine Registerkarte, die als Teil der Layout-Vorlage angeheftet wurde, zur Seite „Projekte“ wechselt, wird die Seite im Bereich [!UICONTROL Alle Projekte] in der linken Navigation geöffnet. Dies tritt auch dann auf, wenn der/die Benutzende einen anderen Bereich der linken Navigation auswählt und dann die Seite „Projekte“ verlässt und wieder zu ihr zurückkehrt.

+++


## Updates im März 2022

+++**Wartungs-Update vom 31. März 2022**

**Zeitzonen zwischen [!DNL Workfront] und [!DNL Workfront Proof]** stimmen nicht überein

*[!DNL Workfront Proof]*

Wenn das Profil eines/r Benutzenden auf eine bestimmte Zeitzone in [!DNL Workfront] festgelegt ist, weist seine/ihre Zeitzone in [!DNL Workfront Proof] eine andere Zeitzone auf.

**Der Link zum Senden eines angeforderten Dokuments führt zu einer leeren Seite**

*Dokumente*

Wenn ein(e) Benutzende(r) eine Anfrage zum Senden eines Dokuments erhält und auf den Link zu dem Objekt klickt, wo das Dokument angefordert wurde, führt der Link zu einer leeren Seite. Dies kann passieren, wenn in einer E-Mail oder in einer In-App-Benachrichtigung auf einen Link geklickt wird.

**Gruppe wird beim Konvertieren des Problems in ein Projekt falsch zugewiesen**

Gruppen

Wenn ein(e) Benutzende(r) ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, passiert Folgendes:

* Wenn der Vorlage eine Gruppe zugewiesen ist, wird diese Gruppe im Problemkonvertierungs-Fenster als die Gruppe für das neue Projekt angezeigt.
* Wenn der Vorlage keine Gruppe zugewiesen ist, wird die Standardgruppe des/r Benutzenden, der/die das Problem konvertiert, im Problemkonvertierungs-Fenster als Gruppe für das neue Projekt angezeigt.
* Wenn die Vorlage keine Gruppe enthält, sollte das neue Projekt die Gruppe im Problemprojekt übernehmen.

**Benutzerdefiniertes objektübergreifendes Formular kann nicht an Anfrage-Warteschlange angehängt werden**

Anforde- rungen

Wenn ein(e) Benutzende(r) versucht, ein benutzerdefiniertes objektübergreifendes Formular zur Detailseite einer Warteschlange hinzuzufügen, wird das objektübergreifende Formular nicht in der Dropdown-Liste der verfügbaren Formulare angezeigt und der/die Benutzende kann es nicht auswählen, um es zu den Warteschlangendetails hinzuzufügen.

**Benutzenden kann im [!UICONTROL Workload Balancer kein „Sekundäres Aufgabengebiet“ zugewiesen werden]**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) versucht, im [!UICONTROL Workload Balancer] eine(n) andere(n) Benutzende(n) einer Aufgabe zuzuweisen und die Aufgabe einem Aufgabengebiet zugewiesen wird, das nicht dem primären Aufgabengebiet des/r Benutzenden entspricht, wird der/die Benutzende über das primäre Aufgabengebiet der Aufgabe zugewiesen und die folgende Meldung wird angezeigt:

„&lt;Name> entspricht nicht der Rolle von &lt;Aufgabenrollenzuweisung>. 1 Arbeitselement, das derzeit der Rolle &lt;Aufgabenrollenzuweisung> zugewiesen ist, wird &lt;Name> in der Rolle &lt;Primäres Aufgabengebiet> zugewiesen.“

Dies tritt auch dann auf, wenn der/die Benutzende das Aufgabengebiet der Aufgabenrollenzuweisung als sekundäres Aufgabengebiet hat.

**Problem mit der Scrum-Board-Leiste „Weitere Arbeitselemente anzeigen“**&#x200B;

*Agile*

Wenn ein(e) Benutzende(r) auf einem Scrum-Board auf die Leiste [!UICONTROL Weitere Arbeitselemente anzeigen] klickt und dann scrollt, um die neuen Elemente anzuzeigen, bleibt die Leiste [!UICONTROL Weitere Arbeitselemente anzeigen] am Scrum-Board haften und bewegt sich beim Scrollen mit ihm. Dadurch ist es schwierig, die Karten zu lesen.

**In Pflichtfeldern in benutzerdefinierten Formularen werden rote Punkte angezeigt**

Benutzerdefinierte Formulare

Wenn ein(e) Benutzende(r) ein Pflichtfeld in einem benutzerdefinierten Formular anzeigt, werden unter dem Sternchen zwei rote Punkte angezeigt, die darauf hinweisen, dass dies ein Pflichtfeld ist.

**Zeitauswahl bei Informationseingabe für Bericht abgeschnitten**

*Berichte*

Wenn ein(e) Benutzende(r) Informationen für einen Bericht eingibt und eine Datumsauswahl vorhanden ist, zeigt die Zeitauswahl am unteren Rand der Datumsauswahl keine Stunden nach 2 an und der/die Benutzende kann keinen Stundenwert außer 1 oder 2 auswählen.

+++

+++**Wartungs-Update (Hotfix) vom 29. März 2022**

**Im benutzerdefinierten Formular-Builder können keine Berechnungen geändert oder gespeichert werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) eine Berechnung manuell in ein Berechnungsfeld im benutzerdefinierten Formular-Builder eingibt und das Formular speichert, wird die Berechnung nicht gespeichert. Wenn der/die Benutzende das benutzerdefinierte Formular erneut öffnet, ist dieses Feld leer.

Wenn ein(e) Benutzende(r) eine Berechnung in ein Berechnungsfeld im benutzerdefinierten Formular-Builder eingibt, indem er/sie die Dropdown-Listen verwendet und das Formular speichert, wird dieser Wert gespeichert. Wenn der/die Benutzende das benutzerdefinierte Formular jedoch erneut öffnet, kann er/sie dieses Feld weder manuell noch mit der Dropdown-Liste bearbeiten oder den Wert entfernen.

HINWEIS: Diese Problembehebung umfasste zusätzliche Funktionen. Wenn Sie nun mit der Eingabe in ein berechnetes Feld beginnen, werden in einer Dropdown-Liste unten mögliche Ausdrücke oder Berechnungen wie im Berechnungs-Editor angezeigt. Klicken Sie auf ein Element in der Dropdown-Liste, um es zum berechneten Feld hinzuzufügen.

+++

+++**Wartungs-Update vom 24. März 2022**

**Zeitzonen zwischen [!DNL Workfront] und [!DNL Workfront Proof]** stimmen nicht überein

*[!DNL Workfront Proof]*

Wenn das Profil eines/r Benutzenden auf eine bestimmte Zeitzone in [!DNL Workfront] festgelegt ist, weist seine/ihre Zeitzone in [!DNL Workfront Proof] eine andere Zeitzone auf.

**Fehler bei Pflichtfeld für ausgefüllte benutzerdefinierte Felder beim Anhängen einer Vorlage**

*Projekte*

Beim Anhängen einer Vorlage mit benutzerdefinierten Pflichtfeldern an ein Projekt, in dem das Feld bereits vorhanden und ausgefüllt ist, wird dem/der Benutzenden folgender Fehler angezeigt: „[!UICONTROL Es gibt unausgefüllte Felder. Geben Sie Werte für die Pflichtfelder ein, damit Sie fortfahren können.]“
Wenn der/die Benutzende auf „[!UICONTROL Anzeigen]“ klickt, kann er/sie sehen, dass die Felder ausgefüllt sind, und die Vorlage kann erfolgreich angehängt werden.

**Der [!UICONTROL Workload Balancer] blinkt, wenn Sie zwischen Datumsangaben wechseln**

*[!UICONTROL Lastenausgleich]*

Die Stunden des/r Benutzenden, der/die im [!UICONTROL Workload Balancer] als Erste(r) aufgelistet ist, werden nicht angezeigt, wenn die Timeline aktualisiert wird. Der/die Benutzende und seine/ihre Stunden werden mit allen grauen Kästchen angezeigt, die blinken. Dies tritt auf, wenn Sie sich in der Timeline vorwärts und rückwärts bewegen.

Durch die Aktualisierung des Filters wird die Anzeige zurückgesetzt. Doch wenn Sie sich erneut auf der Timeline vorwärts und rückwärts bewegen, blinkt die Anzeige wieder und die Stunden werden nicht angezeigt.

**Benutzerdefinierte Terminologie ist inkonsistent**

*Layoutvorlagen*

Benutzende melden, dass, wenn der [!DNL Workfront]-Administrator bzw. die Administratorin die Terminologie mancher Objekte mithilfe einer Layout-Vorlage anpasst, der neue Objektname in der Benutzeroberfläche inkonsistent angezeigt wird.

Beispiel: auf der Seite [!UICONTROL Projekte] wird der Seitentitel als „[!UICONTROL Projekte]“ angezeigt, auch wenn der [!DNL Workfront]-Administrator bzw. die Administratorin hat den Namen „[!UICONTROL Projekte]“ bereits geändert hat.

Dies führt zu Verwirrung bei den Benutzenden.

+++

+++**Wartungs-Update vom 17. März 2022**

**Miniaturansicht und Hauptbilder sind beim Anzeigen mehrseitiger Dateien mit dem [!DNL Safari] -Browser leer**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) versucht, eine Datei mit mehreren Seiten im [!DNL Safari]-Browser zu öffnen, sind die Bilder der Miniaturansicht leer. Manchmal ist auch das Hauptbild leer.

**Falsche Benutzerliste bei der Zuweisung umfangreicher Arbeitsaufträge im [!UICONTROL Workload Balancer]**

*[!UICONTROL Lastenausgleich]*

Wenn ein(e) Benutzende(r) eine umfangreiche Zuweisung von Arbeitsaufträgen im [!UICONTROL Workload Balancer] vornimmt und ein Projekt und ein Aufgabengebiet auswählt, ist die Liste der verfügbaren Benutzenden falsch. Dabei können Benutzende ohne das erforderliche Aufgabengebiet oder die Projektberechtigung angezeigt werden, und Benutzende mit dem erforderlichen Aufgabengebiet und der Projektberechtigung werden nicht in der Liste angezeigt.

**[!UICONTROL Die Sortierung funktioniert nicht in Berichten]**

*Berichte*

Wenn ein(e) Benutzende(r) auf eine Spalte klickt, um sie zu sortieren, scheint die Sortierung zu funktionieren, doch die Sortierung wird sofort wieder zurückgesetzt und die Elemente erscheinen wie vor dem Klicken auf die Spalte. Die Sortierung wird in keiner Spalte beibehalten.

**Durch die Auswahl von „[!UICONTROL Keine]“ wird der Bericht auf die [!UICONTROL standardmäßige Gruppierung] zurückgesetzt**

*Berichte*

Wenn ein Bericht eine integrierte Gruppierung aufweist und der/die Benutzende versucht, im Dropdown-Menü [!UICONTROL Gruppierung] „[!UICONTROL Keine]“ auszuwählen, wird der Bericht kurz ohne Gruppierung angezeigt und dann auf die [!UICONTROL standardmäßige Gruppierung] zurückgesetzt.

**Registerkarte „[!UICONTROL Blueprint-Zugriff]“ wurde aus den Blueprint-Voreinstellungen entfernt**

*Blueprints*

HINWEIS: Dieses Problem tritt nur in der Vorschau-Umgebung auf.

Die Registerkarte [!UICONTROL Blueprint-Zugriff] wurde aus den Blueprints-Voreinstellungen entfernt. Aus den Blueprints-Voreinstellungen wurde aber keine Funktionalität entfernt.

+++

+++**Wartungs-Update (Hotfix) vom 14. März 2022**

**Benutzerliste kann nicht nach unten gescrollt werden, wenn eine Zuweisung auf dem Kanban-Board vorgenommen wird**

*Agile*

Wenn ein(e) Benutzende(r) ein [!DNL Kanban]-Board aufruft und versucht, eine Zuweisung vorzunehmen, springt die Benutzerliste, die beim Tippen angezeigt wird beim Bildlauf nach unten wieder nach oben. Der/die Benutzende kann keine(n) Benutzenden auswählen, der/die nicht oben in der Liste steht und kann die Zuweisung nicht speichern.

**[!UICONTROL Meilenstein]-Ansicht im Projektbericht verursacht Fehler**

*Berichte*

Beim Anzeigen eines Projektberichts mit der [!UICONTROL Meilenstein]-Ansicht erscheint die Fehlermeldung „[!UICONTROL APIModel INTERNAL unterstützt nicht namedQuery TILE:milestone-Ansicht (UIVW)]“.

**Benutzerdefinierte Terminologie ist inkonsistent**

*Layoutvorlagen*

Benutzende melden, dass, wenn der [!DNL Workfront]-Administrator bzw. die Administratorin die Terminologie mancher Objekte mithilfe einer Layout-Vorlage anpasst, der neue Objektname in der Benutzeroberfläche inkonsistent angezeigt wird.

Beispiel: auf der Seite [!UICONTROL Projekte] wird der Seitentitel als „[!UICONTROL Projekte]“ angezeigt, auch wenn der [!DNL Workfront]-Administrator bzw. die Administratorin hat den Namen „[!UICONTROL Projekte]“ bereits geändert hat.

Dies führt zu Verwirrung bei den Benutzenden.

**Berechnungen für vorhandene berechnete Felder können nicht aktualisiert werden**

*Benutzerdefinierte Formulare*

Benutzende können die Berechnungen in berechneten Feldern nicht aktualisieren/ändern. Wenn das Feld ohne eine Berechnung erstellt und gespeichert wurde, erscheint der Builder jedes Mal, wenn Sie versuchen, einen Ausdruck hinzuzufügen und zu speichern/anzuwenden, wieder leer.

Wenn Sie ein berechnetes Feld mit einem Ausdruck erstellen und speichern, wird jedes Mal, wenn Sie versuchen, die Berechnung zu ändern, das Feld auf den vorherigen Wert zurückgesetzt.

**[!UICONTROL Fehler mit ungültigem Parameter] beim Zurücksetzen von Passwörtern**

*Anmeldung*

Benutzende können ihre Passwörter in keiner Umgebung zurücksetzen. Wenn er/sie seine/ihre E-Mail-Adresse eingibt und versucht fortzufahren, wird ein Fehler angezeigt.

[!UICONTROL Fehler: Ungültiger Parameter: Suchparameterwert „domain“].

+++

+++**Wartungs-Update vom 10. März 2022**

**Probleme bei der Anmeldung bei der Vorschau-Umgebung**

*Anmeldung*

Es wurden die folgenden Probleme bei der Anmeldung in die Vorschau-Umgebung gemeldet.

Wenn ein(e) Benutzende(r) versucht, sich bei der Vorschau-Umgebung anzumelden, wird eine Meldung angezeigt, die angibt, dass die falsche ID oder das falsche Passwort eingegeben wurde.

Wenn ein(e) Benutzende(r) versucht, sein/ihr Passwort zurückzusetzen, wird ihm/ihr der Fehler „[!UICONTROL Mehrere Benutzer wurden mit dieser E-Mail-Adresse gefunden <example@example.com>?]“ angezeigt

**Benutzerdefinierte Formulare werden im Bereich [!UICONTROL Projektdetails] nur langsam geladen**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, den Bereich [!UICONTROL Projektdetails] aufzurufen, werden benutzerdefinierte Formulare, die mit dem Projekt verknüpft sind, erst nach einer Verzögerung von 15 Sekunden oder mehr geladen. Die Option [!UICONTROL Benutzerdefinierte Formulare hinzufügen] ist von dieser Verzögerung ebenfalls betroffen.

**Feldwerte von benutzerdefinierten Formularen werden nicht im Dokumentzusammenfassungs-Bedienfeld gespeichert**

*Dokumente*

Wenn ein(e) Benutzende(r) im Dokumentzusammenfassungs-Bedienfeld in einem benutzerdefinierten Formular Felder aktualisiert, von denen mindestens eines ein Feld mit automatischer Textvervollständigung ist, die Änderungen speichert und das Zusammenfassungs-Bedienfeld verlässt, werden die Änderungen nicht gespeichert. Dies tritt nur auf, wenn ein Feld mit automatischer Textvervollständigung bearbeitet wird, es sind jedoch alle Felder betroffen.

**Daten bleiben beim Konvertieren von Vorlagen aufgrund der Zugriffsebenen bei freigegebenen Vorlagen nicht erhalten**

*Projekte*

Wenn ein(e) Benutzende(r), der/die Lesezugriff auf eine freigegebene Vorlage hat, versucht, ein Problem in ein Projekt zu konvertieren, werden keine Daten in den benutzerdefinierten Formularabschnitten in das erstellte Projekt konvertiert, die die Zugriffsebene [!UICONTROL Beitragen] oder eine höhere Zugriffsebene als „Anzeigen“ erfordern.

**Fehler beim Hochladen der neuen Dokumentversion**

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, eine neue Version eines Dokuments aus der Dokumentliste hochzuladen, wird das Dokument nicht hochgeladen und der/die Benutzende sieht den folgenden Fehler:

[!UICONTROL „com.attask.boz.Document.getCurrentVersion()“ kann nicht aufgerufen werden, da „Dokument“ null ist]

**Verrechnungssätze können nicht bearbeitet werden**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, auf der Registerkarte [!UICONTROL Verrechnungssätze] eines Projekts einen Verrechnungssatz zu bearbeiten, wird durch Klicken auf die Schaltfläche [!UICONTROL Bearbeiten] kurz das Fenster [!UICONTROL Bearbeiten] geöffnet, es wird jedoch wieder geschlossen, bevor der/die Benutzende den Verrechnungssatz bearbeiten kann. Durch erneutes Klicken auf die Schaltfläche wird das Bearbeitungsfenster auch nicht geöffnet.

**Öffentlicher Link für ein Dokument führt zu leerer Seite**

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, ein Dokument mithilfe eines öffentlichen Links zu öffnen, führt der Link zu einer leeren Seite. Dies tritt auf, wenn der Link in einem Fenster geöffnet wird, in dem eine aktive [!DNL Workfront]-Sitzung geöffnet ist.

**Hoppla-Fehler beim Hinzufügen von Aufgabe oder Problem zu einer Liste**

*Aufgaben und Probleme*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, eine Aufgabe oder ein Problem zu einer Liste hinzuzufügen und benutzerdefinierte Felder ausfüllt, wird die Aufgabe bzw. das Problem nicht erstellt und der folgende Fehler wird angezeigt:

[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]

**Wird eine Aktualisierung unmittelbar nach einer Statusänderung vorgenommen, wird das Objekt in den vorherigen Status zurückgesetzt**

Projekte, Aufgaben und Probleme

Wenn Sie den Status eines Projekts, einer Aufgabe oder eines Problems ändern und dann sofort mit der Eingabe einer Aktualisierung beginnen, ohne die Seite zu aktualisieren, wird im Aktualisierungsfeld der vorherige Status angezeigt. Wenn die Aktualisierung veröffentlicht wird, wird das Objekt wieder in den vorherigen Status zurückgesetzt.

**Benutzende, die zu Korrekturabzüge hinzugefügt wurden, haben falsche Rollen**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) eine(n) andere(n) Benutzende(n) zu einem Korrekturabzug hinzufügt, wird die Rolle dieses/r Benutzenden im Korrekturabzug als „[!UICONTROL Schreibgeschützt]“ festgelegt trotz der tatsächlichen Korrekturabzugsrolle des/r Benutzenden.

Problemumgehung: Wählen Sie für die Korrekturabzugsrolle des/r Benutzenden in seinem/ihrem Profil einen anderen Wert und wählen Sie danach wieder die richtige Rolle aus.

**Benutzerdefiniertes Formular wird beim Konvertieren eines Problems in ein Projekt mit einer Vorlage nicht geladen**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, werden möglicherweise mindestens eines der benutzerdefinierten Formulare, die an die Vorlage angehängt sind, nicht geladen. Wenn der/die Benutzende die Vorlage für das neue Projekt konfiguriert, wird anstelle der benutzerdefinierten Formulare die folgende Meldung angezeigt:

„[!UICONTROL Ein Fehler ist aufgetreten, Formular konnte nicht geladen werden].“

**Benutzende können ein Problem nicht inline über ein benutzerdefiniertes Dropdown-Feld hinzufügen, das in der Ansicht angezeigt wird**

*Listen*

Wenn ein(e) Benutzende(r) ein Problem inline hinzufügt und eine benutzerdefinierte Ansicht mit benutzerdefinierten Dropdown-Feldern auf die Liste angewendet wird, tritt ein Fehler auf, wenn er/sie nur das Dropdown-Feld ausfüllt. Der/die Benutzende hat Zugriff auf das Bearbeiten eines benutzerdefinierten Formulars und ist der Projektbesitzer mit Verwaltungsrechten für das Projekt.

[!UICONTROL Fehler: Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]

**Berechtigungen zum Hinzufügen von Aufgaben zu einem Projekt sind nicht erforderlich, um eine Aufgabe in das Projekt zu verschieben oder zu kopieren**

*Aufgaben*

Sie können jetzt eine Aufgabe in eine andere Aufgabe in einem Projekt verschieben oder kopieren, ohne über die Berechtigungen zum Hinzufügen von Aufgaben zum Zielprojekt verfügen zu müssen. Sie müssen über die Berechtigung zum Hinzufügen von Aufgaben zu mindestens einer der Aufgaben des Zielprojekts verfügen. Vor diesem Update mussten Sie Berechtigungen zum Hinzufügen von Aufgaben zu einem Projekt besitzen, um eine Aufgabe in das Projekt oder in eine seiner Aufgaben verschieben oder kopieren zu können.  Dieses Update ist jetzt in der Produktionsumgebung verfügbar. Diese Funktionalität ist seit dem Wartungs-Update vom 24. März 2022 in der Vorschau-Umgebung verfügbar.

HINWEIS: Dieses Update wird in der Produktionsumgebung verfügbar sein, wenn Probleme nach der Veröffentlichung der Produktionsversion 22.2 kopiert oder verschoben werden. Weitere Informationen zur aktuellen Version finden Sie unter workfront.com/release.

**Dropdown-Menü in der Eingabeaufforderung ist abgeschnitten.**

*Berichte*

Bei der Verwendung einer Eingabeaufforderung in einem Bericht sind die Dropdown-Menüs abgeschnitten, die die Auswahl der Filterkriterien für den Bericht ermöglichen. Daher werden die im Dropdown-Menü unten stehenden Kriterien nicht angezeigt.

**Arbeitselement wird bei einer Aktualisierung auf den vorherigen Status zurückgesetzt**

*Updates*

Wenn ein(e) Benutzende(r) den Status eines Arbeitselements in der Kopfzeile ändert, wird der Status im [!UICONTROL Aktualisierungsbereich] nicht aktualisiert. Wenn der/die Benutzende dann eine Aktualisierung vornimmt, wird im Dropdown-Menü weiterhin der vorherige Status angezeigt. Wenn die Aktualisierung gespeichert wird, überschreibt dieser vorherige, falsche Status den in der Kopfzeile festgelegten Status.

+++

+++**Wartungs-Update vom 3. März 2022**

**Dokument kann nicht aus [!DNL Google Drive]** hinzugefügt werden

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, ein Dokument aus [!DNL Google Drive] hinzuzufügen, reagiert die Auswahl nicht und der/die Benutzende kann keine Dokumente auswählen, um sie hinzuzufügen.

**Getaggte Benutzende werden nicht zum Aktualisierungs-Thread hinzugefügt**

*Updates*

Wenn ein(e) Benutzende(r) in einer Aktualisierung getaggt ist, wird er/sie nicht im Bereich „[!UICONTROL An]“ der Aktualisierung oder der Antworten angezeigt.

**Der Korrekturabzugsbenutzende hat zwei separate Korrekturabzugskonten**

*[!DNL Workfront Proof]*

Die E-Mail-Adresse eines/r Benutzenden in [!DNL Workfront Proof] kann sich in zwei separaten Konten mit separaten IDs befinden, sodass der/die Benutzende zwei Konten hat. Dadurch kann es schwierig sein, das richtige Konto zu finden.

**Hoppla-Fehler in Berichtskopfzeilen angezeigt**

*Berichte*

Wenn ein(e) Benutzende(r) einen Bericht aufruft, wird in der Kopfzeile des Berichts der folgende Fehler angezeigt:

„[!UICONTROL Versuchen Sie es erneut. Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Wenn der/die Benutzende ein Dashboard öffnet, kann der Fehler in der Kopfzeile aller Berichte im Dashboard angezeigt werden.

**Daten in Feldern in benutzerdefinierten Formularen, die nur von einem Administrator bzw. einer Administratorin bearbeitet werden können, werden beim Konvertieren von Problemen in Projekte nicht beibehalten**

*Projekte*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren und das Problem Daten in Feldern enthält, die nur von einem Administrator bzw. einer Administratorin bearbeitet werden können, werden die Daten in diesen Feldern nicht in das neue Projekt übertragen.

Wenn ein Administrator bzw. einer Administratorin das Problem konvertiert, werden die Daten erwartungsgemäß in das neue Projekt übertragen.

Die Dateigrößenbeschränkung von **[!DNL XLS]- und [!DNL XLSX]-Dateien wurde für Korrekturabzüge vorübergehend auf 100 MB reduziert**

*Proofing*

Um ein Sicherheitsproblem zu beheben, haben wir die maximale Dateigröße für [!DNL XLS]- und [!DNL XLSX]-Dateien bei der Erstellung eines Korrekturabzugs auf 100 MB begrenzt.

HINWEIS: Dieses Update fand am 24. Februar in der Vorschau-Umgebung statt und wird sich ab 3. März in der Produktionsumgebung befinden.

**Update für die Workfront-Suche**

Suchen

Diese Woche begann ein schrittweiser Rollout zur Aktualisierung der Infrastruktur für die [!DNL Workfront]-Suchfunktion. Durch dieses Update werden zukünftige Verbesserungen der Suche einfacher und zuverlässiger. Mit diesen Änderungen werden Elemente, die zu [!DNL Workfront] hinzugefügt werden, schneller indiziert und daher früher in den Suchergebnissen zu finden sein.

Der schrittweise Rollout wird 2 Wochen dauern.

**Symbolleisten für Berichte in Dashboards wurden aktualisiert**

Berichte

In Berichten in Dashboards wird jetzt eine neue Symbolleiste angezeigt. Diese Symbolleiste ist Teil der Updates von Listen und Berichten, die derzeit in allen Bereichen von [!DNL Workfront] vorgenommen werden.

+++


## Updates im Februar 2022

+++**Wartungs-Update (Hotfix) vom 24. Februar 2022**

**Daten werden beim Konvertieren von Problemen in Projekte nicht beibehalten, wenn das Feld in der Vorlage ausgeblendet ist**

*Projekte*

Wenn ein(e) Benutzende(r) ein Problem in eine Vorlage konvertiert und die Vorlage ein benutzerdefiniertes Formular enthält, in dem Felder basierend auf den Werten in anderen Feldern angezeigt oder ausgeblendet werden, werden die Daten in den Feldern, die zum Zeitpunkt der Konvertierung in der (datenlosen) Vorlage verborgen sind, nicht in das neue Projekt übernommen.

**Ressourcenplaner kann nicht nach Rolle exportiert werden**

*Ressourcenplaner*

Wenn ein(e) Benutzende(r) versucht, den [!DNL Resource Planner] mit der Option [!UICONTROL Ansicht nach Rolle] zu exportieren, ist der Export nicht erfolgreich und der/die Benutzende erhält eine E-Mail mit der folgenden Nachricht:

Beim Exportieren Ihrer [!DNL Resource Planner]-Daten ist ein Fehler aufgetreten.

**Schaltfläche „Anfrage kopieren“ funktioniert nicht**

*Anforde- rungen*

Wenn ein(e) Benutzende(r) versucht, eine Anfrage zu kopieren, funktioniert die Schaltfläche [!UICONTROL Anfrage kopieren] nicht, wenn der/die Benutzende keinen Lesezugriff auf das Warteschlangen-Thema hat.

+++

+++**Wartungs-Update vom 24. Februar 2022**

**Daten in benutzerdefinierten Formularen werden ausgeblendet, wenn andere Formularfelder ausgefüllt werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein(e) Benutzende(r) ein benutzerdefinierten Formular ausfüllt, um ein Problem in ein Projekt zu konvertieren, kann das Ausfüllen eines benutzerdefinierten Felds dazu führen, dass Daten in einem anderen benutzerdefinierten Feld nicht mehr angezeigt werden. Wenn der/die Benutzende die fehlenden Daten erneut eingibt und versucht, das Projekt zu erstellen, wird die folgende Fehlermeldung angezeigt:

„[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]“

**Feld „[!UICONTROL Dieser Genehmigungsprozess kann genutzt werden von...]“ fehlt**

*Genehmigungen*

Wenn ein(e) Benutzende(r) einen Genehmigungsprozess im Bereich [!UICONTROL Setup] erstellt oder bearbeitet, fehlt das Feld „[!UICONTROL Dieser Genehmigungsprozess kann genutzt werden von...]“. Dies kann beim Erstellen oder Bearbeiten eines Genehmigungsprozesses auftreten.

**Der Systemadministrator bzw. die Systemadministratorin kann Benutzende beim Löschen einer Gruppe nicht neu zuweisen**

*Gruppen*

Wenn ein Systemadministrator bzw. eine Systemadministratorin eine Gruppe löscht, kann er/sie die Benutzenden dieser Gruppe nur Gruppen zuweisen, für die der Systemadministrator bzw. die Systemadministratorin ein Gruppenadministrator bzw. eine Gruppenadministratorin ist. Andere Gruppen werden nicht im Dropdown-Menü angezeigt und der Administrator bzw. die Administratorin kann sie nicht auswählen.

**Hoppla-Fehler beim Konvertieren eines Problems in ein Projekt**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren und benutzerdefinierte Formulare aus der Vorlage hinzufügt oder daraus entfernt, wird das Problem nicht konvertiert und die folgende Meldung wird angezeigt:

[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]

**Korrekturabzug kann nicht geöffnet werden; Seite wird aktualisiert**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) versucht, einen Korrekturabzug zu öffnen, kann er nicht geöffnet werden. Schließlich wird die Seite aktualisiert.

Die Dateigrößenbeschränkung von **[!DNL XLS]- und [!DNL XLSX]-Dateien wurde für Korrekturabzüge vorübergehend auf 100 MB reduziert**

*Testversand*

Um ein Sicherheitsproblem zu beheben, haben wir die maximale Dateigröße für [!DNL XLS]- und [!DNL XLSX]-Dateien bei der Erstellung eines Korrekturabzugs auf 100 MB begrenzt.

HINWEIS: Dieses Update findet am 24. Februar in der Vorschau-Umgebung statt und befindet sich ab 3. März in der Produktionsumgebung.

**Berechtigungen zum Hinzufügen von Aufgaben oder Problemen zu einem Projekt sind nicht erforderlich, um eine Aufgabe oder ein Problem in das Projekt zu verschieben oder zu kopieren**

*Projekte*

Sie können jetzt eine Aufgabe oder ein Problem in eine andere Aufgabe in einem Projekt verschieben oder kopieren, ohne über die Berechtigungen zum Hinzufügen von Aufgaben oder Problemen zum Zielprojekt verfügen zu müssen. Sie müssen über die Berechtigung zum Hinzufügen von Aufgaben oder Problemen zu mindestens einer der Aufgaben des Zielprojekts verfügen. Vor diesem Update mussten Sie Berechtigungen zum Hinzufügen von Aufgaben oder Problemen zu einem Projekt besitzen, um eine Aufgabe oder ein Problem in das Projekt oder in eine seiner Aufgaben verschieben oder kopieren zu können. Dieses Update ist nur in der Vorschau-Umgebung verfügbar.

HINWEIS: Dieses Update ist ab dem 10. März in der Produktionsumgebung verfügbar, wenn Aufgaben kopiert oder verschoben werden. Dieses Update wird in der Produktionsumgebung verfügbar sein, wenn Probleme nach der Veröffentlichung der Produktionsversion 22.2 kopiert oder verschoben werden. Weitere Informationen zur aktuellen Version finden Sie unter workfront.com/release.

**Update für die Workfront-Suche**

*Suchen*

Diese Woche begann ein schrittweiser Rollout zur Aktualisierung der Infrastruktur für die [!DNL Workfront]-Suchfunktion. Durch dieses Update werden zukünftige Verbesserungen der Suche einfacher und zuverlässiger. Mit diesen Änderungen werden Elemente, die zu [!DNL Workfront] hinzugefügt werden, schneller indiziert und daher früher in den Suchergebnissen zu finden sein.

Der schrittweise Rollout wird 2 Wochen dauern.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update vom 18. Februar 2022**

**Feldwerttyp-Validierung zu den [!DNL Anaplan]-Eigenschaften von Listenelementen hinzugefügt**

*[!DNL Adobe Workfront Fusion]*

Es wurde ein Problem behoben, durch das es Benutzenden möglich war, in Felder für Eigenschaften von Listenelementen den falschen Datentyp einzufügen. Durch die Validierung des Eigenschaftstyps kann [!DNL Fusion] sicherstellen, dass der richtige Datentyp an Anaplan gesendet wird, sodass Fehler, die durch falsche Datentypen verursacht werden, vermieden werden.

+++

+++**Wartungs-Update vom 17. Februar 2022**

**Fehler beim Löschen des Vorgängers auf der Registerkarte „Vorgänger“**

*Aufgaben*

Wenn ein(e) Benutzende(r) versucht, einen Vorgänger aus der Registerkarte [!UICONTROL Vorgänger] einer Aufgabe zu löschen, wird die Aufgabe nicht gelöscht und dem/der Benutzenden wird der folgende Fehler angezeigt:

[!UICONTROL Aufgabe mit primärem/n Schlüsselwert(en) &quot;&quot; nicht gefunden]

**Hoppla-Fehler beim Öffnen der Benutzerseite**

*Benutzer*

Wenn ein(e) Benutzende(r) versucht, die Seite [!UICONTROL Benutzende] zu öffnen, wird die Seite nicht geöffnet und die folgende Fehlermeldung wird angezeigt:

[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie [!DNL Workfront], damit wir die Fehlerursache feststellen und den Fehler beheben können.]

**Elemente in der Kopfzeile eines Berichts in einem Dashboard überschneiden sich**

*Dashboards*

Wenn ein(e) Benutzende(r) einen Bericht in einem Dashboard aufruft, überschneiden sich das Gruppierungssymbol und -bezeichnung und die Links zu den [!UICONTROL Details] und zur [!UICONTROL Zusammenfassung].

**Probleme mit dem Menü „[!UICONTROL Mehr]“ für Dokumente und Korrekturabzüge**

*Dokumente*

Wenn ein(e) Benutzende(r) ein Dokument oder einen Korrekturabzug in einer [!DNL Workfront Classic]-Dokumentliste auswählt und auf „[!UICONTROL Mehr]“ klickt, kann eines der folgenden Probleme auftreten: Die Schaltfläche reagiert nicht
Alle Optionen unter der Schaltfläche sind mit „[!UICONTROL objekt Objekt]“ beschriftet und können nicht verwendet werden.

**Fehler „Sie müssen ein Systemadministrator sein“ beim Erstellen eines Projekts**

*Projekte*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, in dem ein Bereich nur für Administratoren bzw. Administratorinnen zugänglich ist, kann er/sie das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

„Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern“

**Daten in einem benutzerdefinierten Formular, die im Administratoren bzw. Administratorinnen vorbehaltenen Bereich stehen, werden beim Konvertieren von Problemen in Projekte nicht beibehalten**

*Projekte*

Wenn ein(e) Benutzende(r) ein Problem mithilfe einer Vorlage in ein Projekt konvertiert und die Vorlage ein benutzerdefiniertes Formular mit einem reinen Administratorbereich besitzt, werden die Daten im Administratorbereich nicht in das neue Projekt übernommen. Dies tritt auch dann auf, wenn ein Administrator bzw. eine Administratorin das Problem konvertiert.

+++

+++**Wartungs-Update vom 10. Februar 2022**

**Beim Erstellen eines Projekts erscheint der Fehler „[!UICONTROL Sie müssen Systemadministrator sein]“**

*Projekte*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, in dem ein Bereich nur für Administratoren bzw. Administratorinnen zugänglich ist, kann er/sie das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

„[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]“

**Benutzende, die deaktiviert und wieder aktiviert wurden, werden nicht in den [!UICONTROL Korrekturabzugskontakten angezeigt]**

*[!DNL Workfront Proof]*

Wenn ein(e) Benutzende(r) die Kontaktliste in [!DNL Workfront Proof] aufruft, werden Benutzende, die deaktiviert und wieder aktiviert wurden, nicht in der Liste angezeigt.

**Meldung „Irgendetwas ist schiefgelaufen“ beim Konvertieren eines Problems in ein Projekt mithilfe einer Vorlage**

*Projekte*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, wird in benutzerdefinierten Formularfeldern, die nur für Administratoren bzw. Administratorinnen sichtbar sind, die folgende Meldung angezeigt:

„[!UICONTROL Irgendetwas ist schiefgelaufen, Formular konnte nicht geladen werden]“

**Fehler „Seiteninhalt kann nicht geladen werden“ bei der Anzeige von Projektvoreinstellungen**

*Einrichtung*

Wenn ein Administrator oder eine Administratorin versucht, Projekte, Aufgaben oder Probleme unter anzuzeigen [!UICONTROL Projektvoreinstellungen] im Bereich [!UICONTROL Setup] anzuzeigen, wird die Seite nicht geladen und der folgende Fehler wird angezeigt:

„[!UICONTROL Seiteninhalt kann nicht geladen werden. Bitte aktualisieren Sie die Seite.]“

+++

+++**Wartungs-Update vom 3. Februar 2022**

**[!UICONTROL BizContext]-Fehler beim Anmelden**

*Anmeldung*

Wenn ein(e) Benutzende(r) versucht, sich bei [!DNL Workfront] anzumelden, schläft die Anmeldung fehl und die folgende Meldung wird angezeigt:

„[!UICONTROL Versuchen Sie es erneut. Datenbankfehler: BizContext-Commit fehlgeschlagen!]“

Dies wurde in der Vorschau-Umgebung gemeldet.

**Der Aktualisierungsverlauf für Probleme verschwindet, wenn das Problem noch nicht genehmigt wurde**

*Updates*

Wenn ein(e) Benutzende(r) in das Feld [!UICONTROL Neue Aktualisierung] im Aktualisierungsverlauf eines Problems klickt, das noch nicht genehmigt wurde, verschwindet der gesamte Aktualisierungsverlauf.

**Fehler beim Hochladen einer neuen Version eines Dokuments**

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, eine neue Version eines Dokuments hochzuladen, wird die neue Version nicht hochgeladen und eine der folgenden Fehlermeldungen wird angezeigt:

* [!UICONTROL documentID darf nicht null sein]
* [!UICONTROL Fehler: Ungültiger Parameter: documentID-Wert „undefined“]

**Öffentlicher Link für ein Dokument führt zu leerer Seite**

*Dokumente*

Wenn ein(e) Benutzende(r) versucht, ein Dokument mithilfe eines öffentlichen Links zu öffnen, führt der Link zu einer leeren Seite. Dies tritt auf, wenn der Link in einem Fenster geöffnet wird, in dem eine aktive [!DNL Workfront]-Sitzung geöffnet ist.

**Listensteuerelemente funktionieren nicht in Berichten in Dashboards**

*Dashboards*

Wenn ein(e) Benutzende(r) einen Bericht in einem Dashboard aufruft und versucht, den Filter, die Gruppierung oder die Ansicht des Berichts zu ändern, ändert sich der Filter, die Gruppierung oder die Ansicht nicht.

**Beim Erstellen eines Projekts erscheint der Fehler „[!UICONTROL Sie müssen Systemadministrator sein]“**

*Projekte*

Wenn ein(e) Benutzende(r) ohne Administratorrechte versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, in dem ein Bereich nur für Administratoren bzw. Administratorinnen zugänglich ist, kann er/sie das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

„[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]“

**Benutzerdefinierte Daten werden beim Konvertieren eines Problems in ein Projekt nicht beibehalten**

*Projekte*

Wenn ein(e) Benutzende(r) ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, werden die Daten aus einem benutzerdefinierten Formular für das Problem nicht in das entsprechende benutzerdefinierte Formular im Projekt übertragen. Dies geschieht bei Daten in benutzerdefinierten Feldern, die basierend auf den Werten in anderen benutzerdefinierten Feldern ausgeblendet sein könnten.

**Fehler beim Konvertieren eines Problems in ein Projekt**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein Problem in ein Projekt zu konvertieren, wird das Problem nicht konvertiert und der folgende Fehler wird angezeigt:

„[!UICONTROL Unerwarteter Fehler]“

+++


## Updates im Januar 2022

+++**Wartungs-Update vom 27. Januar 2022**

**Benutzerdefinierte Daten werden beim Konvertieren eines Problems in ein Projekt nicht beibehalten**

*Projekte*

Wenn ein(e) Benutzende(r) ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, werden die Daten aus einem benutzerdefinierten Formular für das Problem nicht in das entsprechende benutzerdefinierte Formular im Projekt übertragen. Dies geschieht bei Daten in benutzerdefinierten Feldern, die basierend auf den Werten in anderen benutzerdefinierten Feldern ausgeblendet sein könnten.

**Die Benutzerliste auf dem Agile-Board ist nicht in alphabetischer Reihenfolge**

*Agile*

Wenn ein(e) Benutzende(r) die Benutzerliste auf einem Agile-Board aufruft, werden die Benutzenden nicht in alphabetischer Reihenfolge angezeigt. Stattdessen werden die Benutzenden mit den meisten Arbeitsaufträgen zuerst aufgelistet.

**Links zum Kopieren und Verschieben von Problemen wurden aktualisiert**

*Anfragen*

In der Vorschau-Umgebung wurden die Links zum Kopieren und Verschieben von Problemen sowohl auf der Problem-Seite als auch in der Problem-Liste in „[!UICONTROL Kopieren nach]“ und „[!UICONTROL Verschieben nach]“ geändert.

**Hinzufügen von bis zu 45 IP-Adressen zur [!DNL Workfront] Zulassungsliste**

*Einrichtung*

Das Limit für IP-Adressen, die zur [!DNL Workfront]-Zulassungsliste hinzugefügt werden können, wurde von 30 auf 45 erhöht.

+++

+++**Wartungs-Update vom 20. Januar 2022**

**Fehler „[!UICONTROL Ungültiger Parameter]“ beim Erstellen eines Projekts aus einer Vorlage**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein Projekt aus einer Vorlage zu erstellen und beim Erstellen des Projekts ein benutzerdefiniertes Formular aus der Vorlage entfernt, wird das Projekt nicht erstellt und die Fehlermeldung „[!UICONTROL Ungültiger Parameter]“ wird angezeigt, in der auf ein Pflichtfeld im entfernten benutzerdefinierten Formular hingewiesen wird.

**Benutzerliste wird nicht in [!DNL Safari]-Browser geladen**

*Benutzer*

Wenn ein(e) Benutzende(r) zum Bereich [!UICONTROL Benutzende] wechselt, wird die Kopfzeile angezeigt, die Benutzerliste wird aber nicht geladen.

**Verzögerung beim Verschieben von Aufgaben in einer Liste führt dazu, dass Aufgaben an einer falschen Position abgelegt werden**

*Listen*

Wenn ein(e) Benutzende(r) versucht, eine Aufgabe durch Ziehen in einer Liste zu verschieben, bewegt sich die blaue Linie, die angibt, wohin die Aufgabe verschoben wird, viel langsamer als der Cursor. Wenn der/die Benutzende die Aufgabe ablegt, wird sie an die Position der blauen Linie verschoben, auch wenn der Cursor auf eine andere Position in der Liste zeigt.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update vom 14. Januar 2022**

**Einige zugeordnete Felder werden bei Auswahl eines [!UICONTROL neuen zuzuordnenden Felds zurückgesetzt]**

*[!DNL Workfront Fusion]*

Wenn für mindestens ein Feld im Modul [!UICONTROL Erstellen] oder [!UICONTROL Aktualisieren] von [!DNL Workfront] die Zuordnung aktiviert ist und ein(e) Benutzende(r) ein neues Feld zum Zuordnen auswählt, verschwinden in den zuvor zugeordneten Feldern, für die die Zuordnung aktiviert ist, die Zuordnungswerte.

+++

+++**Wartungs-Update vom 13. Januar 2022**

**Es ist nicht möglich, zu einem Kommentar im Bedienfeld „Zusammenfassung“ einen Hyperlink hinzuzufügen**

*Aufgaben*

Wenn ein(e) Benutzende(r) im Zusammenfassungsfenster einer Aufgabe einen Kommentar abgibt und versucht, dem Kommentar einen Hyperlink hinzuzufügen, wird das Hyperlink-Fenster geöffnet. Doch wenn der/die Benutzende in das Fenster klickt, wird es geschlossen und er/sie kann keinen Hyperlink hinzufügen. Wenn ein(e) Benutzende(r) das Fenster auswählt, kann er/sie einen Link in das Feld eintippen oder einkopieren, doch der Hyperlink wird nicht gespeichert. In beiden Fällen wird die Aufgabe deaktiviert.

**Seite „Team bearbeiten“ wird nicht geschlossen**

*Teams*

Wenn ein(e) Benutzende(r) versucht, ein Team zu bearbeiten, wird die Seite [!DNL Edit team] nicht geschlossen. Der/die Benutzende kann die Seite nicht schließen, indem er auf eine der Schaltflächen klickt, auf das X klickt oder die Seite verlässt.

**E-Mail- und In-App-Benachrichtigungen werden nicht gesendet**

*Benachrichtigungen*

Wenn ein Ereignis eintritt, das den Versand einer Benachrichtigung auslösen sollte, wird die Benachrichtigung nicht gesendet. Dies kann auch dann bei E-Mail- oder In-App-Benachrichtigungen auftreten, wenn andere Benachrichtigungen gesendet werden.

**[!UICONTROL Liste „Meine Arbeit“] erscheint leer**

*[!UICONTROL Meine Arbeit]*

Wenn ein(e) Benutzende(r) seine/ihre Liste [!UICONTROL Meine Arbeit] aufruft und die Layout-Vorlage für die Liste [!UICONTROL Meine Arbeit] einen numerischen Wert enthält, z. B. [!UICONTROL Prozent abgeschlossen], wird die Liste [!UICONTROL Meine Arbeit] nicht angezeigt.

**[!UICONTROL Prozent abgeschlossen] und [!UICONTROL Stunden abgeschlossen] können im Agile-Board nicht geändert werden**

*Agile*

Wenn ein(e) Benutzende(r) auf einem Agile-Board „[!UICONTROL Weiterer Arbeitselemente anzeigen]“ auswählt und dann versucht, [!UICONTROL Prozent abgeschlossen] oder [!UICONTROL Stunden abgeschlossen] für eines der neu geladenen Arbeitselemente zu ändern, können diese Werte nicht geändert werden. Die Schaltfläche [!UICONTROL Prozent abgeschlossen] ist außerdem grau, was bedeutet, dass sie inaktiv ist.

+++

+++**Wartungs-Update vom 6. Januar 2022**

**Fehler „[!UICONTROL Ungültiger Parameter]“ beim Anhängen von Vorlagen oder benutzerdefinierten Formularen an Projekte**

*Projekte*

Wenn ein(e) Benutzende(r) versucht, ein benutzerdefiniertes Formular oder eine Vorlage an ein vorhandenes Projekt anzuhängen, dann die Pflichtfelder im benutzerdefinierten Formular oder in der benutzerdefinierten Vorlage ausfüllt und die Änderungen am Projekt speichert, werden die Änderungen nicht gespeichert und die Fehlermeldung „[!UICONTROL Ungültiger Parameter]“ wird oben auf der Projektdetailseite angezeigt.

**Kommentare zu Korrekturabzügen werden in Dokumentaktualisierungen nicht angezeigt**

*Korrekturabzüge*

Wenn ein(e) Benutzende(r) im Bereich [!UICONTROL Dokumente] einen Korrekturabzug aufruft, werden im Bereich [!UICONTROL Aktualisierungen] des Dokuments keine Kommentare zum Korrekturabzug selbst angezeigt.

**[!UICONTROL Workload Balancer]: „[!UICONTROL ?[objekt Objekt]?]„ wird in Information bei übermäßiger Zuordnung angezeigt**

*[!UICONTROL Lastenausgleich]*

Wenn für eine(n) Benutzende(n) im [!UICONTROL Workload Balancer] eine übermäßige Zuordnung von Aufgaben angezeigt wird, da sich eine Aufgabe mit dem Urlaub eines/r Benutzenden überschneidet, und ein(e) andere(r) Benutzende(r) die übermäßige Zuordnung aufruft, wird im Bereich „[!UICONTROL Kapazität]“ der Zuordnungsinformation „[!UICONTROL ?[objekt Objekt]?]“ anstelle der tatsächlichen Kapazität des/r Benutzenden angezeigt.

+++

## Frühere Wartungs-Updates

Informationen zu früheren Wartungs-Updates finden Sie hier:

* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2021](2021-updates.md)
