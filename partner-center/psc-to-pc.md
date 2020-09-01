---
title: Verweise auf 101 für Partner, die von Partner Sales Connect (PSC) zu Partner Center (PC) migrieren
ms.topic: article
ms.date: 08/27/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Als qualifizierter Microsoft-Partner können Sie Co-Selling mit Microsoft durcharbeiten. Erfahren Sie, wie Sie Deals definieren, Microsoft zur Zusammenarbeit einladen oder gesendete Geschäfte anzeigen.
author: vikramb
ms.author: vikramb
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 4bf873bbd5e12372d73d2ed1b4c3307c71fda359
ms.sourcegitcommit: a2bfdc2ca5fe11afa5e2fb71e1b0fd61180f2d70
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2020
ms.locfileid: "89056187"
---
# <a name="referrals-guide-for-managing-your-deals-in-partner-center-instead-of-partner-sales-connect-psc"></a>Leitfaden für die Verwaltung ihrer Geschäfte im Partner Center anstelle von Partner Sales Connect (PSC)

**Zielgruppe**

- Empfehlungen
- Co-Selling mit Microsoft
- Einrichten des PSC-Benutzerkontos
- Partner Sales Connect-Benutzer (PSC) 

**Geeignete Rollen**

- Kontoadministrator
- Empfehlungsadministrator
- Partner Sales Connect-Verkäufer (PSC)
- Partner Sales Connect-Administrator (PSC)
- Partner Sales Connect (PSC)-Deal-Manager

Wie Sie wissen, verliert Ihr Unternehmen den Zugriff auf den PSC-Beitrag am 31. Dezember 2020. Hier finden Sie alles, was Sie tun möchten, um Ihre Geschäfte zu verwalten und die von Microsoft-Verkäufern an Sie gesendeten Angebote im Partner Center zu agieren. Es gibt jedoch Unterschiede, und die folgende Anleitung hilft Ihnen, den Übergang zu Partner Center zu vereinfachen und zu vereinfachen.

## <a name="before-you-move-things-you-need-to-know"></a>Bevor Sie fortfahren, müssen Sie wissen, was Sie wissen müssen.

### <a name="if-you-are-psc-admin"></a>Wenn Sie PSC-Administrator sind

