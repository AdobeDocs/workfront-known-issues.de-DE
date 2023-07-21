---
title: '„Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern zum Bearbeiten von Feldern die Berechtigung ‚Verwalten‘ oder ‚Bearbeiten‘“'
description: Wenn ein/e Benutzende(r) ein objektübergreifendes Formular erstellt, in dem die Berechtigungen „Verwalten“ oder „Bearbeiten“ erforderlich sind, und diesen Objekttyp dann entfernt, erfordert das benutzerdefinierte Formular weiterhin die Berechtigung „Verwalten“ oder „Bearbeiten“, um die Felder zu bearbeiten. Es gibt keinen visuellen Hinweis darauf, dass die Felder die Berechtigung „Verwalten“ oder „Bearbeiten“ erfordern, und es gibt auch keine Möglichkeit, das Formular zurückzusetzen.
hidefromtoc: true
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 100%

---

# Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern zum Bearbeiten von Feldern die Berechtigung [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten]

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Dieses Problem wurde behoben

Wenn ein/e Benutzende(r) ein objektübergreifendes Formular erstellt, in dem die Berechtigungen [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten] erforderlich sind, und diesen Objekttyp dann entfernt, erfordert das benutzerdefinierte Formular weiterhin die Berechtigung [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten], um die Felder zu bearbeiten. Es gibt keinen visuellen Hinweis darauf, dass die Felder die Berechtigung „Verwalten“ oder „Bearbeiten“ erfordern, und es gibt auch keine Möglichkeit, das Formular zurückzusetzen.

**Problemumgehung**

1. Fügen Sie dem Formular einen Abschnittsumbruch mit Standardwerten hinzu, mit denen es ausgefüllt wird.
2. Verschieben Sie den Abschnittsumbruch an den Anfang des Formulars.
3. Speichern Sie das Formular.
4. Entfernen Sie den soeben hinzugefügten Abschnittsumbruch und speichern Sie das Formular erneut.

_Erste Meldung am 9. November 2022._
