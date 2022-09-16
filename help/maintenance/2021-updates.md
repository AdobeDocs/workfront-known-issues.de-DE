---
title: Workfront-Wartungsupdates für 2021
description: Verlauf der Wartungsupdates 2021 für [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: tm+mt
source-wordcount: '10019'
ht-degree: 3%

---

# 2021 [!DNL Workfront] Wartungsaktualisierungen

Die folgenden Wartungsaktualisierungen wurden 2021 vorgenommen:

## Aktualisierungen im Dezember 2021

+++**Wartungs-Update am 23. Dezember 2021**

**Für neue Aufgaben wird standardmäßig eine falsche Aufgabenbegrenzung festgelegt**

_Aufgaben_

Wenn ein Benutzer eine neue Aufgabe mit dem[!UICONTROL Neue Aufgabe]&quot;, und die [!UICONTROL Neuer Task Default Start] Die Option Datum ist auf &quot;[!UICONTROL Heute],&quot;wird die Aufgabenbegrenzung der erstellten Aufgabe auf &quot;[!UICONTROL So bald wie möglich]&quot; anstelle von &quot;[!UICONTROL Start nicht früher als].&quot; Dies kann auch bei der Verwendung von Projektvorlagen auftreten.

**Zeitplan öffnen in [!UICONTROL Gruppen] -Bereich führt zu einer leeren Seite**

_Setup_

Wenn ein Benutzer Gruppen im [!UICONTROL Einrichtung] -Bereich und versucht, einen Zeitplan zu öffnen, zu bearbeiten oder zu kopieren, wird der Zeitplan nicht geöffnet und dem Benutzer wird eine leere Seite angezeigt.

**Änderungen werden bei der Neuanordnung der linken Navigation nicht angezeigt**

_Navigation_

Wenn ein Benutzer versucht, das linke Navigationsfenster durch Ziehen eines Elements neu anzuordnen, wird das Element an der vorherigen Position angezeigt, wenn der Benutzer es verlässt. Wenn der Benutzer die Seite aktualisiert, wird die neue Reihenfolge im linken Bereich angezeigt.

**Der Link zum Senden eines angeforderten Dokuments führt zu einer leeren Seite.**

_Dokumente_

Wenn ein Benutzer eine Anforderung zum Senden eines Dokuments erhält und auf den Link zu dem Objekt klickt, für das das Dokument angefordert wurde, führt der Link zu einer leeren Seite. Dies kann auftreten, wenn Sie in einer E-Mail oder in einer In-App-Benachrichtigung auf einen Link klicken.

**[!UICONTROL Lastenausgleich] zeigt 0 Stunden zugeteilt**

_[!UICONTROL Workload Balancer]_

Wenn ein Benutzer die [!UICONTROL Lastenausgleich] und &quot;[!UICONTROL Prognosedaten anzeigen]&quot; aktiviert ist, zeigen alle Daten in der Zukunft 0 zugewiesene Stunden an.

**Testsendungen verschwinden gelegentlich aus Ordnern**

_[!DNL Workfront Proof]_

Wenn ein Benutzer, der sich bei [!DNL Workfront Proof] einen Ordner anzeigt, wird der Ordner leer angezeigt. Wenn der Benutzer zu einem späteren Zeitpunkt zurückkehrt, sind die Testsendungen sichtbar.

+++

+++**Wartungs-Update am 16. Dezember 2021**

**Durch Klicken auf die Mitteilung in der Benachrichtigungsliste wird eine leere Seite angezeigt**

_Benachrichtigungen_

Wenn ein Benutzer seine Benachrichtigungsliste über die [!UICONTROL Benachrichtigungen] klicken, klicken Sie dann auf eine Mitteilung, werden sie auf eine leere Seite weitergeleitet und die Mitteilung wird nicht angezeigt.

**Das Zusammenfassungsfenster zeigt Folgendes an:[!UICONTROL Keine Auswahl]&quot; bei Auswahl der Aufgabe**

_Aufgaben_

Wenn ein Benutzer eine Dokumentzusammenfassung in der [!UICONTROL Dokumente] -Bereich eines Projekts, dann zur Aufgabenliste, wählt eine Aufgabe aus und versucht, die Aufgabenzusammenfassung zu öffnen, die Aufgabenzusammenfassung wird nicht angezeigt und der Benutzer sieht die folgende Nachricht:

[!UICONTROL Keine Auswahl getroffen. Ein Dokument in der Liste auswählen, um die Details anzuzeigen.]

In der Nachricht werden Dokumente erwähnt, auch wenn sich der Benutzer in der Aufgabenliste befindet.

**[!UICONTROL Nicht zugewiesene Arbeit] lädt nicht**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer in [!UICONTROL Lastenausgleich] erstellt einen Filter mithilfe der [!UICONTROL Zuweisung:Rolle-ID] -Feld, die [!UICONTROL Nicht zugewiesene Arbeit] -Bereich wird nicht geladen.

**Vorlage anhängen mit &quot;[!UICONTROL Anpassen und Anhängen]&quot;Option löscht benutzerdefinierte Feldwerte**

_Projekte_

Wenn ein Benutzer eine Vorlage mit dem[!UICONTROL Anpassen und Anhängen]&quot;, und dem Projekt ist bereits ein benutzerdefiniertes Formular angehängt. Die benutzerdefinierten Feldwerte werden nicht übernommen und müssen manuell neu eingegeben werden. Dies tritt auch dann auf, wenn die Vorlage dasselbe benutzerdefinierte Formular enthält.

+++

+++**Wartungs-Update (Hotfix) am 10. Dezember 2021**

**[!UICONTROL Hopfen] Fehler beim Anhängen der Vorlage an ein vorhandenes Projekt**

_Projekte_

Wenn ein Benutzer versucht, eine Vorlage an ein vorhandenes Projekt anzuhängen, wird die Vorlage nicht angehängt und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

+++

+++**Wartungs-Update am 9. Dezember 2021**


**Das reduzierte linke Navigationsfenster wird beim Laden der Seite erweitert**

_Navigation_

Wenn ein Benutzer festgelegt hat, dass die linke Navigation reduziert und dann eine Seite aktualisiert wird, wird die linke Navigation auf der neu geladenen Seite erweitert. Die linke Navigation wird auch erweitert, wenn der Benutzer eine Seite in einer neuen Registerkarte öffnet.

**[!UICONTROL Lastenausgleich] zeigt 0 Stunden zugeteilt**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer die [!UICONTROL Lastenausgleich] und &quot;[!UICONTROL Prognosedaten anzeigen]&quot; aktiviert ist, zeigen alle Daten in der Zukunft 0 zugewiesene Stunden an.

+++

+++**Wartungs-Update am 8. Dezember 2021**

**Die Genehmigung wird bei einer Aktualisierung zurückgesetzt**

_Genehmigungen_

Wenn ein Benutzer mithilfe der Objektüberschrift eine Entscheidung über eine Genehmigung trifft und das Objekt dann sofort aktualisiert, werden die Genehmigungssymbole wieder in der Kopfzeile angezeigt und die Genehmigungsentscheidung wird nicht gespeichert.

**[!UICONTROL Zuweisung in einem Bericht kann nicht inline bearbeitet werden]**

_Berichte_

Wenn ein Benutzer versucht, eine Zuweisung in einem Bericht inline zu bearbeiten, ändert sich der Feldwert nicht und die Bearbeitung wird nicht gespeichert.


+++

+++**Wartungs-Update am 2. Dezember 2021**

**Zusätzlicher Schrägstrich bei manueller Eingabe der URL**

_Anforde- rungen_

Wenn ein Benutzer eine Anforderung ausfüllt und manuell mit der Eingabe einer URL beginnt, wird irgendwann ein zusätzlicher Schrägstrich am Anfang der URL hinzugefügt. Der Benutzer kann den Schrägstrich nicht löschen.

**Benutzerdefinierte Abschnitte können nicht aus dem linken Navigationsbereich entfernt werden**

_Navigation_

Wenn ein Benutzer versucht, einen benutzerdefinierten Abschnitt aus dem linken Navigationsbereich zu entfernen, indem er auf das X neben dem Abschnitt klickt, wird der Abschnitt nicht entfernt.

**Nicht zugewiesene Arbeit wird nicht geladen**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer in [!UICONTROL Lastenausgleich] erstellt einen Filter mithilfe der [!UICONTROL Zuweisung:Rolle-ID] -Feld, die [!UICONTROL Nicht zugewiesene Arbeit] -Bereich wird nicht geladen.

**Seiten werden in bestimmten Browsern nicht geladen**

_[!DNL Workfront]_

Wenn ein Benutzer in [!DNL Workfront], werden Seiten nicht geladen und der Benutzer sieht die folgende Fehlermeldung:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Dies wurde in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Dieser Fehler tritt nach dem Zufallsprinzip auf und kann sich auf einen beliebigen Bereich von [!DNL Workfront].

+++


## Aktualisierungen im November 2021

+++**Wartungs-Update am 18. November 2021**

**[!DNL Workfront]für [!DNL Jira] &quot;[!UICONTROL Ungültige clientID oder clientSecret]&quot; Fehler bei Anmeldung**

_Workfront-Integrationen_

Benutzer wurden von der [!DNL Jira] für die Workfront-Integration. Wenn ein Benutzer versucht, sich bei der [!DNL Workfront for Jira] -Integration, können sie sich nicht anmelden und sehen den folgenden Fehler:

&quot;[!UICONTROL Ungültige clientID oder clientSecret]&quot;

**Benutzerdefiniertes Formular, das an die Anforderung angehängt ist, wird nicht aktualisiert, wenn ein neues Warteschlangenthema ausgewählt wird**

_Anforde- rungen_

Wenn ein Benutzer eine Anforderung erstellt und ein Warteschlangenthema auswählt, das automatisch ein benutzerdefiniertes Formular an die Anforderung anhängt, und dann ein anderes Warteschlangenthema auswählt, bleibt das benutzerdefinierte Formular aus dem ersten Warteschlangenthema an die Anforderung angehängt.

**Symbole werden falsch angezeigt**

_[!DNL Workfront]_

Symbolbilder werden falsch angezeigt. Dies wurde in vielen Bereichen der [!UICONTROL Workfront].

**Aufgaben werden nicht nach PDF exportiert, wenn die Option &quot;Andere Größen&quot;ausgewählt ist.**

_Aufgaben_

Wenn ein Benutzer versucht, eine Aufgabenliste auf PDF zu exportieren, und die Option &quot;[!UICONTROL Sonstige Größen]&quot;, können sie eine Größe auswählen und auf [!UICONTROL Export], aber die Liste wird nicht exportiert. Es gibt keine Fehlermeldung und keinen anderen Hinweis darauf, dass der Export nicht erfolgreich war.

**Bildanzeige wird in E-Mail-Benachrichtigungen nicht angezeigt**

_Benachrichtigungen_

Wenn ein Benutzer ein Bild zu einer Aktualisierung hinzufügt und eine E-Mail-Benachrichtigung an den Empfänger der Aktualisierung gesendet wird, enthält die E-Mail keinen Hinweis darauf, dass in der Aktualisierung ein Bild vorhanden ist.

**Seiten werden in bestimmten Browsern nicht geladen**

_[!DNL Workfront]_

Wenn ein Benutzer in [!DNL Workfront], werden Seiten nicht geladen und der Benutzer sieht die folgende Fehlermeldung:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Dies wurde in

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Dieser Fehler tritt nach dem Zufallsprinzip auf und kann sich auf jeden Bereich von Workfront auswirken.

+++

+++**Wartungs-Update am 11. November 2021**

**Problem mit Dokumentintegrationen, leere Seite beim Popup-Fenster zum Hochladen von Dokumenten aus[!DNL Google Drive*]*

_Dokumente_

Wenn ein Benutzer versucht, ein neues Dokument zu [!DNL Workfront] von [!DNL Google Drive] mithilfe von [!UICONTROL Neu hinzufügen] >[!UICONTROL Von [!DNL Google Drive]], bleibt der Popup-Bildschirm für das Hochladen leer.

**Darf nicht mehr als einen Filter im Arbeitslastausgleich verwenden**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer versucht, mehr als einen Filter im [!UICONTROL Lastenausgleich], sehen sie die folgenden Probleme:

* Wenn der Benutzer zwei Filter auswählt, wird nur der untere Filter angewendet.
* Wenn der Benutzer mehr als zwei Filter auswählt, werden keine Ergebnisse angezeigt.

**&quot;[!UICONTROL Projektordner]&quot;Dokumentüberschrift fehlt im Bereich für Projektdokumente**

_Projekte_

Wenn sich ein Benutzer in einem Projekt befindet und die Dokumente des Projekts anzeigt, wird die Überschrift[!UICONTROL Projektordner]&quot; fehlt in der linken Navigation. Der Dropdown-Pfeil ist weiterhin vorhanden und der Benutzer kann einen Ordner auswählen.

**Die Spalten auf Kanban-Brett sind zu breit und können nicht angepasst werden**

_Agile_

Wenn ein Benutzer eine Kanban-Pinnwand mit mehreren Spalten anzeigt, sind die Spalten zu breit, und der Benutzer muss scrollen, um Karten anzuzeigen oder in die ganz rechts gelegenen Spalten zu verschieben. Die Spaltenbreiten sind nicht anpassbar, sodass der Benutzer die Spalten nicht verkleinern kann, sodass sie alle gleichzeitig auf dem Bildschirm sichtbar sind.

**Verbesserte Benutzeroberfläche zum Erstellen eines neuen Teams**

_Teams_

Das Erstellen von Teams ist jetzt mit neuen visuellen Hinweisen intuitiver. Wenn Sie die [!UICONTROL Switch-Teams] auf einer beliebigen Team-Seite, wird die [!UICONTROL Neues Team erstellen] -Link weist ein Symbol auf, das[!UICONTROL new],&quot;und der Link vom Rest der Liste getrennt ist, sodass er nicht wie ein Teamname aussieht. Diese Benutzeroberfläche ist für agile und nicht agile Teams identisch.

+++

+++**Wartungs-Update am 4. November 2021**

**Für neue Aufgaben wird standardmäßig eine falsche Aufgabenbegrenzung festgelegt**

_Aufgaben_

Wenn ein Benutzer eine neue Aufgabe mit dem[!UICONTROL Neue Aufgabe]&quot;, und die Option &quot;New Task Default Start Date&quot;ist auf &quot;[!UICONTROL Heute],&quot;wird die Aufgabenbegrenzung der erstellten Aufgabe auf &quot;[!UICONTROL So bald wie möglich]&quot; anstelle von &quot;[!UICONTROL Start nicht früher als].&quot;

**Felder werden nicht auf Agile-Storys-Karten angezeigt**

_Agile_

Wenn ein Benutzer ein Agile-Storyboard anzeigt, zeigen die Karten nur die [!UICONTROL Beschreibung] und [!UICONTROL Status] -Felder. Andere Felder, einschließlich benutzerdefinierter Felder, werden nicht angezeigt.

**Karten kehren zur ursprünglichen Spalte zurück, bevor sie in eine neue Spalte verschoben werden**

_Agile_

Wenn ein Benutzer eine Karte in eine neue Spalte auf dem Storyboard zieht, kann der Benutzer sehen, wie die Karte gezogen wird. Wenn der Benutzer die Karte jedoch in der neuen Spalte ablegt, wird die Karte kurz in der ursprünglichen Spalte angezeigt, bevor sie in der neuen Spalte angezeigt wird.

**Werte sind nicht für benutzerdefinierte Felder in Filtern verfügbar**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer versucht, einen Filter mithilfe eines benutzerdefinierten Felds zu erstellen, wird der Wert für dieses benutzerdefinierte Feld nicht angezeigt und kann nicht in den Filter eingegeben werden.

**Seiten werden nicht in geladen [!DNL Firefox] browser**

_[!DNL Workfront]_

Wenn ein Benutzer in [!DNL Workfront] mit [!DNL Firefox] -Browser, Seiten werden nicht geladen und der Benutzer sieht die folgende Fehlermeldung:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Dieser Fehler tritt nach dem Zufallsprinzip auf und kann sich auf einen beliebigen Bereich von [!DNL Workfront].

**Datumsbezogene Fehler beim Erstellen eines Projekts aus einer Vorlage.**

_Vorlagen_

Wenn ein Benutzer ein Projekt aus einer Vorlage erstellt und den Planungsmodus auf [!UICONTROL Startdatum], wählt dann eine Aufgabenbegrenzung aus. Wenn der Benutzer versucht, das Projekt zu erstellen, wird das Projekt nicht erstellt und dem Benutzer wird eine Fehlermeldung angezeigt, die auf der Aufgabenbegrenzung basiert.

**[!UICONTROL Gantt-Diagramm exportieren] Dialogfeld reagiert nicht**

_Gantt-Diagramm_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnisversuche, die [!UICONTROL Gantt-Diagramm] und wählt &quot;[!UICONTROL Was ich sehe]&quot;, die [!UICONTROL Gantt-Diagramm] exportiert nicht und das Dialogfeld reagiert nicht. Der Benutzer kann das Dialogfeld nicht schließen oder nicht klicken.

**Symbole werden falsch angezeigt**

_[!DNL Workfront]_

Symbolbilder werden falsch angezeigt. Dies wurde aus folgenden Situationen berichtet:

* Bilder für Auftragsrollen oder Gruppen bei der Freigabe eines Objekts
* Links- und Rechtssymbole für Kalenderberichte
* Sortieren von Symbolen in Berichtsspalten

**Checkboxes zu Anforderungen in der [!UICONTROL Gesendet] Abschnitt [!UICONTROL Anforderungen] area**

_Anforde- rungen_

Wir haben Kontrollkästchen links neben den Anforderungsnamen im [!UICONTROL Gesendete Liste] des [!UICONTROL Anforderungen] Bereich. Dies erleichtert die Auswahl einer Anforderung und die Anzeige zusätzlicher Informationen.

**Benutzerdefinierte Quartale werden jetzt in den Arbeitslastausgleichsfiltern unterstützt**

_[!UICONTROL Lastenausgleich]_

Die Filter in der [!UICONTROL Lastenausgleich] unterstützt jetzt benutzerdefinierte Quartale.

**Aktualisierter Filteroperator für das Feld Dauer in den Arbeitslastausgleichsfiltern**

_[!UICONTROL Lastenausgleich]_

Die Filteroperatoren wurden beim Filtern der[!UICONTROL  Lastenausgleich] Gebiete nach [!UICONTROL Dauer].

+++


## Aktualisierungen im Oktober 2021

+++**Wartungs-Update am 28. Oktober 2021**

**[!UICONTROL Startseite] und [!UICONTROL Meine Arbeit] leere Seite anzeigen**

_[!UICONTROL Startseite] / [!UICONTROL Meine Arbeit]_

Wenn ein Benutzer zu [!UICONTROL Startseite] oder &quot;Meine Arbeit&quot;wird die Seite als leer angezeigt.

**Kann nicht angezeigt oder bearbeitet werden [!UICONTROL Themengruppe] details**

_Anforde- rungen_

Wenn ein Benutzer versucht, die Details einer Themengruppe anzuzeigen oder zu bearbeiten, zeigt die sich öffnende Seite &quot;[!UICONTROL Themengruppendetails]&quot;in der Kopfzeile, ist aber anderweitig leer

**Leere erforderliche Optionsfelder werden automatisch ausgefüllt**

_Anforde- rungen_

Wenn ein Benutzer eine Anforderung mit einem erforderlichen Optionsfeld sendet und der Benutzer vor dem Senden der Anforderung keinen Wert für dieses Feld ausgewählt hat, wird der erste Wert automatisch beim Senden der Anforderung ausgewählt.

+++

+++**Wartungs-Update am 21. Oktober 2021**

**Filter können nicht hinzugefügt werden in [!UICONTROL Lastenausgleich]**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer in [!UICONTROL Lastenausgleich] versucht, einen Filter hinzuzufügen, wird die [!UICONTROL Filter hinzufügen] -Bedienfeld geöffnet wird, der Inhalt des Bedienfelds jedoch nicht geladen wird und der Benutzer den Filter nicht hinzufügen kann.

**Auf der Agile Scrum-Pinnwand werden keine Meldungen angezeigt**

_Agile_

Wenn ein Benutzer versucht, die Scrum-Pinnwand in der Iteration eines Teams anzuzeigen, wird die Scroll-Pinnwand als leer angezeigt.

**Scrum-Story-Pinnwand bei Verwendung von Filtern leer**

_Agile_

Wenn ein Benutzer versucht, eine Scrum-Story-Pinnwand mit einem beliebigen Filter anzuzeigen, aber &quot;[!UICONTROL Alle Teams]&quot;, wird ein leerer Bildschirm angezeigt. Der Benutzer kann nicht zurück zum[!UICONTROL Alle Teams]&quot;.

**Listen sind nur in einem kleinen Bereich des Bildschirms sichtbar**

_Listen_

Wenn ein Benutzer versucht, eine Liste anzuzeigen, während er eine [!DNL Safari] in einem [!DNL Mac] mithilfe der [!DNL Big Sur OS], wird die Liste nur in einem kleinen Bereich des Bildschirms angezeigt. Der Benutzer kann durch die Liste blättern, der Bereich kann jedoch so klein sein, dass die Liste schwierig oder nicht lesbar ist.

**Leere erforderliche Optionsfelder werden automatisch ausgefüllt**

_Anforde- rungen_

Wenn ein Benutzer eine Anforderung mit einem erforderlichen Optionsfeld sendet und der Benutzer vor dem Senden der Anforderung keinen Wert für dieses Feld ausgewählt hat, wird der erste Wert automatisch beim Senden der Anforderung ausgewählt.

+++

+++**Wartungs-Update (Hotfix) am 21. Oktober 2021**

**[!UICONTROL Startseite] und [!UICONTROL Meine Arbeit] leere Seite anzeigen**

_[!UICONTROL Startseite] / [!UICONTROL Meine Arbeit]_

Wenn ein Benutzer zu [!UICONTROL Startseite] oder [!UICONTROL Meine Arbeit], wird die Seite als leer angezeigt.

+++

+++**Wartungs-Update am 20. Oktober 2021**

**[!UICONTROL Lastenausgleich] als Standard-Planungsoption festlegen**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer über die [!UICONTROL Planung] als Standard festgelegt wird, um es zu verwenden, sehen sie, dass die [!UICONTROL Lastenausgleich] wurde als Standard festgelegt.

+++

+++**Wartungs-Update (Hotfix) am 19. Oktober 2021**

**Anforderung kann beim Erstellen nicht zugewiesen werden**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis erstellt eine Anforderung und versucht, einen Benutzer zuzuweisen, indem er seinen Namen in die [!UICONTROL Zuweisungen] festgelegt ist, zeigt das Feld die Dropdown-Liste nicht an und der Benutzer kann den Namen des Empfängers nicht auswählen.

**Scrum-Story-Pinnwand bei Verwendung von Filtern leer**

_Agile_

Wenn ein Benutzer versucht, eine Scrum-Story-Pinnwand mit einem beliebigen Filter anzuzeigen, aber &quot;[!UICONTROL Alle Teams]&quot;, wird ein leerer Bildschirm angezeigt. Der Benutzer kann nicht zurück zum[!UICONTROL Alle Teams]&quot;.

+++

+++**Wartungs-Update am 14. Oktober 2021**

**Vorlagen, die systemweit freigegeben sind, sind nicht sichtbar**

_Vorlagen_

Wenn ein Benutzer ein Projekt erstellt und versucht, eine systemweit freigegebene Vorlage zu verwenden, kann der Benutzer die Vorlage nicht in der Liste der verfügbaren Vorlagen sehen und kann sie nicht verwenden.

**Fehler beim Erstellen von Projekten aus Vorlagen**

_Vorlagen_

Wenn ein Benutzer versucht, ein Projekt aus einer Vorlage zu erstellen, die ein benutzerdefiniertes Formular mit einem Abschnitt enthält, der nur für Administratoren sichtbar ist, kann der Benutzer das Projekt nicht erstellen und die folgende Meldung wird angezeigt:

&quot;[!UICONTROL Kategorie mit Primärschlüsselwert(en) &quot;xxxxxxxxxxxxxxxxxx&quot; nicht gefunden]&quot;

**Aktualisierte Links zum Kopieren und Verschieben von Aufgaben**

_Aufgaben_

Die Links zum Kopieren und Verschieben von Aufgaben wurden in aktualisiert.[!UICONTROL Kopieren nach]&quot; und &quot;[!UICONTROL Verschieben nach]&quot; sowohl auf der Aufgabenseite als auch in einer Aufgabenliste.

**Entfernen Sie die Beschränkung der Suche nach Stellenwerten, wenn Sie die Abrechnungsraten für ein Projekt überschreiben.**

Aufgabengebiete

HINWEIS: Dieses Update befindet sich derzeit in der Vorschau-Umgebung und wird mit der Produktionsversion 2.1 in Betrieb sein. Weitere Informationen finden Sie unter &quot;22.1 - Versionsübersicht&quot;.

Durch das Überschreiben der Abrechnungsraten für Stellenrollen in einem Projekt werden jetzt alle Jobrollen im System gesucht.

Zuvor [!DNL Workfront] in den ersten 2000 Rollen nach Auftragsrollen in alphabetischer Reihenfolge gesucht.

+++

+++**Wartungs-Update am 7. Oktober 2021**

**[!UICONTROL In-App-Benachrichtigungen werden aus] Benachrichtigungszentrum**

_Benachrichtigungen_

Wenn ein Benutzer das Benachrichtigungszentrum anzeigt, sind einige zuvor sichtbare Benachrichtigungen nicht mehr sichtbar. In einigen Fällen kann die Benachrichtigung verschwinden, bevor sie dem Benutzer angezeigt wird.

**Mitteilungen sind nicht auf der [!UICONTROL Alle Mitteilungen] page**

_Benachrichtigungen_

Wenn ein Benutzer die [!UICONTROL Alle Mitteilungen] Seite aus [!UICONTROL Benachrichtigungen] in den folgenden Bereichen keine Ankündigungen sichtbar sind:

* [!UICONTROL Posteingang]
* [!UICONTROL Favoriten]
* [!UICONTROL Entwürfe]
* [!UICONTROL Gelöscht]

**Fehler beim Zuweisen im [!UICONTROL Lastenausgleich]**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer versucht, eine Zuweisung aus der [!UICONTROL Lastenausgleich], wird die Arbeit nicht zugewiesen und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

+++


## Aktualisierungen im September 2021

+++**Wartungs-Update am 30. September 2021**

**Fehler beim schnellen Navigieren zu oder von [!UICONTROL Startseite]**

_Startseite_

Wenn ein Benutzer schnell zu oder von [!UICONTROL Startseite], wird die Seite nicht geladen und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

Dies kann auch auftreten, wenn Sie zu [!UICONTROL Startseite] über eine Stecknadel.

+++

+++**Wartungs-Update am 23. September 2021**

**[!UICONTROL Zugriff verweigert] Fehler bei der Anzeige von gesendeten Tickets[!DNL Workfront]**

_Anfragen_

Wenn ein Benutzer ein Ticket an [!DNL Workfront] und versucht, das Ticket anzuzeigen, wird der folgende Fehler angezeigt:

&quot;[!UICONTROL Zugriff verweigert: Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

**Geschäftsfallzusammenfassung zeigt falsche Werte an**

_Projekte_

Wenn ein Benutzer die [!UICONTROL Geschäftsfall] Zusammenfassungsbereich, spiegeln die angezeigten Werte nicht die Werte in der [!UICONTROL Geschäftsfall] Abschnitte.

**Spaltenüberschriften entsprechen nicht den Spalten in Listen**

_Einrichtung_

Wenn sich Benutzer im [!UICONTROL Einrichtung] -Bereich und zeigt eine Liste an, z. B. [!UICONTROL Benutzerdefinierte Forms] oder [!UICONTROL Zugriffsebenen], entsprechen die Spaltenüberschriften dieser Liste nicht den Spalten in der Liste.

**Benutzer ohne entsprechende Freigabeberechtigungen können benutzerdefinierte Formulare an Objekte anhängen**

_Benutzerdefinierte Formulare_

Wenn ein benutzerdefiniertes Formular im neuen [!DNL Adobe Workfront] -Erlebnis systemweit sichtbar ist, können alle Benutzer dieses benutzerdefinierte Formular an ein Objekt anhängen. Sie sollten jedoch nur das benutzerdefinierte Formular anzeigen und es an ein Objekt anhängen können, sofern es nicht speziell für sie freigegeben wurde.

+++

+++**Wartungs-Update am 16. September 2021**

**Gruppen können nicht bearbeitet werden**

_Gruppen_

Wenn ein Benutzer versucht, eine Gruppe zu bearbeiten oder zu löschen, wird die Gruppe nicht bearbeitet oder gelöscht und der Benutzer sieht die folgende Meldung:

&quot;[!UICONTROL Versuchen Sie es erneut. Gruppe mit Primärschlüsselwerten &quot;(Gruppe-ID)&quot;nicht gefunden]&quot;

**[!UICONTROL Portfolio Optimizer] keine Projekte anzeigen**

_Portfolios_

Wenn ein Benutzer versucht, Projekte im [!UICONTROL Portfolio Optimizer], wird die Projektliste nicht angezeigt und der Benutzer kann daher nicht mit den Projekten interagieren.

+++

+++**Wartungs-Update (Hotfix) am 10. September 2021**

**Datum und Uhrzeit, die bei der Inline-Bearbeitung als UTC markiert werden**

_Listen_

Wenn ein Benutzer ein Datum oder eine Uhrzeit inline bearbeitet (in einer Objektliste), werden Datum und Uhrzeit als UTC markiert. Datum und Uhrzeit werden in UTC nicht festgelegt in [!DNL Workfront]. Dieses Problem betrifft nur die Anzeige, nicht die tatsächlichen Daten.

**Textfarbe wird beim Anwenden der bedingten Formatierung nicht korrekt angezeigt**

_Berichte_

Wenn ein Benutzer einen Bericht mit bedingter Formatierung anzeigt, der die Textfarbe ändert, wird die Textfarbe unverändert angezeigt.

+++

+++**Wartungs-Update am 9. September 2021**

**Probleme zeigen keine Problemdetails an**

_Startseite_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis wählt ein Problem aus der [!UICONTROL Arbeitsliste], zeigt die Vorschau im rechten Bereich bestimmte Felder an, in denen keine Werte eingegeben wurden. Wenn Sie jedoch zum Problem navigieren und die [!UICONTROL Problemdetails]angegeben ist, werden in diese Felder Werte eingegeben.

**Benutzer benötigen Beitragsberechtigungen, um die [!UICONTROL Genehmigungen] im neuen Workfront-Erlebnis**

_Genehmigungen_

Benutzer benötigen [!UICONTROL Beitragen] Berechtigungen für ein Objekt zum Anzeigen der [!UICONTROL Genehmigungen] in der neuen [!DNL Workfront] Erlebnis. Sie sollten nur [!UICONTROL Ansicht] Berechtigungen zum Anzeigen der [!UICONTROL Genehmigungen] Registerkarte, wenn ein Genehmigungsprozess für das Objekt vorhanden ist.

**[!UICONTROL Hopfen] Fehler bei Verwendung von Filtern**

_Listen_

Wenn ein Benutzer versucht, einen der folgenden Filter zu verwenden:

* [!UICONTROL Alle Projekte]
* [!UICONTROL Projekte, an denen ich mitwirke]
* [!UICONTROL Meine aktuellen Aufgaben]

Die Liste wird leer gelassen und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Versuchen Sie es erneut.]&quot;

**[!UICONTROL Aufgaben] -Abschnitt beim Bearbeiten von Inline-Zeilen leer**

_Vorlagen_

Wenn ein Benutzer versucht, Aufgaben in einer Vorlage inline zu bearbeiten, indem er eine Ansicht verwendet, die Folgendes enthält:[!UICONTROL Zuweisen zu: Name]&quot;, und die Zuweisung enthält einen Benutzer, die [!UICONTROL Aufgaben] leer ist und der Benutzer die Vorlagenaufgaben nicht bearbeiten kann.

**Export nicht möglich [!UICONTROL Portfolio Optimizer]**

_Portfolios_

Wenn ein Benutzer versucht, die [!UICONTROL Portfolio Optimizer] und klickt auf eine der Exportoptionen, die [!UICONTROL Portfolio Optimizer] exportiert nicht.

**Benachrichtigungen werden nicht für Antworten gesendet**

_Benachrichtigungen_

Wenn ein Benutzer auf eine Aktualisierung in antwortet [!DNL Workfront], erhalten andere Benutzer im Kommentar-Thread keine Benachrichtigungen.

**Änderungen an benutzerdefinierten Daten führen zu Verzögerungen**

_Benutzerdefinierte Felder_

Wenn ein Benutzer benutzerdefinierte Daten ändert, die Trigger zu anderen angezeigten Daten ändern, werden die Änderungen langsam geladen.

**Gruppierung &quot;[!UICONTROL Alle reduzieren oder erweitern]&quot;-Symbol wird nicht angezeigt**

_Bericht- erstellung_

Die &quot;[!UICONTROL Alle reduzieren oder erweitern]&quot;-Symbol wird nicht in der Kopfzeile einer Liste oder eines Berichts angezeigt, wenn Gruppierungen auf die Liste oder den Bericht angewendet werden.

**[!UICONTROL Überprüfen] und [!UICONTROL Abbrechen] Optionen beim Ändern der Aufgabenzuordnung nicht sichtbar**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer versucht, die Aufgabenzuordnung für eine Aufgabe zu ändern, und der Zeitrahmen dieser Aufgabe sich bis zum Rand der sichtbaren Seite erstreckt, wird die [!UICONTROL Überprüfen] und [!UICONTROL Abbrechen] -Schaltflächen nicht sichtbar sind und der Benutzer die Zuordnungsänderungen nicht speichern oder abbrechen kann.

**Hinzufügen eines benutzerdefinierten Felds zu [!UICONTROL Startseite] verursacht fehlende Felddaten**

_[!UICONTROL Startseite]_

Wenn ein benutzerdefiniertes Feld zu [!UICONTROL Startseite]andere Felder beginnen, Daten zu fehlen und werden falsch angezeigt.

**Verknüpfte Elemente können nicht angezeigt werden, wenn sie als ein anderer Benutzer angemeldet sind**

_Integrationen_

Wenn ein Administrator versucht hat, verknüpfte Elemente von einem externen Anbieter anzuzeigen, während er sich als ein anderer Benutzer angemeldet hat, konnte er die verknüpften Ordner nicht öffnen und die Elemente nicht anzeigen.

+++

+++**Wartungs-Update am 2. September 2021**

**Benutzerdefiniertes Dashboard kann nicht poliert werden**

_Dashboards_

Wenn ein Benutzer versucht, ein benutzerdefiniertes Dashboard zu veröffentlichen, wird das Dashboard nicht veröffentlicht und der Benutzer sieht den folgenden Fehler:

&quot;[!UICONTROL Etwas ist beim Pinning schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir das reparieren können.]&quot;

**[!DNL Workfront Proof]Druckzusammenfassung ist leer**

[!DNL Workfront Proof]

Wenn ein Benutzer die Druckzusammenfassung zum Drucken eines Testversands öffnet, wird die Kopfzeile angezeigt, die Zusammenfassung selbst ist jedoch leer.

+++


## Aktualisierungen im August 2021

+++**Wartungs-Update am 26. August 2021**

**In [!DNL Safari] Es gibt einen dunkelgrauen Hintergrund im Text der Spaltenüberschriften.**

_Listen_

Im [!DNL Safari] -Browser, gibt es einen dunkelgrauen Hintergrund auf Spaltenüberschriften, der den Text hervorhebt. Dieses Problem tritt bei anderen unterstützten Browsern nicht auf.

**Unerwarteter Fehler beim Festlegen von Vorgängern**

_Aufgaben_

Wenn ein Benutzer versucht, eine Aufgabe als Vorgänger mithilfe der Inline-Bearbeitung festzulegen, wird der Vorgänger nicht festgelegt und der Benutzer sieht die folgende Meldung:

&quot;[!UICONTROL Unerwarteter Fehler]&quot;

+++

+++**Wartungs-Update am 19. August 2021**

**Gespeicherte Filter fehlen nach Auswahl eines Filters, der keine Probleme anzeigt**

_Listen_

Gespeicherte Filter fehlen in einer Liste von Problemen, nachdem ein Filter ausgewählt wurde, der keine Ergebnisse anzeigt.

**Probleme zeigen keine Problemdetails an**

_[!UICONTROL Startseite] summary_

Wenn ein Benutzer [!DNL Adobe Workfront Classic] wählt ein Problem aus dem [!UICONTROL Arbeitsliste], zeigt die Vorschau im rechten Bereich bestimmte Felder an, in denen keine Werte eingegeben wurden. Wenn Sie jedoch zum Problem navigieren und die [!UICONTROL Problemdetails]angegeben ist, werden in diese Felder Werte eingegeben.

+++

+++**Wartungs-Update am 12. August 2021**

**Die agile Ansicht kann nicht im Projekt angepasst werden**

_Agile_

Wenn ein Benutzer versucht, eine bereits vorhandene agile Ansicht in einem Projekt anzupassen, wird das Fenster geschlossen und der Benutzer kann die Ansicht nicht bearbeiten.

**Der Name ändert sich in neuen Dokumentversionen nicht**

_Dokumente_

Wenn ein Benutzer eine neue Version eines Dokuments hochlädt, wird der Name des Dokuments nicht aktualisiert, um mit dem Namen der neuesten Version übereinzustimmen.

**Das Symbol &quot;Vorgänger&quot;wird nicht grün, wenn der Vorgänger abgeschlossen ist.**

_Aufgaben_

Wenn eine Aufgabe eine Vorgängeraufgabe hat und diese Vorläuferaufgabe abgeschlossen ist, wird das Vorgängersymbol in der abhängigen Aufgabe nicht grün.

Wenn ein benutzerdefiniertes Formular im neuen [!DNL Adobe Workfront] -Erlebnis systemweit sichtbar ist, können alle Benutzer dieses benutzerdefinierte Formular an ein Objekt anhängen. Sie sollten jedoch nur das benutzerdefinierte Formular anzeigen und es an ein Objekt anhängen können, sofern es nicht speziell für sie freigegeben wurde.

+++

+++**Wartungs-Update (Hotfix) am 6. August 2021**

**Kalender können nicht ausgewählt werden in [!DNL Outloo]k Kalendereinstellungen**

_Startseite_

Wenn ein Benutzer in der neuen [!DNL Workfront] -Erlebnis zeigt die [!DNL Outlook] Kalender in der Startseite und öffnet die Einstellungen. Die Kontrollkästchen zur Auswahl von Kalendern fehlen. Wenn der Benutzer auf die Stelle klickt, an der das Kontrollkästchen aktiviert werden soll, antwortet der Kalender so, als wäre das Kontrollkästchen vorhanden.

**Verbindung kann nicht erneut autorisiert oder überprüft werden [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] Benutzer mit Szenarien, die eine Verbindung zu [!UICONTROL Webdam] sollte wissen, dass [!UICONTROL Webdam] -Verbindungen müssen alle 14 Tage manuell neu authentifiziert werden. Die [!UICONTROL Webdam] Die API unterstützt derzeit keine automatische Neuautorisierung.

+++

+++**Wartungs-Update am 5. August 2021**

**Die Interaktion mit Dokument in [!UICONTROL Zusammenfassungsbereich] oder [!UICONTROL Mehr] Menü**

_Dokumente_

Wenn ein Benutzer in der neuen [!DNL Workfront] Das Erlebnis zeigt ein Dokument an und versucht, eine Auswahl im [!UICONTROL Zusammenfassungsbereich] oder [!UICONTROL Mehr] Menü, wird die Auswahl des Dokuments aufgehoben, wodurch die [!UICONTROL Zusammenfassungsbereich] oder [!UICONTROL Mehr] Menü, um leer zu gehen.

**[!UICONTROL Neue Anforderung] Schaltfläche fehlt**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis wird an [!UICONTROL Anforderungen] Seite, die [!UICONTROL Neue Anforderung] -Schaltfläche wird nicht angezeigt und kann keine Anforderung senden.

**Benutzer ohne entsprechende Freigabeberechtigungen können benutzerdefinierte Formulare an Objekte anhängen**

_Benutzerdefinierte Formulare_

Wenn ein benutzerdefiniertes Formular im neuen [!DNL Adobe Workfront] -Erlebnis systemweit sichtbar ist, können alle Benutzer dieses benutzerdefinierte Formular an ein Objekt anhängen. Sie sollten jedoch nur das benutzerdefinierte Formular anzeigen und es an ein Objekt anhängen können, sofern es nicht speziell für sie freigegeben wurde.

**Die Testversandeinstellungen können beim Erstellen eines neuen Testversands nicht geändert werden**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen neuen Testversand erstellt und versucht, die Einstellungen zu ändern, wird die Einstellung auf eine vorherige Einstellung zurückgesetzt.

**[!UICONTROL Story Board] nicht ordnungsgemäß geladen werden**

_Agile_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis navigiert zu einem [!UICONTROL Story Board]kann es bis zu 10 Sekunden dauern, bis die Pinnwand geladen ist. Die Verzögerung beim Laden liegt daran, dass das System alle Karten lädt, obwohl es nur 50 Karten gleichzeitig laden sollte.

+++


## Aktualisierungen im Juli 2021

+++**Wartungs-Update (Hotfix) am 29. Juli 2021**

**Neue Testversand- oder Testversion kann nicht hochgeladen werden**

_[!DNL Workfront Proof]_

Wenn ein Benutzer versucht, einen neuen Testversand oder eine neue Version eines Testversands im klassischen [!DNL Workfront] Erlebnis, ist die neue Testversand- oder Neuversionsseite leer und der Benutzer kann den Testversand oder die Version nicht hochladen.

+++

+++**Wartungs-Update am 29. Juli 2021**

**[!UICONTROL Testaktivität] und [!UICONTROL Testversand-Viewer-Einstellungen] Seiten immer verfügbar**

_[!DNL Workfront Proof]_

Die [!UICONTROL Testaktivität] und [!UICONTROL Proof Viewer] Einstellungsseiten sind jetzt immer sichtbar, auch wenn der Benutzer keinen Zugriff auf die Aktualisierung dieser Seiten hat.

Wenn ein Benutzer mit einem benutzerdefinierten Profil für Testberechtigungen zuvor zu einem Dokument navigiert hat, wird die [!UICONTROL Testaktivität] und [!UICONTROL Testversand-Viewer-Einstellungen] Seiten auf der linken Seite waren nicht immer sichtbar.

**Fehlermeldung bei Verwendung von [!UICONTROL Prozentsatz] -Option für [!UICONTROL Zugewiesene Stunden]**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer die [!UICONTROL Prozentsatz] -Option für [!UICONTROL Zugewiesene Stunden], und es werden Arbeiten im [!UICONTROL Nicht zugewiesene Arbeit] -Abschnitt wird dem Benutzer der folgende Fehler angezeigt:

&quot;[!UICONTROL Es ist ein Fehler aufgetreten und wir arbeiten daran, das Problem zu beheben. Aktualisieren Sie diese Browserseite, um mit Ihrer Arbeit fortzufahren.]&quot;

+++

+++**Wartungs-Update am 22. Juli 2021**

**Neue Versionsnamen für Testsendungen werden abgeschnitten**

_[!DNL Workfront Proof]_

Wenn ein Benutzer [!DNL Adobe Workfront Classic] lädt eine neue Version eines Testversands hoch, der einen Punkt im Dateinamen enthält. Der Dateiname wird am Ende abgeschnitten.

+++

+++**Wartungs-Update (Hotfix) am 19. Juli 2021**

**Fehler beim Navigieren zu Projekten, Timesheets, Aufgaben oder Programmen**

Im neuen [!DNL Adobe Workfront] Wenn ein Benutzer versucht, zu Projekten, Timesheets, Aufgaben oder Programmen zu navigieren, wird ihm die Fehlermeldung angezeigt.[!UICONTROL Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

+++

+++**Wartungs-Update am 15. Juli 2021**

**Standardpriorität für neue Anforderungen ist falsch**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis erstellt eine Anforderung, die Anforderung entspricht nicht der in [!UICONTROL Projektvoreinstellungen] und sie können die Priorität vor dem Senden der Anfrage nicht anpassen.

**[!UICONTROL Testversand durchführen] Link leitet nicht zum Kommentar**

_E-Mail-Benachrichtigungen_

Wenn ein Benutzer eine E-Mail-Benachrichtigung für einen Testkommentar erhält und auf [!UICONTROL Testversand durchführen], werden sie zum falschen Kommentar im Testversand weitergeleitet oder sind überhaupt nicht zu einem Kommentar weitergeleitet.

**Rich-Text-Feldwerte, die nach dem Konvertieren eines Problems in eine Aufgabe nicht übertragen wurden**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer ein Problem in eine Aufgabe konvertiert und das Problem über ein angehängtes benutzerdefiniertes Formular mit einem Wert verfügt, der in ein Textfeld mit Rich-Text-Formatierung eingegeben wurde, wird der Wert im Textfeld nach der Konvertierung nicht übernommen.

**Benutzerdefinierte Feldwerte ändern sich nach der Auswahl**

_[!DNL Workfront Proof]_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] -Erlebnis einen neuen Testversand erstellt und in einigen benutzerdefinierten Feldern bei einem Testversand einen Wert eingegeben hat, wird der Wert einiger vorheriger Felder auf die Standardwerte zurückgesetzt, anstatt auf den vom Benutzer eingegebenen Wert.

**[!UICONTROL Zuweisen zu] typeahead funktioniert nicht**

_[!UICONTROL Startseite]_

Wenn ein Benutzer [!DNL Adobe Workfront Classic] erstellt ein Projekt, eine Aufgabe oder eine Anforderung aus dem [!UICONTROL Startseite] -Bereich, [!UICONTROL Zuweisen zu] typeahead -Feld füllt keine Benutzernamen.

**Unsachgemäße Rundung der Stunden**

_Arbeitszeit- tabellen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis navigiert zu [!UICONTROL Timesheets] > [!UICONTROL Alle Timesheets], sehen sie, dass die Gesamtstundenzahlen für einige Timesheets auf eine Dezimalstelle statt in Schritten von 0,25 gerundet werden, aber die Gesamtstunden im jeweiligen Timesheet korrekt angezeigt werden. Im Bereich &quot;Alle Timesheets&quot;beispielsweise zeigt ein Timesheet 44,8 Gesamtstunden an, aber beim Öffnen des Zeitblatts werden insgesamt 44,75 Stunden angezeigt.

**Genehmigungen können nicht delegiert werden**

_[!UICONTROL Startseite]_

Wenn ein Benutzer [!DNL Adobe Workfront Classic] Klicks [!UICONTROL Meine Genehmigungen delegieren] im [!UICONTROL Startseite] und sie beginnen, den Namen des Benutzers einzugeben, an den sie delegieren möchten, werden im [!UICONTROL typeahead] und sie können keinen Benutzer auswählen.

**[!UICONTROL Gantt-Diagramm] Ansicht ist nicht für Aufgabenberichte verfügbar**

_Berichte_

HINWEIS: Dies wirkt sich auch auf Projektberichte aus.

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis öffnet einen Task-Bericht, die Option zur Auswahl einer [!UICONTROL Gantt-Diagramm] -Ansicht fehlt in der Berichtssymbolleiste. Wenn die Variable [!UICONTROL Gantt-Diagramm] -Ansicht ausgewählt ist, um standardmäßig im Bericht angezeigt zu werden, wird stattdessen ein Listenformat angezeigt.

**Klicken [!UICONTROL Weitere Informationen] auf Bericht lädt nichts**

_Dashboards_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] -Erlebnis einen Bericht in einem Dashboard anzeigt, und er klickt auf [!UICONTROL Weitere Informationen] -Schaltfläche, nichts passiert und sie können nicht alle Elemente im Bericht anzeigen.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update am 1. Juli 2021**

