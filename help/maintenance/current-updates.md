---
title: Workfront-Wartungs-Updates
description: Wartungsupdates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 6ce6194f9f911b02457240645ce6407ec3eb7e26
workflow-type: tm+mt
source-wordcount: '13915'
ht-degree: 3%

---

# [!DNL Workfront] Wartungsaktualisierungen

Die folgenden Wartungsaktualisierungen wurden 2022 vorgenommen.

>[!NOTE]
>
>Diese Aktualisierungen umfassen auch andere kleinere oder weniger auffällige Fehlerbehebungen. [!DNL Workfront] Der Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Informationen zu Wartungsupdates vor 2022 finden Sie unter [Frühere Wartungsupdates](#previous-maintenance-updates)

## Aktualisierungen im Oktober 2022

+++**Wartungs-Update am 6. Oktober 2022**

**Neuer Blueprint-Typ**

*Blueprints*

Der Blueprint-Typ &quot;Dashboard&quot; wurde dem Blueprint-Katalog hinzugefügt. Zuvor waren nur Projektvorlagen und Blueprints für die Organisationsstruktur verfügbar.

**Elemente, die sich im linken Bereich überschneiden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer im Formular-Builder arbeitet und das Formular mehr als 100 Felder enthält, führt die Meldung, die den Benutzer über die Feldbegrenzung informiert, dazu, dass sich die Elemente im linken Bereich überschneiden.

**Die Datumsauswahl wird nicht mehr automatisch beim Eingabefokus oder Klick geöffnet**

*Navigation*

Wenn ein Benutzer über die Tastatur navigiert, werden die Datumsauswahl bei der Datumseingabe, die den Tastaturfokus erhält, nicht mehr automatisch geöffnet. Stattdessen sollten Tastaturbenutzer die Registerkarte zum Datumsauswahlsymbol öffnen und die Eingabetaste drücken, um die Datumsauswahl zu öffnen. Wenn ein Benutzer mit der Maus navigiert, werden die Datumsauswahl bei angeklickter Datumseingabe nicht mehr automatisch geöffnet. Stattdessen sollten Mausbenutzer auf das Datumsauswahlsymbol klicken, um die Datumsauswahl zu öffnen.

Diese Änderung wurde vorgenommen, um besser mit den Standard-UX-Mustern für die Datumsauswahl übereinzustimmen und ein barrierefreies Erlebnis für Benutzer von Tastatur und Bildschirmlesehilfe zu schaffen.

**Das Zuweisen mehrerer Teams führt dazu, dass nur ein Team zugewiesen ist**

*Teams*

>[!NOTE]
>
>Dieses Problem tritt nur in der Vorschau -Umgebung auf.

Wenn ein Benutzer einer Aufgabe oder einem Problem mehrere Teams zuweist, wird nur ein Team in der Zuweisungsliste angezeigt. Dieses Problem betrifft auch die Berichterstellung. Berichte mit Teamzuweisungen sind ungenau, da nur ein Team als der Aufgabe oder dem Problem zugewiesen angezeigt wird.

**&quot;[!UICONTROL Ihre letzten Änderungen wurden nicht gespeichert.]&quot;-Fehler beim automatischen Speichern von Änderungen in einem Timesheet**

*Arbeitszeit- tabellen*

Wenn ein Benutzer versucht, ein Timesheet so zu bearbeiten, dass die Änderungen automatisch gespeichert und Trigger werden, werden die Änderungen nicht gespeichert und der Benutzer sieht die folgende Meldung:

&quot;[!UICONTROL Ihre letzten Änderungen wurden nicht gespeichert. Aktualisieren Sie die anzuzeigende Seite.]&quot;

Dies wurde beim Bearbeiten der folgenden Elemente berichtet:

* Stunden
* Aufgaben

**E-Mail-Benachrichtigungen werden verzögert**

*Workfront-Korrekturabzug*

Wenn ein Ereignis in [!DNL Workfront Proof] Wenn eine E-Mail-Benachrichtigung Trigger wird, erhält der Benutzer die Benachrichtigung nicht sofort. Die Benachrichtigung kann um mehrere Stunden verzögert werden.

+++

+++**Wartungs-Update am 3. Oktober 2022**

**Speichern Sie Ihr Timesheet manuell, wenn sich die vorherigen Vorgangsrollen geändert haben.**

*Arbeitszeit- tabellen*

Wenn sich die Rolle des Auftrags, für den Sie die Zeit protokolliert haben, geändert hat und die [!UICONTROL Manuelles Zuweisen von Auftragsrollen zu Stundeneinträgen] -Einstellung deaktiviert wurde, müssen Sie Ihre Zeiteinträge manuell speichern, bis Stunden nicht mehr für die geänderte Vorgangsrolle protokolliert werden.

+++

## Aktualisierungen im September 2022

+++**Wartungs-Update am 29. September 2022**

**Benutzer kehrt beim Schließen des Testversands nicht zur vorherigen Seite zurück**

*Korrekturabzüge*

Wenn ein Benutzer einen Testversand in [!DNL Workfront] den Testversand schließt, gibt er nicht die Seite zurück, auf der er sich vor dem Öffnen des Testversands befand. Stattdessen werden sie zu einer anderen Seite in [!DNL Workfront].

**Der Testversand kann nicht geöffnet werden in[!DNL Workfront]**

*Korrekturabzüge*

Wenn ein Benutzer ein Dokument in [!DNL Workfront] und versucht, den Testversand zu öffnen, wird der Testversand nicht geöffnet und der Benutzer wird an die [!UICONTROL Dokumentdetails] Seite.

**Bei Verwendung von [!UICONTROL Registerkarte] key**

*Arbeitszeit- tabellen*

Wenn ein Benutzer ein Zeitblatt ausfüllt und zwischen Zellen mit der [!UICONTROL Registerkarte] -Taste, werden die Stunden nicht gespeichert. Die [!UICONTROL Automatisches Speichern] -Benachrichtigung wird unten im Bildschirm nicht angezeigt. Wenn der Benutzer die Seite aktualisiert, kann er sehen, wie die Stunden nicht gespeichert wurden.

**Leere Seiten bei der Anzeige eines Testversands mit mehreren Seiten**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einen Testversand mit mehreren Seiten anzeigt, kann er Miniaturansichten der Seiten sehen, die Seiten werden jedoch nicht im Hauptansichtsfenster geöffnet.



+++

+++**Wartungs-Update am 22. September 2022**

**Benutzerkarte kann nicht im Aktualisierungsstream geschlossen werden**

*Updates*

Wenn ein Benutzer Aktualisierungen anzeigt und den Mauszeiger über einen Namen bewegt, wird eine Karte mit Details zum Benutzer, dessen Name geöffnet wird und nicht automatisch geschlossen wird, angezeigt. Die Seite reagiert erst, wenn die Karte manuell geschlossen wird, indem Sie auf das X in der oberen rechten Ecke klicken.

+++

+++**Wartungs-Update am 15. September 2022**

**&quot;[!UICONTROL Jemand anders hat versucht, dieses Projekt zu speichern]&quot;-Fehler bei Eingabe der Stunden**

*Arbeitszeit- tabellen*

Wenn ein Benutzer versucht, Stunden für eine Aufgabe auf seinem Zeitblatt zu protokollieren, werden die Stunden nicht automatisch gespeichert und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Hinweis: Das Speichern ist fehlgeschlagen, da ein anderer Benutzer gleichzeitig versucht hat, dieses Projekt zu speichern. Versuchen Sie erneut, das Projekt zu speichern.]&quot;

**Benutzerkarte kann nicht im Aktualisierungsstream geschlossen werden**

*Updates*

Wenn ein Benutzer Aktualisierungen anzeigt und den Mauszeiger über einen Namen bewegt, wird eine Karte mit Details zum Benutzer, dessen Name geöffnet wird und nicht automatisch geschlossen wird, angezeigt. Die Seite reagiert erst, wenn die Karte manuell geschlossen wird, indem Sie auf das X in der oberen rechten Ecke klicken.

**Die &quot;[!UICONTROL Aufgabenrollenzuweisung]&quot; wurde in &quot;[!UICONTROL Rollenzuweisung]&quot; bei der Zuweisung von Aufgaben in großen Mengen mithilfe der [!UICONTROL Lastenausgleich]**

*[!UICONTROL Workload Balancer]*

Um die neue Funktion widerzuspiegeln, mit der sowohl Aufgaben als auch Probleme stapelweise über die [!UICONTROL Nicht zugewiesene Arbeit] wurde in[!UICONTROL Aufgabenrollenzuweisung]&quot;-Feld in &quot;[!UICONTROL Rollenzuweisung]&quot; in der [!UICONTROL Lastenausgleich]. Das Feld bezieht sich auf Vorgangsrollen, die Aufgaben oder Problemen zugewiesen wurden, und wird beim Zuweisen von Benutzern zu Elementen im [!UICONTROL Massenzuweisungen] ankreuzen.

+++

+++**[!DNL Workfront Scenario Planner]Wartungs-Update am 15. September 2022**

**Für eine Gruppe freigegebene Filter wird nun im [!DNL Scenario Planner]s  [!UICONTROL Projekte importieren] Liste für Mitglieder aller Untergruppen**

*[!DNL Workfront Scenario Planner]*

Wenn Sie nun einen Projektfilter für eine Gruppe mit zusätzlichen Untergruppen freigeben, ist der Filter für alle Gruppen- und Untergruppenmitglieder sichtbar, die Projekte im [!UICONTROL Projekte importieren] im Feld eines Plans [!DNL Scenario Planner].

+++

+++**Wartungs-Update am 8. September 2022**

**Aktualisierte Namen, die für die Benutzer- und Rollenzuweisungsfelder zurückgesetzt wurden**

*Zuweisungen*

Die in der letzten Woche vorübergehend umbenannten Zuweisungsfelder wurden auf ihre ursprünglichen Namen zurückgesetzt:

* [!UICONTROL Arbeitsauftrag – Benutzer]
* [!UICONTROL Arbeitsauftrag – Aufgabengebiete]

**Fehler beim Entfernen des Projekteigentümers aus der Kopfzeile**

*Projekte*

Wenn ein Benutzer versucht, eine [!UICONTROL Projektinhaber] aus der Kopfzeile eines Projekts, die [!UICONTROL Projektinhaber] nicht entfernt wurde und dem Benutzer die folgende Fehlermeldung angezeigt wird:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Neu [!UICONTROL Beschreibung] zurück in die Originalgröße**

*Projekte, Aufgaben und Probleme*

Wenn ein Benutzer die Größe [!UICONTROL Beschreibung] im Detailbereich eines Arbeitselements klicken, um es zu vergrößern, und dann mit der Eingabe in das Feld beginnen, kehrt die Originalgröße des Feldes zurück. Der Benutzer kann weiterhin das Feld eingeben und die Inhalte wie erwartet speichern

**Unbeabsichtigtes Beenden beim Erstellen von Aufgaben oder Problemen**

*Aufgaben und Probleme*

Wenn ein Benutzer eine Aufgabe oder ein Problem in einem Projekt erstellt und außerhalb des Erstellungs-Popup klickt, wird das Popup ohne Warnung geschlossen und alle zuvor eingegebenen Informationen gehen verloren.

**Die Möglichkeit, einen Testversand per E-Mail an eine Dropzone zu senden, wurde entfernt**

*[!DNL Workfront Proof]*

Ab Donnerstag, 8. September 2022 haben wir die Möglichkeit entfernt, einen Testversand per E-Mail an eine Dropzone im Standalone-Modus zu senden [!DNL Workfront Proof] Produkt.

Sie können weiterhin Dropzones auf andere Weise verwenden, um neue Testsendungen und neue Versionen von Testsendungen an Ihr Konto zu senden, ohne sich bei Ihrem Konto anmelden zu müssen. Siehe [Die Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) für weitere Informationen.

+++

+++**Wartungs-Update am 6. September 2022**

**Zur Liste der Felder für anpassbare Projekt-Header hinzugefügte Datumsangaben**

*Projekte*

Wir haben die [!UICONTROL Projiziertes Startdatum] und [!UICONTROL Voraussichtlicher Abschluss] in die Liste der Felder für anpassbare Projekt-Header bei Verwendung einer Layoutvorlage.

**Neues Limit mit einer Bestätigungsnachricht, die die Anzahl der zu einem Timesheet hinzugefügten Elemente anzeigt**

*Arbeitszeit- tabellen*

Wenn Sie mehr als 50 Elemente auswählen, die Sie einem Zeitblatt hinzufügen möchten, erhalten Sie jetzt eine Bestätigungsnachricht, die die Anzahl der Elemente anzeigt, die zum Zeitblatt hinzugefügt werden sollen. Außerdem erhalten Sie die Möglichkeit, den Kurs zu ändern und nicht alle Elemente hinzuzufügen. Alle hinzugefügten Elemente werden automatisch in das Timesheet eingefügt und müssen manuell aus den aktuellen und allen zukünftigen Timesheets entfernt werden.

+++

+++**Wartungs-Update am 2. September 2022**

Fügen Sie die [!UICONTROL Integrationen] -Feld in der benutzerdefinierten Kopfzeile des Projekts

*Integrationen*

Sie können jetzt die [!UICONTROL Integrationen] -Feld zum benutzerdefinierten Header eines Projekts hinzufügen, wenn Sie eine Layoutvorlage verwenden. Nach dem Hinzufügen zeigt das Feld einen Link zu einem externen Element an, das mit dem Projekt verknüpft ist, das sich unter [!DNL Salesforce] oder [!DNL Anaplan]- abhängig von Ihrer Integration.

>[!NOTE]
>
>Dieses Wartungsupdate wurde zuvor am 25. August 2022 in der Vorschau-Umgebung veröffentlicht und befindet sich jetzt in der Produktion.

+++

+++**Wartungs-Update am 1. September 2022**

**Abgeschlossene Elemente aus der Zuweisung entfernt**

*Delegierungen*

Jetzt werden nur unvollständige Elemente, deren Daten mit den Daten einer Delegation übereinstimmen, an andere Benutzer delegiert, wenn die Zuweisung von Arbeitselementen beginnt. Wenn die Elemente vor dem Beginn der Delegation abgeschlossen wurden, werden sie nicht delegiert. Elemente, die während des Zeitrahmens der Delegierung ausgefüllt werden, bleiben für den Delegierten und den Verantwortlichen zwei Wochen lang auf der Arbeitsliste des Heimbereichs, bevor sie automatisch entfernt werden, sofern die Delegation in diesen Wochen nicht beendet wurde.

**Metadatenaktualisierungen für die [!DNL Adobe Workfront] für [!DNL Experience Manager Assets] und [!DNL Assets Essentials] Integrationen**

*Integrationen*

Metadaten werden automatisch übergeben, wenn Sie ein Asset zu einem verknüpften Ordner hinzufügen.

Zuvor wurden Metadaten nur gepusht, wenn Sie ein Asset mit dem [!UICONTROL Neu hinzufügen] Dropdown-Menü.

**Stunden für ein Problem können nicht genehmigt oder abgelehnt werden**

*Anfragen*

Wenn ein Benutzer versucht, Stunden für die [!UICONTROL Stunden] Registerkarte eines Problems, die [!UICONTROL Genehmigen] und [!UICONTROL Ablehnen] -Schaltflächen fehlen.

**Beim Konvertieren eines Problems in ein Projekt mit einer Vorlage wird eine falsche Fehlermeldung angezeigt**

*Anfragen*

Wenn ein Problem mithilfe einer Vorlage in ein Projekt konvertiert wird und ein Fehler auftritt, wird dem Benutzer eine Seite mit der Meldung &quot;[!UICONTROL Das Projekt existiert nicht mehr]&quot; anstelle der korrekten Fehlermeldung, die die Ursache der fehlgeschlagenen Konvertierung erklärt.

**Testversand für Dateien mit mehr als 1,5 GB nicht möglich**

*[!DNL Workfront Proof]*

Wenn ein Benutzer beim Erstellen eines neuen Testversands eine Datei mit mehr als 1,5 GB hochlädt, wird der Dateiname rot und der Testversand kann nicht erstellt werden.

+++

## Aktualisierungen im August 2022

+++**Wartungs-Update am 25. August 2022**

**Links zum Arbeitslastausgleich werden in Dashboards falsch angezeigt**

*Dashboards*

Die Links für den Lastenausgleich für die gemeinsame Nutzung werden beim Hinzufügen zu einem Dashboard als externe Seite falsch angezeigt. Anstatt die eindeutige(n) Ansicht(en)/Filter zu verwenden, die mit dem Link verknüpft sind, verwendet das Dashboard die zuletzt angewendete Ansicht(en) für den Arbeitslastausgleich.

