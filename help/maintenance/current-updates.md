---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 6d87394383aaf54385163729f85ea065588967c9
workflow-type: tm+mt
source-wordcount: '7086'
ht-degree: 100%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2023 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [Frühere Wartungs-Updates](#previous-maintenance-updates)

## Updates im November 2023

+++**Wartungs-Update vom 16. November 2023**

**Die im Nutzungsbericht budgetierten Stunden stimmen nicht mit den über die API gemeldeten budgetierten Stunden überein**

_Berichte_

Wenn jemand für ein bestimmtes Projekt einen API-Aufruf an das RPBGHR-Objekt sendet und die Ergebnisse dieses Aufrufs mit dem Nutzungsbericht für dieses Projekt vergleicht, stimmen die Ergebnisse nicht überein.

**Auf der Seite „Neue Anfrage“ wird eine falsche benutzerdefinierte Währung angezeigt**

_Anfragen_

Wenn jemand eine Anfrage sendet und eine Auswahl trifft, die die Anzeigelogik im Anfrageformular ändert, wird die angezeigte Währung wieder in die Standardwährung zurückgesetzt und nicht in die benutzerdefinierte Währung, die für das Projekt festgelegt ist und für das die Anfrage-Warteschlange steht.

Wenn die Anfrage gesendet wird, wird die Währung als die richtige benutzerdefinierte Währung für das Projekt angezeigt, für das die Anfrage-Warteschlange steht

**Zusätzliche Zeilen in Kommentaren, die über API oder[!DNL Workfront Fusion]** erstellt wurden 

_Updates_

Wenn eine Benutzerin bzw. ein Benutzer einen Kommentar über die API oder über [!DNL Workfront Fusion] eingibt, werden im Bereich „Aktualisierungen“ zusätzliche Zeilen angezeigt. Manchmal sind so viele Zeilen vorhanden, dass nach unten gescrollt werden muss, um den Kommentarinhalt anzuzeigen.

Dies wurde für die neue Kommentarerfahrung berichtet.

+++

    +++**Wartungs-Update vom 9. November 2023**

**Im Widget „Meine Arbeit“ fehlen Objekte, wenn es sich nicht oben auf der Seite befindet**

_Startseite_

Wenn sich das Widget „Meine Arbeit“ oben auf der neuen Startseite befindet, werden alle erwarteten Objekte abgerufen. Wenn sich dieses Widget jedoch unter anderen Widgets auf der Seite befindet, werden nur 10 Objekte abgerufen.

**Korrekturabzug kann nicht erstellt werden**

_Korrekturabzüge_

Beim Versuch, einen Korrekturabzug zu generieren, wird der Korrekturabzug nicht erstellt und der folgende Fehler wird angezeigt:

&quot;[!UICONTROL Fehler beim Generieren des Korrekturabzugs]&quot;

Dies tritt auf, wenn die Zugriffsebeneneinstellung [!UICONTROL Kontaktinformationen anzeigen] der Benutzerin bzw. des Benutzers auf „Deaktiviert“ gesetzt ist.

**Felder werden gelöscht, wenn ein Dokument zu einer Anfrage hinzugefügt wird**

_Anfragen_

Wenn jemand eine Anfrage erstellt, Felder in einem Formular ausfüllt und dann ein Dokument hinzufügt oder entfernt, werden einige Felder im Formular aus den Daten gelöscht und müssen erneut ausgefüllt werden, bevor die Anfrage gesendet wird

**Persönliche Aufgaben werden in der Arbeitszeittabelle angezeigt**

_Arbeitszeittabellen_

Wenn ein Benutzer oder eine Benutzerin eine Aufgabe im [!UICONTROL Todo]-Widget des neuen [!UICONTROL Startseitenerlebnisses] erstellt, wird diese Aufgabe auf der Arbeitszeittabelle der Person angezeigt. Dies ist selbst dann der Fall, wenn für die Aufgabe keine Stunden protokolliert sind und das persönliche Projekt nicht angeheftet ist.

+++

+++**Wartungs-Update (Hotfix) am 3. November 2023**

**Untergeordnete Aufgaben werden beim Verschieben unter die übergeordnete Aufgabe nicht in der richtigen Reihenfolge angezeigt**

_Vorlagen_

Wenn eine Benutzerin bzw. ein Benutzer Aufgaben in einer Vorlage erstellt und diese Aufgaben dann unter eine übergeordnete Aufgabe verschiebt, werden die den untergeordneten Aufgaben zugewiesenen Zahlen nicht in der erwarteten Reihenfolge angezeigt. Wenn die Seite aktualisiert wird, werden die untergeordneten Aufgaben nach den unerwarteten Aufgabennummern sortiert, und die untergeordneten Aufgaben sind daher nicht in der richtigen Reihenfolge.

+++

+++**Wartungs-Update vom 2. November 2023**

**Private Aktualisierungen werden in den Feldern „valueexpression“ angezeigt**

_Berichte_

Wenn ein Berichtsfeld eine „valueexpression“ enthält, die auf eine private Aktualisierung verweist, können auch Benutzende, die nicht Teil der privaten Aktualisierung sind, diese im Bericht sehen.

**Die Benutzerin bzw der Benutzer wird aufgrund ungenauer Kapazität als überlastet angezeigt**

_Workload Balancer_

Eine Anwenderin oder ein Anwender kann im Lastenausgleich als überlastet angezeigt werden. Wird der Mauszeiger über die Überlastung bewegt, erscheint die Kapazität als 0.

Wird der Datumsbereich geändert, ist die Zuordnung korrekt. Nach dem Aktualisieren der Seite kann die Kapazität jedoch wieder ungenau sein.

+++

## Updates im Oktober 2023

+++**Wartungs-Update vom 26. Oktober 2023**

**Suche funktioniert nicht**

_Pinnwände_

Beim Versuch, Pinnwände zu durchsuchen, zeigt die Suche nicht alle Karten an, die die Suchkriterien erfüllen.

**Interaktiver Testversand kann im Web-Viewer nicht angezeigt werden**

_Korrekturabzüge_

Beim Versuch, einen Korrekturabzug im Web-Testversand-Viewer anzuzeigen, wird der Korrekturabzug nicht angezeigt, sondern der folgende Fehler:

„[!UICONTROL Fehlender Schlüssel-Paar-ID-Abfrageparameter oder -Cookie-Wert]“

**Es kann keine neue Version eines Korrekturabzugs erstellt werden**

_Korrekturabzüge_

Beim Versuch, eine neue Version eines Korrekturabzugs zu erstellen, wird die neue Version nicht erzeugt und die folgende Fehlermeldung wird angezeigt:

&quot;[!UICONTROL Fehler beim Generieren des Korrekturabzugs]&quot;

**Benutzerin oder Benutzer wird bei der Freigabe einer Anforderung dupliziert**

_Anfragen_

Wenn bei der Freigabe einer Anfrage die Zugriffsebene einer Benutzerin oder eines Benutzers geändert wird, für die bzw. den die Anfrage freigegeben wird, wird die Person direkt über ihr in der Liste zu dieser Person gemacht.

Wenn die Anfrage beispielsweise für Person A und Person B freigegeben wird und der Zugriff von Person B geändert wird, wird Person A zu Person B geändert, und nun ist Person B zweimal in der Liste enthalten. Darüber hinaus wurde nur der Zugriff von Person B geändert.

**„[!UICONTROL Hoppla]“-Fehler in Aufgabenkopfzeile**

_Aufgaben_

Wenn Benutzende eine Aufgabe anzeigen, enthält die Kopfzeile der Aufgabe keine Informationen. Stattdessen wird die folgende Fehlermeldung angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

+++

+++**Wartungs-Update vom 19. Oktober 2023**

Benutzende werden nicht über Antworten auf einen Kommentar-Thread benachrichtigt

_Benachrichtigungen_

Wenn Benutzende auf einen Kommentar antworten, erhalten andere Benutzende, die Benachrichtigungen für die Antwort erhalten sollen, diese nicht. Einige Benutzende erhalten die Benachrichtigung möglicherweise, andere nicht.

**Zusätzlicher, leerer Kommentar bei Kommentaren zu einem Korrekturabzug**

_Korrekturabzüge_

Wenn Benutzende einen Kommentar zu einem Korrekturabzug abgeben, erzeugt der Korrekturabzug noch einen weiteren Kommentar, der leer ist.

Dies wurde für Video-Korrekturabzüge berichtet.

Registerkarte **[!UICONTROL Aktivität von Korrekturabzügen] öffnet sich nicht**

_Korrekturabzüge_

Wenn Benutzende einen Korrekturabzug anzeigen und auf die Registerkarte [!UICONTROL Korrekturabzug-Aktivität] klicken, leitet die Registerkarte die Benutzenden zur Registerkarte [!UICONTROL Korrekturabzug-Details] zurück.

**[!UICONTROL Geplante Stunden] werden neu zugewiesen, wenn eine zusätzliche Person einer Aufgabe zugewiesen wird**

_Aufgaben_

Wenn eine Benutzerin oder ein Benutzer einer Aufgabe zugewiesen wird, die [!UICONTROL geplante Stunden] hat, die anderen der Aufgabe zugeteilten Personen zugewiesen sind, werden die [!UICONTROL geplanten Stunden] der Aufgabe gleichmäßig auf alle der Aufgabe zugewiesenen Personen verteilt.

**In den Systemaktualisierungen wird „[!UICONTROL Gelöscht]“ als Name der Person angezeigt, wenn das Problem in eine Aufgabe umgewandelt wird**

_Updates_

Wenn eine Person, die als eine andere Person angemeldet ist, ein Problem in eine Aufgabe konvertiert und das Problem einem Team zugewiesen wird, zeigen die Systemaktualisierungen als die Person, die angefordert hat, dass das Team an der Aufgabe arbeitet, „[!UICONTROL Gelöscht]“ an.

+++

+++**Wartungs-Update vom 12. Oktober 2023**

**Arbeitsabläufe wurden für Konten entfernt, die sie nicht verwenden**

_Pinnwände_

Bei Konten, die noch nie einen Arbeitsablauf in der Anwendung „Pinnwände“ erstellt haben, wurde der Bereich „Arbeitsabläufe“ aus dem Pinnwand-Dashboard entfernt. Konten, die Arbeitsabläufe verwenden, haben weiterhin Zugriff darauf.

**Berechnete Felder behalten den Wert nicht, wenn ein Problem in eine Aufgabe konvertiert wird**

_Benutzerdefinierte Formulare_

Berechnete Felder, die auf sich selbst verweisen, behalten ihre Werte nicht, wenn ein Problem in eine Aufgabe konvertiert wird.

Beim Konvertieren des Problems in eine Aufgabe wird der gewünschte Wert zwar im Bearbeitungsfenster korrekt angezeigt. Nach Abschluss der Konvertierung zeigt das berechnete Feld jedoch „k. A.“ an.

**Fehler beim Ändern von Filtern auf der [!UICONTROL Startseite]**

_Startseite_

Beim Ändern der Filter auf der [!UICONTROL Startseite] wird der Bereich [!UICONTROL Startseite] nicht geladen und es wird der folgende Fehler angezeigt:

„[!UICONTROL Ein Fehler ist aufgetreten und wir arbeiten an der Behebung des Problems. Bitte versuchen, diese Browser-Seite zu aktualisieren, um mit der Arbeit fortzufahren.]“

+++

+++**Wartungs-Update vom 5. Oktober 2023**

**Die Pinnwand wird langsam geladen**

_Pinnwände_

Wenn Benutzende eine Pinnwand laden, wird die Pinnwand extrem langsam geladen. Dies kann auch auftreten, wenn die Pinnwand nur eine kleine Anzahl von Karten hat.

Archivierte Karten, selbst wenn sie nicht angezeigt wurden, wirkten sich auf die Ladezeit der Pinnwand aus.

**Karten können nicht zwischen Spalten verschoben werden**

_Pinnwände_

Beim Versuch, eine Karte auf einer Pinnwand zu verschieben, wird die Karte nicht verschoben. Dies geschieht unter den folgenden Umständen:

* Drag-and-Drop
* Option „Verschieben“ auf der Karte
* Bearbeiten der Karte

**Karten können nicht aus der Aufnahmespalte verschoben werden**

_Pinnwände_

Man kann eine Karte aus der Aufnahmespalte in eine andere Spalte auf der Pinnwand ziehen, aber nachfolgende Karten können nicht aus der Aufnahmespalte verschoben werden.

**„Gruppieren nach“ hat Auswirkungen auf die Leistung der Pinnwand**

_Pinnwände_

Beim Versuch, die Karten nach Bevollmächtigten oder Tags zu gruppieren, wird die Leistung der Pinnwand sehr langsam.

**Automatische E-Mail-Erinnerungen werden nicht gesendet**

_Benachrichtigungen_

Automatische E-Mail-Erinnerungen werden nicht gesendet. Dies begann am 14. September 2023.

+++

## Updates im September 2023

+++**Wartungs-Update vom 28. September 2023**

**Benutzerdefiniertes Feld kann nicht gelöscht werden**

_Benutzerdefinierte Formulare_

„Beim Versuch, ein benutzerdefiniertes Feld zu löschen, kann es nicht gelöscht werden und es wird die Meldung angezeigt: [!UICONTROL Datenbankfehler aufgrund einer Einschränkungsverletzung].“

**Im neuen Kommentarerlebnis vorgenommene Kommentare sind im alten Erlebnis nicht sichtbar**

_Updates_

Wenn jemand im neuen Kommentarerlebnis einen Kommentar abgibt und dieser im Kommentarbereich des neuen Erlebnisses angezeigt wird, wird derselbe Kommentar möglicherweise nicht im alten Kommentarerlebnis angezeigt. Dies kann dazu führen, dass Benutzende, die das alte Erlebnis verwenden, Kommentare verpassen.

**Auf der Objektseite fehlen Elemente**

_Workfront_

Wenn in [!DNL Workfront] zu einem benutzerdefinierten Abschnitt eines Objekts navigiert wird, fehlen auf der geladenen Seite möglicherweise einige Elemente. Dies können folgende Elemente sein:

* Das linke Navigationsfenster
* Der Name des Objekts, zu dem der benutzerdefinierte Abschnitt gehört
* Felder und Informationen in der Kopfzeile

+++

+++**Wartungs-Update vom 21. September 2023**

**Benutzerin bzw. Benutzer kann auf einer Pinnwand einem Arbeitsablauf nicht zugewiesen werden**

_Pinnwände_

Wenn jemand versucht, einer Aufgabe auf einer Pinnwand, die Teil eines Arbeitsablaufs ist, einer anderen Person zuzuweisen, und beginnt, deren Namen einzugeben, erscheint diese Person nicht in der Dropdown-Liste der verfügbaren Benutzenden. Dies ist auch dann der Fall, wenn die Person aktiv und sowohl Mitglied der Pinnwand als auch des Arbeitsablaufs ist.

Möglicherweise werden auch deaktivierte Personen in der Dropdown-Liste angezeigt.

**Checklisten-Element kann nicht gelöscht werden**

_Pinnwände_

Beim Versuch, ein Checklisten-Element aus einer Karte auf einer Pinnwand zu löschen, reagiert die Schaltfläche [!UICONTROL Löschen] nicht und das Element wird nicht gelöscht.

**Benutzerdefinierte Formulare werden langsam geladen**

_Benutzerdefinierte Formulare_

Beim Versuch, ein benutzerdefiniertes Formular zu laden, wird dieses langsam geladen.

**Dokument kann nicht in einen anderen Ordner verschoben werden**

_Dokumente_

Beim Versuch, ein Dokument in einen Objektordner zu verschieben, lässt sich das Objekt nicht in einen anderen Ordner verschieben.

**XML-Fehler beim Herunterladen**

_Dokumente_

Beim Versuch, ein Dokument herunterzuladen, wird das Dokument nicht heruntergeladen und es wird eine Seite mit der folgenden Meldung gefolgt von XML-Text angezeigt.

„[!UICONTROL Der XML-Datei sind anscheinend keine Stilinformationen zugeordnet. Die Dokumentstruktur befindet sich unten.]“

**Dokumente können nicht aus Vorschau-/Sandbox-Umgebungen heruntergeladen werden**

_Dokumente_

Beim Versuch, ein Dokument aus einer anderen Umgebung als der Produktionsumgebung herunterzuladen, wird es nicht heruntergeladen, und es wird folgender Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

**Korrekturabzüge erscheinen entsättigt oder beschnitten**

_Korrekturabzüge_

Beim Erstellen eines Korrekturabzugs über eine URL wurden die folgenden Probleme gemeldet:

* Der Korrekturabzug erscheint entsättigt oder verwaschen.
* Der Korrekturabzug ist beschnitten.

Dies kann die Entscheidung für einen Korrekturabzug erschweren, da er nicht korrekt dargestellt wird.

**Die Erstellung von Korrekturabzügen dauert zu lange**

_Korrekturabzüge_

Die Erstellung eines Korrekturabzugs dauert übermäßig lange. Die Erstellung eines Korrekturabzugs kann mehrere Tage in Anspruch nehmen.

+++

+++**Wartungs-Update vom 14. September 2023**

**Fehler „[!UICONTROL Keine Fabrik]“ beim Hinzufügen eines Dokuments**

_Dokumente_

Beim Versuch, ein Dokument aus einer externen Quelle hinzuzufügen, [!DNL Workfront] kann nicht auf die Quelle zugegriffen werden, und es wird folgender Fehler angezeigt:

„[!UICONTROL Folgender Fehler ist aufgetreten: Keine Fabrik für den Authentifizierungstyp Null]“

**Fehler „Hoppla“ in Matrix-Berichten**

_Berichte_

Beim Versuch, einen Matrix-Bericht zu öffnen, wird dieser nicht geladen und der folgende Fehler angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies geschieht bei der Gruppierung eines Berichts nach Datumsbereichen.

+++

+++**Wartungs-Update vom 11. September 2023**

**Persönliche Aufgaben werden nicht in Arbeitszeittabellen angezeigt**

_Arbeitszeittabellen_

Persönliche Aufgaben werden nicht mehr standardmäßig in der Arbeitszeittabelle angezeigt. Persönliche Aufgaben werden in der Arbeitszeittabelle angezeigt, wenn sie veröffentlicht oder Stunden protokolliert werden. Vor dieser Änderung wurden persönliche Aufgaben standardmäßig in den Arbeitszeittabellen angezeigt.

+++

+++**Wartungs-Update vom 7. September 2023**

**Das Projekt ist leer, wenn es aus dem neuen [!UICONTROL Startseitenerlebnis] geladen wird**

_Projekte_

Wenn jemand auf der [!UICONTROL Startseite] im neuen Startseitenerlebnis auf ein Projekt klickt, wird die Seite des Projekts nicht geladen.

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

Beim Versuch, einen Matrix-Bericht als Diagramm zu laden, kann eine der folgenden Situationen auftreten:

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

Wenn ein Korrekturabzug im Überprüfungs-Viewer angezeigt wird und versucht wird, Text auszuwählen, der sich in einer Liste oder einem Aufzählungspunkt befindet, ist das Textauswahlwerkzeug nicht wirksam und der Text kann nicht ausgewählt werden.

**Beim Erstellen einer neuen Korrekturabzugsversion werden alle Versionen des Korrekturabzugs gelöscht**

_Korrekturabzüge_

Beim Erstellen eines Korrekturabzugs aus einem Dokument wird der Korrekturabzug zwar erstellt. Wenn jedoch eine andere Version des Korrekturabzugs erstellt wird, werden sowohl die alte als auch die neue Version gelöscht. Es gibt die Option [!UICONTROL Korrekturversand erstellen] für das Originaldokument, und die Korrekturabzugsversion findet sich im [!UICONTROL Papierkorb] des Bereichs [!UICONTROL Proofing] in [!DNL Workfront].

+++

+++**Wartungs-Update vom 17. August 2023**

**Es ist nicht möglich, zu einem Projekt mit einer URL zu navigieren, die eine [!UICONTROL Referenz-ID]** verwendet

_Projekte_

Beim Versuch, mithilfe einer URL, die eine [!UICONTROL Referenz-ID] enthält, zu einem Projekt zu navigieren, wird zu einer Seite mit einer Fehlermeldung umgeleitet. Die Navigation zu einer Aufgabe mithilfe eines URI mit einer [!UICONTROL Referenz-ID] funktioniert erwartungsgemäß.

**Die Einstellung „[!UICONTROL E-Mail-Benachrichtigungen für Korrekturabzug deaktivieren]“ wird ungenau angezeigt**

_Korrekturabzüge_

Wenn jemand in [!DNL Workfront] die Einstellungen für Korrekturabzüge anzeigt, zeigt das Kontrollkästchen „[!UICONTROL E-Mail-Benachrichtigungen für Korrekturabzug deaktivieren]“ nicht die richtige aktuelle Einstellung an. Wenn das Kästchen aktiviert ist und dadurch angibt, dass E-Mail-Benachrichtigungen für einen Korrekturabzug deaktiviert sind, sind Benachrichtigungen trotzdem aktiviert. Umgekehrt ist dies ebenso der Fall.

**Korrekturabzugsmarkierungen können nicht angepasst werden**

_Korrekturabzüge_

Wenn jemand im Überprüfungs-Viewer einen Kommentar abgibt, eine Markierung auf dem Korrekturabzug vornimmt und dann wegklickt, kann die Markierung nicht mehr angepasst werden.

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

**Tags und Checklisten-Elemente funktionieren in der Pinnwandansicht eines Projekts nicht ordnungsgemäß**

_Pinnwände_

Tags und Checklisten-Elemente wurden aus der Pinnwandansicht von Projekten entfernt, da sie nicht zu Workfront-Aufgaben gehören und nicht von Benutzenden gemeinsam genutzt werden können.

**„[!UICONTROL Systemweit aktivieren]“ und „[!UICONTROL Systemweit anzeigen]“ stellen verschiedene Funktionen dar**

_Filter_

Wenn jemand einen Filter freigibt und die Option „[!UICONTROL Systemweit anzeigen]“ aktiviert, wird der Filter für jede Benutzerin bzw. jeden Benutzer im System freigegeben. Wenn Admins diesen Filter jedoch im [!UICONTROL Setup] anzeigen, sehen sie, dass für diesen Filter „[!UICONTROL false]“ in der Spalte „[!UICONTROL Systemweit sichtbar]“ angezeigt wird. Damit dieser Filter zu einer Standardeinstellung des Systems wird, müssen Admins die Option „[!UICONTROL Systemweit aktivieren]“ im [!UICONTROL Setup] aktivieren. Dies kann aufgrund der Ähnlichkeit der Formulierung zu Verwirrung führen.

+++

+++**Wartungs-Update vom 20. Juli 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 13. Juli 2023**

**Timeline wird nicht neu berechnet**

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

Wenn eine Benutzerin oder ein Benutzer versucht, andere Benutzende zu bearbeiten, ist die Seite „Benutzer bearbeiten“ leer und es ist nicht möglich, andere Benutzende zu bearbeiten.

+++

## Updates im Juni 2023

+++**Wartungs-Update vom 29. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 22. Juni 2023**

**Fehler beim Anzeigen des Matrixberichts**

_Berichte_

Wenn jemand einen Matrixbericht anzeigt, erscheint der folgende Fehler:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Dies wurde gemeldet, wenn der Bericht nach Datum sortiert wird und die Option „[!UICONTROL Wochen ohne Ergebnisse anzeigen]“ aktiviert ist.

**Datumsangaben werden in Matrixberichten falsch angezeigt**

_Berichte_

Wenn ein Diagramm oder Matrixbericht nach Datum gruppiert ist, können Datumsangaben in der Nähe der Gruppierungsränder entweder in der richtigen Gruppierung oder der vorherigen/nächsten Gruppierung oder auch in beiden erscheinen.

+++

+++**Wartungs-Update vom 15. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**Wartungs-Update vom 8. Juni 2023**

Dieses Update enthält nur kleinere oder weniger bedeutende Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update vom 8. Juni 2023**

[!DNL Fusion] hat eine Fehlerbehebung implementiert, die verhindert, dass die Verbindungen einer Benutzerin oder eines Benutzers entfernt werden, wenn die Person in [!UICONTROL Adobe Admin Console] deaktiviert ist.

Admins von [!DNL Fusion]-Teams können weiterhin nicht benötigte Verbindungen von der Seite [!UICONTROL Verbindungen] in [!DNL Fusion] entfernen.

+++

+++**Wartungs-Update vom 1. Juni 2023**

**Keine Fehlermeldung bei Neuanordnung einer Aufgabe im Status [!UICONTROL Ausstehende Genehmigung]**

_Aufgaben_

Wenn beim Versuch, eine Aufgabe in einer Aufgabenliste neu anzuordnen, sich die Aufgabe im Status [!UICONTROL Ausstehende Genehmigung] befindet, wird die Aufgabe scheinbar in die Aufgabenliste verschoben. Nach der Aktualisierung zeigt sich jedoch, dass das Element nicht verschoben wurde. Das Element kann nicht verschoben werden, da es sich im Status [!UICONTROL Ausstehende Genehmigung] befindet, doch es gibt keine Meldung, die darauf hinweist, dass das Element nicht verschoben werden kann, was zu Verwirrung führen kann.

**Keine Fehlermeldung beim Verschieben einer Vorgängeraufgabe unter eine abhängige Aufgabe**

_Aufgaben_

Wenn beim Versuch, eine Aufgabe in einer Aufgabenliste neu anzuordnen, sich die Aufgabe im Status [!UICONTROL Ausstehende Genehmigung] befindet, wird die Aufgabe scheinbar in die Aufgabenliste verschoben. Nach der Aktualisierung zeigt sich jedoch, dass das Element nicht verschoben wurde. Das Element kann nicht verschoben werden, da eine Vorgängeraufgabe nicht unter eine Aufgabe verschoben werden kann, deren Vorgänger sie ist. Es gibt jedoch keine Meldung, die darauf hinweist, dass das Element nicht verschoben werden kann, was zu Verwirrung führen kann.

+++

## Updates im Mai 2023

+++**Wartungs-Update vom 25. Mai 2023**

**[!UICONTROL Kanban]-Pinnwand beim Bearbeiten von Karten leer**

_Agile_

Wenn jemand etwas an einer Karte auf der [!UICONTROL Kanban]-Pinnwand ändert, dann wird die [!UICONTROL Kanban]-Pinnwand leer, anstatt mit der Änderung aktualisiert zu werden. Nach manuellem Aktualisieren der Seite wird die [!UICONTROL Kanban]-Pinnwand wieder angezeigt, und zwar mit der korrekten Änderung.

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
Wenn jemand einen Aufgabenbericht ausführt, wird der Bericht beim Laden scheinbar korrekt sortiert, doch nach Abschluss des Ladevorgangs ist ersichtlich, dass der Bericht nicht korrekt sortiert wurde.

Dies scheint zu passieren, wenn alle folgenden Bedingungen erfüllt sind:

* Der Bericht ist ein Aufgabenbericht
* Der Bericht wird nach einem benutzerdefinierten Feld sortiert
* Auf den Bericht wird eine Gruppierung angewendet

+++

+++**Wartungs-Update am 11. Mai 2023**

**Korrekturabzugsversion kann bei der Ansicht des Korrekturstatus nicht gewechselt werden**

_Korrekturabzüge_

Wenn jemand einen Korrekturabzug im [!UICONTROL Überprüfungs-Viewer] anzeigt und zu einer anderen Version wechselt, wird das Dropdown-Menü für die Version deaktiviert, und die Person kann nicht zur Originalversion, die sie angezeigt hat, oder zu einer anderen Version des Korrekturabzugs zurückkehren.

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

Sie können jetzt in Workfront vorhandene Aufgaben- und Problemfilter beim Konfigurieren der Aufnahmespalte für eine Pinnwand verwenden. Vorhandene Aufnahmespaltenfilter sind jetzt jedoch im Konfigurationsbereich schreibgeschützt. Die vorhandenen Filter werden weiterhin auf die Aufnahmespalte angewendet, doch müssen die Filter neu erstellt werden, um sie bearbeiten zu können.

+++

+++**Wartungs-Update vom 4. Mai 2023**

**Vorlage kann nicht aus den [!UICONTROL Favoritenvorlagen]** ausgewählt werden

_Vorlagen_

Wenn jemand versucht, eine Vorlage aus dem Menü „Aktionen“ (drei Punkte) auszuwählen, wird die Liste der Vorlagen ausgeblendet, sobald die Maus zur Liste bewegt wird, und es kann keine Vorlage ausgewählt werden. Dies liegt daran, dass sich die Bildlaufleiste zwischen dem Menü und der Liste der Vorlagen befindet und der Fokus der Maus auf die Bildlaufleiste gelegt wird, wenn sie zur Liste der Vorlagen bewegt wird.

+++

## Updates im April 2023

+++**Wartungs-Update vom 27. April 2023**

**Kann im [!UICONTROL Überprüfungs-Viewer]** nicht zwischen Korrekturabzügen wechseln

_Korrekturabzüge_

Wenn jemand einen Korrekturabzug im [!UICONTROL Überprüfungs-Viewer] anzeigt und zu einem anderen Korrekturabzug wechselt, reagiert die Schaltfläche „Korrekturabzug wechseln“ nicht mehr. Die Person kann nicht zum ursprünglichen Korrekturabzug, den sie angesehen hat, oder zu einem anderen Korrekturabzug zurückkehren.

**Bearbeiten von angehängten Bildern beim Bearbeiten eines Kommentars**

_Updates_

Sie können jetzt das Bild bearbeiten, das an einen Kommentar angehängt ist, wenn Sie einen Kommentar bearbeiten. Dies ist im Abschnitt „Aktualisierungen“ für Workfront-Ziele und im Abschnitt „Probleme“ bei der Aktivierung des Beta-Kommentierungserlebnisses verfügbar.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update vom 25. April 2023**

In-App-Hilfe-Links in **[!DNL Fusion]führen nicht zu den jeweiligen Hilfeseiten**

_[!DNL Workfront Fusion]_

Wenn jemand einen Korrekturabzug im [!UICONTROL Überprüfungs-Viewer] anzeigt und zu einem anderen Korrekturabzug wechselt, reagiert die Schaltfläche „Korrekturabzug wechseln“ nicht mehr. Die Person kann nicht zum ursprünglichen Korrekturabzug, den sie angesehen hat, oder zu einem anderen Korrekturabzug zurückkehren.

+++

+++**Wartungs-Update vom 20. April 2023**

**Probleme in benutzerdefinierten Dropdown-Feldern**

_Benutzerdefinierte Formulare_

Benutzerdefinierte Dropdown-Felder, die als Mehrfachauswahlfelder aktiviert sind, können die folgenden Probleme anzeigen:

* Die Schaltfläche „+[!UICONTROL Hinzufügen]“ ist nicht vorhanden, wenn sich das Formular nicht im Bearbeitungsmodus befindet.
* Felder ohne Werte zeigen eine Option „--[!UICONTROL keine Beschriftung]--“ an.

**Mehrzeilenwerkzeug kann nicht für einen Kommentar zu einem Korrekturabzug verwendet werden**

_Korrekturabzüge_

Wenn jemand einen Korrekturabzug im Überprüfungs-Viewer anzeigt und versucht, mit dem Mehrzeilenwerkzeug einen Kommentar abzugeben, markiert das Werkzeug den Korrekturabzug nicht.

**Feld mit Textoptionen zeigt „textAnnotations“**

_Korrekturabzüge_

Wenn jemand einen Korrekturabzug anzeigt, einen Kommentar verfasst und das Textwerkzeug öffnet, wird neben den Optionen im Werkzeug das Wort „textAnnotation“ angezeigt. Das Textwerkzeug funktioniert dennoch wie erwartet und „textAnnotation“ verschwindet, nachdem der Kommentar veröffentlicht wurde.

**Bilder werden als Entwurf beibehalten, wenn mit der Beta-Kommentar-Funktion von einer Aktualisierung wegnavigiert wird**

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

Die Zugriffsebene einer Benutzerin oder eines Benutzers kann vom System unvorhersehbar geändert werden. In diesem Fall gibt es keine sichtbare Aktualisierung, und die Änderung wird nicht im Administratorprotokoll angezeigt.

+++

+++**Wartungs-Update vom 17. April 2023**

**Anzeige neuer Kommentare außerhalb des sichtbaren Bildschirmbereichs im Abschnitt [!UICONTROL Aktualisierungen] von Problemen (neue Beta-Kommentar-Funktion) und im Abschnitt [!UICONTROL Ziele]**

_Aktualisierungen_

Wir haben ein Benachrichtigungs-Banner für den Abschnitt [!UICONTROL Aktualisierungen] hinzugefügt, um Benutzende darüber zu informieren, wenn neue Kommentare zu einem Element vorhanden sind, das sich außerhalb des sichtbaren Bereichs des Bildschirms befindet. Dieses Update ist derzeit im Abschnitt [!UICONTROL Aktualisierung] bei Zielen sowie Problemen verfügbar, nachdem die neue Beta-Kommentar-Funktion für Probleme aktiviert wurde.

+++

+++**Wartungs-Update vom 13. April 2023**

**Filter werden nicht auf die Anfrageliste angewendet**

_Anfragen_

Wenn eine Liste von Anfragen angezeigt wird, auf die ein Filter angewendet wurde, enthält die Liste Anfragen, die vom Filter ausgeschlossen werden sollten.

**Auswahl von [!UICONTROL Standardstundentyp] oder [!UICONTROL Verfügbare Stundentypen]** ist nicht möglich

_Benutzende_

Wenn Admins eine Benutzerin oder einen Benutzer bearbeiten und versuchen, einen Wert für [!UICONTROL Standardstundentyp] oder [!UICONTROL Verfügbarer Stundentyp] auszuwählen, sind die Dropdown-Listen für diese Felder deaktiviert, sodass keine Stundentypen ausgewählt werden können.

+++

+++**Wartungs-Update vom 6. April 2023**

**Dropdown-Listen werden nicht geöffnet, wenn Benutzende zu einem Korrekturabzug hinzugefügt werden**

_Korrekturabzüge_

Wenn Benutzende andere Benutzende zu einem Korrekturabzug im [!UICONTROL Überprüfungs-Viewer] hinzufügen, können die Dropdown-Listen „[!UICONTROL Korrekturabzug-Rolle]“ und „[!UICONTROL E-Mail-Warnungen]“ nicht geöffnet werden. Die Benutzenden können keine Korrekturabzug-Rolle oder E-Mail-Warnung zuweisen. Dies kann vorkommen, wenn Benutzende über einen Kommentar hinzugefügt werden oder der Korrekturabzug für die Benutzenden freigegeben wird.

+++

## Updates im März 2023

+++**Wartungs-Update vom 30. März 2023**

**Korrekturabzugsversion kann bei der Ansicht des Korrekturstatus nicht gewechselt werden**

_Korrekturabzüge_

Wenn jemand einen Korrekturabzug im [!UICONTROL Überprüfungs-Viewer] anzeigt und zu einer anderen Version wechselt, wird das Dropdown-Menü für die Version deaktiviert, und die Person kann nicht zur Originalversion, die sie angezeigt hat, oder zu einer anderen Version des Korrekturabzugs zurückkehren.

**504-Fehler beim Exportieren von Berichten**

_Berichte_

Wenn jemand versucht, einen Bericht mit einer hohen Anzahl von Elementen zu exportieren, wird ein 504-Fehler angezeigt und der Bericht kann nicht exportiert werden.

**Im Auftrag von Benutzenden vorgenommene Aktualisierungen werden als direkt von dieser Person angezeigt**

_Updates_

Wenn Admins als Benutzende angemeldet sind und einen Kommentar abgeben, wird dieser Kommentar als direkt von dieser Person und nicht als von Admins im Namen der Benutzenden angezeigt.

+++

+++**Wartungs-Update vom 23. März 2023**

Inhalte des Bedienfelds **[!UICONTROL Zusammenfassung] sind zu breit für das Bedienfeld**

_Dokumente_

Wenn jemand das Bedienfeld [!UICONTROL Zusammenfassung] für ein Dokument ansieht, sind die Inhalte zu breit, um im Bedienfeld sichtbar zu sein. Das Bedienfeld verfügt nun über eine horizontale Bildlaufleiste und Benutzende müssen horizontal scrollen, um die Inhalte des Bedienfelds [!UICONTROL Zusammenfassung] zu sehen. Dies geschieht, weil der Dateiname des Dokuments nicht umgebrochen wird. Dieses Problem ist auf Dateien beschränkt, bei welchen der Dateiname eine HTML-Dateierweiterung aufweist.

**Neue [!UICONTROL Desktop Überprüfungs-Viewer]-Version**

_Proofing_

Um ein Kommentierproblem im [!UICONTROL Desktop Überprüfungs-Viewer] zu beheben, haben wir eine neue Version des Desktop Überprüfungs-Viewers bereitgestellt.

Benutzende, die den [!UICONTROL Desktop Überprüfungs-Viewer] bereits installiert haben, erhalten dieses Update automatisch.

Benutzende können die neueste Version auch manuell herunterladen. Weitere Informationen finden Sie unter [[!UICONTROL Installieren des Desktop Überprüfungs-Viewers]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=de).

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

Wenn eine Benutzerin bzw. ein Benutzer eine deaktivierte Person erneut aktiviert und versucht, ihr im Fenster [!UICONTROL Benutzer erneut aktivieren] eine Zugriffsebene zuzuweisen, wird das Dropdown-Menü für die Zugriffsebenen nicht entsprechend der Benutzereingabe angezeigt und es kann keine Zugriffsebene ausgewählt werden. Auch wenn die Zugriffsebene eingegeben und gespeichert wird, wird diese Zugriffsebene der erneut aktivierten Person nicht zugewiesen.

**Speichern eines Kommentarentwurfs im Bereich [!DNL Goals]**

_[!DNL Workfront Goals]_

Wenn Sie von der Seite [!UICONTROL Updates] eines Ziels während der Erstellung einer Nachricht wegnavigieren, wird die Nachricht beim Zurücknavigieren jetzt beibehalten. Vor dieser Aktualisierung wäre der nicht übermittelte Kommentar gelöscht worden.

+++

+++**Wartungs-Update vom 2. März 2023**

**Bei angewendeter Gruppierung können keine Karten hinzugefügt werden**

_Pinnwände_

Wenn jemand eine Pinnwand mit angewendeter Gruppierung anzeigt und versucht, eine Karte hinzuzufügen, lässt sich nur der Name der Karte eingeben. Die übrigen Kartenfelder sind deaktiviert, einschließlich der Schaltfläche [!UICONTROL Speichern].

Auch Wenn die Person die Gruppierung in [!UICONTROL Keine] ändert, bleibt das Problem bestehen. Es muss die Gruppierung in [!UICONTROL Keine] geändert und außerdem die Seite aktualisiert werden, um die Möglichkeit zum Hinzufügen einer Karte wiederherzustellen.

**Verbundene Karten werden nicht nach Status zu Spalten hinzugefügt**

_Pinnwände_

Obwohl Spaltenrichtlinien auf den Status angewendet werden, erscheinen neue verbundene Karten in der Spalte ganz links und nicht in der Spalte, die ihrem Status entspricht.


**Link zu einem Kommentar leitet auf die Seite [!UICONTROL Details] um**

_Updates_

Wenn jemand einem Link zu einem Kommentar folgt, der sich auf ein Objekt in Workfront bezieht, wird der Aktualisierungsstrom kurz geladen und die Person dann zum Bereich [!UICONTROL Details] des Objekts weitergeleitet. Dies kann vorkommen, wenn die Person in einer E-Mail auf den Link klickt oder den Link in den Browser einfügt.

Dies betrifft derzeit nur Dokumentobjekte.

**Druckzusammenfassung wird nicht geladen**

_[!UICONTROL Workfront-Korrekturabzug]_

Wenn eine Benutzerin bzw. ein Benutzer versucht, die Seite „Druckzusammenfassung“ zu laden, scheint die Seite zu laden, sie wird jedoch nie geladen.

+++

## Updates im Februar 2023

+++**Wartungs-Update vom 23. Februar 2023**

**Link zu einem Kommentar leitet auf die Seite [!UICONTROL Details] um**

_Updates_

Wenn jemand einem Link zu einem Kommentar folgt, der sich auf ein Objekt in Workfront bezieht, wird der Aktualisierungsstrom kurz geladen und die Person dann zum Bereich [!UICONTROL Details] des Objekts weitergeleitet. Dies kann vorkommen, wenn die Person in einer E-Mail auf den Link klickt oder den Link in den Browser einfügt.

Dies betrifft derzeit nur Dokumentobjekte.

**Benutzende können ihre eigenen Benachrichtigungseinstellungen nicht bearbeiten**

_Benutzende_

Wenn Benutzende mit der Lizenz [!UICONTROL Arbeitskraft] versuchten, ihre eigenen Benachrichtigungseinstellungen zu bearbeiten, werden die [!UICONTROL Benachrichtigungsoptionen] im Fenster [!UICONTROL Bearbeiten] nicht angezeigt, und die Einstellungen lassen sich nicht bearbeiten.

+++

+++**Wartungs-Update vom 16. Februar 2023**

**Mehrere Team-Zuweisungen auf Pinnwänden**

_Pinnwände_

Sie können jetzt mehrere Teams einer Aufgabe oder einem Problem auf einer Pinnwand und der Pinnwand selbst zuweisen.

**Verlängerung der Gültigkeitsdauer von Karten**

_Pinnwände_

Die Gültigkeitsdauer von Karten wurde von 4 Wochen/30 Tage auf 8 Wochen/60 Tage verlängert.

**Eine geplante Deaktivierung deaktiviert Benutzende nicht**

_Benutzende_

Wenn die Deaktivierung von Benutzenden geplant ist und das geplante Datum und die geplante Uhrzeit vergehen, werden Benutzende nicht deaktiviert.

+++

+++**Wartungs-Update vom 9. Februar 2023**

Das Feld **[!UICONTROL Story-Punkte] wurde zu Aufgaben- und Problemlisten und Berichten hinzugefügt**

_Berichte_

Das Feld [!UICONTROL Story-Punkte] kann jetzt zu Listen und Berichten für Aufgaben oder Probleme hinzugefügt werden. Es handelt sich dabei um ein editierbares Freiform-Feld, das nicht an geplante Stunden oder Team-Arbeitsaufträge gebunden ist.

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

Der Bereich, für den diese Aktionen ausgeführt werden, muss erst hervorgehoben werden, damit sie angewendet werden können.

**Neue Informationssymbole für Arbeitszeittabellen, Arbeitszeittabellenprofile und Arbeitszeittabellen-Voreinstellungen**

_Arbeitszeittabellen_

>[!NOTE]
>
>Dieses Update wurde am 3. November 2022 nur in der Vorschau-Umgebung veröffentlicht und ist jetzt in der Produktionsumgebung verfügbar.

Wir haben zu den folgenden Einstellungen mehrere Informationssymbole hinzugefügt:

* Wenn das Kontrollkästchen „[!UICONTROL Kann Zeit bearbeiten]“ bei der Erstellung oder Bearbeitung einer Arbeitszeittabelle oder eines Arbeitszeittabellenprofils aktiviert wird, bedeutet dies, dass die genehmigenden Personen auch die Arbeitszeittabelle senden, erneut öffnen oder bearbeiten können, es sei denn, die Admins beschränken diese Aktionen im Bereich „[!UICONTROL Arbeitszeittabellen-Voreinstellungen]“ im [!UICONTROL Setup].
* Wenn die Option „[!UICONTROL Bearbeitung von Arbeitszeittabellen auf Eigentümer und Admins beschränken]“ im Bereich [!UICONTROL Arbeitszeittabellen- und Stunden-Voreinstellungen] von [!UICONTROL Setup] deaktiviert ist, können auch die folgenden Benutzenden die Arbeitszeittabellen bearbeiten: Benutzende mit administrativem Zugriff auf Arbeitszeittabellen und Stunden, genehmigende Personen für Arbeitszeittabellen, die die Zeit bearbeiten dürfen, und Führungskräfte der Eigentümerinnen und Eigentümer von Arbeitszeittabellen.

Beachten Sie, dass sich die Funktionalität dieser Einstellungen nicht geändert hat und nur die Informationssymbole hinzugefügt wurden, um den Umfang der Einstellungen zu verdeutlichen.

+++

+++**Wartungs-Update vom 26. Januar 2023**

**Fehler beim Senden einer Anfrage über [!DNL Outlook]**

_Integrationen_

Wenn jemand versucht, eine Anfrage mit Anhängen über eine [!DNL Outlook]-E-Mail-Adresse zu senden, werden ein oder mehrere Anhänge nicht hochgeladen und der folgende Fehler wird angezeigt.

„[!UICONTROL Der folgende Fehler ist aufgetreten: Datei mit Handle xxxx ist nicht vorhanden.]“

Dies tritt nur auf, wenn bei der neuen Anfrage entweder über die Anfrage-Warteschlange oder beim manuellen Erstellen der Anfrage ein Arbeitsauftrag erteilt wird.

**Neue Desktop Überprüfungs-Viewer-Version**

_Proofing_

Um ein Einfrieren im Desktop Überprüfungs-Viewer zu beheben, haben wir eine neue Version des Desktop Überprüfungs-Viewers bereitgestellt. Benutzende, die bereits den Desktop Überprüfungs-Viewer installiert haben, erhalten dieses Update automatisch.

Benutzende können die neueste Version auch manuell herunterladen. Weitere Informationen finden Sie unter [Installieren des Desktop Überprüfungs-Viewers](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=de).

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
* Einen Pin aus dem Menü [!UICONTROL Mehr] entfernen (dabei wird der letzte Pin in der oberen Navigationsleiste in das Menü [!UICONTROL Mehr] verschoben)

+++

+++**Wartungs-Update vom 18. Januar 2023**

**Ausdrücke mit Platzhaltern sind in benutzerdefinierten Feldern nicht gültig**

_Benutzerdefinierte Formulare_

Wenn jemand einen Platzhalter wie \$$TODAY oder $$NOW zusammen mit einem Modifikator (z. B. „-30d“) in einem benutzerdefinierten Feld verwendet, akzeptiert der Validator den Platzhalter nicht als gültig. Platzhalter ohne Modifikatoren werden als gültig betrachtet.

**[!UICONTROL Workload Balancer] zeigt Stunden an, die mit keinem Projekt/keiner Aufgabe/keinem Problem verknüpft sind**

_[!UICONTROL Workload Balancer]_

Wenn Benutzende den [!UICONTROL Lastenausgleich] betrachten, sehen sie Stunden, die für Benutzende protokolliert wurden und keinem Projekt, keiner Aufgabe sowie keinem Problem zugeordnet sind und auch nicht als [!UICONTROL allgemeine] Stunden eingetragen sind. Diese Stunden werden möglicherweise nur in der 4- oder 6-Wochen-Ansicht angezeigt.

+++

+++Wartungs-Update für **[!DNL Adobe Workfront Fusion] (Hotfix) vom 12. Januar 2023**

**404-Fehler bei [!DNL Workfront]-Modulen**

_Workfront Fusion_

Beim Ausführen eines Szenarios wird von einem [!DNL Workfront]-Modul ein 404-Fehler zurückgegeben.

Dies wurde in den folgenden Modulen gemeldet:

* [!UICONTROL Datensatz lesen]

+++

+++**Wartungs-Update (Hotfix) vom 12. Januar 2023**

**„[!UICONTROL Hoppla]“-Fehler beim Einrichten eines berechneten Felds**

_Benutzerdefinierte Formulare_

Wenn jemand ein berechnetes Feld in einem benutzerdefinierten Formular erstellt oder bearbeitet und ein benutzerdefiniertes Feld in den Ausdruck des berechneten Felds einbezieht, wird der Ausdruck als ungültig erachtet. Die Schaltfläche [!UICONTROL Speichern] ist deaktiviert, und es kann nicht vom benutzerdefinierten Feld wegnavigiert werden. Zusätzlich wird unter dem Feld folgende Meldung angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Wird das benutzerdefinierte Feld aus dem Ausdruck entfernt, kann das Feld gespeichert und von ihm wegnavigiert werden.

**Zugriffsebenen können nicht festgelegt werden**

_Benutzende_

Wenn eine Benutzerin bzw. ein Benutzer versucht, die Zugriffsebene einer anderen Person zu ändern, sind die Zugriffsebenen grau ausgeblendet und lassen sich nicht ändern. Dies ist selbst dann der Fall, wenn Systemadmins die Änderung versuchen.

+++

+++**Wartungs-Update vom 12. Januar 2023**

**Strg+F bzw. Befehl+F funktioniert in Dropdown-Feldern nicht wie erwartet**

_Benutzerdefinierte Formulare_

Wenn jemand ein benutzerdefiniertes Formular ausfüllt, dabei mithilfe von Strg+F bzw. Befehl+F eine Dropdown-Liste durchsucht und dann versucht, zur nächsten Instanz dieser Suche zu springen, kehrt die Dropdown-Liste zum Anfang der Liste zurück, anstatt zur nächsten Instanz der Suche zu springen. Dies tritt auf, wenn ein Dropdown-Menü so eingerichtet ist, dass mehrere Auswahlmöglichkeiten zulässig sind.

**[!UICONTROL Berichtbearbeitungsbildschirm] ist leer**

_Berichte_

Wenn jemand einen Bericht betrachtet und versucht, den Bericht zu bearbeiten, wird die Person auf einen leeren Bildschirm weitergeleitet und kann den Bericht nicht bearbeiten.

**Eingerückte Aufgaben bleiben nicht eingerückt**

_Aufgaben_

Wenn jemand eine Aufgabenliste anzeigt und eine Aufgabe einrückt, kehrt die Aufgabe sofort an die ursprüngliche (nicht eingerückte) Position zurück.

+++

+++**Wartungs-Update vom 5. Januar 2023**

**Pin-Funktionalität verfügbar im Menü [!UICONTROL Mehr]**

_Navigation_

Die folgenden Funktionen sind jetzt für Pins im Menü [!UICONTROL Mehr] verfügbar; nur in der Vorschau-Umgebung:

* Pins umbenennen
* Pins innerhalb des Menüs [!UICONTROL Mehr] neu anordnen
* Einen Pin aus dem Menü [!UICONTROL Mehr] entfernen (dabei wird der letzte Pin in der oberen Navigationsleiste in das Menü [!UICONTROL Mehr] verschoben)

**Die Einschränkung für Projektgruppen wurde entfernt, sodass Benutzende zum Projekt-Team hinzugefügt werden können**

_Teams_

Wir haben die Einschränkung entfernt, die verlangte, dass die einem Projekt-Team hinzuzufügenden Benutzenden in der mit dem Projekt verknüpften Gruppe sein mussten. Jetzt können Sie einem Projekt-Team beliebige aktive Benutzerinnen und Benutzer hinzufügen, unabhängig davon, zu welchen Gruppen diese gehören.

**Neue Informationssymbole für Arbeitszeittabellen, Arbeitszeittabellenprofile und Arbeitszeittabellen-Voreinstellungen**

>[!NOTE]
>
>Dieses Update wurde am 3. November 2022 in der Vorschau-Umgebung veröffentlicht und ist jetzt in der Produktionsumgebung verfügbar.

_Workfront_

Wir haben zu den folgenden Einstellungen mehrere Informationssymbole hinzugefügt:

* Wenn das Kontrollkästchen „Kann Zeit bearbeiten“ bei der Erstellung oder Bearbeitung einer Arbeitszeittabelle oder eines Arbeitszeittabellenprofils aktiviert wird, bedeutet dies, dass die genehmigenden Personen auch die Arbeitszeittabelle senden, erneut öffnen oder bearbeiten können, es sei denn, die Admins beschränken diese Aktionen im Bereich „Arbeitszeittabellen-Voreinstellungen“ im Setup.
* Wenn die Option „Bearbeitung von Arbeitszeittabellen auf Eigentümer und Admins beschränken“ im Bereich „Arbeitszeittabellen- und Stunden-Voreinstellungen“ von „Setup“ deaktiviert ist, können auch die folgenden Benutzenden die Arbeitszeittabellen bearbeiten: Benutzende mit administrativem Zugriff auf Arbeitszeittabellen und Stunden, genehmigende Personen für Arbeitszeittabellen, die die Zeit bearbeiten dürfen, und Führungskräfte der Eigentümerinnen und Eigentümer von Arbeitszeittabellen.

Beachten Sie, dass sich die Funktionalität dieser Einstellungen nicht geändert hat und nur die Informationssymbole hinzugefügt wurden, um den Umfang der Einstellungen zu verdeutlichen.

+++

## Frühere Wartungs-Updates

Informationen zu früheren Wartungs-Updates finden Sie hier:

* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2022](2022-updates.md)
* [Archiv mit Wartungs-Updates für [!DNL Workfront] – 2021](2021-updates.md)