**Das Kopieren von Modulen funktioniert nicht**

_[!DNL Adobe Workfront Fusion]_

Wenn ein Benutzer mehrere Module auswählt und versucht, diese zu kopieren und einzufügen, werden die Module nicht eingefügt.

+++

+++**Wartungs-Update am 1. Juli 2021**

**Farbsatz für nicht berücksichtigte Karten**

_Kanban_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis legt bestimmte Kartenfarben in den Teameinstellungen fest, diese Farben werden nicht auf den Kanban-Karten dargestellt.

**Text kann nicht in das benutzerdefinierte Nachrichtenfeld eingefügt werden**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen neuen Testversand im [!UICONTROL Web Proofing Viewer] und sie versuchen, Text in die [!UICONTROL Nachricht] im Feld [!UICONTROL E-Mail-Benachrichtigung] -Abschnitt, können sie den Text nicht einfügen. Dies scheint nur zu geschehen, wenn der Text Absatzformatierung hat und ein Absatzumbruch vorliegt.

**Anforderungen werden mit leeren erforderlichen Feldern gesendet**

_Anforde- rungen_

Wenn ein Benutzer eine Anfrage sendet und diese sendet, werden Informationen in den erforderlichen Feldern nicht zusammen mit der Anfrage gesendet.

**[!UICONTROL Neue Anforderung] Schaltfläche fehlt**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis wird an [!UICONTROL Anforderungen] Seite, die [!UICONTROL Neue Anforderung] -Schaltfläche wird nicht angezeigt und kann keine Anforderung senden.

