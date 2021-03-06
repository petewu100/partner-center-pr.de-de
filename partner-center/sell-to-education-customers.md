---
title: Verkaufen von Angeboten an Bildungs Kunden
description: Erfahren Sie, wie Sie einen Bildungs Kunden erstellen und Angebote in Partner Center verkaufen. Beinhaltet die Bestätigung des Überprüfungs Status für ihren Bildungs Kunden.
ms.topic: how-to
ms.date: 12/17/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
author: alikhaki
ms.author: alikhaki
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 5af6ae0d3c11d2ea59e4b8ef2224393e48d6a3df
ms.sourcegitcommit: cd4047e46ed116339bd9918b94af7138bcae6603
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/06/2021
ms.locfileid: "97916911"
---
# <a name="how-to-sell-offers-to-education-customers-and-how-to-create-an-education-customer-in-partner-center"></a>Verkaufen von Angeboten an Bildungs Kunden und How to Create a Education Customer in Partner Center


**Geeignete Rollen**

- Globaler Administrator
- Administrator-Agent
- Vertriebsbeauftragter

## <a name="create-an-education-customer"></a>Erstellen eines Education-Kunden

In diesem Artikel wird erläutert, wie Sie einen Bildungs Kunden in Partner Center erstellen und Schulungsprodukte an Sie verkaufen. Außerdem wird erläutert, wie Sie den Überprüfungs Status anzeigen und ggf. die Überprüfungs Anforderung erneut senden.

> [!IMPORTANT]
> Microsoft überprüft jeden neu erstellten Kunden Mandanten für Bildungseinrichtungen, um sicherzustellen, dass Sie für Schulungsangebote qualifiziert sind.  Stellen Sie sicher, dass Sie die erforderlichen Informationen so genau und vollständig wie möglich eingeben, um Verzögerungen beim Überprüfungsprozess zu verhindern.

1. Melden Sie sich bei Partner Center an.

2. Wählen Sie **Kunden** und dann **Kunde hinzufügen** aus. Wählen Sie in der Dropdown Liste **spezielle Qualifikationen** die Option **Education** aus.  Geben Sie die restlichen Kontoinformationen nach Bedarf ein.  Wichtige Felder, die den Überprüfungsprozess unterstützen, sind:

   - **Firmenname**: Geben Sie den juristischen Entitäts Namen für die Überprüfung ein.
   - **Land/Region und Adresszeile**: Geben Sie die vollständige Adresse der Entitäts Adresse ein – für die Überprüfung
   - **E-Mail-Adresse**: Geben Sie die e-Mail-Adresse des Unternehmens ein, die für die Überprüfung erforderlich ist.
   - **Kundenkontaktinformationen**: Diese Details werden im Rahmen des Überprüfungsprozesses verwendet.
   - **Primärer Domänen Name**: wird zum Erstellen des Kundenkontos und der e-Mail-Adressen verwendet  Wählen Sie einen Namen aus, der dem Firmennamen ohne Leerzeichen oder Sonderzeichen ähnelt.  Dieser Name kann später nicht mehr geändert werden.

3. Wenn Sie fertig sind, wählen Sie **überprüfen** aus.

   :::image type="content" source="images/eduaccountinfo.png" alt-text="Education-Kundenkonto":::

4. Nachdem Sie die **Überprüfung** bestätigt haben, erhalten Sie einen **inreview** -Status, wenn die übermittelten Informationen gültig sind. 

    :::image type="content" source="images/edu/create-review.png" alt-text="Schulungskunden Konto in Review"lightbox="images/edu/create-review-expanded.png":::

### <a name="confirm-your-education-customers-verification-status"></a>Verifizierungs Status Ihres Bildungs Kunden bestätigen

**Weitere Informationen** finden Sie auf der Seite **Konto** des Kunden.
Status Beispiele:

- Wenn der Kunde die Überprüfung erfolgreich war: Education

   :::image type="content" source="images/edupassedvetting.png" alt-text="Die Bildungs Überprüfung war erfolgreich.":::

- Wenn der Kunde die Überprüfung nicht bestanden hat: kein Education-Kunde

   :::image type="content" source="images/edu/fail-reason.png" alt-text="Die Bildungs Überprüfung war nicht erfolgreich." lightbox="images/edu/fail-reason-expanded.png":::

- Wenn der Kunde nicht als Education-Kunde gekennzeichnet war: keine

   :::image type="content" source="images/edu/account-one.png" alt-text="Education Customer ist nicht als solche gekennzeichnet." lightbox="images/edu/account-one-expanded.png":::

- Wenn der Kunde als Bildungs Kunde überprüft wird: Review

    :::image type="content" source="images/edu/in-review.png" alt-text="Education Customer ist in Review" lightbox="images/edu/in-review-expanded.png":::

## <a name="correct-the-customer-account-info-and-resubmit-for-verification"></a>Kundenkontoinformationen korrigieren und zur Überprüfung erneut einreichen

Wenn Ihr Kunde die anfängliche Überprüfung nicht bestanden hat, können Sie nun die Informationen korrigieren und erneut übermitteln.

### <a name="correct-the-customer-account-information"></a>Kundenkontoinformationen korrigieren

Sie müssen über globale Administratorrechte verfügen, um die Kundeninformationen aktualisieren zu können. Sie aktualisieren die Informationen im Office 365-Portal, da diese Daten nicht über das Partner Center-Portal aktualisiert werden können.

1. Auf der Seite **Konto** werden Informationen angezeigt, die angeben, dass die Kunden Qualifikation als "kein Bildungs Kunde" angesehen wird.

2. Aktualisieren Sie den Browser, um die Seite zurückzusetzen. Es gibt eine **Aktualisierungs** Schaltfläche, und der **Status der speziellen Qualifikationen** ist auf **None** festgelegt.

3. Wählen Sie **Update** aus. Wählen Sie auf der Seite **Dienst Verwaltung** die Option **Office 365** aus.

4. Sie werden auf einer neuen Registerkarte Ihres Browsers an das Office 365 Admin Center umgeleitet. Möglicherweise werden Sie aufgefordert, sich mit Ihren Anmelde Informationen anzumelden.

5. Wählen Sie **Einstellungen** aus.

6. Wählen Sie oben auf dem Bildschirm die Registerkarte **Organisations Profil** und dann **Organisations Informationen** aus. Sie können jetzt die Kunden Details aktualisieren.

7. Wählen Sie am unteren Rand der Rand Leiste die Option **Änderungen speichern** aus.  

### <a name="resubmit-for-verification"></a>Zur Überprüfung erneut senden

1. Navigieren Sie zu ihrer Partner Center-Registerkarte und zur Seite Kunden **Konto** . Aktualisieren Sie den Browser, und überprüfen Sie, ob die Unternehmensseite auf die neuen Informationen aktualisiert wurde. Wählen Sie die Schaltfläche **Aktualisieren** , um die erneute Überprüfung von Schulungen anzufordern

2. Wenn die aktualisierten Kunden Details für Schulungsangebote qualifiziert sind, sehen Sie, dass die **speziellen Qualifikationen** auf **Education** aktualisiert werden. Wenn Sie immer noch **keinen Bildungs Kunden** sehen, wenden Sie sich an den Support für die manuelle Überprüfung.

## <a name="next-steps"></a>Nächste Schritte

- [Verkaufen an spezielle Branchen](get-special-pricing-for-offers.md)

- [Hinzufügen neuer Kunden](add-a-new-customer.md)

- [Verkaufen von minecraft: Education Edition-Abonnements für Bildungs Kunden](minecraft-subscriptions.md)
