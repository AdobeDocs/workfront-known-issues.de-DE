---
title: Wartungs-Updates für Workfront
description: Wartungs-Updates für [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: efa58e381aba8aaba59f0c19362f3da0cc81154f
workflow-type: tm+mt
source-wordcount: '951'
ht-degree: 75%

---

# Wartungs-Updates für [!DNL Workfront]

Die folgenden Wartungs-Updates wurden 2023 vorgenommen.

>[!NOTE]
>
>Diese Updates beinhalten auch kleinere oder weniger wichtige Fehlerbehebungen. Der [!DNL Workfront]-Support benachrichtigt Sie, wenn ein von Ihnen gesendetes Problem behoben wurde.

Informationen zu Wartungs-Updates, die vor 2023 durchgeführt wurden, finden Sie unter [früheren Wartungs-Updates](#previous-maintenance-updates)

## Updates im Januar 2023

+++**(Geplantes) Wartungs-Update vom 26. Januar 2023**

**Fehler beim Senden der Anforderung von[!DNL Outlook]**

_Integrationen_

Wenn ein(e) Benutzende(r) versucht, eine Anfrage mit Anhängen über eine [!DNL Outlook]-E-Mail-Adresse zu senden, werden ein oder mehrere Anhänge nicht hochgeladen und der folgende Fehler wird angezeigt.

„[!UICONTROL Der folgende Fehler ist aufgetreten: Datei mit Handle xxxx ist nicht vorhanden.]“

Dies tritt nur auf, wenn bei der neuen Anfrage entweder über die Anfrage-Warteschlange oder beim manuellen Erstellen der Anfrage ein Arbeitsauftrag erteilt wird.

+++

+++**Wartungs-Update vom 19. Januar 2023**

**Spaltenfilter für Aufnahme können jetzt freigegeben werden.**

_Pinnwände_

Wenn die Aufnahmespaltenfunktion in Pinnwänden veröffentlicht wurde, konnten die Filter zur Einrichtung der Ansauspalte nur von der Person gesehen werden, die diese Filter erstellt hat. Jetzt kann der Ersteller die Filter für andere Benutzer oder Teams freigeben.

**PIN-Funktion verfügbar im Menü [!UICONTROL Mehr]**

_Navigation_

Die folgenden Funktionen sind jetzt im [!UICONTROL Mehr] Menü für Pins in der Produktionsumgebung:

* Pins umbenennen
* Pins innerhalb des Menüs [!UICONTROL Mehr] neu anordnen
* Pin aus dem Menü [!UICONTROL Mehr] entfernen (dabei wird der letzte Pin in der oberen Navigationsleiste in das Menü [!UICONTROL Mehr] verschoben)

+++

+++**Wartungs-Update vom 18. Januar 2023**

**Ausdrücke mit Platzhaltern sind in benutzerdefinierten Feldern nicht gültig**

_Benutzerdefinierte Formulare_

Wenn ein Benutzer einen Platzhalter wie \$$TODAY oder $$NOW zusammen mit einem Modifikator (z. B. &quot;-30d&quot;) in einem benutzerdefinierten Feld verwendet, akzeptiert der Validator den Platzhalter nicht als gültig. Platzhalter ohne Modifikatoren werden als gültig betrachtet.

**[!UICONTROL Lastenausgleich] zeigt Stunden an, die nicht mit einem Projekt/einer Aufgabe/einem Problem verknüpft sind**

_[!UICONTROL Workload-Balancer]_

Wenn ein Benutzer die [!UICONTROL Lastenausgleich], sehen sie Stunden, die für einen Benutzer protokolliert wurden, der keinem Projekt, keiner Aufgabe oder einem Problem zugeordnet ist, und werden auch nicht als [!UICONTROL Allgemein] Stunden. Diese Stunden werden möglicherweise nur in der Ansicht 4 Wochen oder 6 Wochen angezeigt.

+++

+++**[!DNL Adobe Workfront Fusion]Wartungs-Update (Hotfix) am 12. Januar 2023**

**404-Fehler bei [!DNL Workfront]-Modulen**

_Workfront Fusion_

Beim Ausführen eines Szenarios, wird von einem [!DNL Workfront]-Modul ein 404-Fehler zurückgegeben.

Dies wurde in den folgenden Modulen gemeldet:

* [!UICONTROL Datensatz lesen]

+++

+++**Wartungs-Update (Hotfix) am 12. Januar 2023**

**&quot;[!UICONTROL Hopfen]&quot;-Fehler beim Einrichten eines berechneten Felds**

_Benutzerdefinierte Formulare_

Wenn ein(e) Benutzende(r) ein berechnetes Feld in einem benutzerdefinierten Formular erstellt oder bearbeitet und ein benutzerdefiniertes Feld in den Ausdruck des berechneten Felds einbezieht, wird der Ausdruck als ungültig erachtet. Die Schaltfläche [!UICONTROL Speichern] ist deaktiviert und der Benutzer kann das benutzerdefinierte Feld nicht verlassen. Zusätzlich wird unter dem Feld folgende angezeigt:

„[!UICONTROL Hoppla! Etwas ist schiefgelaufen. Bitte kontaktieren Sie Workfront, damit wir die Fehlerursache feststellen und den Fehler beheben können.]“

Wenn Sie das benutzerdefinierte Feld aus dem Ausdruck entfernen, können Sie das Feld speichern und verlassen.

**Zugriffsebenen können nicht festgelegt werden**

_Benutzer_

Wenn ein Benutzer versucht, die Zugriffsebene eines anderen Benutzers zu ändern, sind die Zugriffsebenen grau ausgeblendet und der Benutzer kann sie nicht ändern. Dies tritt auch dann auf, wenn der Benutzer, der die Änderung durchführt, ein Systemadministrator ist.

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