**Fehler beim Erweitern eines benutzerdefinierten Formulars**

_Projekte_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis versucht, ein benutzerdefiniertes Formular zu erweitern, das an ein Projekt angehängt ist, es kann das benutzerdefinierte Formular nicht öffnen und die Fehlermeldung anzeigen[!UICONTROL Es ist ein Fehler aufgetreten, und wir arbeiten daran, das Problem zu beheben. Um mit der Arbeit fortzufahren, versuchen Sie, diese Browser-Seite zu aktualisieren.]Durch Aktualisieren der Seite wird das Problem nicht behoben.

**[!DNL Adobe Workfront]-Branding wird jetzt in E-Mails des Ankündigungs-Centers angezeigt**

E-Mails

Als [!DNL Adobe Workfront] -Branding wird überall in der Anwendung eingeführt. Die folgenden Aktualisierungen wurden an den E-Mails des Ankündigungs-Centers vorgenommen:

* Die [!DNL Adobe Workfront] Dem Hauptinhaltsbereich wurde ein Löwe hinzugefügt.
* Die [!DNL Adobe Workfront] -Logo wurde der Fußzeile hinzugefügt.

Künftig wird dieses Branding bei weiteren E-Mail-Typen aus Workfront angezeigt.

+++


## Aktualisierungen im Juni 2021