- Sie benötigen eine geschäftliche e-Mail-Adresse für die Anmeldung bei [Partner Center](https://partner.microsoft.com/).
- Richten Sie Ihr Konto mit der Hilfe des Partner Center- [Konto Administrators](https://docs.microsoft.com/partner-center/permissions-overview#manage-mpn-membership-and-your-company-non-aad-roles-these-roles-manage-the-company-business-rather-than-the-tenant)ein.
- Lesen Sie dieses Dokument, um zu erfahren, wie Sie im Partner Center mitverkaufen.
- Richten Sie Ihren PSC-Deal-Manager und die Verkäufer Konten im Partner Center ein, und weisen Sie Ihnen die [Verweis Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals) Rolle zu.

### <a name="if-you-are-psc-deal-manager-or-seller"></a>Wenn Sie PSC-Deal-Manager oder Verkäufer sind

- Sie benötigen eine geschäftliche e-Mail-Adresse für die Anmeldung bei [Partner Center](https://partner.microsoft.com/).
- Wenn Sie ein nicht Geschäftskonto in PSC oder eine andere Domäne als die andere in PSC verwenden, wenden Sie sich für die Einrichtung des Kontos an Ihren PSC-Administrator.
- Wenden Sie sich an Ihren PSC-Administrator, wenn das Einrichten Ihres Partner Center-Kontos unabhängig von dem Konto, mit dem Sie sich beim PSC anmelden, fertiggestellt ist.
- Überprüfen Sie, ob Sie Zugriff auf Partner Center und den Abschnitt "Verweise" haben.
- Lesen Sie dieses Dokument, um sich mit den Workflows und den Änderungen in Partner Center vertraut zu machen.

## <a name="as-an-admin-in-psc-these-are-your-next-steps"></a>Als Administrator in PSC sind dies die nächsten Schritte.

Wenn die Registerkarte Verweise nicht angezeigt wird:

- Der [Konto Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-mpn-membership-and-your-company-non-aad-roles-these-roles-manage-the-company-business-rather-than-the-tenant) Ihres Unternehmens kann Ihnen Zugriff auf die Registerkarte "Verweise" gewähren. Um Ihren Konto Administrator zu finden, wechseln Sie über das Zahnrad Symbol in der oberen rechten Ecke des Partner Centers zu den Partner Einstellungen. Wählen Sie die Seite Benutzerverwaltung auf der zweiten Ebene der linken Navigationsleiste aus. Klicken Sie oben rechts auf der Seite auf die Dropdown-Ansicht mit "alle Benutzer", und wechseln Sie zu "Konto Administratoren". Auf der Seite werden dann alle Konto Administratoren mit ihren jeweiligen e-Mail-IDs angezeigt. Wenden Sie sich an die IT-Abteilung, um den Zugriff auf Ihr Geschäftskonto zu erhalten.

 :::image type="content" source="images/pscmigration/accountadmin.png" alt-text="Das Bild zeigt die Konto Administratoren auf der Seite Einstellungen für die Benutzerverwaltung an.":::

- Wechseln Sie im linken Navigationsbereich zur Registerkarte Verweise, und überprüfen Sie, ob Sie auf die Seiten zugreifen können.

Nachdem Sie Ihr Konto in Partner Center eingerichtet haben,

- Laden Sie alle Benutzer, die die Rolle "Deal Manager" oder "Verkäufer" im PSC zu Partner Center haben, als nächsten Schritt ein.
- Der [Konto Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-mpn-membership-and-your-company-non-aad-roles-these-roles-manage-the-company-business-rather-than-the-tenant) , der Ihnen beim Zugriff auf Verweise geholfen hat, kann alle Benutzer einladen.
- Bitten Sie den Konto Administrator beim einladen der Benutzer, ihm die [verweisadministrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals) -Rolle zuzuweisen.
- Einige ihrer PSC-Benutzer verwenden möglicherweise ein nicht-Geschäftskonto oder ein Konto aus einer Domäne, die sich von der Domäne unterscheidet, die Sie im Partner Center verwenden. Alle Benutzer müssen sich mit Ihrem Geschäftskonto, das an Ihren Azure AD Mandanten angefügt ist, bei Partner Center anmelden. Der [globale Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-commercial-transactions-in-partner-center-azure-ad-and-csp-roles) kann dabei helfen. Um ihren globalen Administrator zu finden, wechseln Sie über das Zahnrad Symbol in der oberen rechten Ecke des Partner Centers zu den Partner Einstellungen. Klicken Sie auf der zweiten Ebene der linken Navigationsleiste auf die Seite Benutzerverwaltung. Klicken Sie oben rechts auf der Seite auf die Dropdown-Ansicht mit "alle Benutzer", und wechseln Sie zu "globale Administratoren".
- Der globale Administrator kann entweder ein neues Benutzerkonto in Ihrem Azure AD-Mandanten erstellen oder den Benutzern Zugriff auf Gastbenutzer zuweisen.
- Nachdem die Konten für alle PSC-Deal-Manager und Benutzer eingerichtet sind, müssen Sie sich bei Partner Center anmelden, auf der Registerkarte "Referenzen" im linken Navigationsbereich auf "überprüfen" klicken und sicherstellen, dass die Seite "Verweise" angezeigt wird.

Wenn Ihr Unternehmen über ein PDM verfügt: Wenn Ihr Partner Center-Konto eingerichtet ist und Ihre Benutzer überrollen und Berechtigungen verfügen, können Sie Ihre Co-Selling-Aktivitäten in Partner Center verschieben. Informieren Sie das PDM, um den Switch zu erstellen, mit dem all Ihre neuen Geschäfte in Partner Center übertragen werden können.
>[!Note]
>Nachdem Sie diesen Switch vorgenommen haben, können Sie nur auf die vorhandenen aktiven Vorgänge in PSC reagieren. Sie können weder neue Angebote erstellen noch Angebote von Microsoft-Verkäufern im PSC erhalten.

Wenn Ihr Unternehmen nicht über ein PDM verfügt, stellen Sie sicher, dass alle Benutzerkonten von allen Benutzern eingerichtet und überprüft werden. Sie werden über eine e-Mail und ein Banner im PSC benachrichtigt, wenn Sie mit dem Co-Selling im Partner Center beginnen können. Denken Sie daran, dass Sie weiterhin die vorhandenen aktiven Geschäfte in PSC verwalten müssen.

>[!Important]
>Aktive Geschäfte werden nicht auf den PC migriert. Bis zum 31. Dezember 2020 können Sie die Geschäfte schließen und registrieren.

## <a name="next-steps-for-psc-admins-psc-deal-managers-and-psc-sellers"></a>Nächste Schritte für PSC-Administratoren, PSC-Deal-Manager und PSC-Verkäufer

Erfahren Sie, wie Sie im Partner Center mitverkaufen.
Dies ist ein wichtiger Schritt, der Ihnen bei der Vorbereitung auf Co-Selling im Partner Center behilflich ist. Machen Sie sich mit den Workflows und den Änderungen im Partner Center vertraut, damit Sie den gemeinsamen Co-Selling von Tag a durcharbeiten können. Beginnen Sie, indem Sie dieses Dokument vollständig lesen. Ein guter Satz an Ressourcen ist auch im [Co-Selling Gallery](https://aka.ms/cosellexperience)-Katalog verfügbar.

## <a name="major-differences-between-psc-and-pc-workflows"></a>Wichtige Unterschiede zwischen PSC-und PC-Workflows

|**Szenario**|**Partner Sales Connect**|**Partner Center**|
|-----|:-----|:-----|
|Benutzerrollen|PSC verfügt über die Rollen admin, Deal Manager und Verkäufer.|Der PC verfügt nur über die Rolle " [Verweis Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals) ", die Lese-und Schreibberechtigungen für alle Geschäfte erteilt.|
|Co-Selling-Anforderung|Vom Microsoft-Verkäufer initiiert, gibt es keine explizite Frage nach Partner.|Der Partner muss eine [explizite Anfrage](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#add-solutions) stellen, wenn eine Microsoft-Verkäufer Hilfe benötigt wird. Der Microsoft-Verkäufer hat die Möglichkeit, die Anforderung abzulehnen.|
|Expiry|Es gibt kein Konzept für eine Ablaufzeit.|Eingehende Partner Verträge laufen in 14 Tagen ab, wenn Sie vom Partner nicht akzeptiert werden. Dasselbe gilt für ausgehende Partnerangebote, bei denen Sie in den abgelaufenen Status wechseln können, wenn der Microsoft-Verkäufer nicht innerhalb von 14 Tagen darauf reagiert.|
|Details des Microsoft-Verkäufers|Sichtbar, sobald ein Problem erstellt wird.|Details des Microsoft-Verkäufers werden nur dann für Partner freigegeben, wenn der Verkäufer die Einladung zum Co-Selling von Partner explizit akzeptiert.|
|[Private Pipeline](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#types-of-co-sell-opportunities)|Nicht verfügbar.|Partner können ihre Pipeline freigeben, ohne den Microsoft-Verkäufern Einblick zu geben.|
|Lösungen|Es können nur Lösungen hinzugefügt werden, die zu einer Preisliste gehören.|Partner können [Lösungen](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#add-solutions) hinzufügen, die den folgenden Listen angehören. a) ihre eigenen Lösungen b) Lösungen von Microsoft First Party Catalog (Deal role: Transaction in PSC) und c) Co-Selling Solutions von anderen Drittanbieter Partnern (Rolle: ISV in PSC).|
|Zuweisungs Zuweisung|Nur der zugewiesene Verkäufer kann die Geschäfte anzeigen und darauf reagieren.|Team Mitglieder können einem Teil hinzugefügt werden, um die Mitarbeiter anzugeben, die an einem Teil arbeiten. es gibt keine Blockierung anderer verweisadministratoren, die diese Aktionen nicht anzeigen oder darauf reagieren.|
|Kundenorganisation|Freier Formular Text Eintrag.|Sie können die [Kundenorganisation](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#select-your-customer) anhand der [D-&B-Datenbank](https://www.dnb.com/) durchsuchen, indem Sie nur einige Zeichen eingeben. Der rechtliche Name und die Adresse werden automatisch basierend auf der Wahl aufgefüllt.|
|Kundenkontakt|Nicht obligatorisch.|Für die private Pipeline Freigabe nicht obligatorisch. Erforderlich, wenn der Microsoft-Verkäufer eingeladen wird, an einer Co-Selling-Anforderung teilzunehmen.|
|Öffentliche API|Nicht verfügbar.|[Öffentliche API](https://docs.microsoft.com/partner/develop/referrals) zum programmgesteuerten Verwalten von Partner Center-verweisen.|

## <a name="psc-and-partner-center-field-mapping"></a>PSC-und Partner Center-Feld Zuordnung

In diesem Abschnitt erfahren Sie, wie Sie die genaue Zuordnung von Attributen zwischen PSC und Partner Center verstehen. Jeder Bildschirm im PSC wird mit der relevanten Ansicht im Partner Center-Bereich Co-Selling-Verkaufschancen verglichen. 

>[!Note]
>Folgen Sie den Zahlen auf den gelben Blasen in den PSC-Screenshots, um das entsprechende Attribut in Partner Center zu suchen. Die roten Blasen geben an, dass das Profil in Partner Center nicht verfügbar ist.

### <a name="home-page-of-psc-and-default-view-of-the-co-sell-opportunities-in-partner-center"></a>Startseite des PSC und Standardansicht der Co-Selling-Verkaufschancen in Partner Center

 :::image type="content" source="images/pscmigration/homepage.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Startseite von Partner Sales Connect und der Standardansicht der Co-Selling-Verkaufschancen in Partner Center.":::

### <a name="psc-grid-view-and-the-partner-center-deal-view"></a>PSC-Rasteransicht und Partner Center-Ansicht

- Im Partner Center gibt es keine Listenansicht wie die des PSC.  Alle Geschäfte werden basierend auf dem Datum der letzten empfangenen oder erstellten Informationen mit den Kundeninformationen und dem Typ des Deals aufgelistet. Der erste Teil der Ansicht ist standardmäßig ausgewählt. Die meisten der Werte, die im PSC-Tabellenformat angezeigt werden, sind in der Detailansicht des PCs (PC) verfügbar.
- Die Rolle "Geschäft" ist kein Pflichtfeld im PC. Sie wird weder in einem der Workflows angezeigt noch aufgezeichnet. Es wird automatisch auf der Seite des Microsoft-Verkäufers basierend auf den Lösungen abgeleitet, die dem Geschäft hinzugefügt werden.
- Das Datum der letzten Änderung wird nicht auf der Seite mit den Verweis Details auf dem PC angezeigt. Partner können die Sortierungs Funktionen verwenden, um die Geschäfte basierend auf dem Datum der letzten Aktualisierung zu sortieren.

 :::image type="content" source="images/pscmigration/gridview.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Ansicht Partner Sales Connect (PSC) und der Partner Center-Ansicht.":::

### <a name="deal-details-view-in-psc-and-partner-center"></a>Detailansicht im PSC und Partner Center

- Partner können einen Teil bearbeiten, indem Sie auf die Schaltfläche "Bearbeiten" in der Detailansicht für Partner Details (6) klicken. Wenn Sie auf die Schaltfläche "Bearbeiten" klicken, werden alle Felder bearbeitbar, und die Option zum Speichern oder Abbrechen der Änderungen, die an der Sache vorgenommen wurden, wird gespeichert.
- Es gibt keine Option zum Schließen des Deals als Duplizierung in Partner Center.
- Das Kunden Ergebnis ist nicht im Partner Center verfügbar. Alle Details im Zusammenhang mit Kundeninteraktionen können im Abschnitt "Hinweise" des PCs aktualisiert werden.
- Das geschätzte Lösungs Schluss Datum ist nur für OEM-IOT-Angebote verfügbar. Sie wird für andere Typen von Typen nicht angezeigt.
- Das Lizenzierungsprogramm ist auf dem PC nicht erforderlich. Sie wird automatisch basierend auf den Lösungen abgeleitet, die in der Vereinbarung ausgewählt wurden.

>[!Note]
>Alle als "gewinnt" oder "verloren" markierten Geschäfte können nicht bearbeitet werden. Seien Sie vorsichtig, wenn Sie eine Aufgabe in einen dieser Terminal Zustände verschieben.

 :::image type="content" source="images/pscmigration/dealdetails.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Partner Sales Connect (PSC)-Detailansicht und der Partner Center-Detailansicht.":::

### <a name="psc-add-products-view-and-the-partner-center-add-solutions-view"></a>PSC-Ansicht "Produkte hinzufügen" und "Partner Center hinzufügen"

 :::image type="content" source="images/pscmigration/products.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Ansicht Partner Sales Connect (PSC) Add Products (Partner Sales Connect) und der Partner Center-Ansicht Lösungen hinzufügen.":::

### <a name="user-management-in-psc-and-partner-center"></a>Benutzerverwaltung in PSC und Partner Center

 :::image type="content" source="images/pscmigration/usermanagement.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Partner Sales Connect (PSC)-Startseite und der Partner Center-Benutzerverwaltung in der Ansicht Kontoeinstellungen.":::

### <a name="user-role-assignment-in-psc-and-partner-center"></a>Benutzer Rollenzuweisung in PSC und Partner Center

- Die entsprechende Rolle für den PSC-Administrator ist die Konto Administrator Rolle in Partner Center.
- Im Partner Center gibt es nur eine Rolle für die Co-Selling-Verwaltung, bei der es sich um die Verweis Administrator Rolle handelt.
- Alle Deal-Manager und die Verkäufer in PSC sollten der Referenz Administrator Rolle zugewiesen werden.

 :::image type="content" source="images/pscmigration/roles.png" alt-text="Das Bild zeigt die Feld Zuordnungen zwischen der Rollen Zuweisungs Ansicht Partner Sales Connect (PSC) und der Partner Center-Rollen Zuweisungs Ansicht.":::

### <a name="notifications-in-psc-and-partner-center"></a>Benachrichtigungen in PSC und Partner Center

 :::image type="content" source="images/pscmigration/notifications.png" alt-text="Das Image zeigt die Zuordnung zwischen den PSC-Benachrichtigungen (Partner Sales Connect) und der Partner Center-Benachrichtigungs Ansicht.":::

## <a name="moving-from-psc-to-partner-center---frequently-asked-questions"></a>Wechseln vom PSC zu Partner Center: häufig gestellte Fragen

### <a name="q-what-should-i-do-if-i-dont-have-access-to-partner-center"></a>Q. Was soll ich tun, wenn ich keinen Zugriff auf Partner Center habe?

Sie können sich an Ihre Administratoren wenden, die auf der Seite "kein Zugriff" aufgeführt sind, um die zugewiesenen Rollen zu erhalten. Sie benötigen die Rolle "[Verweis admin](https://docs.microsoft.com/partner-center/permissions-overview#manage-referrals)" für Lese-und Schreibberechtigungen im Abschnitt "Verweise". Wenn Sie nur geschäftsprofile verwalten, benötigen Sie die Rolle "Geschäftsprofil Administrator" im Partner Center.

### <a name="q-who-can-grant-me-access-to-the-referrals-section-in-partner-center"></a>Q. Wer kann mir Zugriff auf den Abschnitt "Verweise" in Partner Center gewähren?

Ihr [Konto Administrator](https://docs.microsoft.com/partner-center/permissions-overview#manage-mpn-membership-and-your-company-non-aad-roles-these-roles-manage-the-company-business-rather-than-the-tenant) kann Ihnen Zugriff auf die Registerkarte "Verweise" gewähren. Um Ihren Konto Administrator zu finden, wechseln Sie über das Zahnrad Symbol in der oberen rechten Ecke des Partner Centers zu den Partner Einstellungen. Klicken Sie auf der zweiten Ebene der linken Navigationsleiste auf die Seite Benutzerverwaltung. Klicken Sie oben rechts auf der Seite auf die Dropdown-Ansicht mit "alle Benutzer", und wechseln Sie zu "Konto Administratoren". Auf der Seite werden dann alle Konto Administratoren mit ihren jeweiligen e-Mail-IDs angezeigt. Wenden Sie sich an die IT-Abteilung, um den Zugriff auf Ihr Geschäftskonto zu erhalten.

### <a name="q-the-new-deal-button-is-greyed-out-for-our-account-what-should-i-do-to-start-creating-deals"></a>Q. Die Schaltfläche + neu bearbeiten ist für unser Konto abgeblendet. Was soll ich tun, um mit dem Erstellen von Deals zu beginnen?

Dies geschieht nur, wenn keine Co-Selling-Lösungen an die MPN-Organisation angefügt sind, die Sie im Partner Center verwenden. Wenden Sie sich an Ihr PDM, um die MPN-ID Ihrer Lösungen korrigiert zu erhalten, oder erstellen Sie ein Support Ticket, das das Problem "neue Schaltfläche nach der PSC-Migration abgeblendet" darstellt.

### <a name="q-can-i-assign-deals-to-a-specific-person-from-our-organization-like-psc"></a>Q. Kann ich den Mitarbeitern eine bestimmte Person aus unserer Organisation zuweisen, wie z. b. PSC?

Sie können Teammitglieder einer bestimmten Sache zuweisen. Es verhindert nicht, dass andere Verweises-Administratoren diese Angebote anzeigen oder darauf reagieren. 

### <a name="q-is-there-a-view-of-all-the-deals-assigned-to-me"></a>Q. Gibt es eine Ansicht aller mir zugewiesenen Angebote?

Sie können das Feature "Favoriten" verwenden, das eine Registerkarte auf Benutzerebene ist. Sie können alle als Favoriten zugewiesenen Angebote markieren, um einen schnellen Zugriff auf die Geschäfte zu erhalten.

### <a name="q-is-there-a-read-only-view-for-the-deals"></a>Q. Gibt es eine schreibgeschützte Ansicht für die Geschäfte?

Nein, es gibt keine schreibgeschützte Ansicht der Deals im Abschnitt "Verweise". Alle verweisadministratoren verfügen über vollständigen Lese-und Schreibzugriff auf alle Geschäfte.

### <a name="q-how-can-i-register-a-deal-after-making-it-as-won"></a>Q. Wie kann ich ein Problem registrieren, nachdem es als gewonnen gewonnen wurde?

Wenn der Vorgang die unten aufgeführten Kriterien erfüllt, wird ein Popup Fenster angezeigt, um die [Registrierung](https://docs.microsoft.com/partner-center/register-deals)zu beginnen.

- Es gibt eine berechtigte berechtigte Lösung, die an den Vertrag angeschlossen ist.
- Der Microsoft-Verkäufer ist eingeladen, am Umgang teilzunehmen, oder Sie haben Sie zur Sache eingeladen.
- Die Microsoft-Karte hat den Status "akzeptiert" oder "Won" im Partner Center.

### <a name="q-i-get-an-error-message-when-i-click-on-new-deal-registration-button-in-the-deal-registration-section-how-can-i-register-my-deals"></a>Q. Ich erhalte eine Fehlermeldung, wenn ich auf die Schaltfläche "+ New-Deal-Registrierung" im Abschnitt "Registrierungs Registrierung" klicke. Wie kann ich meine Geschäfte registrieren?

Die "+ New-Deal-Registrierung" soll nur von den Partnern verwendet werden, die im ISV Connect-Programm registriert sind, um ein Geschäft ohne entsprechende Co-Selling-Verkaufschancen in Partner Center zu registrieren. Für die Registrierung mit einer Co-Selling-Verkaufschance wird ein Popup Fenster angezeigt, wenn das Geschäft als gewonnen gekennzeichnet ist, und wenn es die Kriterien für die Registrierungs Registrierung erfüllt.

### <a name="q-is-adding-a-customer-organization-mandatory"></a>Q. Ist das Hinzufügen einer Kundenorganisation obligatorisch?

Ja, das Hinzufügen einer [Kundenorganisation](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#select-your-customer) ist im Partner Center obligatorisch. Zuerst suchen Sie nach dem Speicherort, an dem sich der Kunde befindet. Basierend auf den Details, die Sie besitzen. Sie können genau den genauen Gebäude Namen einschließen oder nur die Details der Stadt angeben. Bei der Organisations Suche werden alle juristischen Entitäten abgerufen, die mit dem eingegebenen Namen übereinstimmen, sodass Sie keine Adressen Details eingeben müssen. Alle Details werden automatisch basierend auf der ausgewählten Organisation ausgefüllt.

### <a name="q-are-customer-contact-details-mandatory"></a>Q. Sind Kundenkontakt Details obligatorisch?

Hängt vom [Typ des](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#types-of-co-sell-opportunities) zu erstellenden Typs ab. Wenn Sie nur ihre Pipeline freigeben und keine Hilfe von der Microsoft-Vertriebsorganisation benötigen, können Sie auswählen, dass Sie keine Kundenkontaktinformationen erhalten. Wenn Sie gemeinsam mit der Unterstützung von Microsoft-Verkäufern Hilfe benötigen, müssen Sie die Details des Kundenkontakts angeben. Sie sollten vor dem Erstellen einer Co-Selling-Anforderung im Partner Center eine explizite Zustimmung des Kunden erhalten.

### <a name="q-how-many-solutions-can-i-add-to-a-deal"></a>Q. Wie viele Lösungen kann ich zu einem Teil hinzufügen?

Sie können bis zu 50 Lösungen (Produkte in PSC) zu einem Geschäft hinzufügen. Anders als bei PSC können Sie Lösungen aus ihren eigenen Co-Selling-Lösungen, von Microsoft-SKUs für erste Parteien und von anderen Co-Selling-Lösungen von Drittanbietern kombinieren. Es gibt keine Rolle "Rolle", die ausgewählt oder im Partner Center verfügbar sein soll. Bei Microsoft-SKUs können Sie optional die Menge und den Preis für jede SKU hinzufügen, die dem jeweiligen Geschäft hinzugefügt wird.

### <a name="q-when-will-i-get-to-know-the-microsoft-seller-details-after-creating-a-deal"></a>Q. Wann erhalte ich die Details des Microsoft-Verkäufers nach dem Erstellen eines Deals?

Microsoft-Verkäufer werden erst zugewiesen, nachdem die genaue Hilfe Anforderung abgeglichen wurde, die beim Erstellen des Deals mit der relevanten Verkäufer-Persona auf der Microsoft-Seite angegeben wurde. Auch nach der Zuweisung haben Microsoft-Verkäufer die Möglichkeit, die Co-Selling-Einladung anzunehmen oder abzulehnen. Nur wenn eine Co-Selling-Einladung von einem Verkäufer akzeptiert wird, wird der Vorgang mit den Kontaktinformationen des Microsoft-Verkäufers aktualisiert. Die SLA für Microsoft-Verkäufer, die für das Geschäft tätig sein soll, ist 14 Tage. Es handelt sich um die gleiche SLA, die Partner für das Geschäft tun müssen, bevor Sie in den abgelaufenen Zustand übergeht.

### <a name="q-where-can-i-find-the-opportunity-id"></a>Q. Wo finde ich die Verkaufschancen-ID?

Die Verkaufschancen-ID im PSC ist mit der ID des Deals im PC identisch. Sie können die ID des Deals neben dem Namen des Deals finden, wenn Sie eine beliebige Menge öffnen.

### <a name="q-how-can-my-pdm-get-access-to-pc"></a>Q. Wie kann meine PDM auf den PC zugreifen?

Ihr PDMS kann nicht direkt im Gegensatz zu PSC auf Partner Center zugreifen. Es gibt mehrere Optionen, um diese Funktion zu aktivieren, die unten erwähnt werden.

- OCP Insights: Wenn PDMS nur die & fortlaufenden Status anzeigen, können Sie das OCP Insights-Portal verwenden, um Ihre Organisations Ansicht zu erhalten. Hierbei handelt es sich um ein internes Tool, das nur für PDMS und Ihre Benutzer verfügbar ist.
- Gastbenutzer in Partner Center: Sie können Ihr PDM- @microsoft.com Konto als Gastbenutzer in Partner Center hinzufügen und ihm eine verweisadministrator-Rolle zuweisen, damit Sie Verweise anzeigen und darauf reagieren können.
- Erstellen eines [neuen Benutzers](https://docs.microsoft.com/partner-center/create-user-accounts-and-set-permissions#add-a-new-user) in Ihrem Mandanten: Sie können einen neuen Benutzer in Ihrem eigenen Mandanten erstellen und diese Details mit dem PDM teilen, sodass Sie Verweise anzeigen und auf ähnliche Verweise wie andere verweisbenutzer in Ihrem Konto reagieren können.

## <a name="resources-to-help-you-create-and-manage-your-deals-in-partner-center"></a>Ressourcen, die Sie beim Erstellen und Verwalten Ihrer Geschäfte in Partner Center unterstützen

Wenn Sie die Hilfe Themen für die Co-Selling-Hilfe noch nicht gelesen haben, helfen Ihnen die folgenden Ressourcen bei der Verwaltung von Geschäften im Partner Center.

|**Aufgabe**   |**Artikel**   |
|-----------------------|:-----------------------|
|Grundlegendes zu den Registerkarten und Navigation auf der Seite mit den Möglichkeiten|[Navigieren im Co-Selling-Abschnitt](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#navigating-the-co-sell-section)|
|Auswählen einer Kundenorganisation aus der Liste der D-&B |[Wählen Sie Ihren Kunden aus](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#select-your-customer)|
|Ändern der Felder im Abschnitt "Details zum Abschnitt"|[Details zum Umgang](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#deal-details)|
|Hinzufügen der Mitarbeiter Ihres Unternehmens zu einem Deal-Team|[Mitarbeiter hinzufügen](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#add-your-employees)|
|Antworten auf einen Co-Selling-Deal|[Verwalten von Co-Selling-Geschäften](https://docs.microsoft.com/partner-center/manage-co-sell-opportunities#responding-to-a-co-sell-opportunity)
|Von Ihnen im Partner Center ersicherte Angebote registrieren |[Registrieren eines neuen Angebots](https://docs.microsoft.com/partner-center/register-deals)
|Verschaffen Sie sich Einblicke, und informieren Sie sich über die Funktionsweise ihrer Verweise. |[Einblicke zu Empfehlungen](https://docs.microsoft.com/partner-center/referral-insights)
|Erstellen und Verwalten von Geschäftsprofilen|[Verwalten von Geschäftsprofilen](https://docs.microsoft.com/partner-center/create-a-marketing-profile)
|Verwalten von Leads für Ihr Geschäftsprofil |[Verwalten von Leads](https://docs.microsoft.com/partner-center/manage-leads)|

## <a name="additional-resources"></a>Zusätzliche Ressourcen

- [Partner Verkäufe stellen eine Verbindung mit der Partner Center-Arbeitsmappe](https://partner.microsoft.com/resources/detail/partner-sales-connect-to-partner-center-transition-workbook-pptx) her, um die Vertriebsprozesse und-Rollen der Partner mithilfe von Partner Center im Vergleich zu Partner Sales Connect mit neuen Vertriebsprozessen auszurichten.
- [Partner Center Co-Selling Operating Guide](https://partner.microsoft.com/resources/detail/co-sell-operating-model-guide-pptx) : Leitfaden zum Identifizieren eines Betriebsmodells über Partner Center, um Leads oder Co-Selling-Verkaufschancen zu verwalten und Angebote zu registrieren.
- [Referenz Verwaltung](https://partner.microsoft.com/resources/detail/referral-management-in-partner-center-pptx) : eine Schritt-für-Schritt-Anleitung zum Verwalten von Leads und Co-Selling-Verkaufschancen über Partner Center.
- [Veröffentlichen und Verwalten von in der kommerziellen Marketplace](https://partner.microsoft.com/resources/detail/publishing-and-managing-co-sell-offers-in-commercial-marketplace-pptx) -visualisierten Schritt-für-Schritt-Anleitung zum Erstellen, verwalten und Veröffentlichen von Angeboten über Partner Center im kommerziellen Marketplace.