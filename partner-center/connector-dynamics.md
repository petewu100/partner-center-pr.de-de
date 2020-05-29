---
title: Der Co-Selling-Connector für Dynamics 365 CRM Partner Center
ms.topic: article
ms.date: 05/27/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Synchronisieren Ihrer Verweise in Partner Center mit Dynamics 365 CRM
ms.assetid: c6fca2c0-2e6c-41b1-9be8-b363b139f15b
author: LauraBrenner
ms.author: labrenne
keywords: ''
ms.localizationpriority: medium
ms.openlocfilehash: 87b1d27fa2f42eeba3b0f8308648536c0686911e
ms.sourcegitcommit: c13723216761e60d2b37596efc71f5fdecb30be1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/28/2020
ms.locfileid: "84145134"
---
# <a name="co-sell-connector-for-dynamics-365-crm--overview"></a>Co-Selling-Connector für Dynamics 365 CRM – Übersicht

### <a name="appropriate-roles"></a>Geeignete Rollen

- Empfehlungsadministrator
- Systemadministrator oder systemanpassungsprogramm im CRM

Der Partner Center-Co-Selling-Connector ermöglicht ihren Verkäufern das Co-Selling mit Microsoft innerhalb Ihrer CRM-Systeme. Sie müssen nicht für die Verwendung von Partner Center zur Verwaltung von Co-Selling-Geschäften geschult werden. Verwenden Sie die Co-Selling-Connectors, um einen neuen Co-Selling-Verweis zum Einbinden eines Microsoft-Verkäufers zu erstellen, Referenzen von Microsoft-Verkäufern zu erhalten, Verweise zu akzeptieren/ablehnen, Daten zu ändern, wie z. b. den Geschäftswert und das Enddatum. Sie können für diese Co-Selling-Angebote auch Updates von den Microsoft-Verkäufern erhalten. Sie können alle Ihre Verweise im CRM Ihrer Wahl und nicht im Partner Center verwenden. 

Die Lösung basiert auf der Microsoft Power automatisieren-Lösung und verwendet Partner Center-APIs.

## <a name="before-you-install---pre-requisites"></a>Vor der Installation von-Pre-Requirements