+++**Wartungs-Update am 24. Juni 2021**

**Team kann nicht bearbeitet werden**

_Agile_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnisklicks [!UICONTROL Bearbeiten] , um [!DNL Edit] Team-Seite für ein Agile-Team, die Seite wird zunächst geladen, dann verschwinden die Einstellungen und es wird leer.

**Aus der gesendeten Anfrage entfernte Daten**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] -Erlebnis füllt eine Anforderung aus. In der gesendeten Anfrage fehlen die eingegebenen Werte für einige benutzerdefinierte Felder, manchmal auch für erforderliche Felder.

**Spalten werden nicht angezeigt**

_Kanban_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis fügt ein benutzerdefiniertes [!UICONTROL Zusätzliche Felder] -Spalte auf einem Kanban-Board werden alle Spaltenüberschriften nicht mehr auf der Pinnwand angezeigt.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update am 23. Juni 2021**

**Beschädigter Link in Benachrichtigungs-E-Mails entfernt**

_[!DNL Adobe Workfront Fusion]_

Wir haben den Link zu den Benachrichtigungseinstellungen aus [!DNL Adobe Workfront Fusion] Benachrichtigungs-E-Mails.
Informationen zum Ändern der Benachrichtigungseinstellungen finden Sie unter [!DNL Adobe Workfront Fusion] Organisationen und Teams.

