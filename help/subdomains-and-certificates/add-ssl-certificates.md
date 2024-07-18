---
title: Hinzufügen von SSL-Zertifikaten
description: Erfahren Sie, wie Sie SSL-Zertifikate hinzufügen, um Ihre Subdomains zu schützen.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 100%

---

# Hinzufügen von SSL-Zertifikaten

Mit dem Adobe Campaign [!UICONTROL Control Panel] können Sie SSL-Zertifikate hinzufügen, um Ihre Subdomains zu schützen.

## Zugriff auf die Verwaltung von Subdomains im Control Panel

Um auf die Verwaltung von Subdomains im Control Panel zuzugreifen, navigieren Sie zu:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Lösungsauswahl: **[!DNL Campaign]** > **[!UICONTROL Control Panel]**-Karte > **[!UICONTROL Subdomains und Zertifikate]**-Karte

  oder
* Direkt über die URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Schritte zum Hinzufügen von SSL-Zertifikaten

Das Hinzufügen von SSL-Zertifikaten erfordert drei Schritte:

### 1. Certificate Signing Requests erzeugen

Für den Erwerb eines SSL-Zertifikats ist eine Certificate Signing Request (CSR) erforderlich. Sie muss für die Instanz und die Subdomains, die Sie schützen möchten, generiert werden.

Im folgenden Video erfahren Sie, wie Sie eine Certificate Signing Request im Control Panel generieren.

>[!VIDEO](https://video.tv.adobe.com/v/31317?learn=on){transcript=true}

*Certificate Signing Requests generieren (02:36 Min.)*

>[!NOTE]
>
>An der CSR-Generierung wurden verschiedene Verbesserungen vorgenommen:
>
>* Beim Generieren einer CSR können Sie jetzt eine der eingeschlossenen Subdomains als Gebrauchsnamen auswählen.
>* Sie können jetzt die CSR-Zusammenfassung kopieren, bevor Sie die CSR generieren.
>* Nachdem eine CSR generiert wurde, können Sie sie erneut aus den Vorgangslogs herunterladen. Diese Funktion gilt nicht für Zertifikate, die vor dieser Version generiert wurden.
>
>![CSR herunterladen](/help/assets/download-csr.gif)
>
>Weitere Informationen erhalten Sie in der [Produktdokumentation](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=de).
>

### 2- SSL-Zertifikat kaufen

Kaufen Sie nach dem Erhalt der CSR das SSL-Zertifikat von einer Zertifizierungsstelle, die von Ihrem Unternehmen validiert wurde.

### 3- SSL-Zertifikate installieren

Nachdem Sie das SSL-Zertifikat erhalten haben, muss es für die Subdomains, die Sie schützen möchten, installiert werden.

Im folgenden Video erfahren Sie, wie SSL-Zertifikate im [!UICONTROL Control Panel]installiert werden.

>[!VIDEO](https://video.tv.adobe.com/v/31166?learn=on){transcript=true}

*SSL-Zertifikate installieren (01:25 Min.)*


