---
title: "Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern Zugriff auf Verwalten oder Bearbeiten, um Felder zu bearbeiten."
description: '"Wenn ein Benutzer ein Formular mit mehreren Objekten erstellt, die nur den Zugriff auf "Verwalten"oder "Bearbeiten"erlauben, und diesen Objekttyp dann entfernt, erfordert das benutzerdefinierte Formular weiterhin Zugriff auf "Verwalten"oder "Bearbeiten", um die Felder zu bearbeiten. Es gibt keinen visuellen Hinweis darauf, dass die Felder Zugriff auf Verwalten oder Bearbeiten erfordern, und es gibt keine Möglichkeit, das Formular zurückzusetzen."'
hidefromtoc: true
source-git-commit: be498327ea7bb2a49be0fc65e53806ddb217aa8c
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 2%

---


# Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten] Zugriff auf Bearbeitungsfelder

>[!NOTE]
>
>Dieses Problem wurde behoben

Wenn ein Benutzer ein Formular mit Kreuzobjekten erstellt, die nur [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten] auf diesen Objekttyp zugreifen und ihn dann entfernen, erfordert das benutzerdefinierte Formular weiterhin [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten] Zugriff zur Bearbeitung der Felder. Es gibt keinen visuellen Hinweis darauf, dass die Felder Zugriff auf Verwalten oder Bearbeiten erfordern, und es gibt keine Möglichkeit, das Formular zurückzusetzen.

**Problemumgehung**

1. Fügen Sie dem Formular einen Abschnittsumbruch mit Standardwerten hinzu, wenn diese ausgefüllt sind.
2. Verschieben Sie den Abschnittsumbruch an den Anfang des Formulars.
3. Speichern Sie das Formular.
4. Entfernen Sie die soeben hinzugefügte Abschnittspause und speichern Sie das Formular erneut.

_Erste Meldung am 9. November 2022._