+++

+++**Wartungs-Update am 17. Juni 2021**

**[!UICONTROL Gantt-Diagramm] Ansicht ist nicht für Aufgabenbericht verfügbar**

_Berichte_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis öffnet einen Task-Bericht, die Option zur Auswahl einer [!UICONTROL Gantt-Diagramm] -Ansicht fehlt in der Berichtssymbolleiste. Wenn die Variable [!UICONTROL Gantt-Diagramm] -Ansicht ausgewählt ist, um standardmäßig im Bericht angezeigt zu werden, wird stattdessen ein Listenformat angezeigt.

**Zeichenbegrenzungsfehler bei Anfrageübermittlung nicht aufgetreten**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] -Erlebnis versucht, eine Anforderung zu senden, die die Zeichenbeschränkung für ein Feld überschreitet, die Anforderung nicht senden kann und es wird keine Fehlermeldung angezeigt. In [!DNL Adobe Workfront Classic], wird dem Benutzer die Warnung angezeigt &quot;[!UICONTROL [number] Zeichen überschreiben&quot;und wenn sie versuchen, die Anfrage zu senden, wird ihnen die Fehlermeldung &quot;Bitte überprüfen Sie Folgendes: Bitte geben Sie höchstens 2000 Zeichen ein (eingegebenen [number] Zeichen).]&quot;

+++

+++**Wartungs-Update am 10. Juni 2021**

**Neu angeordnete Vorlagenaufgaben werden nicht verschoben**

_Vorlagen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Das Erlebnis verschiebt eine Vorlagenaufgabe an eine neue Position in einer Liste. Die Anzahl der Vorlagenaufgaben wird aktualisiert, es wird jedoch nicht neu angeordnet.

**Untergeordnete Aufgaben, die nicht mit übergeordneten Aufgaben ausgewählt wurden**

_Vorlagen_

Wenn ein Benutzer eine übergeordnete Aufgabe für ein Projekt auswählt, das aus einer Vorlage erstellt wurde, werden die untergeordneten Aufgaben nicht automatisch ausgewählt.

**Inline-Bearbeitungs-Meilensteine auf einer Aufgabenliste zeigen alle Meilensteine an**

_Projekte_

Wenn einem Projekt ein Meilensteinpfad hinzugefügt wurde und ein Benutzer in der neuen [!DNL Adobe Workfront] Inline-Bearbeitung des Erlebnisses [!UICONTROL Milestone: Name] in dieser Aufgabenliste werden alle Meilensteinpfade im Dropdown-Menü angezeigt und nicht nur die Meilensteinpfade, die mit diesem Projekt verbunden sind.

+++

+++**Wartungs-Update am 3. Juni 2021**

**Durch Aufforderung wird die Seite verschoben**

_Berichte_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] -Erlebnis einen Bericht mit einer Eingabeaufforderung ausführt, werden die Spalten im Bericht schnell von links nach rechts verschoben.

**Einige Ausdrücke auf der [!UICONTROL Neuer Testversand] Seite nicht richtig übersetzt**

_[!DNL Workfront Proof]_

Wenn ein Benutzer zur [!UICONTROL Neue Testversand-Erstellung] Seite in [!DNL Workfront Proof] und der Inhalt in eine andere Sprache als Englisch übersetzt wird, werden einige Ausdrücke noch auf Englisch angezeigt.

**Benutzern hinzugefügte deaktivierte und gelöschte Beschriftungen[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Deaktiviert] und [!UICONTROL Gelöscht] Benutzerbeschriftungen wurden den folgenden Bereichen in [!DNL Workfront] Testversand:

* [!UICONTROL Testversanddetails] page
* [!UICONTROL Testversandansichten]
* [!UICONTROL Testversand-Viewer]
* [!UICONTROL Testversand-Workflows]
* [!UICONTROL Kommentare drucken] page
* [!UICONTROL Benutzer] page

+++


## Aktualisierungen im Mai 2021

+++**Wartungs-Update am 27. Mai 2021**

**[!UICONTROL Datum der Übermittlung] Kalender wird für Aktualisierungen angezeigt**

_Aufgaben_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Erlebnis gibt eine Aktualisierung für eine Aufgabe ein, die [!UICONTROL Datum der Übermittlung] wird angezeigt, ohne dass der Benutzer die [!UICONTROL Datum der Übermittlung] -Feld.

**[!UICONTROL Mehr] aus Filtern, Ansichten und Gruppierungen fehlendes Menü**

_Listen_

Wenn ein Benutzer in der neuen [!DNL Adobe Workfront] Das Erlebnis zeigt die Filter, Ansichten oder Gruppierungen für eine Liste an, die [!UICONTROL Mehr] -Menüsymbol fehlt, was verhindert, dass sie Filter, Ansichten oder Gruppierungen freigeben oder - falls sie Zugriff haben - entfernen.

**Kopieren und Einfügen eines Projekts [!UICONTROL Referenz Nr.] fügt hinzu[!UICONTROL Diese]&quot;**

_Projekte_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis navigiert zu einem Projekt, kopiert die [!UICONTROL Referenz Nr.] von [!UICONTROL Übersicht] Bereich, und fügen Sie ihn dann ein, das Wort &quot;[!UICONTROL Diese]&quot; wird am Ende der Zahl hinzugefügt.

**[!UICONTROL Daily Digest] E-Mails werden gesendet, wenn sie deaktiviert sind**

_E-Mail-Benachrichtigungen_

Einige Benutzer erhalten [!UICONTROL Daily Digest] E-Mail-Benachrichtigungen, wenn sie in den Benutzereinstellungen nicht aktiviert wurden.

**Fehler &quot;Objekt existiert nicht mehr&quot;**

_Objekte_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnisversuche, bestimmte Objekte zu öffnen, sehen sie die Fehlermeldung &quot;[!UICONTROL Das Objekt (Objekt) ist nicht mehr vorhanden: Möglicherweise haben Sie die Webadresse falsch eingegeben. Überprüfen Sie es und versuchen Sie erneut, die Adresse einzugeben.]&quot;Die Objektverknüpfung wird weiterhin in Listen, Neuigkeiten, Favoriten, Suchergebnissen usw. angezeigt, kann jedoch nicht darauf zugreifen und wird nicht im Papierkorb mit gelöschten Objekten angezeigt.



+++

+++**Wartungs-Update am 20. Mai 2021**

**Testversandoptionen fehlen**

_Korrekturabzüge_

Wenn ein Benutzer eine andere Version eines Testversands in [!DNL Workfront], die [!UICONTROL Offener Testversand] und [!UICONTROL Testversand-Workflow] -Links fehlen, sodass es als Dokument anstatt als Testversand erscheint. Wenn diese Links fehlen, wird die Bezeichnung [!UICONTROL Ausstehend] auch angezeigt wird und andere Benutzer den Testversand nicht erstellen können, während er sich in diesem befindet [!UICONTROL Ausstehend] Status.

**Benutzer, die keine geplanten Berichtbereitstellungen erhalten**

_Berichte_

Wenn einige Berichte für die Bereitstellung von Berichten geplant sind, erhalten die Benutzer manchmal keine Berichte.

**Zugriff für Layoutvorlage kann nicht entfernt werden**

_Dashboards_

Wenn ein Benutzer geöffnet wird [!UICONTROL Freigabe] Optionen für ein Dashboard zum Entfernen des Zugriffs für eine Layout-Vorlage, keine [!UICONTROL Löschen] neben der Layout-Vorlage angezeigt wird und sie den Zugriff nicht entfernen können.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 17. Mai 2021**

**Im Organisations-Dashboard wird nun die Anzahl der aktiven Szenarien korrekt angezeigt**

_[!DNL Workfront Fusion]_

Die [!UICONTROL Einrichtung] Im Dashboard wurde zuvor ein leeres Feld anstelle der Anzahl der verwendeten Szenarien angezeigt.

**Das Durchsuchen von Datenspeichern zeigt jetzt Spaltenbezeichnungen an**

_[!DNL Workfront Fusion]_

In Datenstrukturen, in denen Spaltenbezeichnungen verwendet wurden, wurde zuvor der Spaltenname im [!UICONTROL Durchsuchen von Datenspeichern] anzeigen.  Jetzt wird der Spaltentitel angezeigt.  Wenn für die Spalte keine Beschriftung angegeben ist, wird der Spaltenname angezeigt.

**Der Initialisierungsfehler eines Szenarios wirkt sich nicht mehr auf Webhook-Daten aus**

_[!DNL Workfront Fusion]_