**Fügen Sie die [!UICONTROL Integrationen] -Feld in der benutzerdefinierten Kopfzeile des Projekts**

*Projekte*

Sie können jetzt die [!UICONTROL Integrationen] -Feld zum benutzerdefinierten Header eines Projekts hinzufügen, wenn Sie eine Layoutvorlage verwenden. Nach dem Hinzufügen zeigt das Feld einen Link zu einem externen Element an, das mit dem Projekt verknüpft ist, das sich unter [!DNL Salesforce] oder [!DNL Anaplan]- abhängig von Ihrer Integration.

>[!NOTE]
>
>Dieses Wartungsupdate befindet sich derzeit nur in der Umgebung &quot;Vorschau&quot;. Er wird eine Woche nach der Vorschau-Veröffentlichung für die Produktion freigegeben.

**Benutzerdefinierte Daten werden beim Konvertieren eines Problems in ein leeres Projekt nicht beibehalten**

*Projekte*

Wenn ein Benutzer ein Problem in ein leeres Projekt konvertiert (ohne Vorlage), werden Daten in berechneten Feldern nicht an das neue Projekt übertragen.

**Fehler &quot;Timeline-Planungsmodus&quot; beim Ändern eines Datums in einem Projekt**

*Projekte*

Wenn ein Benutzer versucht, ein Datum in einem Projekt zu ändern, das die [!UICONTROL Planmodus] auf [!UICONTROL Manuelles Speichern] > [!UICONTROL Timeline-Planung], ändert sich das Datum nicht und der Benutzer sieht einen Fehler.

&quot;[!UICONTROL Der Timeline-Planungsmodus ist nur verfügbar, wenn timelineDate geladen wird. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

**Konsistenz beim Öffnen des Workload Balancer mithilfe der Monatsansicht**

*Lastenausgleich*

Jetzt zeigt der Lastenausgleich die zugewiesenen Elemente der Benutzer an, die bei der Anzeige im [!UICONTROL Tag], [!UICONTROL Woche]oder [!UICONTROL Monat] Ansichten. Vor dieser Aktualisierung wurden die zugewiesenen Elemente für die [!UICONTROL Tag] und [!UICONTROL Woche] Ansichten und reduzierte für die [!UICONTROL Monat] anzeigen.


+++

+++**Wartungs-Update am 18. August 2022**

**&quot;[!UICONTROL Zu Iteration hinzufügen]&quot; und &quot;[!UICONTROL Hinzufügen zum Kanban Board]&quot;Optionen sind bei der Inline-Bearbeitung von Aufgaben in einem Bericht nicht verfügbar**

*Berichte*

Wenn ein Benutzer eine Liste von Aufgaben in einem Bericht anzeigt und die [!UICONTROL Mehr] Menü (mit drei Punkten), das[!UICONTROL Zu Iteration hinzufügen]&quot; und &quot;[!UICONTROL Hinzufügen zum Kanban Board]Die Optionen sind im Dropdown-Menü nicht verfügbar. Wenn der Bericht in einem Dashboard angezeigt wird, wird die[!UICONTROL Zu Iteration hinzufügen]&quot; und &quot;[!UICONTROL Hinzufügen zum Kanban Board]Die Optionen sind im Dropdown-Menü verfügbar.

**Matrix-Berichte werden beim Scrollen falsch angezeigt**

*Berichte*

Wenn ein Benutzer einen Matrix-Bericht anzeigt und scrollt, können sich einige visuelle Elemente des Berichts überschneiden oder duplizieren.

**[!UICONTROL Milestone] Aus der Timesheets-Projektliste entfernte Ansicht**

*Arbeitszeit- tabellen*

Die [!UICONTROL Milestone] wurde beim Hinzufügen eines Projekts aus der Timesheet-Projektliste entfernt.

**Hyperlinks in einem interaktiven Testversand sind nicht aktiv**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einen interaktiven Testversand anzeigt und auf einen Link oder eine Schaltfläche klickt, die einen Link enthält, wird der Benutzer nicht zu der Seite weitergeleitet, auf die der Link oder die Schaltfläche verweist.

**Neue Felder für fehlende Testseiten**

*[!DNL Workfront Proof]*

Im [!DNL New Proof] -Seite, werden viele Textfelder nicht angezeigt (einschließlich Feldbezeichnungen, Dropdown-Optionen und Checkbox-Namen).

**Benutzer erhalten keine Benachrichtigungen, wenn sie in einem Testversand getaggt werden**

*[!DNL Workfront Proof]*

Wenn ein Benutzer in einem Testversand-Kommentar getaggt wird, erhält er keine E-Mail-Benachrichtigung über den Kommentar.

+++

+++**Wartungs-Update am 12. August 2022**

**Neues anpassbares Kopfzeilenfeld am Anfang der Kopfzeile hinzugefügt**

*Kopfzeilen*

Wenn Sie ein neues Feld zu einer anpassbaren Kopfzeile hinzufügen, wird das Feld jetzt als erstes Feld links in der Kopfzeile oder direkt nach dem [!UICONTROL Suche] in der Layout-Vorlage. Vor dieser Änderung wurde das Feld als letztes Feld in der Kopfzeile hinzugefügt.

+++

+++**Wartungs-Update am 11. August 2022**

**Benutzerdefinierte Formulare können aufgrund einer falschen Zeichenbeschränkung für beschreibende Textfelder nicht bearbeitet werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer versucht, ein benutzerdefiniertes Formular zu bearbeiten, und dieses benutzerdefinierte Formular über eine [!UICONTROL Beschreibender Text] -Feld, das derzeit mehr als 512 Zeichen enthält, kann der Benutzer die Änderungen nicht im benutzerdefinierten Formular speichern. Der folgende Fehler tritt auf:

&quot;Die folgenden Felder sind ungültig: (Feld) ist zu lang, max. 512&quot;

Diese Auswirkungen [!UICONTROL Beschreibender Text] Felder, die zuvor gut funktioniert haben, obwohl sie mehr als 512 Zeichen enthalten.

**Daten in Feldern, die nach Abschnittsumbruch ausgeblendet werden, bleiben beim Konvertieren eines Problems in ein Projekt nicht erhalten**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer ein Problem in ein Projekt konvertiert und das Problem ein benutzerdefiniertes Formular mit Daten in einem Abschnittsumbruch enthält, die mithilfe der Anzeigerogik ausgeblendet werden können, werden die Daten in diesem Abschnitt nicht an das neue Projekt übertragen.

**Daten in Feldern, die nach Abschnittsumbruch ausgeblendet werden, bleiben beim Konvertieren einer Anforderung in ein Projekt nicht erhalten**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer eine Anforderung in ein Projekt konvertiert und die Anforderung ein benutzerdefiniertes Formular mit Daten in einem Abschnittsumbruch enthält, die mithilfe der Anzeigerogik ausgeblendet werden können, werden die Daten in diesem Abschnitt nicht an das neue Projekt übertragen.

**Benutzerdefinierte Formulare können aufgrund des Textfelds &quot;Beschreibender Text&quot;nicht bearbeitet werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer versucht, ein benutzerdefiniertes Formular zu bearbeiten, das ein Feld mit beschreibendem Text enthält, wird die Feldbeschriftung nicht ausgefüllt. Der Benutzer sieht den Fehler &quot;[!UICONTROL Dieses Feld ist erforderlich]&quot; unter dem Beschriftungsfeld ein, und der Benutzer kann das benutzerdefinierte Formular aufgrund dieses Fehlers nicht bearbeiten.

**Anweisungen können nicht aus einem benutzerdefinierten Feld im benutzerdefinierten Formular-Builder entfernt werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer ein benutzerdefiniertes Feld bearbeitet und versucht, vorhandenen Text im [!UICONTROL Anweisungen] -Bereich, wird der Text beim Speichern des Felds nicht entfernt. Der Benutzer kann Text bearbeiten, aber nicht vollständig entfernen.

**Teamzuweisung beim Erstellen einer Anforderung wird nicht in der neuen Anforderung angezeigt**

*Anforde- rungen*

Wenn ein Benutzer eine Anforderung erstellt und der Anforderung ein Team zuweist und dann die Anforderung sendet, wird das Team der erstellten Anforderung nicht zugewiesen. Dies wirkt sich nur auf die Teamzuweisung aus. Benutzerzuweisungen funktionieren erwartungsgemäß.

+++

+++**Wartungs-Update am 4. August 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis.

Alle [!DNL Workfront Classic] wurde am 14. Juli 2022 entfernt.

**Fehler beim Ändern des geplanten Abschlussdatums in der Kopfzeile einer Aufgabe oder eines Problems**

*Aufgaben und Probleme*

Wenn ein Benutzer versucht, die [!UICONTROL Geplantes Abschlussdatum] in der Kopfzeile einer Aufgabe oder eines Problems wird das Datum nicht geändert und der Benutzer sieht einen Fehler ähnlich dem folgenden:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Aktualisierungen im Juli 2022

+++**Wartungs-Update am 28. Juli 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis.

Alle [!DNL Workfront Classic] wurde am 14. Juli 2022 entfernt.

**Fehler beim Öffnen eines Elements über [!UICONTROL Homepage-Arbeitsliste]**

*[!UICONTROL Startseite]*

Wenn ein Benutzer versucht, ein Element auf seiner [!UICONTROL Homepage-Arbeitsliste], wird das Element nicht geöffnet und der Benutzer sieht die folgende Nachricht:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten, und wir arbeiten daran, das Problem zu beheben. Um mit Ihrer Arbeit fortzufahren, aktualisieren Sie diese Browser-Seite.]&quot;

**Aufgaben und Probleme, die einem Benutzer zugewiesen wurden, werden nicht in der Startseiten-Arbeitsliste des Benutzers angezeigt**

*[!UICONTROL Startseite]*

Wenn der Benutzer die [!UICONTROL Homepage-Arbeitsliste], werden alle dem Benutzer zugewiesenen Aufgaben oder Probleme nicht in der Liste aufgeführt und dem Benutzer sind die Delegationen möglicherweise nicht bekannt.

**Geplante Berichte werden nicht an alle Empfänger gesendet**

*Berichte*

Wenn ein terminierter Bericht gesendet wird, wird er nicht an alle Benutzer in der[!UICONTROL Senden an]&quot;. Die ausgesetzten Benutzer sind zufällig und können bei jedem Versand des Berichts variieren.

**[!UICONTROL Auswahl von Aufgaben beim Anhängen einer Vorlage nicht aufheben]**

*Vorlagen*

Wenn ein Benutzer eine Vorlage anhängt und anpasst, wird er aufgefordert, die Auswahl der Aufgaben aufzuheben, die er nicht einbeziehen möchte. Keine der Aufgaben wird jedoch als ausgewählt angezeigt und der Benutzer kann die Auswahl nicht aufheben.

**Felder vom Typ &quot;Gebietsschema&quot;haben jetzt spezifischere Bezeichnungen**

*Terminologie*

So erstellen Sie die Funktion des[!UICONTROL Gebietsschema]&quot;-Felder klarer, wir haben ihre Titel aktualisiert.

* Die &quot;[!UICONTROL Gebietsschema]&quot;-Feld im Benutzerprofil ist jetzt mit &quot;[!UICONTROL Gebietsschema der E-Mail]&quot;
* Die &quot;[!UICONTROL Gebietsschema]&quot;-Feld im [!UICONTROL Einrichtung] >[!UICONTROL System] >[!UICONTROL Kundeninformationen] Bereich ist jetzt mit &quot;[!UICONTROL Standard-E-Mail-Gebietsschema]&quot;

Die Funktionalität dieser Felder hat sich nicht geändert.

**Probleme beim Erstellen von Timesheets**

*Arbeitszeit- tabellen*

Die folgenden Probleme wurden bezüglich der Erstellung von Timesheets gemeldet:

* Wenn ein Benutzer versucht, ein Timesheet für eine Rolle zu erstellen, wird das Timesheet nicht erstellt und der Benutzer sieht den Fehler &quot;[!UICONTROL Benutzer mit Primärschlüsselwerten &quot;XXXXXXXXXXXXX&quot;nicht gefunden.]&quot;
* Wenn ein Benutzer versucht, ein Timesheet für ein Team zu erstellen, wird die [!UICONTROL typeahead] -Feld wird nicht mit Teams aufgefüllt und die [!UICONTROL Erstellen eines Zeitplans] -Schaltfläche deaktiviert ist.


**Gebiete von [!DNL Workfront Proof] nicht aktualisieren, wenn ein Testversand erstellt, verschoben oder archiviert wird**

*[!DNL Workfront]Korrekturabzug*

Beim Testversand treten derzeit Indizierungsverzögerungen auf. Dies kann sich auf das Benutzererlebnis auswirken, z. B. auf Folgendes:

* In Dashboards wird nicht die richtige Anzahl von Testsendungen angezeigt
* Ordner werden beim Erstellen oder Verschieben eines Testversands nicht aktualisiert
* Archivierte Testsendungen bleiben auf aktiven Testversandlisten.

+++

+++**Wartungs-Update (Hotfix) am 26. Juli 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis.

Alle [!DNL Workfront Classic] wurde am 14. Juli 2022 entfernt.

**Die auf dem Timesheet angezeigten Stunden unterscheiden sich von der Timesheets-Liste**

*Arbeitszeit- tabellen*

Wenn ein Benutzer ein Timesheet öffnet, um es anzuzeigen, unterscheiden sich die angezeigten Stunden von denen, wenn der Benutzer dasselbe Timesheet in einer Timesheet-Liste anzeigt.


**In ein Projekt konvertierte Anforderung mit Vorlage zeigt Gruppe aus Anforderungswarteschlange, nicht Gruppe aus Vorlage**

*Anforde- rungen*

Wenn ein Benutzer eine Anforderung mithilfe einer Vorlage in ein Projekt konvertiert, wird das neu erstellte Projekt der Gruppe zugeordnet, der die Anforderungswarteschlange gehört, nicht der Gruppe, die der Vorlage zugewiesen ist. Dies geschieht auch, wenn bei der Erstellung des Projekts die mit der Vorlage verknüpfte Gruppe in der [!UICONTROL Gruppe] -Feld.

+++

+++**Wartungs-Update am 21. Juli 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis.

Alle [!DNL Workfront Classic] wurde am 14. Juli 2022 entfernt.

**Der mit einer Genehmigung verknüpfte Abweisungsstatus berücksichtigt den Genehmigungs-Workflow**

**HINWEIS: Diese Funktion wurde am 22. Juli 2022 veröffentlicht.**

*Genehmigungen*

Wenn Sie einen mit einem Validierungsprozess verknüpften Status als Zurückweisungsstatus für einen Validierungspfad auswählen, wechselt das zurückgewiesene Objekt in den ausgewählten Status und wird als &quot;&quot;markiert[!UICONTROL Ausstehende Genehmigung]&quot;. Wenn Sie beispielsweise [!UICONTROL Halten] für den Zurückweisungsstatus und [!UICONTROL Halten] -Status mit einem Genehmigungsprozess verknüpft ist, wird das zurückgewiesene Objekt in den Status[!UICONTROL Bei Genehmigung in Wartezeit]&quot;, was die Genehmigung erfordert.

Vor dieser Aktualisierung umging das Objekt den Genehmigungsprozess für den Zurückweisungsstatus und wurde in die [!UICONTROL Halten] Status.

**Benutzerdefinierte Hilfe-URL konfigurieren**

*[!UICONTROL Hauptmenü]*

Wenn Ihr Unternehmen über eine benutzerdefinierte interne Hilfeseite verfügt, können Sie die [!UICONTROL Hauptmenü] [!UICONTROL Hilfe] -Symbol, um zu dieser Site zu gelangen. Dies ist nützlich, wenn die Hilfeseite Informationen darüber enthält, wie Ihr Unternehmen [!DNL Workfront].
Diese benutzerdefinierte URL hat keine Auswirkungen auf den Haupt-Hilfe-Link im oberen Bereich von [!DNL Workfront], noch die kontextsensitiven Hilfelinks in [!DNL Workfront], wodurch Benutzer zu den [!DNL Workfront] Hilfeseite.

**Vergangene Zeit kann bei der Inline-Bearbeitung nicht ausgewählt werden [!UICONTROL Aufgabendauer]**

*Aufgaben*

Wenn ein Benutzer eine Aufgabenliste anzeigt und versucht, die [!UICONTROL Aufgabendauer], sind folgende Zeiteinheiten nicht verfügbar:

* [!UICONTROL Verstrichene Minuten]
* [!UICONTROL Verstrichene Stunden]
* [!UICONTROL Verstrichene Tage]
* [!UICONTROL Verstrichene Wochen]
* [!UICONTROL Verstrichene Monate]

**[!UICONTROL Meine Aktualisierungen] Seite ist leer**

*Updates*

Wenn ein Benutzer versucht, seine [!UICONTROL Meine Aktualisierungen] -Seite, wird die Seite nicht geladen. Der Benutzer kann nur die [!DNL Workfront] Navigationskopfzeile.

**&quot;[!UICONTROL Nur SAML 2.0-Authentifizierung zulassen]&quot;-Einstellung fehlt beim Kopieren eines Benutzers**

*Benutzer*

Wenn ein Gruppenadministrator einen Benutzer kopiert und die &quot;[!UICONTROL Eine Einladungs-E-Mail an diese Person senden]&quot;, die Option &quot;O&quot;[!UICONTROL Nur SAML 2.0-Authentifizierung zulassen]&quot;, wird nicht wie erwartet angezeigt. Dies kann auch dann vorkommen, wenn alle Zugriffs- und Berechtigungsanforderungen für diese Aktion erfüllt sind.

+++

+++**Wartungs-Update am 14. Juli 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis.

Alle [!DNL Workfront Classic] wurde am 14. Juli 2022 entfernt.

**Fehler beim Zurücksetzen des Kennworts**

*Anmeldung*

Wenn ein Benutzer versucht, sein Passwort zurückzusetzen, kann er es nicht zurücksetzen und er wird in einer Meldung darüber informiert, dass er keinen Zugriff hat. Der Benutzer kann sich nicht bei Workfront anmelden.

**Es kann kein weiterer Zugriff auf einen Bericht angefordert werden**

*Berichte*

Wenn ein Benutzer mit eingeschränktem Zugriff auf einen Bericht versucht, mehr Zugriff auf einen Bericht anzufordern, ist die Option, mehr Zugriff anzufordern, nicht verfügbar unter [!UICONTROL Berichtsaktionen] Menü.

**Bestätigungsnachricht beim Löschen eines Anfrageentwurfs aktualisiert**

*Anforde- rungen*

Wenn Sie eine entworfene Anforderung verwerfen, wird die Bestätigungsmeldung angezeigt, die nach dem Klicken auf[!UICONTROL Entwurf verwerfen]&quot; zeigt Folgendes an:

* [!UICONTROL Entwurf wurde verworfen] (Dies ist eine Benachrichtigung, die Sie darüber informiert, dass Ihr Entwurf verworfen wurde)
* [!UICONTROL Rückgängig] (Dies ist ein Link, auf den Sie klicken können, um die Aktion zum Löschen des Entwurfs wiederherzustellen. Dadurch wird der Entwurf beibehalten, anstatt ihn zu löschen.)

Vor dieser Änderung waren folgende Optionen verfügbar:

* [!UICONTROL Entwurf wird verworfen]
* [!UICONTROL Abbrechen]

**Datumswerte für Journaleintragsfelder sind beim Zugriff über die API falsch**

*Updates*

Wenn ein Benutzer einen Datumswert für ein Objekt ändert und dann über die API auf den Journaleintrag zugegriffen wird, der diese Datumsänderung darstellt, werden die Datumswerte für [!UICONTROL oldDateVal] und [!UICONTROL newDateVal] von der API zurückgegeben wurden, sind falsch.

**Fehler beim Versuch, Kommentar rückgängig zu machen**

*Updates*

Wenn ein Benutzer versucht, einen Kommentar rückgängig zu machen, wird der Kommentar nicht rückgängig gemacht und der Benutzer sieht den folgenden Fehler:

[!UICONTROL Fehler 403: Sie haben nicht genügend Zugriff, um diese Anmerkung zu löschen /attask/api-internal/NOTE]

**Neue Begrenzung der Zeichenanzahl in einer Aktualisierung in der Vorschau**

*Updates*

Verbesserung der Leistung der [!UICONTROL Updates] hinzugefügt, haben wir eine neue Begrenzung für die Anzahl der Zeichen eingeführt, die Sie in einer Aktualisierung oder einer Antwort auf eine vorhandene Aktualisierung eingeben können. Die neue Beschränkung beträgt 15.000 Zeichen. Durch diese Aktualisierung wurde die zulässige Zeichenanzahl bei Verwendung der API nicht geändert. Die API-Zeichenbeschränkung für Aktualisierungen beträgt 4.000.

**Fehler beim Hochladen des Anhangs von [!DNL Workfront] für die Outlook-Integration**

*Workfront-Integrationen*

Wenn ein Benutzer versucht, eine Anlage mit dem [!DNL Workfront for Outlook] -Integration, wird der Anhang nicht hochgeladen und der Benutzer sieht die folgende Nachricht:

[!UICONTROL Einige Anlagen wurden nicht hochgeladen. Grund: Beim Hochladen von Anhängen ist etwas schiefgelaufen.]

**Aktualisierung der E-Mail-Benachrichtigung zum Testversand**

*[!DNL Workfront]Korrekturabzug*

