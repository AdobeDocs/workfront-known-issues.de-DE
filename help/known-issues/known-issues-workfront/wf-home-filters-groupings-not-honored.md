---
title: 'Neue Startseite: Die Standardeinstellungen für Widget-Filter und Gruppierung entsprechen nicht der Layoutvorlage'
description: Wenn versucht wird, das Widget „Meine Projekte“, „Meine Aufgaben“ oder „Meine Probleme“ im neuen Startseiten-Erlebnis anzuzeigen, sind die Standardfilter und die Standardgruppierung für dieses Widget nicht die Standardeinstellung in der dieser Person zugewiesenen Layout-Vorlage.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 93%

---

# Neue [!UICONTROL Startseite]: Die Standardwerte für Widget-Filter und Gruppierungen entsprechen nicht der Layout-Vorlage

>[!NOTE]
>
>Dieser Problemfall wurde geschlossen, da die Funktion ordnungsgemäß funktioniert.

Wenn versucht wird, das Widget [!UICONTROL Meine Projekte], [!UICONTROL Meine Aufgaben] oder [!UICONTROL Meine Probleme] im neuen [!UICONTROL Startseiten-Erlebnis] anzuzeigen, sind die Standardfilter und die Standardgruppierung für dieses Widget nicht die Standardeinstellung in der dieser Benutzerin bzw. diesem Benutzer zugewiesenen Layout-Vorlage.

**Problemumgehung**:

Bei der Verwendung der neuen Startseite ist unbedingt zu beachten, dass die Benutzereinstellungen (Voreinstellungen) priorisiert werden. Wenn Sie daher mithilfe einer Layout-Vorlage einen Standardfilter oder eine Gruppierung für ein bestimmtes Widget festlegen, wird dieser bzw. diese möglicherweise aufgrund bestehender Benutzereinstellungen nicht sofort wirksam. Um den neuen Filter oder die neue Gruppierung anzuwenden, müssen Sie oder der Benutzer bzw. die Benutzerin möglicherweise die Voreinstellungen zurücksetzen. Zu diesem Zweck können Sie `/resetUser` an Ihre URL anhängen.

_Erste Meldung am 3. Januar 2024._