Zuvor führte ein Webhook-initiiertes Szenario (einschließlich derjenigen, die Echtzeit-Ereignisse für Trigger verwenden), bei dem bei der Initialisierung eines Szenarios ein Fehler auftrat, möglicherweise dazu, dass der Zugriff auf diese Webhook-Daten verloren ging.  Wenn nun bei der Initialisierung eines Szenarios ein Fehler auftritt (z. B. wenn eine Verbindung nicht überprüft werden kann), werden die Webhook-Daten in der Webhook-Warteschlange gespeichert und die Ausführung wird automatisch wiederholt.  Nach drei fehlgeschlagenen Versuchen wird das Szenario deaktiviert und die Informationen verbleiben weiterhin in der Warteschlange.

**Datensätze in Webhook-Warteschlangen werden jetzt in kleineren Batches verarbeitet**

_[!DNL Workfront Fusion]_

Wenn ein Benutzer zuvor ein inaktives Szenario aktiviert hat, das mit einer Webhook-Warteschlange mit vielen Datensätzen verknüpft war, [!DNL Workfront Fusion] würde versuchen, die gesamte Warteschlange in einer einzigen Ausführung zu verarbeiten (wenn auch mehrere Zyklen).  Je nach Menge der verarbeiteten Datensätze kann dies dazu führen, dass die einzelne Ausführung manchmal die maximale Ausführungsdauer (40 Minuten) überschreitet.  Wenn Sie jetzt ein inaktives Szenario aktivieren, das mit einer Webhook-Warteschlange von Datensätzen verknüpft ist, verarbeitet Workfront Fusion bis zu der maximalen Anzahl von Datensätzen, die in einer Ausführung identifiziert werden (in der Regel 2 Datensätze pro Ausführung).

**Datenspeicher zeigen jetzt Werte vom Typ &quot;0&quot;korrekt an**

_[!DNL Workfront Fusion]_

Zuvor wurden Datenspeicherwerte von 0 als leer angezeigt. &lt;..>

+++

+++**Wartungs-Update am 13. Mai 2021**

**Dropdown-Kalender wird hinter dem [!UICONTROL Nicht zugewiesene Arbeit] header**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer zur [!UICONTROL Lastenausgleich] in [!DNL Workfront Classic], wird der obere Rand der Datumsauswahl hinter dem [!UICONTROL Nicht zugewiesene Arbeit] -Kopfzeile, die verhindert, dass der Benutzer zu verschiedenen Monaten navigiert.

**Text kann nicht in das benutzerdefinierte Nachrichtenfeld eingefügt werden**

_[!DNL Workfront Proof]_

Hinweis: Diese Frage scheint sich nur auf die [!DNL Google Chrome] Webbrowser zu diesem Zeitpunkt.

Wenn ein Benutzer einen neuen Testversand in [!DNL Workfront Proof] und sie versuchen, Text aus einer E-Mail in die [!UICONTROL Nachricht] im Feld [!UICONTROL E-Mail-Benachrichtigung] -Abschnitt, können sie den Text nicht einfügen.

**Nicht unterstützte Felder werden im Builder angezeigt**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer ein benutzerdefiniertes Formular erstellt und versucht, ein berechnetes Feld mithilfe eines dynamischen Felds zu erstellen, z. B. [!UICONTROL Anzahl offener Risiken]- das Feld für die Berechnung markiert Rot und erlaubt es Ihnen nicht, Ihre Änderungen zu speichern. Dynamische Felder sollten nicht in der Auswahl für berechnete Felder angezeigt werden.

**Vorschau für Aufgaben in [!UICONTROL Arbeitsliste] wird nicht geladen**

_Startseite_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis wird einer Layout-Vorlage zugewiesen, die benutzerdefinierte Felder in [!UICONTROL Startseite], reagiert die Seite nicht und lädt keine Aufgaben aus der [!UICONTROL Arbeitsliste] , wenn die Benutzer sie auswählen.

**Objekte in [!UICONTROL Arbeitsliste] wird nicht geladen [!UICONTROL Startseite]**

_[!UICONTROL Startseite]_

Wenn ein Benutzer auf ein Objekt im [!UICONTROL Homepage-Arbeitsliste], wird die Kopfzeile des Objekts im rechten Bereich angezeigt, die Details des Objekts werden jedoch nicht angezeigt. Schließlich sieht der Benutzer die Nachricht &quot;[!UICONTROL Seiten reagieren nicht.]&quot;

**Probleme mit Rich-Text-Feldern[!DNL Microsoft Outlook]**

_Workfront-Integrationen_

Wenn ein Benutzer ein Rich-Text-Feld mit dem [!DNL Workfront for Outlook] -Integration, können sie nicht:

* Rücktaste
* Text kopieren
* Text einfügen
* Senden einer Anforderung, wenn alle Felder ausgefüllt sind

+++

+++**Wartungs-Update am 6. Mai 2021**

**[!UICONTROL Währung] Feld funktioniert nicht erwartungsgemäß**

_Listen_

Wenn ein Benutzer versucht, den Cursor inline zu bearbeiten-Währungsfeld in einer Liste speichern kann, sind sie aufgrund der folgenden Probleme nicht in der Lage, Änderungen zu speichern:

* Aufgaben- und Problemlisten lassen die Eingabe von Währungssymbolen nicht zu
* Listen erlauben keine Eingabe von Währungsabkürzungen bei der Verwendung eines anderen Gebietsschemas als Englisch
* Unteraufgaben- und Problemlisten, die nur die Währungsabkürzung von USD zulassen, unabhängig von der festgelegten Projektwährung

**Name wird nicht aktualisiert, um neuen Testnamen zu entsprechen**

_Dokumente_

Wenn ein Benutzer eine neue Version eines Testversands erstellt und den Testversand-Namen aktualisiert, wird das Dokumentobjekt in [!DNL Workfront] behält den ursprünglichen Namen bei, anstatt dem neuen Testversand-Namen zu entsprechen.

**[!UICONTROL Geschäftsfall] -Schaltflächen funktionieren nicht, wenn benutzerdefinierte Formulare angehängt werden**

_Projekte_

Wenn ein Projekt in der neuen [!DNL Workfront] Erlebnis wird aus einer Projektvorlage erstellt und es wird ein benutzerdefiniertes Formular angehängt. Benutzer können einen Geschäftsfall nicht senden, ablehnen oder genehmigen.

**Archivierte Testsendungen, die in Listen und Berichten angezeigt werden**

_Korrekturabzüge_

Wenn ein Benutzer seine Arbeitsliste in [!UICONTROL Startseite] oder [!UICONTROL Meine Arbeit], werden bereits archivierte Testsendungen in der Liste angezeigt. Archivierte Testsendungen werden auch in Berichten und Dashboards angezeigt.

**Aus einer Vorlage erstellte Projekte haben falsche Zugriffseinstellungen**

_Projekte_

Wenn ein Benutzer ein Projekt aus einer Vorlage erstellt, werden die Zugriffseinstellungen der Vorlage nicht in das neu erstellte Projekt übernommen.

**Objekte in [!UICONTROL Arbeitsliste] wird nicht geladen [!UICONTROL Startseite]**

_[!UICONTROL Startseite]_

Wenn ein Benutzer auf ein Objekt im [!UICONTROL Homepage-Arbeitsliste], wird die Kopfzeile des Objekts im rechten Bereich angezeigt, die Details des Objekts werden jedoch nicht angezeigt. Schließlich sieht der Benutzer die Nachricht &quot;[!UICONTROL Seiten reagieren nicht.]&quot;

+++


## Aktualisierungen im April 2021

+++**Wartungs-Update am 29. April 2021**

**[!DNL SharePoint]Integration authentifiziert sich mithilfe von Anmeldeinformationen aus einer separaten Integration**

_Workfront-Integrationen_

Wenn ein Benutzer mehr als einen [!DNL SharePoint] Integration, eine [!DNL SharePoint] Authentifizierungsversuche zur Authentifizierung mit den Anmeldeinformationen eines anderen [!DNL SharePoint] Integration.

**Dateien können nicht von hochgeladen oder exportiert werden [!DNL Adobe] products**

_Workfront-Integrationen_

Wenn ein Benutzer versucht, Dateien mit dem [!DNL Workfront for Adobe Creative Cloud] -Integration, sehen sie die Fehlermeldung &quot;[!UICONTROL Die Eigenschaft &quot;Phasen&quot;der nicht definierten Eigenschaft kann nicht gelesen werden]und die Dateien nicht hochladen oder exportieren können.

**Dateien sind in nicht sichtbar[!DNL Internet Explorer]**

_Dokumente_

Wenn ein Benutzer mit einer [!DNL Internet Explorer] Browser navigiert zum [!UICONTROL Dokumente] -Bereich eines Objekts, die [!UICONTROL Dokumente] -Bildschirm ist leer und lädt die Dateien nicht. Für einige Benutzer werden auf dem Bildschirm zwar einige Dateien geladen, die Anzahl der angezeigten Dateien stimmt jedoch nicht mit der Anzahl der Dateien überein, die neben dem [!UICONTROL Dokumente] Abschnitt.

+++

+++**Wartungs-Update am 22. April 2021**

**Aufgaben in der falschen Reihenfolge hinzugefügt**

_Vorlagen_

Wenn ein Benutzer einer Vorlage eine Aufgabe hinzufügt, erhält die Aufgabe nicht die erwartete Aufgabennummer und die Aufgabe wird an der falschen Stelle hinzugefügt.

**Testsendungen werden jetzt in einer E-Mail zusammengefasst**

_Korrekturabzüge_

[!DNL Workfront] sendet jetzt eine E-Mail für kombinierte Testsendungen, anstatt für jede enthaltene Datei eine E-Mail zu versenden.
+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 15. April 2021**

**&quot;[!UICONTROL Szenario abgelehnt]&quot;-Fehler beim Ausführen eines Szenarios**

_[!DNL Workfront Fusion]_

Wenn ein Benutzer versucht, ein Szenario auszuführen, wird das Szenario nicht ausgeführt und der Benutzer erhält die Nachricht &quot;[!UICONTROL Szenario abgelehnt.]&quot;

+++

+++**Wartungs-Update am 15. April 2021**

**[!UICONTROL Lastenausgleich] falsche geplante Stunden anzeigen**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer die geplanten Stunden einer Aufgabe in der [!UICONTROL Lastenausgleich] der Wert der geplanten Stunden nicht mit den der Aufgabe zugewiesenen geplanten Stunden übereinstimmt.