|**Themen**   |**Details**   |**Links**   |
|--------------|--------------------|------|
|Microsoft Partner Network-ID |Sie benötigen eine gültige MPN-ID.|So fügen Sie [MPN](https://partner.microsoft.com/) an|
|Cosell bereit|Ihre IP-/Dienst-Lösung muss für den Co-Selling bereit sein.|[Vertrieb mit Microsoft](https://partner.microsoft.com/membership/sell-with-microsoft)| 
|Partner Center-Konto|Die MPN-ID, die dem Partner Center-Mandanten zugeordnet ist, muss mit der MPN-ID identisch sein, die ihrer Co-Selling-Lösung zugeordnet ist. Vergewissern Sie sich, dass Sie Ihre Co-Selling-Verweise im Partner Center-Portal sehen können, bevor Sie die Connectors bereitstellen.|[Verwalten Ihres Kontos](create-user-accounts-and-set-permissions.md)|
|Partner Center-Benutzerrollen|Der Mitarbeiter, der die Connectors installieren und verwenden soll, muss ein Administrator sein.|[Zuweisen von Rollen und Berechtigungen zu Benutzern](create-user-accounts-and-set-permissions.md)| |Dynamics 365 CRM|Die CRM-Benutzerrolle ist Systemadministrator oder SystemCustomizer.|[Zuweisen von Rollen in Dynamics 365](https://docs.microsoft.com/dynamics365/customerengagement/on-premises/customize/privileges-required-customization)|
|Energie automatisierter Fluss Konto|Ein aktives, [Energie automatisierbares](https://flow.microsoft.com) Konto für den CRM-Systemadministrator oder den SystemCustomizer. Dieser Benutzer sollte sich mindestens einmal vor der Installation bei der [Strom Automatisierung](https://flow.microsoft.com) anmelden.|

## <a name="install-partner-center-referrals-synchronization-for-dynamics-365-power-automate-solution"></a>Installieren der Partner Center-Synchronisierung für Dynamics 365 (Energie automatisierte Lösung) 

1. Wechseln Sie zu " [Energie Automatisierung](https://flow.microsoft.com) ", und wählen Sie in der rechten oberen Ecke **Umgebungen** aus. In diesem Schritt werden die verfügbaren CRM-Instanzen angezeigt.

2. Wählen Sie in der Dropdown-Dropdown-Ecke in der rechten oberen Ecke die entsprechende CRM-Instanz aus. 

3. Wählen Sie in der linken Navigationsleiste **Lösungen** aus.

4. Klicken Sie im oberen Menü auf den Link **appsource öffnen** .

![Appsource öffnen](images/cosellconnectors/openappsource.png)

5. Suchen Sie im Popup-Bildschirm nach **Partner Center-verweisverweisconnectors für Dynamics365** .  

6. Klicken Sie auf die Schaltfläche **jetzt starten** und dann auf **weiter**. 

7. Dadurch wird die Seite geöffnet, auf der Sie die CRM-Umgebung (Dynamics 365) zum Installieren der Anwendung auswählen können.  Stimmen Sie den Geschäftsbedingungen zu. 

8. Anschließend werden Sie zur Seite **Verwalten Ihrer Lösungen** weitergeleitet.  Navigieren Sie zu "Partner Center-Verweise", indem Sie die Pfeil Schaltflächen unten auf der Seite verwenden. Die **geplante Installation** sollte neben der Projekt Mappe für Partner Center-Verweise angezeigt werden. Die Installation wird 10-15 Minuten dauern. 

9. Nachdem die Installation fertiggestellt ist, navigieren Sie zurück zu [Energie Automatisierung](https://flow.microsoft.com) , und wählen Sie im linken Navigationsbereich **Lösungen** aus. Beachten Sie, dass die **Synchronisierung der Partner Center-Verweise für Dynamics 365** in der Lösungs Liste verfügbar ist.

10. Wählen Sie **Partner Center-Synchronisierungs Referenz für Dynamics 365 aus**. Die folgenden Strom automatisierten Flows und Entitäten sind verfügbar:

![Verfügbare CRMs](images/cosellconnectors/dynamics-available-crms.png)

## <a name="best-practice-test-before-you-go-live"></a>Bewährte Vorgehensweise: testen, bevor Sie fortfahren

Stellen Sie sicher, dass Sie die Lösung in einer-Staging-Instanz von CRM testen, bevor Sie die Energie automatisierte Lösung in der Produktionsumgebung installieren, konfigurieren und anpassen.

- Installieren Sie die Microsoft powerautomatisieren-Lösung auf einer Staging-Umgebung/CRM-Instanz.
- Erstellen Sie eine Kopie der Projekt Mappe, und führen Sie die Konfiguration aus, und führen Sie die Automatisierung der Fluss Anpassungen in der Stagingumgebung durch
- Testen Sie die Lösung auf einer Staging/CRM-Instanz. 
- Importieren Sie bei Erfolg als verwaltete Lösung in die Produktions Instanz. 

## <a name="configure-the-solution"></a>Konfigurieren der Projektmappe

1. Nachdem Sie die Lösung in Ihrer CRM-Instanz installiert haben, navigieren Sie zurück zu [Energie Automatisierung](https://flow.microsoft.com/).

2. Wählen Sie in der Dropdown- **Umgebung** in der rechten oberen Ecke die CRM-Instanz aus, auf der Sie die Energie automatisierte Lösung installiert haben.

3. Sie müssen Verbindungen erstellen, die die drei Benutzerkonten zuordnen: 

- Partner Center-Benutzer mit referenrals Administrator Anmelde Informationen 

- Partner Center-Ereignisse

- Der CRM-Administrator mit den Energie automatisierten Flows in der Lösung. 

    a. Wählen Sie in der linken Navigationsleiste **Verbindungen** aus, und wählen Sie die Projekt Mappe "Partner Center-Verweise" aus der Liste aus.

    b. Erstellen Sie eine Verbindung, indem Sie auf **Verbindung erstellen**klicken.

    ![Erstellen der Verbindung](images/cosellconnectors/createconnection.png)

    c. Suchen Sie in der Suchleiste in der oberen rechten Ecke nach **Partner Center-Referenzen (Vorschau)** .

    d. Erstellen Sie eine Verbindung für Ihren Partner Center-Benutzer mit der Rolle "Anmelde Informationen" des Administrators "Administrator".

    e. Erstellen Sie als nächstes eine Partner Center-Ereignis Verbindung für Ihren Partner Center-Benutzer mit den Anmelde Informationen für den Administrator.

    f. Erstellen Sie eine Verbindung für Common Data Service (aktuelle Umgebung) für den CRM-Administrator Benutzer.

4. Um die Strom automatisierten Flows den Verbindungen zuzuordnen, bearbeiten Sie jeden der Strom automatisierten Flows, um eine Verbindung mit Common Data Service-und Partner Center-Referenzen herzustellen. Speichern Sie die Änderungen.

5. **Schalten** Sie die Strom automatisierten Flows ein.

## <a name="use-webhook-apis-to-register-for-resource-change-events"></a>Verwenden von webhook-APIs zum Registrieren für Ressourcen Änderungs Ereignisse

Die Partner Center-webhook-APIs ermöglichen es Ihnen, sich für Ressourcen Änderungs Ereignisse zu registrieren. Diese Änderungs Ereignisse werden als http-Beiträge an Ihre URL gesendet.

1. Um Ihre URL zu registrieren, wählen Sie **Partner Center-webhook-Registrierung (Insider Vorschau)** Energie automatisierter Flow aus.

2. Hinzufügen von Verbindungen für (a.) Partner Center-Benutzer mit referengenalen Administrator Anmelde Informationen (b) Partner Center-Veranstaltungen wie unten gezeigt

![Trigger](images/cosellconnectors/triggerflow.png)

3. Wenn Sie diese Updates vornehmen, wird Folgendes angezeigt:

![webhooks](images/cosellconnectors/webhook1.png)

4. Speichern Sie die Änderungen, und wählen Sie **einschalten aus**. 

Führen Sie die folgenden Schritte aus, um Partner Center-webhooks zum lauschen auf Ereignis Änderungen zu aktivieren:

5. Wählen Sie **Partner Center auf Dynamics 365 (Insider Preview)** aus.

6. Wählen Sie das **Bearbeitungs** Symbol aus, und wählen Sie **bei Empfang einer HTTP-Anforderung**aus.

7. Wählen Sie das **Kopier** Symbol aus, um die bereitgestellte HTTP Post-URL zu kopieren.

![Kopieren der URL](images/cosellconnectors/copyurl.png)

8. Wählen Sie jetzt die Option "Partner Center-webhook-Registrierung (Insider Vorschau)", und wählen Sie **Ausführen**aus.

9. Stellen Sie sicher, dass im rechten Bereich das Fenster "Flow ausführen" geöffnet wird, und klicken Sie auf **weiter**.

10. Geben Sie die folgenden Details ein: 

    a. **Http-auslöserendpunkt**: aus dem vorherigen Schritt kopierte URL

    b. **Zu Registrier folgende Ereignisse**: "Verweis-erstellt" und "Verweis-aktualisiert"

    c. **Vorhandene auslöserendpunkte überschreiben, falls vorhanden**: Ja (Dadurch werden alle vorhandenen Endpunkte überschrieben.) 

11. Wählen Sie **Ausführen** aus, und wählen Sie dann **abgeschlossen aus.**

Der webhook kann nun auf Create-und Update-Ereignisse lauschen.

## <a name="customize-synchronization-steps"></a>Synchronisierungs Schritte anpassen

Wenn Co-Selling-Referenzen zwischen Partner Center und Ihrem CRM-System synchronisiert werden, werden die Felder, die auf dem Partner Center-PC synchronisiert werden, hier aufgeführt.

Häufig sind CRM-Systeme hochgradig angepasst. Sie können die Strom automatisierten Flows anpassen. Befolgen Sie den Leitfaden für die Feld Zuordnung, und nehmen Sie ggf. entsprechende Änderungen in den Schritten der Strom automatisierten Flows vor.  Microsoft Partner Centers für CRM-Zuordnungen werden bereitgestellt, aber je nach Ihrer CRM-Umgebung können Sie die Felder weiter anpassen.

Je nach Ihren Anforderungen können mehrere Schritte der einzelnen Strom automatisierten Flows angepasst werden. Im folgenden finden Sie Beispiele für verfügbare Anpassungen:

1. So passen Sie die Felder für die CREATE-oder Update-Ereignisse im Partner Center an die CRM-Referenz Synchronisierung an: 

    a. Wählen Sie Partner Center für Dynamics 365 (Insider Preview) oder Partner Center für Salesforce (Insider Preview) aus.

    b. Wählen Sie **Bearbeiten** aus, um den Energie automatisierten Flow zu bearbeiten bzw. anzupassen.

    c. Select **(Bereich) Hiermit wird der Lead oder die Verkaufschance synchronisiert**.

2. Wählen Sie zum Anpassen von CRM-Feld Zuordnungen (basierend auf Feld Zuordnungs Handbuch) für Erstellungs Ereignisse aus, wenn es sich um eine **neue freigegebene Chance handelt, und** Wählen Sie den unterschritt aus, **Falls ja** , und erweitern Sie dann die Option **neue Gelegenheit im CRM**. Sie können die Zuordnungen in diesem Abschnitt mithilfe des Leitfaden für die Feld Zuordnung bearbeiten.

    d. Zum Anpassen von CRM-Feld Zuordnungen (basierend auf Feld Zuordnungs Handbuch) für Update Ereignisse klicken Sie auf den Schritt "(Bereich) Synchronisieren des Leads oder der Verkaufschance".

    e. Wählen Sie aus **, ob es sich um ein Update für eine Verkaufschance handelt**. Wählen Sie den unterschritt **bei ja** aus, und erweitern Sie dann bei **Unterschied zwischen den Verkaufschancen-Objekten in Partner Center und CRM**.  

    f. Wählen Sie aus, **ob ja** gefolgt von **vorhandener Option aktualisieren**
       
3. So passen Sie die Felder für die CRM-zu-PC-Referenz Synchronisierung für Update Ereignisse an

    a. Wählen Sie **Bearbeiten** aus, um den Energie automatisierten Flow zu bearbeiten bzw. anzupassen.

    b. Select **(Bereich) Synchronisieren der Verkaufschance**.

    c. Wenn Sie die CRM-Feld Zuordnungen für Update Ereignisse anpassen möchten, wählen Sie aus, **ob es Unterschiede zwischen den führenden Objekten in Partner Center und CRM gibt**. 

    d. Wählen Sie den unterschritt aus, **Wenn ja** , und erweitern Sie dann den Schritt **Aktualisieren eines Verweises mit Verkaufschancen Daten**.

Sie können die Zuordnungen in diesem Abschnitt basierend auf dem Leitfaden für die Feld Zuordnung bearbeiten.

4. Zum Anpassen der Felder für die CRM-zu-PC-Referenz Synchronisierung für Erstellungs Ereignisse

   a. Wählen Sie **Bearbeiten** aus, um den Energie automatisierten Flow zu bearbeiten bzw. anzupassen.

   b. Wählen Sie die **Synchronisierungs Verweise aus (Bereich).**

   c. Wählen Sie zum Anpassen von CRM-Feld Zuordnungen (basierend auf Feld Zuordnungs Handbuch) für Create Events die Option **Microsoft-Verweis erstellen**. 

Sie können die Zuordnungen in diesem Abschnitt basierend auf dem Leitfaden für die Feld Zuordnung bearbeiten.

## <a name="end-to-end-bi-directional-co-sell-referral-synchronization"></a>End-to-End-bidirektionale Co-Selling-Synchronisierung

Nachdem Sie die Energie automatisierte Lösung installiert, konfiguriert und angepasst haben, können Sie die Synchronisierung von Co-Selling-Referenzen zwischen Dynamics 365 und Partner Center testen.

### <a name="pre-requisites"></a>Voraussetzungen

Um die Verweise auf Partner Center und Dynamics 365 CRM zu synchronisieren, werden die Microsoft-spezifischen verweigerfelder von der Energie automatisierten Lösung eindeutig abgegrenzt. Diese Identifikation gibt Ihren Verkäufer Teams die Möglichkeit, sich zu entscheiden, welche Referenzen Sie gemeinsam mit Microsoft für Co-Selling verwenden möchten.

Ein Satz benutzerdefinierter Felder ist als Teil der Entität " **Chance** " verfügbar. Ein CRM-Administrator Benutzer muss einen separaten CRM-Abschnitt mit den benutzerdefinierten Feldern für die Verkaufs **Chance** erstellen.

Die folgenden benutzerdefinierten Felder sollten Teil des CRM-Abschnitts sein:

- **Synchronisierung mit Partner Center**: ob die Gelegenheit mit dem Microsoft Partner Center synchronisiert werden soll

- **Verweis Bezeichner**: ein Schreib geschütztes Bezeichnerfeld für die Microsoft Partner Center-Referenz

- **Verweis Link**: ein Schreib geschützter Link zum Verweis im Microsoft Partner Center

- **Wie kann Microsoft Hilfe erhalten?**: Hilfe von Microsoft für den Verweis

- **Produkte**: Liste der Produkte, die dieser Verkaufschance zugeordnet sind

- Überwachung **: ein**Schreib geschützter Überwachungs Pfad für die Synchronisierung mit Partner Center-verweisen


### <a name="scenarios"></a>SS

1. Verweis Synchronisierung, wenn der Verweis in CRM erstellt oder aktualisiert und in Partner Center synchronisiert wird:

    a. Melden Sie sich bei ihrer Dynamics 365 CRM-Umgebung mit einem Benutzer an, der im Bereich "Verkaufs **Chancen** " von CRM Einblick hat.

    b. Stellen Sie sicher, dass der folgende Abschnitt vorhanden ist, wenn Sie eine "neue Verkaufschance" in der Dynamics 365-Umgebung erstellen.

   ![Verkaufschance](images/cosellconnectors/opportunity.png)

    c. Wenn Sie diese Gelegenheit mit dem Microsoft Partner Center synchronisieren möchten, stellen Sie sicher, dass Sie die folgenden Felder in der Kartenansicht festlegen:

    - **Mit Partner Center synchronisieren**: Ja

    - **Wie kann Microsoft Help?**: Wählen Sie eine der folgenden Aktionen aus:

    ![Auswahl von Hilfe](images/cosellconnectors/help.png)

    - **Produkte**: Lösungs-IDs des Produkts

    d. Wenn die Verkaufschance in Dynamics 365 mit der Option **sync with Partner Center** auf **Ja**festgelegt ist, warten Sie 10 Minuten, und melden Sie sich dann bei Ihrem Partner Center-Konto an. Ihre Verweise werden mit Dynamics 365 synchronisiert.

    e. Für eine Gelegenheit, bei der die Option "Synchronisierung mit Partner Center" auf "Ja" festgelegt wurde, werden die Änderungen bei der Aktualisierung der Gelegenheit in Dynamics 365 CRM in Ihrem Partner Center-Konto synchronisiert.

    f. Verkaufschancen, die mit Partner Center erfolgreich synchronisiert werden, werden mit ✔ Symbol in Dynamics 365 identifiziert.

2. Verweis Synchronisierung, wenn der Verweis im Microsoft Partner Center erstellt oder aktualisiert und in der Dynamics 365-Umgebung synchronisiert wird:

    a. Melden Sie sich bei Ihrem Partner Center- [Dashboard](https://partner.microsoft.com/dashboard/home)an.

    b. Wählen Sie im Menü auf der linken Seite die Option **Verweise** aus.

    c. Erstellen Sie einen neuen Co-Selling-Verweis aus Partner Center, indem Sie auf die Option "neu erstellen" klicken.

    d. Melden Sie sich bei ihrer Dynamics 365 CRM-Umgebung an. 

    e. Navigieren Sie zu **Open Verkaufschancen**. Der im Microsoft Partner Center erstellte Verweis ist nun in Dynamics 365 CRM synchronisiert.

    f. Wenn Sie einen synchronisierten Verweis auswählen, werden die Details der Kartenansicht aufgefüllt.

## <a name="next-steps"></a>Nächste Schritte

- [Verwalten von Leads](manage-leads.md)

- [Co-Selling-Verkaufschancen](manage-co-sell-opportunities.md)

- [Weitere Informationen zur Microsoft powerautomatisieren-Plattform](https://docs.microsoft.com/power-automate/)

- [Partner Center-Webhooks](https://docs.microsoft.com/partner-center/develop/partner-center-webhooks)