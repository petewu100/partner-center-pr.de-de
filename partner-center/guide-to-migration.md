---
title: Migrieren von PMC zu Partner Center
ms.topic: article
ms.date: 10/02/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Erfahren Sie, wie Sie Ihr Unternehmen vom Partner Membership Center (PMC) zum Partner Center migrieren, einschließlich der erforderlichen Schritte.
author: parthpandyaMSFT
ms.author: parthp
ms.localizationpriority: high
ms.custom: SEOMAY.20
ms.openlocfilehash: 8b6646ff943ff219c41c975d60e66a46d1e0f595
ms.sourcegitcommit: 3c45a181ef86b3a4866e97fb50efeae8714ab3f7
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2020
ms.locfileid: "92175238"
---
# <a name="guide-to-migrating-from-pmc-to-partner-center"></a>Leitfaden zum Migrieren von PMC zu Partner Center

**Geeignete Rollen**

- Globaler Administrator

Die Microsoft-Partner-Website unter „partner.microsoft.com“ ist ein einheitliches digitales Verfahren für Partner. Über die Partner-Website können Sie Ihre Verkaufschancen untersuchen und sich mit Anleitungen befassen, die Ihrem Unternehmen bei der Erstellung und dem Vertrieb Ihrer Apps und Dienste mit Microsoft helfen. Über den Dashboard-Link, der auf der Partner-Website zur Verfügung steht, können sich Mitglieder des Microsoft Partner Networks bei dem Partner Center anmelden, in dem Sie Ihre Beziehung mit Microsoft verwalten sowie sich für Programme und Angebote registrieren.

Das Partner Membership Center (PMC) wird außer Betrieb gesetzt. Ihr Unternehmen wurde eingeladen, Ihre Microsoft Partner Network-Mitgliedschaftsverwaltung auf Partner Center umzustellen. In dieser Anleitung werden Sie darauf vorbereitet, was zu erwarten ist, wenn Sie den Wechsel von PMC zu Partner Center durchführen.

>[!NOTE]
>Auch wenn Ihr Unternehmen mehrere Konten oder Standorte hat, beginnt der Wechsel zu Partner Center mit dem Verschieben eines (Ihres ersten) Kontos in Partner Center.

## <a name="get-started"></a>Erste Schritte

Der Verschiebevorgang beginnt in PMC. Ihr globaler Administrator erhält eine Einladung, mit dem Verschieben zu beginnen.

### <a name="prepare-in-pmc"></a>Vorbereiten in PMC

- Überprüfen Ihrer Unternehmensdetails
- Überprüfen Ihres primären Programmkontakts
- Überprüfen Ihrer Unternehmensstandorte
- Aktualisieren Ihrer genehmigten Benutzer

### <a name="when-youre-ready"></a>Wenn Sie bereit sind

Wählen Sie in Ihrer Einladung **Erste Schritte** aus. Daraufhin wird die Partner Center-Anmeldeseite angezeigt.

:::image type="content" source="images/migration/getstarted.jpg" alt-text="Erste Schritte":::

## <a name="start-with-your-work-email"></a>Beginnen mit Ihrer geschäftlichen E-Mail-Adresse

Wenn Ihr Unternehmen keine geschäftliche E-Mail-Adresse und keinen AAD-Mandanten aufweist, können wir Ihnen während des Partner Center-Anmeldevorgangs helfen, eine Adresse und einen Mandanten einzurichten. Wenn Sie versuchen, sich mit einem E-Mail-Konto anzumelden, das keiner geschäftlichen E-Mail-Adresse entspricht (z. B. Ihrem persönlichen Konto), werden Sie aufgefordert, Informationen zu Ihrem Unternehmen anzugeben, damit wir einen AAD-Mandanten und eine geschäftliche E-Mail-Adresse einrichten können. Weil diese Unternehmensdetails zum Fertigstellen Ihres Kontos in Partner Center verwendet werden, sorgen Sie dafür, dass sie korrekt sind.

>[!NOTE]
>Wenn Sie ein Partner in China sind und sowohl im Microsoft Partner Network als auch im Cloud Solution Provider-Programm (CSP) registriert sind, haben Sie einen separaten Mandanten für jedes Konto. Ihr Konto mit dem Cloud Solution Provider-Programm wird in der nationalen Cloud verwaltet und Ihr Microsoft Partner Network-Konto in der globalen Cloud. Die beiden Konten können nicht verknüpft werden.

:::image type="content" source="images/migration/newtellusabout.png" alt-text="Erste Schritte":::

Nachdem Sie die Informationen überprüft oder aktualisiert haben, wählen Sie **Zustimmen und fortfahren** aus.
Die „Bestimmungen“ auf dieser Seite sind **identisch mit denjenigen** in der Vereinbarung, die Ihr Unternehmen bereits in PMC unterzeichnet hat.  
Durch diesen Schritt wird die Erstellung Ihres Azure AD-Mandanten eingeleitet, und Sie erhalten Ihr Geschäftskonto.

Wenn Sie **Zustimmen und fortfahren** auswählen, werden auch folgende Schritte ausgeführt:

- Ihr Konto wird zusammen mit ALLEN Standorten zum Partner Center migriert.

- Kompetenzen oder MAPs, die Sie u. U. im PMC erworben haben, werden migriert.

- Marketingressourcen, Angebote und Programme (MAPs, Silver, Gold) aus dem PMC werden migriert.

