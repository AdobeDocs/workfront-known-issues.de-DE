---
title: 'Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern zum Bearbeiten von Feldern die Berechtigung Verwalten oder Bearbeiten .'
description: Wenn ein/e Benutzende(r) ein objektübergreifendes Formular erstellt, in dem die Berechtigungen „Verwalten“ oder „Bearbeiten“ erforderlich sind, und diesen Objekttyp dann entfernt, erfordert das benutzerdefinierte Formular weiterhin die Berechtigung „Verwalten“ oder „Bearbeiten“, um die Felder zu bearbeiten. Es gibt keinen visuellen Hinweis darauf, dass die Felder die Berechtigung „Verwalten“ oder „Bearbeiten“ erfordern, und es gibt auch keine Möglichkeit, das Formular zurückzusetzen.
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%
---
# Benutzerdefinierte Formulare: Benutzerdefinierte, objektübergreifende Formulare erfordern zum Bearbeiten von Feldern die Berechtigung [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten]

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Dieses Problem wurde behoben

Wenn ein/e Benutzende(r) ein objektübergreifendes Formular erstellt, in dem die Berechtigungen [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten] erforderlich sind, und diesen Objekttyp dann entfernt, erfordert das benutzerdefinierte Formular weiterhin die Berechtigung [!UICONTROL Verwalten] oder [!UICONTROL Bearbeiten], um die Felder zu bearbeiten. Es gibt keinen visuellen Hinweis darauf, dass die Felder die Berechtigung „Verwalten“ oder „Bearbeiten“ erfordern, und es gibt auch keine Möglichkeit, das Formular zurückzusetzen.

**Umgehungslösung**

1. Fügen Sie dem Formular einen Abschnittsumbruch mit Standardwerten hinzu, mit denen es ausgefüllt wird.
2. Verschieben Sie den Abschnittsumbruch an den Anfang des Formulars.
3. Speichern Sie das Formular.
4. Entfernen Sie den soeben hinzugefügten Abschnittsumbruch und speichern Sie das Formular erneut.

_Erste Meldung am Donnerstag, 9. November 2022._
