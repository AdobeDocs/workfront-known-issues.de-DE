---
title: "Neue Startseite: Die Standardwerte für Widget-Filter und Gruppierungen entsprechen nicht der Layoutvorlage."
description: Wenn ein Benutzer das Widget "Meine Projekte", "Meine Aufgaben"oder "Meine Probleme"im neuen Starterlebnis anzeigt, sind der Standardfilter und die Gruppierung für dieses Widget nicht die Standardeinstellung in der diesem Benutzer zugewiesenen Layoutvorlage.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 36%

---

# Neue [!UICONTROL Startseite]: Die Standardwerte für Widget-Filter und Gruppierungen entsprechen nicht der Layout-Vorlage

>[!NOTE]
>
>Dieser Problemfall wurde geschlossen, da die Funktion ordnungsgemäß funktioniert.

Wenn versucht wird, das Widget [!UICONTROL Meine Projekte], [!UICONTROL Meine Aufgaben] oder [!UICONTROL Meine Probleme] im neuen [!UICONTROL Startseiten-Erlebnis] anzuzeigen, sind die Standardfilter und die Standardgruppierung für dieses Widget nicht die Standardeinstellung in der dieser Benutzerin bzw. diesem Benutzer zugewiesenen Layout-Vorlage.

**Problemumgehung**:

Bei der Verwendung der neuen Startseite ist es wichtig, dass die Benutzereinstellungen (Voreinstellungen) priorisiert werden. Wenn Sie daher einen Standardfilter oder eine Gruppierung für ein bestimmtes Widget mithilfe einer Layoutvorlage festlegen, wird dieser möglicherweise aufgrund bestehender Benutzereinstellungen nicht sofort wirksam. Um den neuen Filter oder die neue Gruppierung anzuwenden, müssen Sie oder der Benutzer möglicherweise die Voreinstellungen zurücksetzen. Dies kann durch Anhängen von `/resetUser` zu Ihrer URL hinzufügen.

_Erste Meldung am 3. Januar 2024._