**Die Navigationsleiste am oberen Rand ist in[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Wenn ein Benutzer zu einem [!DNL Workfront Proof] -Seite, die nicht zur Dashboard-Seite gehört, wird die obere Navigationsleiste ausgeblendet. Der Benutzer kann nicht auf die Funktionalität in der Navigationsleiste zugreifen, z. B. auf die Kontoeinstellungen oder das Profil.

**Verbesserungen bei benutzerdefinierten Formularen**

_Benutzerdefinierte Formulare in meiner Gruppe_

Für ein besseres Benutzererlebnis beim Ausfüllen eines benutzerdefinierten Formulars haben wir die Anzeige der langen benutzerdefinierten Feldbezeichnungen verbessert. Wenn ausreichend horizontaler Platz vorhanden ist, um sie vollständig anzuzeigen, werden diese Beschriftungen nicht mehr abgeschnitten.

+++

+++**Wartungs-Update am 8. April 2021**

**Testsendungen können nicht erstellt werden in [!DNL Adobe Creative Cloud] Integration**

_Workfront-Integrationen_

Wenn ein Benutzer versucht, einen Testversand direkt über die [!DNL Adobe Creative Cloud], wird der Testversand nicht erzeugt.

+++

+++**Wartungs-Update am 1. April 2021**

**Probleme beim Anzeigen des Übersichtsbereichs in[!DNL Chrome]**

_[!UICONTROL Zusammenfassung]_

Wenn ein Benutzer die [!UICONTROL Zusammenfassung] Bedienfeld bei Verwendung von [!DNL Chrome] -Browser, verhält sich die Benutzeroberfläche des Zusammenfassungsbereichs nicht wie erwartet. Der Benutzer kann nicht scrollen, die Symbole werden möglicherweise ausgeblendet und der Inhalt kann sich mit anderen Inhalten überschneiden.

**[!UICONTROL Teams] Gebiet in [!UICONTROL Einrichtung] nicht alle Teams anzeigen**

_[!UICONTROL Einrichtung]_

Wenn ein Administrator zur [!UICONTROL Teams] Gebiet von [!UICONTROL Einrichtung], können sie nur von ihnen erstellte Teams anzeigen. Von anderen Administratoren erstellte Teams sind nicht sichtbar.

**Es können keine Aktualisierungen für das Projekt in [!UICONTROL Ausstehende Genehmigung] status**

_Projekte_

Wenn ein Benutzer versucht, einem Projekt eine Aktualisierung hinzuzufügen in [!UICONTROL Ausstehende Genehmigung] und nicht der Benutzer ist, der für die Genehmigung des Projekts zugewiesen wurde, wird die Aktualisierung nicht hinzugefügt und es wird folgender Hinweis angezeigt:

Ein Projekt mit einem[!DNL Pending Approval]Der Status kann nicht bearbeitet werden. Sie können das Projekt ändern, indem Sie den Status ändern.

+++


## Aktualisierungen im März 2021

+++**Wartungs-Update am 26. März 2021**

**Schaltflächen in einem Geschäftsfall werden falsch angezeigt**

_Projekte_

Wenn ein Benutzer einen Geschäftsfall anzeigt und sich das Fenster im Vollbildmodus befindet, wird die [!UICONTROL Speichern] und [!UICONTROL Abbrechen] -Schaltflächen erscheinen in der Mitte des Bildschirms und überschneiden sich die Elemente der Geschäftsszenarios.

**Die Sortierung eines Berichts kann nicht geändert werden**

_Berichte_

Wenn ein Benutzer versucht, die Sortierung eines Berichts in der neuen [!DNL Workfront] -Erfahrung verwenden, ändert sich die Sortierung nicht von der bei der Berichterstellung ausgewählten Sortierung.

**Freigabe für neue Testsendungen deaktiviert**

_[!DNL Workfront Proof]_

Wenn ein Benutzer [!UICONTROL Öffentliche Freigabe] in den Standardeinstellungen für den Testversand aktiviert wurde, wird der Testversand mit deaktivierter Freigabe erstellt. Andere Benutzer können die [!UICONTROL Freigeben] oder teilen Sie den Testversand.

**&quot;[!UICONTROL Testversand konnte nicht generiert werden]&quot;-Fehler bei der Erstellung des Testversands**

_[!DNL Workfront Proof]_

Wenn ein Benutzer versucht, einen Testversand zu erstellen, wird der Testversand nicht erstellt und der Benutzer wird über die folgende Fehlermeldung informiert:

&quot;[!UICONTROL Testversand fehlgeschlagen — interner Fehler]&quot;

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 25. März 2021**

**Redundante Sammlung oder Referenzfeld aus dem Zuordnungsbereich entfernt**

_[!DNL Workfront Fusion]2,0_

Wenn ein Benutzer einen Begriff aus der [!DNL Workfront] API zur Auswahl eines Sammlungs- oder Referenzfelds, das in die Ausgabe eines [!DNL Workfront] -Modul, zeigt die Ausgabe für dieses Modul dieses Feld mit einem Doppelpunkt (z. B. [!UICONTROL owner:name]) und auch in den Attributen (name ist ein Feld unter owner). Das mit einem Doppelpunkt gekennzeichnete Feld enthält keine Daten und liefert falsche Daten, wenn es später im Szenario einem Modul zugeordnet wird.

+++

+++**[!DNL Workfront Fusion]Wartungs-Update am 18. März 2021**

**Die Einstellungen der Projektvorlage gelten jetzt für Projekte, die über erstellt werden [!DNL Workfront Fusion] 2,0**

_[!DNL Workfront Fusion]2,0_

Beim Erstellen eines Projekts aus einer Vorlage mit dem [!DNL Workfront Fusion] 2.0, werden die Vorlageneinstellungen auf das neue Projekt angewendet. Dieses Verhalten ist beim Erstellen eines Projekts aus einer Vorlage im [!DNL Workfront] Anwendung.

+++

+++**Wartungs-Update am 18. März 2021**

**Die Einstellungen der Projektvorlage gelten jetzt für Projekte, die über die API erstellt wurden**

_[!DNL Workfront]API_

Beim Erstellen eines Projekts aus einer Vorlage mit dem [!DNL Workfront] API verwenden, werden die Vorlageneinstellungen auf das neue Projekt angewendet. Dieses Verhalten ist beim Erstellen eines Projekts aus einer Vorlage im [!DNL Workfront] Anwendung.

+++

+++**Wartungs-Update (Hotfix) am 15. März 2021**

**Freigegebene Komponente funktioniert nicht erwartungsgemäß**

_[!DNL Workfront Proof]_

Wenn eigenständig [!DNL Workfront Proof] -Konten in eine freigegebene Komponente verschoben werden, kann die folgende Funktion auftreten, wenn ein Benutzer eine neue Version eines Testversands oder Dokuments hinzufügt:

* Der Benutzer kann den Benutzer nicht löschen [!UICONTROL Studio Proof].
* Die Standardmeldung wird in der neuen Version nicht angezeigt.

**Öffentliche Linkfreigabe bei neuer Version eines Testversands nicht aktiviert**

_Dokumente_

Wenn ein Benutzer die Freigabe öffentlicher Links für einen Testversand aktiviert und dann eine neue Version des Testversands hochlädt, wird die Freigabe öffentlicher Links in der neuen Version des Testversands nicht automatisch aktiviert.

**[!UICONTROL Genehmigen], [!UICONTROL Änderungen], [!UICONTROL Ablehnen] Schaltflächen fehlen beim Testversand**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen Testversand im Testversand-Viewer anzeigt, wird die [!UICONTROL Genehmigen], [!UICONTROL Änderungen]und [!UICONTROL Ablehnen] -Schaltflächen am oberen Bildschirmrand fehlen.

**Die Sortierung eines Berichts kann nicht geändert werden**

_Berichte_

Wenn ein Benutzer versucht, die Sortierung eines Berichts in der neuen [!DNL Workfront] -Erfahrung verwenden, ändert sich die Sortierung nicht von der bei der Berichterstellung ausgewählten Sortierung.

**Benutzerdefinierte Nachricht beim Testversand, die nicht auf eine neue Version übertragen wird**

_[!DNL Workfront Proof]_

Wenn ein Benutzer eine benutzerdefinierte Nachricht an einen Testversand anhängt und dann eine neue Version dieses Testversands hochlädt, wird die benutzerdefinierte Nachricht nicht im neuen Testversand angezeigt.

**Benutzerliste wird nicht angezeigt**

_Listen_

Wenn ein Benutzer versucht, eine Benutzerliste anzuzeigen, und die Ansicht die[!UICONTROL Statussymbole]&quot;, wird die Liste nicht angezeigt.

**&quot;[!UICONTROL Empfänger über diesen Testversand informieren]&quot;Option deaktiviert, unabhängig von Workflow-Einstellungen**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen neuen Testversand erstellt und nicht manuell den[!UICONTROL Empfänger über diesen Testversand informieren]&quot;, wird der vorgesehene Empfänger nicht benachrichtigt. Dies gilt auch dann, wenn die Option in den Workflow-Einstellungen aktiviert ist.

**Zeitrahmen kann nicht geändert werden**

_[!UICONTROL Verbesserte Analytics]_

Wenn ein Benutzer [!UICONTROL Verbesserte Analyse] und auf den Kalender klicken, um den Datumsbereich anzupassen, ändern sich die Daten nicht.

**Das öffentlich freigegebene Dokument kann nicht heruntergeladen werden**

_Dokumente_

Wenn ein Benutzer auf einen freigegebenen Link klickt, um ein Dokument herunterzuladen, wird das Dokument nicht heruntergeladen, und der Benutzer erhält eine Fehlermeldung vom Browser, dass die Seite nicht vorhanden ist.

+++

+++**Wartungs-Update am 11. März 2021**

**Abschnitt eines benutzerdefinierten Formulars, der nicht für Benutzer ohne Administratorrechte exportiert wird**

_Benutzerdefinierte Formulare_

Wenn ein benutzerdefiniertes Formular an ein Objekt angehängt ist, einen Abschnittsumbruch aufweist, der etwas über &quot;[!UICONTROL Ansicht]&quot; Zugriff erforderlich, um den Inhalt des Abschnitts anzuzeigen, kann der Inhalt des Abschnitts nur von einem Administrator exportiert werden.

**Heruntergeladenes Dokument hat falschen Namen**

_[!DNL Workfront Proof]_

Wenn ein Benutzer ein Dokument aus der [!UICONTROL Prüfer], hat das Dokument den Namen einer früheren Version des Dokuments, nicht die heruntergeladene Version.

+++

+++**Wartungs-Update am 4. März 2021**

**Fehler beim Zugriff auf Layoutvorlage**

_Layoutvorlagen_

Wenn sich ein Benutzer bei der neuen [!DNL Workfront] Erlebnis wechselt zur [!DNL Classic] Erfahrung und Versuche, auf eine [!DNL Classic] Layout-Vorlage, sehen sie den Fehler &quot;[!UICONTROL Diese Seite existiert nicht.]&quot;

**Filter in [!UICONTROL Lastenausgleich]**

_[!UICONTROL Lastenausgleich]_

Wenn ein Benutzer versucht, einen Filter im [!UICONTROL Lastenausgleich], wird der Filter-Builder nicht geöffnet.

**&quot;[!UICONTROL Alle Benachrichtigungen anzeigen]&quot;-Link in E-Mail-Benachrichtigung leitet zu falscher Seite um**

_E-Mail-Benachrichtigungen_

Wenn ein Benutzer auf &quot;[!UICONTROL Alle Benachrichtigungen anzeigen]&quot; in einer E-Mail-Benachrichtigung, werden sie zu einer Seite mit der folgenden Nachricht umgeleitet:

&quot;[!UICONTROL Der Benutzer existiert nicht mehr. Sie haben möglicherweise die Internet-Adresse falsch eingegeben. Überprüfen Sie diese und geben Sie sie ggf. erneut ein.]&quot;

**Der Benutzer wird nicht zu dem Testversand-Kommentar weitergeleitet, in dem er getaggt ist**

_E-Mail-Benachrichtigungen_

Wenn ein Benutzer in einem Testversand-Kommentar getaggt wird und er auf die [!UICONTROL Gehe zu Testversand] in einer E-Mail-Benachrichtigung, werden sie zum Testversand weitergeleitet, nicht aber zu dem jeweiligen Kommentar. Wenn sich der Benutzer in [!DNL Workfront Classic], werden sie an die [!UICONTROL Dokumentdetails] anstatt des Kommentars im Testversand.

**Benutzer hinzugefügt zu [!DNL Workfront] Statusempfang**

_[!DNL Workfront Proof]_

Wenn ein Benutzer, der sich nicht im Workflow befindet, einen Testversand von öffnet [!DNL Workfront], erstellt das System automatisch eine Phase, fügt diesen Benutzer zum Testversand hinzu und sendet eine [!UICONTROL Neuer Testversand] E-Mail-Benachrichtigung.

**Dokumentzusammenfassungs-Bedienfeld wird dunkel, sodass Aktionen nicht verfügbar sind**

_Dokumente_

Wenn sich ein Benutzer auf einer Dokumentseite befindet und den Mauszeiger über den Bereich mit der Dokumentzusammenfassung bewegt, wird der Bereich dunkel und kann andere Schaltflächen anzeigen. Der Benutzer kann nicht auf die Aktionen im Zusammenfassungsbereich klicken.

**Änderungen der Stream-Leistung aktualisieren**

_Stream aktualisieren_

Die Anzahl der Benutzeraktualisierungen, die im [!UICONTROL Updates] von jeweils 50 bis 25 zu ändern, um die Leistung zu verbessern.

+++

+++**Wartungs-Update (Hotfix) am 1. März 2021**

**Neue Testversand-E-Mails werden nicht gesendet**

_[!DNL Workfront Proof]_

HINWEIS: Dieses Problem wurde in der neuen [!DNL Workfront] Erlebnis am 26. Februar 2021.
Sie wurde im [!DNL Classic] Erfahrung am 1. März 2021.

Wenn ein Benutzer einen neuen Testversand erstellt und die Option aktiviert [!UICONTROL Empfänger über diesen Testversand informieren]keine E-Mail gesendet, um den Empfänger zu benachrichtigen.

+++


## Aktualisierungen im Februar 2021

+++**Wartungs-Update am 25. Februar 2021**

**[!UICONTROL Planung] -Tool wird in keinem Bereich geladen**

_Ressourcenverwaltung_

Wenn ein Benutzer mit einem Apostroph in seinem Benutzernamen versucht, auf die [!UICONTROL Planung] Tool in [!DNL Workfront Classic], ist die Seite leer und das Tool wird nie geladen.

**Der Name ändert sich in neuen Testversandversionen nicht**

_Dokumente_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis lädt eine neue Version eines Dokuments mit einem anderen Namen hoch. Der Name wird nicht aktualisiert und entspricht nicht dem Namen der neuesten Version.

**[!UICONTROL Document Share] Fehler beim Löschen von Projekten**

_Projekte_

Wenn ein Systemadministrator über Zugriff auf ein kopiertes Projekt verfügt und versucht, es zu löschen oder ein Dokument im Projekt zu löschen, kann er das Objekt nicht löschen, und ihm wird der Fehler angezeigt.[!UICONTROL Dokumentfreigabe mit Primärschlüsselwerten nicht gefunden.]&quot;

**Benutzerbericht wendet nicht alle Filter an**

_Berichte_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis erstellt einen Benutzerbericht mit einer Filterregel, die Folgendes enthält: [!UICONTROL Oberste übergeordnete ID] festgelegt ist, werden keine anderen Filterregeln im Bericht angewendet.

**Berechnete Felder werden nach Bearbeitung nicht neu berechnet**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis bearbeitet und speichert ein benutzerdefiniertes Formular, das berechnete Felder enthält. Diese Felder werden nicht aktualisiert.

**Dokumente, die beim Löschen eines benutzerdefinierten Formulars gelöscht werden**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis löscht ein benutzerdefiniertes Formular &quot;Dokumente&quot;, das an Dokumente angehängt ist. Diese Dokumente werden ebenfalls gelöscht.

+++

+++**Wartungs-Update am 18. Februar 2021**

**Unnötiges Kontrollkästchen wurde aus entfernt [!UICONTROL Anforderungen] area**

_Anforde- rungen_

Das Kontrollkästchen links neben den Anforderungsnamen in der Liste &quot;Gesendet&quot;der [!UICONTROL Anforderungen] Bereich. Dieses Kontrollkästchen war mit keiner Funktionalität verbunden. Daher wurde es entfernt, um ein verwirrendes Erlebnis zu vermeiden.

**Zugriff auf Dokumente über Links nicht möglich**

_Dokumente_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis klickt auf einige Dokumentlinks, kann nicht auf das Dokument zugreifen und die Fehlermeldung wird angezeigt.[!UICONTROL Das Dokument existiert nicht mehr: Möglicherweise haben Sie die Webadresse falsch eingegeben. Überprüfen Sie es und versuchen Sie erneut, die Adresse einzugeben.]&quot; Derselbe Fehler tritt bei der [!UICONTROL Details anzeigen] in den E-Mail-Benachrichtigungen zu Testsendungen.

+++

+++**Workfront Fusion Maintenance Update am 16. Februar 2021**

**[!DNL Workfront Fusion]2.0 zeigt ungenaue Zeitzonen an**

_Szenarios_

Durch diese Aktualisierung wurde ein Problem behoben, bei dem [!DNL Fusion] In 2.0 wurden die Zeitzonen der Benutzer falsch angezeigt. Benutzer können nun ihre Zeitzone unter Eingabefeldern für Datumsangaben sehen.

+++

+++**Wartungs-Update am 11. Februar 2021**

**Testsendungen werden nicht in den ausgewählten Ordner hochgeladen**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen Ordner öffnet und einen neuen Testversand hinzufügt, wird der Testversand in den allgemeinen [!UICONTROL Dokumente] -Bereich des Objekts und nicht innerhalb des Ordners.

**Zu viele fixierte Seiten führen dazu, dass die obere Navigation ausgeblendet wird.**

_Navigation_

Wenn ein Benutzer über mehr als 60 fixierte Seiten verfügt, wird die Ansicht &quot;Top Navigation&quot;nicht mehr angezeigt, was den Benutzer daran hindert, auf [!UICONTROL Suche], die [!UICONTROL Hauptmenü], [!UICONTROL Benachrichtigungen]und mehr.

**Benutzer können Text nicht in ein Rich-Text-Feld eingeben**

_Listen_

Wenn ein Benutzer versucht, ein Rich-Text-Feld inline zu bearbeiten, kann er nur ein einzelnes Zeichen eingeben.

+++

+++**Wartungs-Update am 4. Februar 2021**

**Exportierte Berichte zeigen [!DNL Workfront Classic] Branding**

_Berichte_

Wenn ein Benutzer im neuen Workfront-Erlebnis einen Bericht exportiert, stimmt das Logo, das im exportierten Bericht angezeigt wird, mit dem [!DNL Workfront Classic] unter [!UICONTROL Einrichtung] > [!UICONTROL System] > [!UICONTROL Branding].

+++


## Aktualisierungen im Januar 2021

+++**Wartungs-Update am 28. Januar 2021**

**Kommentare werden nicht angezeigt[!UICONTROL im Namen von]&quot;**

_Updates_

Wenn eine [!DNL Workfront] Der Administrator meldet sich als ein anderer Benutzer an und antwortet auf einen Kommentar in [!UICONTROL Updates] -Bereich eines Objekts den Text &quot;[!UICONTROL im Namen von]&quot; wird nicht vor dem Benutzernamen angezeigt.

**Dokument kann nicht angehängt werden**

_Anforde- rungen_

Wenn ein Benutzer in der neuen [!DNL Workfront] -Erlebnis versucht, ein Dokument zu einer neuen Anforderung von einem externen Dokumentanbieter hinzuzufügen. [!UICONTROL Dokumente] -Liste wird nicht geladen, was verhindert, dass der Benutzer das Dokument auswählt und die Anforderung abschließt.

**Bildschirmbreite nach rechts erweitert, was zu Navigationsproblemen führt**

_[!UICONTROL Home Calendar]_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis öffnet die [!UICONTROL Home Calendar] und einige Wochen fällig sind, wird der Bildschirm nach rechts erweitert, was verhindert, dass die ganze Woche angezeigt wird. Wenn der Benutzer ein Element zum Öffnen des [!UICONTROL Details] -Bedienfeld in diesem Status angezeigt werden und sie Details für ein anderes Element anzeigen möchten, müssen sie nach links blättern, wodurch die [!UICONTROL Details] Bereich.

**Beschriftung des Validierungsprozesses für den einmaligen Einsatz korrigiert**

_Projekte_

Bei Verwendung eines einmaligen Genehmigungsprozesses für ein Projekt in der neuen [!DNL Workfront] Erlebnis wird nun als[!UICONTROL Genehmigungsverfahren für den einmaligen Gebrauch]&quot; anstelle von &quot;\&lt;custom>&quot; in der [!UICONTROL Projekt bearbeiten] ankreuzen. Dies ist noch nicht für Aufgaben und Probleme verfügbar.

**Verbessertes Erscheinungsbild für benutzerdefinierte Formulare**

_Projekte_

Das Erscheinungsbild der Arbeit mit benutzerdefinierten Formularen in der neuen [!DNL Workfront] Erfahrung für Projekte.

**API-Funktionalität für die Projektwährung stimmt jetzt mit der In-App-Funktionalität überein**

_Projekte_

Sie können die Währung eines Projekts nicht ändern, wenn bereits Finanzinformationen zum Projekt vorhanden sind. Mit dem neuesten Wartungsupdate entspricht die API-Funktionalität für diesen Fall jetzt dem Erlebnis im [!DNL Workfront] -Schnittstelle.

**Generiert nicht automatisch die folgende Woche**

_Arbeitszeit- tabellen_

Wenn ein Benutzer zur [!UICONTROL Timesheets] -Bereich, sehen sie nur das Timesheet für die aktuelle Woche. Das Timesheet für die kommenden Wochen wird nicht automatisch generiert.

+++

+++**Wartungs-Update am 21. Januar 2021**

**Die manuelle Sortierung nach einer Spalte zeigt alle Ergebnisse an**

_Berichte_

Wenn ein Benutzer in der neuen [!DNL Workfront] Erlebnis klickt auf einen Balken im Diagramm eines Berichts und klickt dann auf eine Spaltenüberschrift, um die Ergebnisse für diese Gruppierung manuell zu sortieren. Alle Berichtsergebnisse werden angezeigt, nicht nur die Ergebnisse für die ursprünglich ausgewählte Gruppierung.

**&quot;[!UICONTROL Freigabe über URL oder Einbettungscode zulassen]&quot; Einstellungen ändern**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen Testversand erstellt und die Einstellung deaktiviert [!UICONTROL Freigabe über URL oder Einbettungscode zulassen], wird die Einstellung nach der Erstellung des Testversands erneut aktiviert. Wenn der Benutzer die Einstellung aktiviert lässt, wird sie nach der Erstellung des Testversands deaktiviert.

**[!DNL Mac]Benutzer können nicht in Textfelder in der Testversand-Ansicht einfügen**

_[!DNL Workfront Proof]_

Wenn ein Benutzer versucht, Text in bestimmte Felder in der Testversand-Ansicht einzufügen, wird der Text nicht im Feld angezeigt.

+++

+++**Wartungs-Update am 14. Januar 2021**

**E-Mail-Benachrichtigungseinstellungen können nicht aktualisiert werden**

_Einrichtung_

Wenn ein Benutzer versucht, Einstellungen für E-Mail-Benachrichtigungen zu aktualisieren, kann er nicht auf die [!UICONTROL E-Mail-Benachrichtigungen] und die Fehlermeldung anzeigen &quot;[!UICONTROL Versuchen wir es noch einmal! Ups! Etwas ist schiefgelaufen. Bitte kontaktieren Sie uns [!DNL Workfront] damit wir herausfinden können, was schiefgelaufen ist, und es beheben können.]&quot;

**[!UICONTROL Gantt-Diagramm] führt dazu, dass einige Felder abgeschnitten werden**

_Listen_

Wenn ein Benutzer die [!UICONTROL Gantt-Diagramm] in einigen Listenbereichen bestimmte Felder, z. B. [!UICONTROL Beschreibung]—schneiden Sie den Text ab. Der Benutzer muss auf das Feld doppelklicken, um den Volltext anzuzeigen.

**Dateien können nicht von gesendet werden [!UICONTROL Dokumentdetails]**

_Dokumente_

Wenn ein Benutzer in der neuen [!DNL Workfront] -Erlebnis versucht, ein Dokument aus dem [!UICONTROL Dokumentdetails] Seite, sehen sie die Fehlermeldung &quot;[!UICONTROL Es ist ein Fehler aufgetreten, und wir arbeiten daran, das Problem zu beheben. Um mit der Arbeit fortzufahren, versuchen Sie, diese Browser-Seite zu aktualisieren.]&quot;

+++

+++**Wartungs-Update am 7. Januar 2021**

**Dialogfeld &quot;Genehmigungen delegieren&quot;wird geschlossen**

_Startseite_

Wenn ein Benutzer versucht, Genehmigungen in [!UICONTROL Startseite] und auf ein beliebiges Datum klicken, wird das Dialogfeld geschlossen, ohne das Datum auszuwählen oder es dem Benutzer zu ermöglichen, die Benutzerdelegation abzuschließen.

**Problem beim Verschieben eines Dokuments in eine Aufgabe**

_Dokumente_

Wenn ein Benutzer versucht, ein Dokument oder einen Testversand in die neue [!DNL Workfront] -Erfahrung verwenden, wird das übergeordnete Projekt bei einigen Aufgaben außerhalb des Projekts nicht wie erwartet aufgelistet.

**Heruntergeladene PDF hat falschen Namen**

_[!DNL Workfront Proof]_

Wenn ein Benutzer einen Downloadlink per E-Mail erhält ([!UICONTROL Testversand] > [!UICONTROL Kommentare drucken] > [!UICONTROL PDF]) und sie die Datei exportieren, wird die heruntergeladene Datei mit zufälligen Zahlen anstelle der Testversand-ID benannt.

+++
