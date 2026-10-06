---
title: Fehlerbehebung im Control Panel
description: Erfahren Sie, wie Sie Fehler im Control Panel beheben.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: 'https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: e4a8e51ee4016895090eb90d528d0a2707fd0225
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 92%
---
# Fehlerbehebung im [!UICONTROL Control Panel]

## Anmelden und Homepage

### Problem: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Die Benutzerin bzw. der Benutzer muss die eigene IMS-Org-ID (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil „Campaign-xxx-Admins“ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Links auf der Experience Cloud-Startseite für den Zugriff auf das [!UICONTROL Control Panel] werden einem Benutzer nicht angezeigt.

**Ursache:**
Diese Links werden Benutzenden erst angezeigt, nachdem sie dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzende hinzugefügt wurden.

**Vorgehensweise:**
Die bzw. der Admin muss die Benutzerin bzw. den Benutzer für jede Instanz, die verwaltet werden soll, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt.

**Ursache:**
Die Benutzerin bzw. der Benutzer muss wahrscheinlich für die fehlende Instanz dem Produktprofil _Campaign-xxx-Administrators/Admin_ als *Benutzer* hinzugefügt werden.

**Vorgehensweise:**
Die bzw. der Admin muss die Benutzerin bzw. den Benutzer für jede Instanz, die verwaltet werden soll, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/34928?captions=ger&learn=on){transcript=true}

*IMS-Organisations-ID überprüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/34781?captions=ger&learn=on){transcript=true}

*Hinzufügen eines Administrators zum Produktprofil-Administratoren zur Verwendung von [!UICONTROL Systemsteuerung] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [Verwalten von Berechtigungen für das [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Schlüsselpaar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie auch SFTP-Client-Software.

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
