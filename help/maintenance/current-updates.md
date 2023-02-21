---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: e98fb79ece32db7e590078660a4fcf560b8e6be8
workflow-type: tm+mt
source-wordcount: '1693'
ht-degree: 70%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2023 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [früheren Wartungs-Updates](#previous-maintenance-updates)

## Updates im Februar 2023

+++**(Geplant) Aktualisierung der Wartung am 23. Februar 2023**

**Link zu einem Kommentar, der zu [!UICONTROL Details] page**

_Updates_

Wenn ein Benutzer einer Verknüpfung zu einem Kommentar zu einem Objekt in Workfront folgt, wird der Aktualisierungsstream kurz geladen und der Benutzer wird dann zum Objekt [!UICONTROL Details] Bereich. Dies kann vorkommen, wenn der Benutzer in einer E-Mail auf den Link klickt oder den Link in den Browser einfügt.

Dies betrifft derzeit nur Dokumentobjekte.

**Benutzer können ihre eigenen Benachrichtigungseinstellungen nicht bearbeiten**

_Benutzende_

Wenn ein Benutzer mit [!UICONTROL Worker] -Lizenz versucht, ihre eigenen Benachrichtigungseinstellungen zu bearbeiten, die [!UICONTROL Benachrichtigungen] -Optionen in der [!UICONTROL Bearbeiten] und der Benutzer die Einstellungen nicht bearbeiten kann.

+++

+++**Wartungs-Update vom 16. Februar 2023**

**Mehrere Teamzuweisungen auf Pinnwänden**

_Pinnwände_

Sie können jetzt mehrere Teams einer Aufgabe oder einem Problem in einer Pinnwand und der Pinnwand selbst zuweisen.

**Erhöhung der Kartenabsturzgrenze**

_Pinnwände_

Die Falloff-Zeitlimits für die Karte wurden auf 8 Wochen/60 Tage statt auf 4 Wochen/30 Tage erhöht.

**Die geplante Deaktivierung deaktiviert den Benutzer nicht**

_Benutzende_

Wenn die Deaktivierung von Benutzenden geplant ist und das geplante Datum und die geplante Uhrzeit vergehen, werden Benutzende nicht deaktiviert.

+++

+++**Wartungs-Update vom 9. Februar 2023**

**[!UICONTROL Story Points] Feld zu Aufgaben- und Problemlisten und Berichten hinzugefügt**

_Berichte_

Die [!UICONTROL Story Points] ist jetzt verfügbar, um Listen und Berichten für Aufgaben oder Probleme hinzuzufügen. Es handelt sich dabei um ein editierbares, freies Formularfeld, das nicht an geplante Stunden oder Teamzuweisungen gebunden ist.

+++

+++**Wartungs-Update vom 8. Februar 2023**

**Filterschaltfläche in Ansauspalte**

_Pinnwände_

Die Aufnahmespalte auf einer Pinnwand enthält jetzt eine **[!UICONTROL Filter hinzufügen]** -Schaltfläche, wenn die Spalte leer ist und keine Filter erstellt wurden. Die Schaltfläche öffnet den Konfigurationsbereich, in dem Sie Filter hinzufügen können, um Aufgaben und Probleme in die Aufnahmespalte zu übernehmen.

+++

+++**Wartungs-Update vom 2. Februar 2023**

**[!UICONTROL Pinnwände] wird angezeigt in [!UICONTROL Hauptmenü] standardmäßig**

_Pinnwände_

Die [!UICONTROL Pinnwände] wird nun im [!UICONTROL Hauptmenü] für Benutzer ohne Layoutvorlage. Pinnwände sind standardmäßig auch im Hauptmenü für alle neuen Layoutvorlagen enthalten, die erstellt werden. Bestehende Layoutvorlagen wurden nicht geändert.

**E-Mail-Vorlagen können nicht gespeichert werden**

_Setup_

Wenn Benutzende versuchen, eine E-Mail-Vorlage zu erstellen oder zu bearbeiten, reagiert die Schaltfläche [!UICONTROL Speichern] nicht, und sie können die Vorlage nicht speichern.

+++

## Aktualisierungen im Januar 2023

+++**Wartungs-Update vom 30. Januar 2023**

**Tastaturbefehle für gängige Zeitblatt-Aktionen hinzugefügt**

_Arbeitszeittabellen_

Wir haben die folgenden Tastaturbefehle für die folgenden häufig durchgeführten Aktionen in einem Timesheet eingeführt:

* Zeile hinzufügen (Befehl+Option++/Strg+Option+++)
* Löschen Sie die Zeile (Befehl+Option+-/Strg+Option+-)
* Ein Arbeitselement fixieren oder aufheben (Option+P/Option+P)
* Kommentar öffnen (Umschalt+F2/Umschalt+F2)
* Kommentar speichern (Befehl+Eingabetaste/Strg+Eingabetaste)
* Erweitern (Umschalt+Option+Nach-oben-Taste/Umschalt+Alt+Nach-oben-Taste)
* Reduzieren (Umschalt+Option+Abwärtspfeil/Umschalt+Alt+Abwärtspfeil)

Der Bereich, in dem diese Aktionen ausgeführt werden, muss hervorgehoben werden, damit sie angewendet werden können.

**Neue Informationssymbole für Arbeitszeittabellen, Arbeitszeittabellenprofile und Arbeitszeittabellen-Voreinstellungen**

_Arbeitszeittabellen_

>[!NOTE]
>
>Dieses Update wurde nur am 3. November 2022 in der Vorschau-Umgebung veröffentlicht und ist jetzt in der Produktion verfügbar.

Wir haben zu den folgenden Einstellungen mehrere Informationssymbole hinzugefügt:

* &quot;[!UICONTROL Kann die Zeit bearbeiten]&quot;bei der Erstellung oder Bearbeitung eines Timesheets oder eines Timesheet-Profils das Kontrollkästchen aktivieren, um anzugeben, dass Genehmiger bei Aktivierung auch das Timesheet senden, erneut öffnen oder bearbeiten können, es sei denn, Ihr Administrator beschränkt diese Aktionen im [!UICONTROL Voreinstellungen für das Datenblatt] Gebiet von [!UICONTROL Einrichtung].
* &quot;[!UICONTROL Beschränken der Bearbeitung von Zeitblättern auf Eigentümer und Administratoren]&quot; in der [!UICONTROL Zeitblatt- und Stundeneinstellungen] Gebiet von [!UICONTROL Einrichtung] um anzugeben, dass die folgenden Benutzer bei Deaktivierung auch die Timesheets bearbeiten können: Benutzer mit administrativem Zugriff auf Timesheets und Stunden, Timesheet-Genehmiger zur Bearbeitung der Zeit und Timesheet-Manager.

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

**Die Einschränkung für Projektgruppen wurde entfernt, sodass Benutzende zum Projektteam hinzugefügt werden können.**

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

* [Archiv mit Wartungs-Updates für [!DNL Workfront]– 2022](2022-updates.md)
* [Archiv mit Wartungs-Updates für [!DNL Workfront]– 2021](2021-updates.md)
