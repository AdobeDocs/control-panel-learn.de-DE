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
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 100%

---

# Fehlerbehebung im [!UICONTROL Control Panel]

## Anmelden und Homepage

### Problem: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss seine IMS-Organisations-ID (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil „Campaign-xxx-Admins“ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Links auf der Experience Cloud-Startseite für den Zugriff auf das [!UICONTROL Control Panel] werden einem Benutzer nicht angezeigt.

**Ursache:**
Diese Links werden Benutzern erst dann angezeigt, nachdem sie dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt.

**Ursache:****
Der Benutzer muss wahrscheinlich für die fehlende Instanz dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt werden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/34928?learn=on&captions=ger){transcript=true}

*IMS-Organisations-ID prüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/34781?learn=on&captions=ger){transcript=true}

*Hinzufügen eines Administrators zum Produktprofil „Administratoren“ für die Verwendung des [!UICONTROL Control Panel] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panels](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [[!UICONTROL Verwalten von Berechtigungen für das ]Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Schlüsselpaar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie auch SFTP-Client-Software.

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