Anfang dieses Monats als Teil eines Patches für die [!DNL Workfront] Produktionsumgebung, haben wir einen Fehler im Benachrichtigungssystem für Testversand-E-Mails behoben. Diese Änderung wurde im Wartungs-Update zum Zeitpunkt der Veröffentlichung nicht mitgeteilt. Wir haben die folgenden Informationen zum [Wartungs-Update am 2. Juni 2022](#maintenance-update-on-june-2-2022) :

Infolge dieser Fehlerkorrekturen hat sich die E-Mail-Adresse geändert, die zum Senden von Testversandbenachrichtigungen verwendet wird.

Zuvor enthielten Testversand-E-Mail-Adressen die Subdomain Ihres Unternehmens. Beispiel: notifications@[Unternehmensdomäne].my.workfront.com

Jetzt enthalten die Zustellung von E-Mail-Adressen keine Organisations-Subdomain mehr. Alle E-Mail-Benachrichtigungen zum Testversand werden von der folgenden Adresse gesendet: notification@my.workfront.com

Daher empfehlen wir, die folgenden Aktionen durchzuführen, falls Sie dies noch nicht getan haben:

* Aktualisieren Sie Ihre Spamfilter, um E-Mails von notification@my.workfront.com zu akzeptieren.
* Aktualisieren Sie Ihre Zulassungslisten, um E-Mails von notification@my.workfront.com zu akzeptieren.

**Benutzeroptionen können nach der ersten Konfiguration in Workflow-Vorlagen nicht mehr geändert werden**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einer Workflow-Vorlage einen Benutzer hinzufügt, kann er Optionen konfigurieren. Nach Abschluss der ersten Konfiguration kann der Benutzer jedoch Folgendes nicht mehr ändern:

* &quot;[!UICONTROL Kommentare auflösen und Aktionen anwenden]&quot;-Fähigkeit
* [!UICONTROL &quot;Freigeben des Testversands durch Tagging]&quot;-Fähigkeit
* Proof role ([!UICONTROL Überprüfer], [!UICONTROL Genehmiger]usw.)

**&quot;[!UICONTROL Die Arbeitselemente dieses Projekts]&quot; Filter wurde im Projekt wiederhergestellt [!UICONTROL Lastenausgleich]**

*[!UICONTROL Lastenausgleich]*

Wir haben den Filter &quot;Arbeitselemente dieses Projekts&quot;im Abschnitt [!UICONTROL Zugeordnet] Bereich, in dem Sie auf [!UICONTROL Lastenausgleich] aus einem Projekt.

Dieser Filter wird jetzt unter der[!UICONTROL Vorgeschlagen]&quot;-Abschnitt der Filter für die [!UICONTROL Zugewiesene Arbeit] Bereich eines Projekts [!UICONTROL Lastenausgleich].

+++

## Aktualisierungen im Juni 2022

+++**Wartungs-Update am 30. Juni 2022**

**Anzeigen der [!UICONTROL Lastenausgleich] für eine Woche**

*[!UICONTROL Lastenausgleich]*

Basierend auf dem Feedback, das wir von vielen Kunden erhalten haben, haben wir nun eine Option hinzugefügt, um die [!UICONTROL Lastenausgleich] für eine Woche. Vor dieser Aktualisierung können Sie die [!UICONTROL Lastenausgleich] 4, 6 und 12 Wochen. Mit diesem Update haben wir auch die 12-Wochen-Option auf 3 Monate geändert.

**Das Bedienfeld &quot;Delegieren&quot;ist jetzt über den Lastenausgleich verfügbar.**

*[!UICONTROL Lastenausgleich]*

HINWEIS: Diese Aktualisierung ist nur in der Vorschau -Umgebung verfügbar. Die mit dieser Aktualisierung verknüpfte Funktion wird ab Version 22.3 in der Produktion verfügbar sein.

Sie können jetzt die Delegaten einer Aufgabe oder eines Problems über den Lastenausgleich anzeigen. Beim Zuweisen einer Aufgabe oder eines Problems aus dem Arbeitslastausgleich können Sie eine Liste der Zuweisungen sowie eine Liste der Delegierten für die Aufgabe oder das Problem anzeigen, sofern diese derzeit zugewiesen sind.

**Endpunktinformationen können nicht in API Explorer geöffnet werden**

*API*

Wenn ein Benutzer die [!DNL API Explorer] und auf einen Endpunkt klickt, werden die Endpunktinformationen nicht angezeigt.

**Probleme mit [!UICONTROL Details] bei Verwendung der [!UICONTROL Home Calendar]**

*Startseite*

Wenn ein Benutzer die [!UICONTROL Home Calendar] und auf eine Aufgabe klickt, kann eine der folgenden Aktionen eintreten:

* Die [!UICONTROL Details] wird kurz angezeigt und verschwindet dann. Der Benutzer kann nicht auf die Details zugreifen.
* Die [!UICONTROL Details] -Schaltfläche wird nicht angezeigt. Der Benutzer kann nicht auf die Details zugreifen.
* Die [!UICONTROL Details] angezeigt, sich jedoch nicht an der richtigen Stelle befindet. Der Benutzer kann auf die Schaltfläche klicken, um auf die Details zuzugreifen.

+++

+++**Wartungs-Update (Hotfix) am 24. Juni 2022**

**Datumsauswahl wird beim Bearbeiten eines benutzerdefinierten Formulars nicht geschlossen**

*Benutzerdefinierte Formulare*

Wenn ein Benutzer ein benutzerdefiniertes Formular bearbeitet und versucht, ein Datum zu ändern, wird die Datumsauswahl bei Auswahl des Datums nicht geschlossen. Der Benutzer kann die Datumsauswahl nicht durch Speichern, Abbrechen oder Klicken weg von der Datumsauswahl schließen.

Dies wurde in den folgenden Bereichen gemeldet:

* [!UICONTROL Updates] area
* [!UICONTROL Startseite]

**Benutzer können sich nicht in eine andere Testphase verschieben**

*Korrekturabzüge*

Wenn ein Benutzer die [!UICONTROL Testversand-Workflow] des Testversands und versucht, sich selbst in eine andere Testphase zu ziehen, wird der Name des Benutzers in die ursprüngliche Phase zurückgesetzt und nicht zur gewünschten Phase hinzugefügt.

+++

+++**Wartungs-Update am 23. Juni 2022**

**[!UICONTROL Neue Anforderung kann nicht über das Dashboard hinzugefügt werden]**

*Dashboards*

Wenn ein Benutzer ein Dashboard in einem Projekt anzeigt und versucht, eine neue Anforderung hinzuzufügen, indem er auf [!UICONTROL +Neue Anforderung] nicht reagiert, ist die Schaltfläche nicht responsiv und der Benutzer kann keine neue Anforderung hinzufügen.

**Fehler beim Anzeigen von Elementen in der Startseite-Arbeitsliste**

*[!UICONTROL Startseite]*

Wenn ein Benutzer seine [!UICONTROL Homepage-Arbeitsliste] und auf ein Element im [!UICONTROL Gesendete Genehmigungen] -Abschnitt, zeigt die Seite den folgenden Fehler an:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Wenn der Benutzer die Seite aktualisiert, klickt er auf ein Element im [!UICONTROL Arbeitsliste], wird der Fehler angezeigt. Das Problem betrifft nicht mehr nur Elemente im [!UICONTROL Gesendete Genehmigungen] Abschnitt.

**Benutzerdefinierter Abschnitt eines Objekts enthält Ergebnisse, die nicht in diesem Objekt enthalten sind**

*Objekte*

Wenn ein Benutzer eine [!UICONTROL custom] -Abschnitt eines Objekts zeigt der benutzerdefinierte Abschnitt Elemente an, die nicht Teil dieses Objekts sind. Dies wurde gemeldet, wenn der benutzerdefinierte Abschnitt direkt zum Objekt hinzugefügt wird und wenn ein benutzerdefinierter Abschnitt über eine Layoutvorlage hinzugefügt wird.

**Aufgaben werden in ein falsches Projekt verschoben**

*Aufgaben*

Wenn ein Benutzer Aufgaben von Projekt A zu Projekt B wechselt und dann mehr Aufgaben von Projekt A zu Projekt C wechselt, werden die ursprünglich in Projekt B verschoben Aufgaben in Projekt C angezeigt.

**Einige Schaltflächen/Symbole funktionieren nicht beim Zugriff auf [!UICONTROL Lastenausgleich] über einen freigegebenen Link oder ein freigegebenes Dashboard**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer zum [!UICONTROL Lastenausgleich] über einen freigegebenen Link oder einen Link in einem Dashboard und versucht, das Element oben im Bildschirm zu verwenden, funktionieren die Elemente nicht. Dies wurde für die folgenden Elemente gemeldet:

* [!UICONTROL Heute]
* Pfeile &quot;Zurück&quot;und &quot;Weiter&quot;
* [!UICONTROL Wochen]
* Kalendersymbol (Datumsauswahl)

+++

+++**[!DNL Workfront]Aktualisierung des Szenario-Planers für die Wartung am 23. Juni 2022**

**Benutzer mit [!UICONTROL Verwalten] Berechtigungen für einen Plan können ihn für andere freigeben**

Als Benutzer mit [!UICONTROL Verwalten] Berechtigungen für einen Plan im [!DNL Scenario Planner], können Sie sie jetzt für andere Benutzer freigeben. Vor dieser Aktualisierung konnte nur der Ersteller des Plans den Plan für andere Benutzer freigeben.

+++

+++**Wartungs-Update am 16. Juni 2022**

**Gruppenadministrator kann keine Mitglieder zu Gruppe hinzufügen**

*Gruppen*

Wenn ein Gruppenadministrator versucht, einen Benutzer zu einer Gruppe hinzuzufügen, wird das Dropdown-Menü zur Auswahl des Benutzers nicht ausgefüllt. Der Gruppenadministrator kann keine Benutzer auswählen und kann daher keine Benutzer zur Gruppe hinzufügen.

**Benutzerdefinierte Quartale werden beim Festlegen eines Filters nicht angezeigt**

*Filter*

Wenn ein Benutzer einen Filter erstellt und nach einem Datumsfeld filtert, enthält die Dropdown-Liste der verfügbaren Operatoren für das Datumsfeld keine kürzlich hinzugefügten benutzerdefinierten Quartale.

**Fehler &quot;Bounces&quot; beim Konvertieren eines Problems in ein Projekt über eine Vorlage**

*Projekte*

Wenn ein Benutzer versucht, ein Problem über eine Vorlage in ein Projekt zu konvertieren, und das Problem über ein benutzerdefiniertes Formular verfügt, das einen reinen Administratorabschnitt enthält, wird das Problem nicht konvertiert und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Versuchen Sie es erneut. Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

**Anforderungen werden gesendet, ohne dass erforderliche Felder ausgefüllt werden**

*Anforde- rungen*

Wenn ein Benutzer eine Anforderung erstellt und die erforderlichen Felder nicht ausfüllt und dann die Anforderung sendet, wird die Anforderung ohne Daten in den erforderlichen Feldern gesendet. Es wird erwartet, dass die Anfrage nicht gesendet wird und der Benutzer benachrichtigt wird, dass er die erforderlichen Felder ausfüllen muss, bevor er die Anfrage sendet.

**Neue benutzerdefinierte Quartale werden anscheinend nicht gespeichert**

*Setup*

Wenn ein Benutzer ein neues benutzerdefiniertes Quartal im Bereich &quot;Projekte&quot;der Einrichtung hinzufügt und auf [!UICONTROL Speichern], gibt es keinen visuellen Hinweis auf die Speicherung. Dem Benutzer wird keine Erfolgsmeldung angezeigt und die Variable [!UICONTROL Speichern] in noch vorhanden und aktiv. Wenn der Benutzer die Seite jedoch aktualisiert, kann er sehen, dass die neuen Quartale in der Liste der benutzerdefinierten Quartale angezeigt werden.

Wenn der Benutzer ein neues Quartal hinzufügt, klickt auf [!UICONTROL Speichern], erhält keine Angabe zum Speichern, fügt ein weiteres Quartal hinzu, ohne die Seite zu aktualisieren, und klickt auf [!UICONTROL Speichern] erneut verwenden, kann das zweite hinzugefügte Quartal möglicherweise nicht gespeichert werden.

**[!UICONTROL Team-Arbeitsanforderungen] Seite ist leer**

*Teams*

HINWEIS: Dieses Problem tritt nur in der Vorschau -Umgebung auf.

Wenn ein Benutzer versucht, die [!UICONTROL Arbeitsanforderungen] auf einer Team-Seite ist die Seite leer. Der Benutzer kann die obere Navigationsleiste sehen, jedoch keinen Seiteninhalt.

+++

+++**Wartungs-Update am 9. Juni 2022**

**Objekte können nicht ausgewählt werden, die gefiltert werden sollen [!UICONTROL Portfolio Optimizer] Voreinstellungen**

*Portfolios*

Wenn sich ein Benutzer im [!UICONTROL Portfolio Optimizer] und zeigt die [!UICONTROL Projektfilter] im [!UICONTROL Voreinstellungen] -Bereich, fehlen die Kontrollkästchen neben den Objekten. Der Benutzer kann die Kontrollkästchen nicht aktivieren oder deaktivieren und kann daher keine zu filternden Objekte auswählen.

**Kann nicht geändert werden [!UICONTROL Geplantes Startdatum] oder [!UICONTROL Geplantes Abschlussdatum] wenn[!UICONTROL Zeitplan ab]&quot; ist nicht markiert**

*Projekte*

Wenn ein Benutzer versucht, die [!UICONTROL Geplantes Startdatum] oder [!UICONTROL Geplantes Abschlussdatum] eines Projekts und der[!UICONTROL Zeitplan ab]&quot; nicht aktiviert ist, wird die [!UICONTROL Geplantes Startdatum] und [!UICONTROL Geplantes Abschlussdatum] -Bereiche deaktiviert sind und der Benutzer diese Daten nicht bearbeiten kann.

**Zugriffsebene von Benutzern kann nicht bearbeitet werden**

*Benutzer*

Wenn ein Benutzer mit Planungszugriff, der Benutzeradministratoren (Gruppenbenutzer) enthält, versucht, Benutzer in der Gruppe zu bearbeiten, für die er Administrator ist, wird die [!UICONTROL Zugriff] -Feld deaktiviert ist und der Benutzer die Zugriffsebene nicht bearbeiten kann.

+++

+++**[!DNL Workfront Scenario Planner]Wartungs-Update am 9. Juni 2022**

**Anpassbare linke Leiste im[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Sie können jetzt die Größe des linken Bereichs in einem Plan ändern, indem Sie im [!DNL Scenario Planner]. Dadurch können längere Initiativnamen vollständig angezeigt werden. Vor dieser Aktualisierung wurden längere Initiativnamen abgeschnitten.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 9. Juni 2022**

**Daten aus benutzerdefinierten Formularen, die in nicht verfügbar sind [!DNL Workfront Fusion] [!DNL Workfront] Module**

*[!DNL Workfront Fusion]*

Wenn ein Benutzer eine [!DNL Workfront] -Modul in [!DNL Workfront Fusion]und versucht, Ausgaben für das Modul auszuwählen, sind Felder aus benutzerdefinierten Formularen nicht sichtbar. Dies tritt auf, wenn das benutzerdefinierte Formular für einen Typ von [!DNL Workfront] -Objekt und anschließend wurde ein anderer Typ hinzugefügt. [!DNL Workfront Fusion] zeigt nur Felder aus benutzerdefinierten Formularen an, die ursprünglich für den ausgewählten Objekttyp erstellt wurden.

**Es kann nicht gescrollt werden, um alle Szenario-Ausführungen anzuzeigen**

*[!DNL Workfront Fusion]*

Wenn ein Benutzer den Ausführungsverlauf eines Szenarios anzeigt und versucht, nach unten zu scrollen, um weitere Ausführungen anzuzeigen, wird das Laden der Ausführungen beendet und der Benutzer kann sie nicht anzeigen. Außerdem kann der Benutzer nicht zu den neuesten Ausführungen zurückkehren.

+++

+++**Wartungs-Update am 2. Juni 2022**

**[!UICONTROL Portfolio Optimizer] zeigt den Wert 0 bei Verwendung einer anderen Sprache als Englisch an**

*Portfolios*

Wenn ein Benutzer [!DNL Workfront] in einer anderen Sprache als Englisch und zeigt die [!UICONTROL Portfolio Optimizer], wird der Wert als 0 angezeigt. Dies kann auch auftreten, wenn der Geschäftsfall nicht abgeschlossen ist.

**Berechnete Feldwerte falsch bei der Erstellung eines Projekts aus einer Vorlage**

*Projekte*

Wenn ein Benutzer ein Projekt aus einer Vorlage erstellt, die berechnete Felder enthält, sind die im neuen Projekt angezeigten Feldwerte falsch.

**Kann nicht bearbeitet werden [!UICONTROL Bedingungen] in [!UICONTROL Projektvoreinstellungen] Gebiet von [!UICONTROL Einrichtung]**

*[!UICONTROL Einrichtung]*

Wenn ein Benutzer versucht, [!UICONTROL Bedingungen] im [!UICONTROL Projektvoreinstellungen] Gebiet von [!UICONTROL Einrichtung], ist die Seite leer.

**Neue Begrenzung der Zeichenanzahl in einer Aktualisierung in der Vorschau**

*[!UICONTROL Lastenausgleich]*

>[!NOTE]
>
>Diese Aktualisierung gilt nur für die Vorschau -Umgebung.

Um die Leistung des Bereichs Updates zu verbessern, haben wir eine neue Begrenzung für die Anzahl der Zeichen eingeführt, die Sie in einer Aktualisierung oder einer Antwort auf eine vorhandene Aktualisierung eingeben können. Die neue Beschränkung beträgt 15.000 Zeichen. Durch diese Aktualisierung wurde die zulässige Zeichenanzahl bei Verwendung der API nicht geändert. Die API-Zeichenbeschränkung für Aktualisierungen beträgt 4.000. Aktualisierungen Unterstützung für benutzerdefinierte Felder vom Typ &quot;Typehead&quot;in den Arbeitslastausgleichsfiltern

Wir unterstützen nun Filter, die auf der [!UICONTROL Typahead] Geben Sie benutzerdefinierte Felder in den Lastenausgleich ein. Vor diesem Patch war das Filtern nach diesem Typ von benutzerdefinierten Feldern im Arbeitslastausgleich nicht möglich.

**Berechtigungen für Benutzerrollen können nicht bearbeitet werden**

*[!DNL Workfront Proof]*

Wenn ein Benutzer versucht, den[!UICONTROL Kommentare auflösen und Aktionen anwenden]&quot; oder &quot;[!UICONTROL Testversand durch Tagging freigeben]&quot; -Berechtigungen für die Rolle eines Benutzers in [!DNL Workfront Proof], werden die Änderungen nicht gespeichert. Der Benutzer erhält eine Benachrichtigung, dass die Vorlage aktualisiert wurde. Wenn der Benutzer die Rollenberechtigungen jedoch erneut öffnet, kann er sehen, dass die Änderungen nicht gespeichert wurden.

+++


## Aktualisierungen im Mai 2022

+++**Wartungs-Update am 26. Mai 2022**

Diese Probleme wurden nur in der neuen [!DNL Workfront] Erlebnis. [!DNL Adobe Workfront Classic] wird nicht mehr unterstützt.

Alle [!DNL Workfront Classic] -Funktion wird im Juli 2022 entfernt. Bitte wechseln Sie so bald wie möglich zum neuen Erlebnis.

**Aktualisierte Breadcrumb-Trennzeichen**

*[!DNL Workfront]*

HINWEIS: Dieses Update wurde am 24. Mai 2022 veröffentlicht.

Wir haben die Breadcrumb-Trennzeichen in allen Bereichen aktualisiert, in denen Breadcrumbs verfügbar sind. Jetzt werden die Objekte in den Breadcrumbs durch senkrechte Striche (|) getrennt. Vor dieser Aktualisierung wurden sie durch Schrägstriche (/) getrennt.

**Benutzerdefinierte Formulare mit Abschnittspausen können nicht bearbeitet werden**

*Benutzerdefinierte Formulare*

Wenn ein Benutzer versucht, ein benutzerdefiniertes Formular mit einem Abschnittsumbruch zu bearbeiten, kann er das Formular nicht bearbeiten, und ihm wird die folgende Meldung angezeigt:

[!UICONTROL Der angegebene Schutz für den Abschnittsumbruch kann nicht auf alle Objekttypen angewendet werden]

**Probleme beim Drucken von Dashboards unter PDF**

*Dashboards*

Beim Drucken eines Dashboards auf einer PDF wurden die folgenden Probleme gemeldet: Die PDF druckt nicht jede Zeile im Bericht. Wenn Zeilen fehlen, wird nur leerer Leerraum angezeigt.
Die PDF enthält leere Leerzeichen zwischen den Spaltenüberschriften und der ersten Zeile des Berichts.

**[!DNL Portfolio Optimizer]zeigt den Wert 0 bei Verwendung einer anderen Sprache als Englisch an**

*Portfolios*

Wenn ein Benutzer [!DNL Workfront] in einer anderen Sprache als Englisch und zeigt die [!UICONTROL Portfolio Optimizer], wird der Wert als 0 angezeigt. Dies kann auch auftreten, wenn der Geschäftsfall nicht abgeschlossen ist.

**Einige benutzerdefinierte Formulare werden beim Bearbeiten einer Vorlage nicht angezeigt**

*Vorlagen*

Wenn ein Benutzer versucht, die benutzerdefinierten Formulare in einer Vorlage zu bearbeiten, indem er auf [!UICONTROL Bearbeiten] in der Kopfzeile der Vorlage die [!UICONTROL Vorlage bearbeiten] nur eines der benutzerdefinierten Formulare angezeigt, die an die Vorlage angehängt sind.

**Freigegebener Link zum Arbeitslastausgleich zeigt zugewiesene Arbeit falsch an**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer die [!UICONTROL Lastenausgleich] über einen freigegebenen Link die [!DNL Workload Balancer] include [!UICONTROL Zugewiesene Arbeit] im [!UICONTROL Nicht zugewiesene Arbeit] Abschnitt. [!UICONTROL Zugewiesene Arbeit] hat keinen separaten Abschnitt. Wenn der Benutzer die [!UICONTROL Lastenausgleich] , ohne den freigegebenen Link zu verwenden, [!UICONTROL Zugewiesene Arbeit] angezeigt.

+++

+++**Wartungs-Update am 19. Mai 2022**

**Der Testversand kann nicht aus einer[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Wenn ein Benutzer versucht, einen Testversand aus einem [!DNL PowerPoint] , das ein Diagramm enthält, schlägt die Erstellung des Testversands fehl.

**Der Testversand kann nicht aus einer [!UICONTROL Word] Dokument**

*[!DNL Workfront Proof]*

Wenn ein Benutzer versucht, einen Testversand aus einem [!DNL Word] -Dokument, das ein Diagramm enthält, schlägt die Erstellung des Testversands fehl.

**Benutzerdefinierte Nachricht kann beim Freigeben eines Testversands nicht hinzugefügt werden**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einen Testversand anzeigt, öffnet er die [!UICONTROL Testversand freigeben] und wählt den [!UICONTROL Benutzerdefinierte Nachricht hinzufügen] -Schaltfläche, kann der Benutzer nicht in das sich öffnende Textfeld eingeben. Wenn der Benutzer versucht, in dieses Feld einzugeben, wird das Feld sofort ausgeblendet.

**Testversand kann nicht geschlossen werden**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einen Testversand anzeigt und versucht, ihn zu schließen, fehlt das X zum Schließen des Testversands in der oberen rechten Ecke des Testversands.

**Gruppenadministrator kann nicht hinzugefügt oder entfernt werden**

*Gruppen*

Wenn ein Benutzer eine [!UICONTROL Gruppe] und versucht, einen Gruppenadministrator mithilfe der [!UICONTROL Gruppenadministratoren] -Bereich in der Kopfzeile werden die Änderungen nicht gespeichert und der Benutzer sieht den folgenden Fehler:

[!UICONTROL Fehler-Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]

**Horizontaler Bildlaufbalken blockiert Element am Ende der Liste**

*Projekte*

Wenn ein Benutzer eine Liste mit einer Ansicht anzeigt, die sich von der Bildschirmseite erstreckt, blockiert die horizontale Bildlaufleiste die Ansicht des Benutzers vom letzten Element auf der Liste.

**&quot;[!UICONTROL Unerwarteter Fehler]&quot; beim Konvertieren eines Problems in ein Projekt mithilfe einer Vorlage**

*Listen*

Wenn ein Benutzer versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, wird das Problem nicht konvertiert, und der Benutzer sieht die folgende Meldung:

[!UICONTROL Unerwarteter Fehler]

**Die [!UICONTROL Status] -Feld in einer Timesheet-Ansicht ist jetzt schreibgeschützt**

*Arbeitszeit- tabellen*

Wir haben die [!UICONTROL Status] in einer Timesheet-Ansicht schreibgeschützt sein. Vor dieser Änderung konnten Benutzer den Status eines Zeitblatts inline bearbeiten, wodurch sie die Entscheidung der Timesheet-Genehmiger überschreiben konnten.

+++

+++**Wartungs-Update am 12. Mai 2022**

**[!UICONTROL Speichern] Schaltfläche wird beim Bearbeiten eines Projekts nicht geladen**

*Projekte*

Wenn ein Benutzer ein Projekt bearbeitet und versucht, zu speichern, erkennt er, dass die [!UICONTROL Speichern] -Schaltfläche zeigt das Wort &quot;[!UICONTROL Laden].&quot; Wenn der Benutzer auf diese Schaltfläche klickt, um die Änderungen am Projekt zu speichern, reagiert die Schaltfläche nicht und die Änderungen werden nicht gespeichert.

**Feldbeschriftungen werden beim Anzeigen eines Objekts in [!UICONTROL Startseite]**

*Startseite*

Wenn ein Benutzer ein Objekt aus seiner [!UICONTROL Homepage-Arbeitsliste], das Gebiet rechts von der [!UICONTROL Homepage-Arbeitsliste] zeigt an, dass das Objekt keine Feldbeschriftungen enthält. Die Feldwerte sind vorhanden.

**Schnellfilter konzentriert sich nicht automatisch auf die Suchleiste**

*Listen*

Wenn sich ein Benutzer in einer Liste befindet und auf die Lupe klickt, um schnell zu filtern, und dann mit der Eingabe beginnt, wird der Text nicht angezeigt. Der Grund dafür ist, dass der Fokus nicht auf die Suchleiste, sondern auf das Lupensymbol bleibt.

Durch Klicken auf die Suchleiste wird der Fokus übertragen und der Benutzer kann den Text seiner Suche eingeben.

**Benutzer können Felder in einem Bericht nicht inline bearbeiten**

*Berichte*

Wenn ein Benutzer versucht, ein Feld in einem Bericht zu bearbeiten, und dieses Feld aus einem benutzerdefinierten Formular abgerufen wird, kann er das Feld nicht bearbeiten. Dies tritt auf, wenn das benutzerdefinierte Formular ursprünglich für einen anderen Objekttyp als das Objekt erstellt wurde, an das es angehängt ist.

**Titel und Schaltflächentext werden beim Erstellen eines Testversands nicht angezeigt**

*[!DNL Workfront Proof]*

HINWEIS: Dieses Problem tritt nur in der Vorschau -Umgebung auf.

Wenn ein Benutzer versucht, einen Testversand zu erstellen, ist der Text für Optionen oder Schaltflächen nicht sichtbar. Daher weiß der Benutzer nicht, was die einzelnen Optionen oder Schaltflächen darstellen, und kann den Testversand nicht konfigurieren.

+++

+++**Wartungs-Update am 5. Mai 2022**

**Neuen Rechnungsdatensatz kann nicht hinzugefügt werden**

*Projekte*

Wenn sich ein Benutzer im [!UICONTROL Rechnungsdatensätze] -Bereich eines Projekts und verwendet die [!UICONTROL Neuer Rechnungsdatensatz] Wenn der Benutzer versucht, einen neuen Rechnungsdatensatz hinzuzufügen, werden die Felder für einen neuen Rechnungsdatensatz nicht angezeigt und der Rechnungsdatensatz kann nicht erstellt werden.

**Fehler bei der Massenzuweisung in [!UICONTROL Lastenausgleich]**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer versucht, Zuweisungen in der [!DNL Workload Balancer] eines Projekts wird der Benutzer zu einer Seite mit der folgenden Meldung umgeleitet:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Der Benutzer kann von dieser Seite nicht weg navigieren, bis er die Seite aktualisiert hat.

**Aktualisierte Navigation zum Öffnen der [!UICONTROL Zusammenfassung] Bereich für Aufgaben und Probleme in [!UICONTROL Lastenausgleich]**

*[!UICONTROL Lastenausgleich]*

Klicken Sie jetzt einfach auf eine Aufgabe oder eine Problemleiste im [!UICONTROL Lastenausgleich] öffnet das Bedienfeld &quot;Zusammenfassung&quot;. Vor dieser Aktualisierung mussten Sie auf die [!UICONTROL Zusammenfassung öffnen] in der Symbolleiste und klicken Sie dann auf die Aufgabe oder das Problem. Dies hatte sich als verwirrendes Erlebnis erwiesen, das nun korrigiert wird. Alternativ können Sie auf die [!UICONTROL Mehr] Menü neben dem Namen der Aufgabe oder des Problems und klicken Sie auf [!UICONTROL Zusammenfassung öffnen].

**Gruppenadministrator kann Details zu Benutzern in der Gruppe nicht anzeigen**

*Benutzer*

Wenn ein Benutzer, der einer Zugriffsstufe zugewiesen ist, die Folgendes enthält: [!UICONTROL Benutzerverwaltung (Gruppenbenutzer)] Die Zugriffseinstellung versucht, Details eines Benutzers in seiner Gruppe anzuzeigen. Er sieht den folgenden Fehler:

&quot;[!UICONTROL Versuchen Sie es erneut. Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

**Benutzerdefinierter Gruppenstatus kann nicht gelöscht werden**

*Gruppen*

Wenn ein Benutzer versucht, einen benutzerspezifischen Gruppenstatus aus dem [!UICONTROL Gruppe] -Seite, wird die Seite leer gelassen und der Status wird nicht gelöscht.

**E-Mail-Warnhinweiseinstellungen sind zwischen dem Bereich &quot;Kontakte&quot;und den Benutzerdetails nicht konsistent**

*[!DNL Workfront Proof]*

Die Einstellungen für den E-Mail-Warnhinweis werden in der [!UICONTROL Kontakte] Gebiet von [!DNL Workfront Proof] für einen bestimmten Benutzer sich von der E-Mail-Warnhinweiseinstellung unterscheiden, die im [!UICONTROL Benutzerdetails].

**Text-Tool kann nicht verwendet werden, wenn Sie einen Kommentar zu einem Testversand abgeben**

*[!DNL Workfront Proof]*

Wenn ein Benutzer einen Kommentar zu einem Testversand abgibt und versucht, den [!UICONTROL Text] -Tool nicht geöffnet ist, wird dem Benutzer die folgende Nachricht angezeigt:

&quot;[!UICONTROL Textdaten für diese Seite werden noch heruntergeladen. Bitte warten Sie.]&quot;

**Testversand-E-Mails werden an die primäre E-Mail des Benutzers gesendet**

*[!DNL Workfront Proof]*

Wir passen die Art und Weise an, wie Testversand-E-Mail-Benachrichtigungen gesendet werden. Jetzt werden Benachrichtigungen an die primäre E-Mail-Adresse des Benutzers gesendet und nicht an die vom System generierte Alias-E-Mail.

Weitere Informationen dazu, warum das System Alias-E-Mails generiert, finden Sie unter Benutzersynchronisierung zwischen Adobe [!DNL Workfront] und [!DNL Workfront Proof].

+++

## Aktualisierungen im April 2022

+++**Wartungs-Update am 28. April 2022**

**Es kann nicht zum [!UICONTROL Speichern] Schaltfläche beim Bearbeiten eines Zeitplans**

*Arbeitszeit- tabellen*

Wenn ein Benutzer ein Timesheet bearbeitet, kann er nicht weit genug scrollen, um das Bearbeitungsfenster anzuzeigen [!UICONTROL Speichern] und kann daher das Timesheet nicht bearbeiten.

**Elektronische Signatur überprüft jetzt die Föderations-ID**

*Korrekturabzüge*

Beim elektronischen Signieren eines Testversands prüft das System jetzt die Föderations-ID, wenn Sie SSO in [!DNL Workfront Proof]zusätzlich zu Ihrer E-Mail in [!DNL Workfront].

Zuvor hat das System nur Ihre E-Mail in Workfront überprüft.

+++

+++**Wartungs-Update (Hotfix) am 25. April 2022**

**[!UICONTROL Lastenausgleich] lädt nicht**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer versucht, die [!UICONTROL Lastenausgleich], der Kopfzeile und der linken Navigationslast, aber der Inhalt des Workload-Balancers wird nicht geladen. Der Benutzer sieht blinkende graue Quadrate anstelle von Daten. Gelegentlich wird ein Teil des Inhalts geladen, aber der Benutzer sieht immer noch blinkende graue Quadrate, in denen die fehlenden Daten enthalten wären.

+++

+++**Wartungs-Update am 21. April 2022**

**Das Hinzufügen einer Aufgabe bewirkt, dass die Seite nach unten springt**

*Aufgaben*

Wenn ein Benutzer eine Aufgabe unterhalb einer vorhandenen Aufgabe in einer Liste hinzufügt, wird die Seite in der Liste nach unten verschoben. Obwohl sich die neue Aufgabe an der richtigen Stelle befindet, muss der Benutzer nach oben scrollen, um sie zu finden.

**Benutzer, die zu einem Testversand hinzugefügt wurden, können nicht auf das Arbeitselement des Testversands zugreifen in[!DNL Workfront]**

*Korrekturabzüge*

Wenn ein Benutzer einer Phase im Workflow eines Testversands hinzugefügt wird, wird der Benutzer nicht zur Freigabe des Dokuments hinzugefügt und erhält keine Berechtigungen für das Arbeitselement des Testversands in [!DNL Workfront]. Wenn sich der Benutzer in [!DNL Workfront] und versucht, das Arbeitselement zu öffnen, an das der Testversand angehängt ist, sehen sie die folgende Meldung:

&quot;[!UICONTROL Sie haben nicht genügend Zugriff, um diese Ansicht anzuzeigen (Objekt)]&quot;

Dieses Problem betrifft nur Testsendungen, die bereits erstellt wurden und denen Benutzer hinzugefügt wurden, nachdem sie durchgeführt wurden. Das Hinzufügen von Benutzern zum Workflow vor der Erstellung eines Testversands funktioniert erwartungsgemäß.

**Die E-Mail zum Zurücksetzen des Kennworts kann nicht gesendet werden von[!DNL Workfront]**

*Benutzer*

Wenn ein Benutzer versucht, eine E-Mail zum Zurücksetzen des Kennworts von einer Benutzerliste in [!DNL Workfront], ist die Option zum Senden der E-Mail nicht verfügbar.

**Schaltfläche zeigt an[!UICONTROL Startproblem]&quot; anstelle von &quot;[!UICONTROL Anfrage starten]&quot;**

*Anforde- rungen*

Wenn ein Benutzer eine seinem Team zugewiesene Anforderung anzeigt, wird ihm ein[!UICONTROL Startproblem]&quot;-Schaltfläche in der Kopfzeile anstatt eines &quot;[!UICONTROL Anfrage starten]&quot;.

**&quot;[!UICONTROL Kommentar rückgängig machen]&quot; entfernt markierte Benutzer**

*Updates*

Wenn ein Benutzer einen anderen Benutzer in einem Kommentar markiert, sendet er den Kommentar und wählt dann die[!UICONTROL Kommentar rückgängig machen]&quot;, wird der Kommentar wie gewohnt in einem Aktualisierungsfeld angezeigt, der getaggte Benutzer ist jedoch nicht in der [!UICONTROL Benutzer mit Tags] ankreuzen.

**Bei Verwendung von [!UICONTROL Milestone] Ansicht in einem Bericht**

*Berichte*

Wenn ein Benutzer einen Bericht anzeigt und die [!UICONTROL Milestone] angezeigt, zeigt die Seite die Meilensteinansicht an, führt aber keinen Bildlauf mehr durch. Außerdem kann der Benutzer keine Meilensteine anzeigen, die weiter unten auf der Seite stehen würden.

**Falsche Währung bei Anzeige des Berichts im Dashboard**

*Berichte*

Wenn ein Benutzer einen Bericht in einem Dashboard anzeigt, ist die im Bericht verwendete Währung falsch. Wenn der Benutzer den Bericht außerhalb des Dashboards anzeigt, ist die Währung korrekt.

**Abgeschlossener Filter zeigt kein abgeschlossenes Arbeitselement an**&#x200B;

*[!UICONTROL Startseite]*

Wenn ein Benutzer seine [!UICONTROL Homepage-Arbeitsliste] mit dem [!UICONTROL Abgeschlossen] ausgewählte, abgeschlossene Arbeitselemente werden nicht in der Liste angezeigt. Wenn die [!UICONTROL Alle] ausgewählt ist, werden die abgeschlossenen Elemente in die Liste aufgenommen und zeigen an, dass die abgeschlossenen Elemente vorhanden sind.

**[!DNL Workfront]lädt nicht**

*[!DNL Workfront]*

Wenn ein Benutzer versucht, sich anzumelden [!DNL Workfront], scheint die Seite in einer Schleife von Umleitungen oder Aktualisierungen festzuhalten und wird nicht geladen.

+++

+++**Wartungs-Update am 14. April 2022**

**Aufgabe kann nicht aus einem Bericht für einen benutzerdefinierten Abschnitt zu einer Aufgabe hinzugefügt werden**

*Aufgaben*

Wenn ein Benutzer einen benutzerdefinierten Abschnitt zu einer Aufgabe anzeigt und der Abschnitt einen Aufgabenbericht enthält, kann der Benutzer keine Aufgabe aus diesem Bericht hinzufügen. Die [!UICONTROL Aufgabe hinzufügen] -Schaltfläche markiert den Bericht, öffnet jedoch kein Fenster, in dem der Benutzer eine Aufgabe hinzufügen kann.

**Schaltfläche &quot;Fertig&quot;an der falschen Stelle beim Bearbeiten einer Ansicht**

*Ansichten*

Wenn ein Benutzer eine Ansicht bearbeitet, wird die [!UICONTROL Fertig] oberhalb des Bildschirms angezeigt und kann den Text überlappen.

Der Benutzer kann die Ansicht wie gewohnt bearbeiten. Die Funktionalität ist nicht betroffen.

**Bei Verwendung von [!UICONTROL Milestone] Ansicht in einem Bericht**

*Berichte*

Wenn ein Benutzer einen Bericht anzeigt und die [!UICONTROL Milestone] angezeigt, zeigt die Seite die Meilensteinansicht an, führt aber keinen Bildlauf mehr durch. Außerdem kann der Benutzer keine Meilensteine anzeigen, die weiter unten auf der Seite stehen würden.

**Leerer Bildschirm beim Anzeigen von Updates**

*Updates*

Wenn ein Benutzer Aktualisierungen anzeigt und den Bildschirm scrollt, um Updates weiter unten anzuzeigen, wird der Bildschirm leer, und der Benutzer kann keine Updates sehen.

**Fehler bei der Massenzuweisung von Benutzern zu Aufgaben, die nicht der Benutzerrolle zugewiesen sind**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer in [!UICONTROL Lastenausgleich] versucht, einem Benutzer Aufgaben zuzuweisen, dessen Rolle &quot;Auftrag&quot;nicht mit der den Aufgaben zugewiesenen Rolle &quot;Auftrag&quot;übereinstimmt, wird ihm eine Meldung angezeigt, dass die Aufgabe mit der primären Rolle &quot;Auftrag&quot;des zugewiesenen Benutzers zugewiesen wird. Wenn der Benutzer jedoch auf &quot;[!UICONTROL Zuweisen],&quot;werden die Aufgaben nicht zugewiesen und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Fehler. Unbekannter Server-Fehler.]&quot;

+++

+++**Wartungs-Update am 7. April 2022**

**Benutzer, die zu Testsendungen hinzugefügt wurden, haben falsche Rollen**

*Korrekturabzüge*

Wenn ein Benutzer einen anderen Benutzer zu einem Testversand hinzufügt, wird die Rolle dieses Benutzers im Testversand als &quot;&quot;festgelegt.[!UICONTROL Schreibgeschützt]&quot; trotz der tatsächlichen Testversandrolle des Benutzers.

**E-Mail zum Zurücksetzen des Kennworts kann nicht an den Benutzer gesendet werden**

*Benutzer*

Wenn ein Benutzer versucht, ein Kennwort an einen anderen Benutzer zurückzusetzen, sieht er, dass die [!UICONTROL E-Mail zum vergessenen Kennwort senden] -Option ist im [!UICONTROL Mehr] Menü.

**[!UICONTROL Alle aktualisieren] sendet Aktualisierungen an Benutzerprofile anstelle des Projekts**

*Updates*

Wenn ein Benutzer die [!UICONTROL Personen] Bereich eines Projekts aus und wählt die [!UICONTROL Alle aktualisieren] und gibt eine Aktualisierung ein. Die Aktualisierung wird nicht im Projekt selbst veröffentlicht. Stattdessen wird sie an die einzelnen Benutzerprofile jedes Benutzers im Projekt gesendet.

**Übermäßige Anzahl von Seiten beim Drucken von Aktualisierungen**

*Updates*

Wenn ein Benutzer einen Aktualisierungsstream anzeigt, der mehr als eine gedruckte Seite sein würde, und versucht, die Seite zu drucken, zeigt der Druckbildschirm, dass die Anzahl der Seiten weit über der tatsächlichen Anzahl der Seiten liegt, die zum Drucken der Aktualisierungen erforderlich sind. Wenn der Benutzer dann versucht, auf PDF zu drucken, schlägt die Erstellung der PDF fehl.

**Benutzer können nicht die gesamte Liste der für einen Bericht freigegebenen Entitäten anzeigen, wenn die[!UICONTROL Systemweit sichtbar]&quot; ist aktiviert**

*Berichte*

Beim Freigeben von Berichten für mehrere Entitäten, die im [!UICONTROL Zugriff auf Berichte] -Feld können Benutzer nicht zum unteren Rand der Liste scrollen, um die gesamte Liste anzuzeigen, wenn die[!UICONTROL Systemweit sichtbar]&quot;.

**Falsche Währung in Berichten**

*Berichte*

Wenn ein Benutzer festlegt, dass die Währung eines Projekts sich von der Standardwährung unterscheidet, und dann einen Bericht zu diesem Projekt anzeigt, wird die Währung anstelle der Währung des Projekts als Standardwährung angezeigt.

**Zuletzt angezeigte Informationen werden nicht aktualisiert in [!UICONTROL Nutzung von Berichten] Berichte**

*Berichte*

Wenn ein Benutzer einen Bericht anzeigt, der Informationen zum letzten Mal anzeigt, dass der Bericht angezeigt wurde, können diese Informationen leer sein oder alte Daten sein. Dieses Problem betrifft Felder, darunter die folgenden:

* [!UICONTROL Zuletzt angezeigt von]
* [!UICONTROL Zuletzt angezeigte Daten]
* [!UICONTROL Letzte X Viewer]
* [!UICONTROL Ansichten diesen Monat/Quartal/Jahr]

**Abgeschlossene Aufgaben, die in [!UICONTROL Homepage-Arbeitsliste]**

*[!UICONTROL Startseite]*

Wenn ein Benutzer seine [!UICONTROL Homepage-Arbeitsliste], sehen sie Aufgaben abschließen in der Liste, selbst wenn die Option zum Anzeigen abgeschlossener Aufgaben nicht ausgewählt ist.

**Schaltfläche &quot;Zeitplan&quot;ist nicht sichtbar, um die Sandbox-Aktualisierung zu planen**

*Sandbox-Umgebung*

Die [!UICONTROL Zeitplan] -Schaltfläche zum Planen einer Sandbox-Aktualisierung wird nicht im oberen Banner der Sandbox-Umgebung angezeigt.

**Änderungen an einem berechneten Feld wirken sich auf alle berechneten Felder in einem Formular aus**

*Benutzerdefinierte Formulare*

Wenn sich ein Benutzer im benutzerdefinierten Formular-Builder befindet und den Wert eines berechneten Formulars ändert, wird der neue Wert in allen berechneten Feldern des Formulars angezeigt. Dies kann sich auf neue oder vorhandene berechnete Felder auswirken.

**Farben, die auf dem benutzerdefinierten Formular-Builder flackern**

*Benutzerdefinierte Formulare*

Wenn ein Benutzer mit berechneten Feldern im benutzerdefinierten Formular-Builder arbeitet, flackern die Farben der Felder und Ausdrücke.

**[!UICONTROL Validierungen können nicht abgelehnt werden]**

*Genehmigungen*

Wenn ein Benutzer versucht, eine Genehmigung abzulehnen, wird die [!UICONTROL Ablehnen] nicht reagiert und die Genehmigung nicht abgelehnt wird.

**[!UICONTROL Projekte] Registerkarte standardmäßig auf den Bereich Alle Projekte trotz vorheriger Auswahl eingestellt**

*Projekte*

Wenn ein Benutzer über eine Registerkarte, die als Teil der Layoutvorlage eingefügt wurde, zu einer Seite &quot;Projekte&quot;wechselt, wird standardmäßig die Seite [!UICONTROL Alle Projekte] Bereich der linken Navigation. Dies tritt auch dann auf, wenn der Benutzer einen anderen Bereich der linken Navigation auswählt und dann von der Seite &quot;Projekte&quot;weg und zurück navigiert.

+++


## Aktualisierungen im März 2022

+++**Wartungs-Update am 31. März 2022**

**Zeitzonen sind nicht konsistent zwischen [!DNL Workfront] und[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wenn das Profil eines Benutzers auf eine bestimmte Zeitzone in [!DNL Workfront], die Zeitzone des Benutzers in [!DNL Workfront Proof] auf eine andere Zeitzone eingestellt ist.

**Link zum Senden eines angeforderten Dokuments führt zu einer leeren Seite**

*Dokumente*

Wenn ein Benutzer eine Anforderung zum Senden eines Dokuments erhält und auf den Link zu dem Objekt klickt, für das das Dokument angefordert wurde, führt der Link zu einer leeren Seite. Dies kann auftreten, wenn Sie in einer E-Mail oder in einer In-App-Benachrichtigung auf einen Link klicken.

**Gruppe wird beim Konvertieren des Problems in ein Projekt falsch zugewiesen**

Gruppen

Wenn ein Benutzer ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, lautet die Funktionalität:

* Wenn der Vorlage eine Gruppe zugewiesen ist, wird diese Gruppe im Fenster zur Problemkonvertierung als Gruppe für das neue Projekt angezeigt.
* Wenn der Vorlage keine Gruppe zugewiesen ist, wird die Standardgruppe des Benutzers, der das Problem konvertiert, im Fenster zur Problemkonvertierung als Gruppe für das neue Projekt angezeigt.
* Wenn die Vorlage keine Gruppe enthält, sollte das neue Projekt die Gruppe vom Projekt des Problems übernehmen.

**Benutzerdefiniertes Objekt-übergreifendes Formular kann nicht an Anforderungswarteschlange angehängt werden**

Anforde- rungen

Wenn ein Benutzer versucht, ein benutzerdefiniertes Objekt-übergreifendes Formular zur Detailseite einer Warteschlange hinzuzufügen, wird das objektübergreifende Formular nicht in der Dropdown-Liste der verfügbaren Formulare angezeigt und der Benutzer kann es nicht auswählen, um es zur Warteschlangendetails hinzuzufügen.

**Benutzer können nicht mit der Rolle &quot;Sekundärer Auftrag&quot;für [!UICONTROL Lastenausgleich]**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer versucht, einen anderen Benutzer einer Aufgabe für die [!UICONTROL Lastenausgleich]und die Aufgabe einer anderen Rolle als der Rolle des zugewiesenen Hauptauftrags zugewiesen ist, wird der Benutzer der Aufgabe durch die Rolle des Hauptauftrags zugewiesen und die folgende Meldung wird angezeigt:

&quot;\&lt;name> entspricht nicht der Rolle von \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 Arbeitselement, das derzeit der Rolle &lt;\Task role assignment\> zugewiesen ist, wird \&lt;name> in der Rolle von \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Dies tritt auch dann auf, wenn der Benutzer die Rolle &quot;Auftrag&quot;der Aufgabenrollenzuweisung als sekundäre Aufgabe hat.

**Problem mit der Trommelfläche &quot;Weitere Arbeitselemente anzeigen&quot;b**&#x200B;

*Agile*

Wenn ein Benutzer auf die [!UICONTROL Anzeigen weiterer Arbeitselemente] Balken auf einem Scrum-Board, dann scrollen, um die neuen Elemente zu sehen, die [!UICONTROL Anzeigen weiterer Arbeitselemente] Der Balken bleibt am Scrum Board und bewegt sich mit ihm beim Scrollen. Dadurch können die Karten schwer lesbar werden.

**In benutzerdefinierten Formularen werden rote Punkte auf den erforderlichen Feldern angezeigt**

Benutzerdefinierte Formulare

Wenn ein Benutzer ein erforderliches Feld in einem benutzerdefinierten Formular anzeigt, werden unter dem Sternchen zwei rote Punkte angezeigt, die darauf hinweisen, dass das Feld erforderlich ist.

**Zeitabbruch in Eingabeaufforderungen**

*Berichte*

Wenn ein Benutzer die Aufforderung zur Eingabe eines Berichts ausfüllt und auf eine Datumsauswahl trifft, zeigt die Zeitauswahl am unteren Rand der Datumsauswahl keine Stunden nach 2 an und der Benutzer kann keinen Stundenwert neben 1 oder 2 auswählen.

+++

+++**Wartungs-Update (Hotfix) am 29. März 2022**

**Berechnungen können nicht im benutzerdefinierten Formular-Builder geändert oder gespeichert werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer eine Berechnung manuell in ein Berechnungsfeld im benutzerdefinierten Formular-Builder eingibt und das Formular speichert, wird die Berechnung nicht gespeichert. Wenn der Benutzer das benutzerdefinierte Formular erneut öffnet, ist dieses Feld leer.

Wenn ein Benutzer eine Berechnung in ein Berechnungsfeld im benutzerdefinierten Formular-Builder eingibt, indem er die Dropdown-Liste verwendet und das Formular speichert, wird dieser Wert gespeichert. Wenn der Benutzer das benutzerdefinierte Formular jedoch erneut öffnet, kann er dieses Feld weder manuell noch mit der Dropdown-Liste bearbeiten oder den Wert entfernen.

HINWEIS: Diese Problembehebung umfasste zusätzliche Funktionen. Wenn Sie nun mit der Eingabe in ein berechnetes Feld beginnen, werden mögliche Ausdrücke oder Berechnungen in einer Dropdown-Liste unten wie im Berechnungs-Editor angezeigt. Klicken Sie auf ein Element in der Dropdown-Liste, um es dem berechneten Feld hinzuzufügen.

+++

+++**Wartungs-Update am 24. März 2022**

**Zeitzonen sind nicht konsistent zwischen [!DNL Workfront] und[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Wenn das Profil eines Benutzers auf eine bestimmte Zeitzone in [!DNL Workfront], die Zeitzone des Benutzers in [!DNL Workfront Proof] auf eine andere Zeitzone eingestellt ist.

**Erforderlicher Feldfehler für ausgefüllte benutzerdefinierte Felder beim Anhängen einer Vorlage**

*Projekte*

Beim Anhängen einer Vorlage mit erforderlichen benutzerdefinierten Feldern an ein Projekt, in dem das Feld bereits vorhanden und ausgefüllt ist, wird dem Benutzer folgender Fehler angezeigt: &quot;[!UICONTROL Es gibt unvollständige Felder. Geben Sie Werte für die erforderlichen Felder ein, bevor Sie fortfahren können.]&quot; Klicken auf &quot;[!UICONTROL Bring mich dorthin]&quot; gibt ihnen die Möglichkeit zu sehen, dass die Felder ausgefüllt sind und sie die Vorlage erfolgreich anhängen können.

**Die [!UICONTROL Lastenausgleich] blinkt, wenn Sie zwischen Daten wechseln**

*[!UICONTROL Lastenausgleich]*

Die Stunden des Benutzers, die zuerst in der Variablen [!UICONTROL Lastenausgleich] werden nicht angezeigt, wenn Sie die Timeline aktualisieren. Der Benutzer und seine Stunden werden mit allen grauen Kästchen angezeigt, die einfach blinken. Dies geschieht, wenn Sie in der Timeline vorwärts und rückwärts fahren.

Durch die Aktualisierung des Filters wird die Anzeige offenbar zurückgesetzt. Wenn Sie die Timeline jedoch rückwärts und vorwärts bewegen, wird der Anzeigeblitz erneut angezeigt und die Benutzerzeiten werden nicht angezeigt.

**Benutzerdefinierte Terminologie ist inkonsistent**

*Layoutvorlagen*

Benutzer melden dies, wenn die [!DNL Workfront] Administrator passt die Terminologie für einige Objekte mithilfe einer Layout-Vorlage an. Der neue Objektname wird in der Benutzeroberfläche inkonsistent angezeigt.

Beispiel: auf der [!UICONTROL Projekte] Seite, können Sie weiterhin sehen, dass der Seitentitel als &quot;[!UICONTROL Projekte]&quot;, auch wenn die [!DNL Workfront] Administrator hat den Namen für &quot;[!UICONTROL Projekte]&quot;auf etwas Anderes.

Dies führt zu Verwirrung für Endbenutzer.

+++

+++**Wartungs-Update am 17. März 2022**

**Miniaturansichten und Hauptbilder sind beim Anzeigen mehrseitiger Dateien mit [!DNL Safari] browser**

*[!DNL Workfront Proof]*

Wenn ein Benutzer versucht, eine Datei mit mehreren Seiten im [!DNL Safari] -Browser verwenden, sind die Bilder der Miniaturansichten leer. Gelegentlich kann das Hauptbild auch leer sein.

**Falsche Benutzerliste bei Massenzuweisungen in der [!UICONTROL Lastenausgleich]**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer eine Massenzuweisung in der [!UICONTROL Lastenausgleich] und ein Projekt und eine Rolle &quot;Auftrag&quot;auswählt, ist die Liste der verfügbaren Benutzer falsch. Es kann Benutzer ohne die Rolle &quot;Auftrag&quot;oder &quot;Projekt&quot;anzeigen, und Benutzer mit der Rolle &quot;Auftrag&quot;und den Projektberechtigungen werden nicht in der Liste angezeigt.

**[!UICONTROL Die Sortierung funktioniert nicht in Berichten]**

*Berichte*

Wenn ein Benutzer auf eine Spalte klickt, um sie zu sortieren, scheint die Sortierung zu funktionieren, aber die Ergebnisse werden sofort in die ursprüngliche Sortierung zurückgesetzt, wie sie vor dem Klicken auf die Spalte angezeigt wird. Die Sortierung in einer Spalte wird nicht beibehalten.

**Auswählen von &quot;[!UICONTROL Nichts]&quot; wird auf die [!UICONTROL Berichtsstandard] grouping**

*Berichte*

Wenn ein Bericht eine integrierte Gruppierung aufweist und der Benutzer versucht, &quot;[!UICONTROL Nichts]&quot; in der [!UICONTROL Gruppierung] Dropdown-Menü, wird der Bericht in Kürze ohne Gruppierung angezeigt und kehrt dann zur [!UICONTROL Berichtsstandard] Gruppierung.

**Entfernt &quot;[!UICONTROL Blueprint-Zugriff]Registerkarte &quot;in Blueprint-Voreinstellungen**

*Blueprints*

HINWEIS: Dieses Problem tritt nur in der Vorschau -Umgebung auf.

Die [!UICONTROL Blueprint-Zugriff] -Registerkarte aus dem Modal für Blueprints-Voreinstellungen entfernt. In den Blueprints-Voreinstellungen wurde keine Funktionalität entfernt.

+++

+++**Wartungs-Update (Hotfix) am 14. März 2022**

**Benutzerliste kann nicht nach unten gescrollt werden, wenn eine Zuweisung auf der Kanban-Pinnwand vorgenommen wird**

*Agile*

Wenn ein Benutzer eine [!DNL Kanban] Pinnwand und versucht, eine Zuweisung vorzunehmen, die Benutzerliste, die angezeigt wird, wenn sie tippen, springt beim Bildlauf nach unten wieder nach oben. Der Benutzer kann keinen Benutzer auswählen, der sich nicht oben in der Liste befindet, und kann die Änderung der Zuweisung nicht speichern.

**[!UICONTROL Milestone] Anzeigen im Projektbericht verursacht Fehler**

*Berichte*

Beim Anzeigen eines Projektberichts mit dem [!UICONTROL Milestone] Anzeigen: Benutzer erhalten eine[!UICONTROL APIModel INTERNAL unterstützt &quot;namedQuery TILE:milestone-view&quot;(UIVW) nicht]&quot;.

**Benutzerdefinierte Terminologie ist inkonsistent**

*Layoutvorlagen*

Benutzer melden dies, wenn die [!DNL Workfront] Administrator passt die Terminologie für einige Objekte mithilfe einer Layout-Vorlage an. Der neue Objektname wird in der Benutzeroberfläche inkonsistent angezeigt.

Beispiel: auf der [!UICONTROL Projekte] Seite, können Sie weiterhin sehen, dass der Seitentitel als &quot;[!UICONTROL Projekte]&quot;, auch wenn die [!DNL Workfront] Administrator hat den Namen für &quot;[!UICONTROL Projekte]&quot;auf etwas Anderes.

Dies führt zu Verwirrung für Endbenutzer.

**Berechnungen für vorhandene berechnete Felder können nicht aktualisiert werden**

*Benutzerdefinierte Formulare*

Benutzer können die Berechnungen in berechneten Feldern nicht aktualisieren/ändern. Wenn das Feld ohne Berechnung erstellt und gespeichert wurde, wird der Builder jedes Mal, wenn Sie versuchen, einen Ausdruck hinzuzufügen und zu speichern/anzuwenden, wieder leer.

Wenn Sie ein berechnetes Feld mit einem bestimmten Ausdruck erstellen und speichern, wird jedes Mal, wenn Sie versuchen, die Berechnung zu ändern, der vorherige Wert zurückgesetzt.

**[!UICONTROL Ungültiger Parameter] Fehler beim Zurücksetzen von Kennwörtern**

*Anmeldung*

Benutzer können ihre Kennwörter in keiner Umgebung zurücksetzen. Wenn er seine E-Mail-Adresse eingibt und versucht, fortzufahren, wird ein Fehler angezeigt.

[!UICONTROL Fehler: Ungültiger Parameter: Suchparameterwert &quot;domain&quot;].

+++

+++**Wartungs-Update am 10. März 2022**

**Probleme bei der Anmeldung bei der Vorschau der Umgebung**

*Anmeldung*

Die folgenden Probleme bei der Anmeldung in der Vorschau-Umgebung wurden berichtet.

Wenn ein Benutzer versucht, sich bei der Vorschau-Umgebung anzumelden, wird eine Meldung angezeigt, die angibt, dass er die falsche ID oder das falsche Kennwort eingegeben hat.

Wenn ein Benutzer versucht, sein Kennwort zurückzusetzen, wird ihm der Fehler angezeigt:[!UICONTROL ?Mehrere Benutzer wurden mit der E-Mail-Adresse gefunden <example@example.com>?]&quot;

**Benutzerdefinierte Formulare werden langsam in [!UICONTROL Projektdetails] area**

*Projekte*

Wenn ein Benutzer versucht, die [!UICONTROL Projektdetails] -Bereich, alle benutzerdefinierten Formulare, die mit dem Projekt verknüpft sind, werden erst nach einer Verzögerung von 15 Sekunden oder mehr geladen. Die [!UICONTROL Hinzufügen benutzerdefinierter Formulare] ebenfalls von dieser Verzögerung betroffen ist.

**Benutzerdefinierte Formularfeldwerte, die nicht im Bereich &quot;Dokumentzusammenfassung&quot;gespeichert werden**

*Dokumente*

Wenn ein Benutzer benutzerdefinierte Formularfelder im Bereich mit der Dokumentzusammenfassung aktualisiert und mindestens eines davon ein typeahead -Feld ist, speichert dann die Änderungen und navigiert weg vom Zusammenfassungsbereich, werden die Aktualisierungen nicht gespeichert. Dies geschieht nur, wenn ein typeahead -Feld bearbeitet wird, jedoch alle Felder betroffen sind.

**Daten werden beim Konvertieren von Vorlagen aufgrund von Zugriffsstufen bei der Vorlagenfreigabe nicht beibehalten**

*Projekte*

Wenn ein Benutzer, der Zugriff auf eine freigegebene Vorlage hat, versucht, ein Problem in ein Projekt zu konvertieren, alle Daten in benutzerdefinierten Formularabschnitten, die [!UICONTROL Beitrag] oder ein höherer Zugriff auf die Ansicht nicht an das erstellte Projekt übertragen wird.

**Fehler beim Hochladen der neuen Dokumentversion**

*Dokumente*

Wenn ein Benutzer versucht, eine neue Version eines Dokuments aus der Dokumentliste hochzuladen, wird das Dokument nicht hochgeladen und der Benutzer sieht den folgenden Fehler:

[!UICONTROL Fehler Kann &quot;com.attask.boz.Document.getCurrentVersion()&quot;nicht aufrufen, da &quot;document&quot;null ist]

**Rechnungszinssätze können nicht bearbeitet werden**

*Projekte*

Wenn ein Benutzer versucht, eine Abrechnungsrate für die [!UICONTROL Abrechnungssätze] Registerkarte eines Projekts durch Klicken auf die [!UICONTROL Bearbeiten] -Schaltfläche öffnet die [!UICONTROL Bearbeiten] -Fenster kurz, es wird jedoch geschlossen, bevor der Benutzer die Abrechnungsrate bearbeiten kann. Durch erneutes Klicken auf die Schaltfläche wird das Bearbeitungsfenster nicht geöffnet.

**Öffentlicher Link für Dokument führt zu leerer Seite**

*Dokumente*

Wenn ein Benutzer versucht, ein Dokument mithilfe eines öffentlichen Links zu öffnen, führt der Link zu einer leeren Seite. Dies tritt auf, wenn der Link in einem Fenster geöffnet wird, in dem ein aktiver [!DNL Workfront] -Sitzung geöffnet ist.

**Hopfenfehler beim Hinzufügen von Aufgabe oder Problem zur Liste**

*Aufgaben und Probleme*

Wenn ein Benutzer, der kein Administrator ist, versucht, eine Aufgabe oder ein Problem zu einer Liste hinzuzufügen und benutzerdefinierte Felder auszufüllen, wird die Aufgabe bzw. das Problem nicht erstellt und der Benutzer sieht den folgenden Fehler:

[!UICONTROL Fehler-Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]

**Wird eine Aktualisierung nach einer Statusänderung beibehalten, wird das Objekt wieder in den vorherigen Status versetzt**

Projekte, Aufgaben und Probleme

Wenn Sie den Status eines Projekts, einer Aufgabe oder eines Problems ändern und dann sofort mit der Eingabe eines Updates beginnen, ohne die Seite zu aktualisieren, zeigt das Aktualisierungsfeld den vorherigen Status an. Wenn die Aktualisierung veröffentlicht wird, wird das Objekt wieder in den vorherigen Status versetzt.

**Benutzer, die zu Testsendungen hinzugefügt wurden, haben falsche Rollen**

*Korrekturabzüge*

Wenn ein Benutzer einen anderen Benutzer zu einem Testversand hinzufügt, wird die Rolle dieses Benutzers im Testversand als &quot;&quot;festgelegt.[!UICONTROL Schreibgeschützt]&quot; trotz der tatsächlichen Testversandrolle des Benutzers.

Problemumgehung: Setzen Sie die Rolle &quot;Testversand&quot;des Benutzers in seinem Profil auf etwas Anderes und setzen Sie dann die richtige Rolle zurück.

**Benutzerdefiniertes Formular wird beim Konvertieren des Problems in ein Projekt mit einer Vorlage nicht geladen**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, werden möglicherweise mindestens eines der benutzerdefinierten Formulare, die an die Vorlage angehängt sind, nicht geladen. Wenn der Benutzer die Vorlage für das neue Projekt konfiguriert, wird anstelle der benutzerdefinierten Formulare die folgende Meldung angezeigt:

&quot;[!UICONTROL Irgendetwas ist schiefgelaufen, Formular konnte nicht geladen werden].&quot;

**Benutzer können Problem nicht inline mit benutzerdefiniertem Dropdown-Feld hinzufügen, das in der Ansicht angezeigt wird**

*Listen*

Wenn ein Benutzer ein Problem inline hinzufügt und eine benutzerdefinierte Ansicht mit benutzerdefinierten Dropdown-Feldern auf die Liste angewendet wird, tritt ein Fehler auf, wenn er nur das Dropdown-Feld ausfüllt. Der Benutzer hat Zugriff auf das Bearbeiten eines benutzerdefinierten Formulars und ist der Projekteigentümer mit Verwaltungsrechten für das Projekt.

[!UICONTROL Fehler: Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es reparieren können!]

**Berechtigungen zum Hinzufügen von Aufgaben zu einem Projekt sind nicht erforderlich, um eine Aufgabe in das Projekt zu verschieben oder zu kopieren**

*Aufgaben*

Sie können jetzt eine Aufgabe in eine andere Aufgabe in einem Projekt verschieben oder kopieren, ohne über die Berechtigungen zum Hinzufügen von Aufgaben zum Zielprojekt verfügen zu müssen. Sie müssen über die Berechtigung zum Hinzufügen von Aufgaben zu mindestens einer der Aufgaben des Zielprojekts verfügen. Vor dieser Aktualisierung waren Sie berechtigt, dem Projekt Aufgaben hinzuzufügen, mit denen Sie eine Aufgabe in das Projekt oder eine seiner Aufgaben verschieben oder kopieren können.  Dieses Update ist jetzt in der Produktionsumgebung verfügbar. Sie ist ab dem 24. März 2022 Maintenance Update in der Vorschau-Umgebung verfügbar.

HINWEIS: Dieses Update ist in der Produktionsumgebung verfügbar, wenn Probleme nach der Produktionsversion 2.2 kopiert oder verschoben werden. Weitere Informationen zur aktuellen Version finden Sie unter workfront.com/release.

**Dropdown-Menü &quot;Eingabeaufforderung&quot;ist abgeschnitten.**

*Berichte*

Bei der Verwendung einer Eingabeaufforderung in einem Bericht werden die Dropdownmenüs, die die Auswahl der Filterkriterien für den Bericht ermöglichen, abgeschnitten. Daher werden die Kriterien unten im Auswahl-Dropdown-Menü nicht angezeigt.

**Das Arbeitselement kehrt bei einer Aktualisierung zum vorherigen Status zurück**

*Updates*

Wenn ein Benutzer den Status eines Arbeitselements in der Kopfzeile ändert, wird der Status im [!UICONTROL Aktualisieren] Bereich. Wenn der Benutzer dann eine Aktualisierung vornimmt, zeigt das Dropdown-Menü weiterhin den vorherigen Status an. Wenn die Aktualisierung gespeichert wird, überschreibt dieser vorherige, falsche Status den in der Kopfzeile festgelegten Status.

+++

+++**Wartungs-Update am 3. März 2022**

**Dokument kann nicht hinzugefügt werden aus[!DNL Google Drive]**

*Dokumente*

Wenn ein Benutzer versucht, ein Dokument aus [!DNL Google Drive], reagiert die Auswahl nicht und der Benutzer kann keine Dokumente auswählen, die hinzugefügt werden sollen.

**Tagging-Benutzer werden nicht zum Aktualisieren von Threads hinzugefügt**

*Updates*

Wenn ein Benutzer in einer Aktualisierung mit Tags versehen ist, wird er nicht im[!UICONTROL nach]&quot;Bereich der Aktualisierung oder der Antworten.

**Der Testversand-Benutzer verfügt über zwei separate Testversandkonten.**

*[!DNL Workfront Proof]*

Die E-Mail-Adresse eines Benutzers in [!DNL Workfront Proof] kann sich in zwei separaten Konten mit separaten IDs befinden, sodass der Benutzer zwei Konten erhält. Dadurch kann es schwierig werden, das richtige Konto zu finden.

**Hopfenfehler in Berichtkopfzeilen angezeigt**

*Berichte*

Wenn ein Benutzer einen Bericht anzeigt, wird der folgende Fehler in der Kopfzeile des Berichts angezeigt:

&quot;[!UICONTROL Versuchen Sie es erneut. Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

Wenn der Benutzer ein Dashboard anzeigt, wird der Fehler möglicherweise in der Kopfzeile aller Berichte im Dashboard angezeigt.

**Daten in Feldern, die nur in der Admin-Bearbeitung des benutzerdefinierten Formulars enthalten sind, werden beim Konvertieren von Problemen in Projekte nicht beibehalten**

*Projekte*

Wenn ein Benutzer ohne Administratorrechte versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, und das Problem Daten in Feldern enthält, die nur von einem Administrator bearbeitet werden können, werden die Daten in diesen Feldern nicht in das neue Projekt übertragen.

Wenn ein Administrator das Problem konvertiert, werden die Daten erwartungsgemäß in das neue Projekt übertragen.

**[!DNL XLS]und [!DNL XLSX] Die Dateigrößenbeschränkung wurde für Testsendungen vorübergehend auf 100 MB reduziert**

*Proofing*

Um ein Sicherheitsproblem zu beheben, haben wir die maximale Dateigröße für [!DNL XLS] und [!DNL XLSX] -Dateien bei der Erstellung eines Testversands auf 100 MB erhöht.

HINWEIS: Diese Aktualisierung fand am 24. Februar in der Vorschau-Umgebung statt und wird sich am 3. März in der Produktionsumgebung befinden.

**Aktualisierung der Workfront-Suche**

Suchen

Eine schrittweise Einführung begann diese Woche, um die Infrastruktur für die [!DNL Workfront] Suchfunktion. Die Aktualisierung wird zukünftige Verbesserungen der Suche einfacher und zuverlässiger machen. Mit diesen Änderungen werden Elemente zu [!DNL Workfront] schneller indiziert werden und daher früher in den Suchergebnissen zurückgegeben werden.

Die schrittweise Einführung wird 2 Wochen dauern.

**Aktualisierte Symbolleisten für Berichte in Dashboards**

Berichte

In Berichten in Dashboards wird jetzt eine neue Symbolleiste angezeigt. Diese Symbolleiste ist Teil der Aktualisierungen von Listen und Berichten, die in allen [!DNL Workfront].

+++


## Aktualisierungen im Februar 2022

+++**Wartungs-Update (Hotfix) am 24. Februar 2022**

**Daten werden beim Konvertieren von Problemen in Projekte nicht beibehalten, wenn das Feld in der Vorlage ausgeblendet ist**

*Projekte*

Wenn ein Benutzer ein Problem in eine Vorlage konvertiert und die Vorlage ein benutzerdefiniertes Formular enthält, das Felder basierend auf den Werten in anderen Feldern anzeigt oder ausblendet, werden Daten in Feldern, die zum Zeitpunkt der Konvertierung in der (datallosen) Vorlage verborgen sind, nicht in das neue Projekt übernommen.

**Ressourcenplaner kann nicht nach Rolle exportiert werden**

*Ressourcenplaner*

Wenn ein Benutzer versucht, die [!DNL Resource Planner] bei Verwendung der [!UICONTROL Ansicht nach Rolle] gesetzt ist, ist der Export nicht erfolgreich und der Benutzer erhält eine E-Mail mit der folgenden Nachricht:

Beim Exportieren Ihrer [!DNL Resource Planner] Daten.

**Schaltfläche &quot;Anforderung kopieren&quot;funktioniert nicht**

*Anforde- rungen*

Wenn ein Benutzer versucht, eine Anforderung zu kopieren, wird die [!UICONTROL Anforderung kopieren] -Schaltfläche funktioniert nicht, wenn der Benutzer keinen Zugriff auf das Warteschlangenthema hat.

+++

+++**Wartungs-Update am 24. Februar 2022**

**Benutzerdefinierte Formulardaten werden ausgeblendet, wenn andere Formularfelder ausgefüllt werden**

*Benutzerdefinierte Formulare in meiner Gruppe*

Wenn ein Benutzer ein benutzerdefiniertes Formular ausfüllt, um ein Problem in ein Projekt zu konvertieren, kann das Ausfüllen eines benutzerdefinierten Felds dazu führen, dass Daten in einem anderen benutzerdefinierten Feld nicht mehr angezeigt werden. Wenn der Benutzer die fehlenden Daten erneut eingibt und versucht, das Projekt zu erstellen, wird ihm die folgende Fehlermeldung angezeigt:

&quot;[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]&quot;

**&quot;[!UICONTROL Dieser Validierungsprozess kann von ...]&quot; -Feld fehlt**

*Genehmigungen*

Wenn ein Benutzer einen Genehmigungsprozess im [!UICONTROL Einrichtung] -Bereich[!UICONTROL Dieser Validierungsprozess kann von ...]&quot;-Feld fehlt. Dies kann beim Erstellen eines Validierungsprozesses oder beim Bearbeiten eines vorhandenen Validierungsprozesses auftreten.

**Der Systemadministrator kann Benutzer beim Löschen einer Gruppe nicht neu zuweisen**

*Gruppen*

Wenn ein Systemadministrator eine Gruppe löscht, kann er die Benutzer dieser Gruppe nur Gruppen zuweisen, für die der Systemadministrator ein Gruppenadministrator ist. Andere Gruppen werden nicht im Dropdown-Menü angezeigt und der Administrator kann sie nicht auswählen.

**Hopfenfehler beim Konvertieren des Problems in ein Projekt**

*Projekte*

Wenn ein Benutzer versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren und benutzerdefinierte Formulare aus der Vorlage hinzufügt oder daraus entfernt, wird das Problem nicht konvertiert und der Benutzer wird über die folgende Meldung informiert:

[!UICONTROL Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]

**Testversand kann nicht geöffnet werden; Seitenaktualisierungen**

*Korrekturabzüge*

Wenn ein Benutzer versucht, einen Testversand zu öffnen, kann der Testversand nicht geöffnet werden. Schließlich wird die Seite aktualisiert.

**[!DNL XLS]und [!DNL XLSX] Die Dateigrößenbeschränkung wurde für Testsendungen vorübergehend auf 100 MB reduziert**

*Testversand*

Um ein Sicherheitsproblem zu beheben, haben wir die maximale Dateigröße für [!DNL XLS] und [!DNL XLSX] -Dateien bei der Erstellung eines Testversands auf 100 MB erhöht.

HINWEIS: Diese Aktualisierung wird am 24. Februar in der Vorschau-Umgebung und am 3. März in der Produktionsumgebung vorgenommen.

**Berechtigungen zum Hinzufügen von Aufgaben oder Problemen zu einem Projekt sind nicht erforderlich, um eine Aufgabe oder ein Problem in das Projekt zu verschieben oder zu kopieren**

*Projekte*

Sie können jetzt eine Aufgabe oder ein Problem in eine andere Aufgabe in einem Projekt verschieben oder kopieren, ohne über die Berechtigungen zum Hinzufügen von Aufgaben oder Problemen zum Zielprojekt verfügen zu müssen. Sie müssen über die Berechtigung zum Hinzufügen von Aufgaben oder Problemen zu mindestens einer der Aufgaben des Zielprojekts verfügen. Vor dieser Aktualisierung waren Sie berechtigt, Aufgaben oder Probleme zum Verschieben oder Kopieren einer Aufgabe oder eines Problems in das Projekt oder in eine seiner Aufgaben hinzuzufügen. Diese Aktualisierung ist nur in der Vorschau -Umgebung verfügbar.

HINWEIS: Dieses Update ist ab dem 10. März in der Produktionsumgebung verfügbar, wenn Aufgaben bearbeitet oder verschoben werden. Dieses Update ist in der Produktionsumgebung verfügbar, wenn Probleme mit der Produktionsversion 2.2 kopiert oder verschoben werden. Weitere Informationen zur aktuellen Version finden Sie unter workfront.com/release.

**Aktualisierung der Workfront-Suche**

*Suchen*

Eine schrittweise Einführung begann diese Woche, um die Infrastruktur für die [!DNL Workfront] Suchfunktion. Die Aktualisierung wird zukünftige Verbesserungen der Suche einfacher und zuverlässiger machen. Mit diesen Änderungen werden Elemente zu [!DNL Workfront] schneller indiziert werden und daher früher in den Suchergebnissen zurückgegeben werden.

Die schrittweise Einführung wird 2 Wochen dauern.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 18. Februar 2022**

**Validierung des Feldwerttyps hinzugefügt [!DNL Anaplan] Eigenschaften von Listenelementen**

*[!DNL Adobe Workfront Fusion]*

Es wurde ein Problem behoben, durch das Benutzer den falschen Datentyp in Felder für Eigenschaften von Listenelementen einfügen konnten. Die Validierung des Eigenschaftstyps ermöglicht Folgendes: [!DNL Fusion] um sicherzustellen, dass der richtige Datentyp an Anaplan gesendet wird, sodass Fehler, die durch falsche Datentypen verursacht werden, vermieden werden.

+++

+++**Wartungs-Update am 17. Februar 2022**

**Fehler beim Löschen des Vorgängers auf der Registerkarte &quot;Vorgänger&quot;**

*Aufgaben*

Wenn ein Benutzer versucht, einen Vorgänger aus der [!UICONTROL Vorgänger] -Tab einer Aufgabe wird die Aufgabe nicht gelöscht und dem Benutzer wird der folgende Fehler angezeigt:

[!UICONTROL Aufgabe mit dem/den Primärschlüsselwert(en) &quot;&quot;nicht gefunden]

**Hopfenfehler beim Öffnen der Benutzerseite**

*Benutzer*

Wenn ein Benutzer versucht, die [!UICONTROL Benutzer] -Seite, wird die Seite nicht geöffnet und der Benutzer sieht den folgenden Fehler:

[!UICONTROL Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]

**Elemente in der Kopfzeile eines Berichts in einem Dashboard überschneiden**

*Dashboards*

Wenn ein Benutzer einen Bericht in einem Dashboard anzeigt, sieht er, dass das Gruppierungssymbol und die Bezeichnung die Links zu [!UICONTROL Details] und [!UICONTROL Zusammenfassung].

**Probleme mit[!UICONTROL Mehr]&quot;Menü für Dokumente und Testsendungen**

*Dokumente*

Wenn ein Benutzer ein Dokument oder einen Testversand für eine [!DNL Workfront Classic] Dokumentliste und klickt dann auf &quot;[!UICONTROL Mehr],&quot;kann eines der folgenden Probleme auftreten: Die Schaltfläche reagiert nicht Alle Optionen unter der Schaltfläche sind mit &quot;[!UICONTROL Objekt-Objekt]&quot; und kann nicht verwendet werden.

**Fehler &quot;Sie müssen ein Systemadministrator sein&quot;beim Erstellen eines Projekts**

*Projekte*

Wenn ein Benutzer, der kein Administrator ist, versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, für das nur Administratoren einen Abschnitt zur Verfügung haben, kann er das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

&quot;Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern&quot;

**Daten im Abschnitt &quot;Nur Administrator&quot;des benutzerdefinierten Formulars werden beim Konvertieren von Problemen in Projekte nicht beibehalten**

*Projekte*

Wenn ein Benutzer ein Problem mithilfe einer Vorlage mit einem benutzerdefinierten Formular mit einem reinen Administratorbereich in ein Projekt konvertiert, werden keine Daten im Abschnitt &quot;Nur Administrator&quot;in das neue Projekt übernommen. Dies tritt auch dann auf, wenn ein Administrator das Problem konvertiert.

+++

+++**Wartungs-Update am 10. Februar 2022**

**&quot;[!UICONTROL Sie müssen Systemadministrator sein.]&quot;-Fehler beim Erstellen eines Projekts**

*Projekte*

Wenn ein Benutzer, der kein Administrator ist, versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, für das nur Administratoren einen Abschnitt zur Verfügung haben, kann er das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

&quot;[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]&quot;

**Benutzer, die deaktiviert und reaktiviert wurden, werden nicht in [!UICONTROL Kontakte nachweisen]**

*[!DNL Workfront Proof]*

Wenn ein Benutzer seine Kontaktliste in [!DNL Workfront Proof], werden Benutzer, die deaktiviert und reaktiviert wurden, nicht in der Liste angezeigt.

**Meldung &quot;Irgendetwas ist schiefgelaufen&quot; beim Konvertieren eines Problems in ein Projekt mithilfe einer Vorlage**

*Projekte*

Wenn ein Benutzer, der kein Administrator ist, versucht, ein Problem mithilfe einer Vorlage in ein Projekt zu konvertieren, wird in benutzerdefinierten Formularfeldern, die nur für Administratoren sichtbar sind, die folgende Meldung angezeigt:

&quot;[!UICONTROL Irgendetwas ist schiefgelaufen, Formular konnte nicht geladen werden]&quot;

**Fehler &quot;Seiteninhalt kann nicht geladen werden&quot;bei der Anzeige von Projektanvoreinstellungen**

*Einrichtung*

Wenn ein Administrator versucht, Projekte, Aufgaben oder Probleme unter anzuzeigen [!UICONTROL Projektvoreinstellungen] im [!UICONTROL Einrichtung] -Bereich, wird die Seite nicht geladen und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Seiteninhalt kann nicht geladen werden. Bitte aktualisieren Sie die Seite.]&quot;

+++

+++**Wartungs-Update am 3. Februar 2022**

**[!UICONTROL BizContext] Fehler beim Anmelden**

*Anmeldung*

Wenn ein Benutzer versucht, sich bei [!DNL Workfront], ist die Anmeldung nicht erfolgreich und die folgende Meldung wird angezeigt:

&quot;[!UICONTROL Versuchen Sie es erneut. Datenbankfehler: BizContext commit failed!]&quot;

Dies wurde in der Vorschau -Umgebung gemeldet.

**Der Aktualisierungsstream für Probleme verschwindet, wenn das Problem noch nicht genehmigt wurde**

*Updates*

Wenn ein Benutzer in die [!UICONTROL Neues Update] im Aktualisierungsstream eines Problems, das noch nicht genehmigt wurde, wird der gesamte Aktualisierungsstream ausgeblendet.

**Fehler beim Hochladen einer neuen Version eines Dokuments**

*Dokumente*

Wenn ein Benutzer versucht, eine neue Version eines Dokuments hochzuladen, wird die neue Version nicht hochgeladen und der Benutzer sieht einen der folgenden Fehler:

* [!UICONTROL documentID darf nicht null sein]
* [!UICONTROL Fehler: Ungültiger Parameter: documentID-Wert &quot;undefined&quot;]

**Öffentlicher Link für Dokument führt zu leerer Seite**

*Dokumente*

Wenn ein Benutzer versucht, ein Dokument mithilfe eines öffentlichen Links zu öffnen, führt der Link zu einer leeren Seite. Dies tritt auf, wenn der Link in einem Fenster geöffnet wird, in dem ein aktiver [!DNL Workfront] -Sitzung geöffnet ist.

**Listensteuerelemente funktionieren nicht in Berichten in Dashboards**

*Dashboards*

Wenn ein Benutzer einen Bericht in einem Dashboard anzeigt und versucht, den Filter, die Gruppierung oder die Ansicht des Berichts zu ändern, ändert sich der Filter, die Gruppierung oder die Ansicht nicht.

**&quot;[!UICONTROL Sie müssen Systemadministrator sein.]&quot;-Fehler beim Erstellen eines Projekts**

*Projekte*

Wenn ein Benutzer, der kein Administrator ist, versucht, ein Projekt zu erstellen und ein benutzerdefiniertes Formular angehängt, für das nur Administratoren einen Abschnitt zur Verfügung haben, kann er das Projekt nicht erstellen und es wird der folgende Fehler angezeigt:

&quot;[!UICONTROL Sie müssen Systemadministrator sein, um diesen benutzerspezifischen Parameterwert zu ändern]&quot;

**Benutzerdefinierte Daten werden beim Konvertieren des Problems in das Projekt nicht beibehalten**

*Projekte*

Wenn ein Benutzer ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, werden die Daten aus einem benutzerdefinierten Formular zum Problem nicht in das vergleichbare benutzerdefinierte Formular im Projekt übertragen. Dies geschieht mit Daten in benutzerdefinierten Feldern, die basierend auf den Werten anderer benutzerdefinierter Felder ausgeblendet werden können.

**Fehler beim Konvertieren des Problems in ein Projekt**

*Projekte*

Wenn ein Benutzer versucht, ein Problem in ein Projekt zu konvertieren, wird das Problem nicht konvertiert und der folgende Fehler wird angezeigt:

&quot;[!UICONTROL Unerwarteter Fehler]&quot;

+++


## Aktualisierungen im Januar 2022

+++**Wartungs-Update am 27. Januar 2022**

**Benutzerdefinierte Daten werden beim Konvertieren des Problems in das Projekt nicht beibehalten**

*Projekte*

Wenn ein Benutzer ein Problem mithilfe einer Vorlage in ein Projekt konvertiert, werden die Daten aus einem benutzerdefinierten Formular zum Problem nicht in das vergleichbare benutzerdefinierte Formular im Projekt übertragen. Dies geschieht mit Daten in benutzerdefinierten Feldern, die basierend auf den Werten anderer benutzerdefinierter Felder ausgeblendet werden können.

**Die Benutzerliste auf der agilen Pinnwand ist nicht alphabetisch**

*Agile*

Wenn ein Benutzer die Benutzerliste auf einer agilen Pinnwand anzeigt, werden die Benutzer nicht in alphabetischer Reihenfolge angezeigt. Stattdessen werden die Benutzer mit den meisten Zuweisungen zuerst aufgelistet.

**Aktualisierte Links zum Kopieren und Verschieben von Problemen**

*Anfragen*

In der Umgebung &quot;Vorschau&quot;wurden die Links zum Kopieren und Verschieben von Problemen auf &quot;[!UICONTROL Kopieren nach]&quot; und &quot;[!UICONTROL Verschieben nach]&quot;sowohl auf der Seite mit den Problemen als auch in der Liste der Probleme.

**Fügen Sie bis zu 45 IP-Adressen zu Ihren [!DNL Workfront] Zulassungsliste**

*Einrichtung*

Die Beschränkung für IP-Adressen, die zu Ihren [!DNL Workfront] Die Zulassungsliste von  ist von 30 auf 45 gestiegen.

+++

+++**Wartungs-Update am 20. Januar 2022**

**&quot;[!UICONTROL Ungültiger Parameter]&quot;-Fehler beim Erstellen eines Projekts aus einer Vorlage**

*Projekte*

Wenn ein Benutzer versucht, ein Projekt aus einer Vorlage zu erstellen, und beim Erstellen des Projekts ein benutzerdefiniertes Formular aus der Vorlage entfernt, wird das Projekt nicht erstellt und dem Benutzer wird ein[!UICONTROL Ungültiger Parameter]&quot; Fehlermeldung, die ein erforderliches Feld im entfernten benutzerdefinierten Formular erwähnt.

**Benutzerliste wird nicht geladen in [!DNL Safari] browser**

*Benutzer*

Wenn ein Benutzer zum [!UICONTROL Benutzer] -Bereich, wird die Kopfzeile angezeigt, die Liste der Benutzer wird jedoch nicht geladen.

**Wenn Sie Aufgaben in eine Liste ziehen, wird die Aufgabe beim Ziehen an die falsche Position verschoben**

*Listen*

Wenn ein Benutzer versucht, eine Aufgabe durch Ziehen in eine Liste zu verschieben, wird die blaue Linie, die angibt, wohin die Aufgabe verschoben wird, viel langsamer verschoben als der Cursor. Wenn der Benutzer die Aufgabe freigibt, wird er an die blaue Linie verschoben, auch wenn der Cursor auf eine andere Position in der Liste zeigt.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 14. Januar 2022**

**Einige zugeordnete Felder werden bei Auswahl zurückgesetzt [!UICONTROL Neues Feld zur Zuordnung]**

*[!DNL Workfront Fusion]*

Wenn mindestens ein Feld im [!DNL Workfront] [!UICONTROL Erstellen] oder [!UICONTROL Aktualisieren] -Module sind für die Zuordnung aktiviert und ein Benutzer wählt ein neues Feld aus, das zugeordnet werden soll. Die zuvor zugeordneten Felder, für die die Zuordnung aktiviert ist, verlieren die Zuordnungswerte.

+++

+++**Wartungs-Update am 13. Januar 2022**

**Es ist nicht möglich, einen Hyperlink zu einem Kommentar im Bereich &quot;Zusammenfassung&quot;hinzuzufügen**

*Aufgaben*

Wenn ein Benutzer im Zusammenfassungsfenster einer Aufgabe einen Kommentar abgibt und versucht, dem Kommentar einen Hyperlink hinzuzufügen, wird das Hyperlink-Fenster geöffnet. Sobald der Benutzer jedoch in das Fenster klickt, wird es geschlossen und der Benutzer kann keinen Hyperlink hinzufügen. Wenn ein Benutzer mit der Tabulatortaste in das Fenster springt, kann er einen Link in das Feld eingeben oder einfügen, der Hyperlink wird jedoch nicht gespeichert. In beiden Fällen wird die Aufgabe deaktiviert.

**Seite &quot;Team bearbeiten&quot;wird nicht geschlossen**

*Teams*

Wenn ein Benutzer versucht, ein Team zu bearbeiten, wird die [!DNL Edit team] Seite wird nicht geschlossen. Der Benutzer kann die Seite nicht schließen, indem er auf eine der Schaltflächen klickt, auf das X klickt oder von der Seite weg navigiert.

**E-Mail- und In-App-Benachrichtigungen werden nicht gesendet**

*Benachrichtigungen*

Wenn ein Ereignis auftritt, das eine Benachrichtigung Trigger, wird die Benachrichtigung nicht gesendet. Dies kann bei E-Mail- oder In-App-Benachrichtigungen auftreten, auch wenn andere Benachrichtigungen gesendet werden.

**[!UICONTROL Meine Arbeit] Liste erscheint leer**

*[!UICONTROL Meine Arbeit]*

Wenn ein Benutzer seine [!UICONTROL Meine Arbeit] und die Layout-Vorlage für [!UICONTROL Meine Arbeit] enthält einen numerischen Wert, z. B. [!UICONTROL Prozent abgeschlossen], die [!UICONTROL Meine Arbeit] Liste wird nicht angezeigt.

**[!UICONTROL Prozent abgeschlossen] und [!UICONTROL Stunden abgeschlossen] kann nicht auf der Agile Board geändert werden**

*Agile*

Wenn ein Benutzer &quot;[!UICONTROL Anzeigen weiterer Arbeitselemente]&quot; auf der Agile-Pinnwand, versucht dann, die [!UICONTROL Prozent abgeschlossen] oder [!UICONTROL Stunden abgeschlossen] für eines der neu geladenen Arbeitselemente, können sie die &quot;Percent Complete&quot;oder &quot;Hours Complete&quot;nicht ändern. Die [!UICONTROL Prozent abgeschlossen] -Schaltfläche ist auch grau und zeigt an, dass sie inaktiv ist.

+++

+++**Wartungs-Update am 6. Januar 2022**

**&quot;[!UICONTROL Ungültiger Parameter]&quot;-Fehler beim Anhängen von Vorlagen oder benutzerdefinierten Formularen an Projekte**

*Projekte*

Wenn ein Benutzer versucht, ein benutzerdefiniertes Formular oder eine Vorlage an ein vorhandenes Projekt anzuhängen, dann die erforderlichen Felder im benutzerdefinierten Formular oder in der benutzerdefinierten Vorlage ausfüllt und die Änderungen am Projekt speichert, werden die Änderungen nicht gespeichert und der Benutzer sieht ein &quot;[!UICONTROL Ungültiger Parameter]&quot; oben auf der Seite mit den Projektdetails angezeigt.

**Testkommentare werden in Dokumentaktualisierungen nicht angezeigt**

*Korrekturabzüge*

Wenn ein Benutzer einen Testversand in der [!UICONTROL Dokumente] -Bereich, alle Kommentare zum Testversand selbst werden nicht im [!UICONTROL Updates] Bereich des Dokuments.

**[!UICONTROL Workload Balancer]: &quot;[!UICONTROL ?[Objekt-Objekt]?]&quot; wird in Überzuordnungs-Informationen angezeigt**

*[!UICONTROL Lastenausgleich]*

Wenn ein Benutzer in der Variablen [!UICONTROL Lastenausgleich] aufgrund einer Aufgabe, die die Zeitüberschreitung des Benutzers überschneidet, und einem anderen Benutzer die Überzuweisung anzeigt,[!UICONTROL Kapazität]&quot; Der Bereich der Überzuordnungs-Informationen zeigt &quot;[!UICONTROL ?[Objekt-Objekt]?]&quot; anstelle der tatsächlichen Kapazität des Benutzers.

+++

## Vorherige Wartungsupdates

Informationen zu vorherigen Wartungsupdates finden Sie hier:

* [[!DNL Workfront] Archiv für Wartungsaktualisierungen - 2021](2021-updates.md)