## <a name="invite-employees-to-join-you"></a>Einladen von Mitarbeitern, Ihnen beizutreten

Nachdem Ihr neuer Azure AD-Mandant erstellt wurde, können Sie Ihre Mitarbeiter einladen, sich bei Partner Center anzumelden.

:::image type="content" source="images/migration/invite.png" alt-text="Erste Schritte":::

Falls Sie sich bei einem vorhandenen AAD-Mandanten angemeldet haben, wurden Ihre Mitarbeiter zusammen mit Ihnen verschoben. Weisen Sie in diesem Fall Ihren Mitarbeitern Rollen zu, die festlegen, welche Berechtigungen sie in Partner Center haben. 

>[!NOTE] 
>Rollen in Partner Center unterscheiden sich von Rollen in PMC. Weitere Informationen finden Sie unter [Wechsel von PMC zu Partner Center](move-pmc-pc-map.md).

## <a name="verify-your-domain-and-become-a-global-admin"></a>Überprüfen Ihrer Domäne und ein globaler Administrator werden  

Sollte Ihr AAD-Mandant neu sein, wurde niemandem die Rolle „globaler Administrator“ zugewiesen. Wenn Sie der globale Administrator werden möchten, müssen Sie Ihren Domänenbesitz überprüfen. Möglicherweise müssen Sie dazu den Domänenadministrator um Hilfe bitten.

Während Sie bereits erworbene Angebote sofort nutzen können, können Sie neue Angebote erst dann erwerben, nachdem Sie den Schritt zum Zuweisen eines globalen Administrators abgeschlossen haben.

:::image type="content" source="images/migration/takecontrol.png" alt-text="Erste Schritte":::

Wenn Sie „Erste Schritte“ auswählen, wird folgender Bildschirm angezeigt:

:::image type="content" source="images/migration/verifytxt.png" alt-text="Erste Schritte":::

Ihre Domänenregistrierungsstelle wurde bereits automatisch ausgefüllt. Nur der Domänenbesitzer kann die DNS-Datei aktualisieren. Wenn Sie also die Textdatei kopieren und Ihrem DNS-Datensatz hinzufügen, können wir überprüfen, ob Sie der Besitzer sind. Es dauert ein paar Minuten, bis das Update erfolgt. Sie müssen sich bei Partner Center abmelden und dann wieder anmelden. Jetzt lautet Ihre Rolle „globaler Administrator“.

## <a name="get-acquainted-with-your-dashboard-and-partner-center"></a>Vertrautmachen mit Ihrem Dashboard und Partner Center

Sehen Sie sich die Einführung zum Dashboard an. Hier können Sie Ihre Mitgliedschaft verwalten, ein Geschäftsprofil für Empfehlungen hinzufügen, sich beim Cloud Solution Provider-Programm registrieren sowie für Ihr Unternehmen relevante Benachrichtigungen und Angebote jederzeit anzeigen, indem Sie **Dashboard** auswählen. Sie können auch Incentives verwalten, auf dem Marketplace kaufen, sich für Markteinführungsdienste registrieren und vieles mehr ausführen.  

:::image type="content" source="images/migration/fre.png" alt-text="Erste Schritte":::

## <a name="sign-the-microsoft-partner-agreement"></a>Unterzeichnen der Microsoft Partner-Vereinbarung

Wenn Sie ein indirekter Vertriebspartner sind, müssen Sie sich nach der Einrichtung Ihres Partner Center-Kontos immer noch offiziell beim Cloud Solution Provider-Programm registrieren. Zum Überprüfen Ihres Mitgliedschaftsstatus wechseln Sie zu Ihrem [Partner-Profil](https://partner.microsoft.com/pcv/accountsettings/partnerprofile), und bestätigen Sie den Kontotyp. Dann registrieren Sie sich in CSP als [indirekter Vertriebspartner](enrolling-in-the-csp-program.md).

 Nachdem Sie sich als indirekter Vertriebspartner registriert haben, nehmen Sie die [Anfrage für eine CSP-Beziehung mit Ihrem indirekten Anbieter](indirect-reseller-tasks-in-partner-center.md) an.

Anschließend stimmen Sie der Microsoft Partner-Vereinbarung in der [Dashboardübersicht](https://partner.microsoft.com/pvc/dashboard) im Partner Center mit den Anmeldeinformationen eines globalen Administrators zu. Vergewissern Sie sich im Abschnitt mit den Programminformationen im Partner-Profil, dass Sie die Microsoft Partner-Vereinbarung unterzeichnet haben. Außerdem wird auf der CSP-Übersichtsseite eine Bannerbenachrichtigung zur Bestätigung angezeigt. 

## <a name="next-steps"></a>Nächste Schritte

- [Finden des globalen Administrators](become-global-admin.md)

- [Microsoft-Partnervereinbarung](microsoft-partner-agreement.md)

- [Erstellen von Benutzerkonten](create-user-accounts-and-set-permissions.md)

- [Zuweisen von Benutzerrollen und Berechtigungen](permissions-overview.md)

- [Verwalten der Microsoft Partner Network-Mitgliedschaftsprogramme](renew-mpn-offers.md)

- [Erstellen Ihres Unternehmensprofils](create-a-marketing-profile.md)

- [Kontaktaufnahme mit Kunden durch Empfehlungen](manage-leads.md)

- [Leitfaden zum Migrieren mehrerer Unternehmen von PMC zu Partner Center](move-multiple-companies.md)
