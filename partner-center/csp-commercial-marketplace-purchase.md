---
title: Erwerben kommerzieller Marketplace-Angebote
ms.topic: how-to
ms.date: 05/05/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Erfahren Sie, wie CSP-Programmpartner den Partner Center Marketplace nutzen können, um Kunden Käufe von SaaS-Angeboten von unabhängigen Software Anbietern (ISVs) zu tätigen.
author: rbars
ms.author: rbars
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 841308d535d4071ee0a8eabf3e70325edea5777c
ms.sourcegitcommit: a78dd3c532860d01867d116bfb4e2c88b84bcd25
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/08/2021
ms.locfileid: "97979715"
---
# <a name="purchase-commercial-marketplace-products-for-your-customers-in-partner-center"></a>Erwerben Sie kommerzielle Marketplace-Produkte für Ihre Kunden im Partner Center


**Geeignete Rollen**

- Globaler Administrator
- Administrator-Agent

Als Partner im CSP-Programm (Cloud Solution Provider) können Sie den kommerziellen Marketplace verwenden, um Abonnements für Ihre Kunden an bestimmte SaaS-Produkte (Software-as-a-Service) zu erwerben, die von unabhängigen Softwareanbietern (ISVs) angeboten werden.

Wenn Sie Ihren Kunden ISV-Saas-Abonnements anbieten, können Sie Ihr Unternehmen unterscheiden. Außerdem können Sie Kunden Zugriff auf Softwarepakete bieten, die Ihren speziellen Geschäftsanforderungen gerecht werden. Sie verwalten Lizenzen und Abonnements für diese Marketplace-SaaS-Produkte von ISV-Verlegern, genauso wie Sie Lizenzen und Abonnements für Microsoft-Produkte verwalten.

Sie können entweder **Lizenz basierte Saas-** Abonnements oder **nutzungsbasierte** Abonnements erwerben. Weitere Informationen zum Unterschied zwischen der lizenzbasierten und der nutzungsbasierten Abrechnung finden Sie unter [Grundlagen der Abrechnung](billing-basics.md).

## <a name="purchase-license-based-and-metered-saas-subscriptions-in-partner-center"></a>Erwerben Sie Lizenz basierte und getaktete Saas-Abonnements im Partner Center

Abonnements für Lizenz basierte oder getaktete SaaS-Produkte, die von ISV-Verlegern angeboten werden, werden mit demselben Prozess erworben, den Sie zum Erwerb von Abonnements für Microsoft-Produkte verwenden.

Informationen zum Erwerb eines lizenzbasierten oder getakteten Saas-Abonnements im Partner Center finden Sie unter [erstellen, aussetzen oder Abbrechen von Kunden Abonnements](create-a-new-subscription.md#create-a-new-subscription).

Sie können auch [Partner Center-APIs](/partner-center/develop/) verwenden, um Abonnements für Ihre Kunden im kommerziellen Marketplace zu erstellen. (Weitere Informationen zur Verwendung von Partner Center-APIs finden Sie unter [Erstellen eines Abonnements für kommerzielle Marketplace-Produkte](/partner-center/develop/create-subscription-azure-marketplace-products).)

>[!IMPORTANT]
> Als Partner im CSP-Programm können Sie **Lizenz basierte** oder getaktete Saas  -Abonnements von ISV-Verlegern innerhalb von Partner Center erwerben. Dies bedeutet, dass Sie ein **Lizenz basiertes** **oder** getaktetes SaaS-Angebot erwerben können, das der ISV-Verleger zur Verfügung gestellt hat, einschließlich [exklusiver Angebote](csp-commercial-marketplace-discover.md#learn-about-marketplace-exclusive-offers) , auf die Sie Zugriff haben. Zum Erwerb oder zur Verwaltung anderer kommerzieller Marketplace-Angebote von ISVs (z. b. nutzungsbasierte Angebote mit Azure-Anwendungen, Containern oder VMS) müssen Sie zum [Azure-Portal](https://portal.azure.com/)wechseln.

## <a name="purchase-usage-based-subscriptions-in-the-azure-portal"></a>Nutzungsbasierte Abonnements im Azure-Portal erwerben

Im Gegensatz zu lizenzbasierten Saas-Abonnements von Drittanbieter-ISV-Verlegern erfordern nutzungsbasierte Abonnements zunächst, dass ein Kunde über ein Azure-Abonnement verfügt. Abrechnung für kommerziellen Marketplace, nutzungsbasierte Ressourcen fallen unter das Azure-Abonnement des Kunden. Sobald Ihr Kunde über ein Azure-Abonnement verfügt, kann ein Partner im CSP-Programm die folgenden Schritte ausführen, um ein kommerzielles Marketplace-Abonnement für Sie zu erwerben:

1. Melden Sie sich beim Partner Center- [Dashboard](https://partner.microsoft.com/dashboard)an, und wählen Sie im Menü auf der linken Seite die Option **Kunden** aus.

2. Wählen Sie den jeweiligen Kunden aus, und wählen Sie dann **Abonnements** aus.  

3. Wählen Sie unter **nutzungsbasierte Abonnements** die Option **alle Ressourcen** aus. Dadurch gelangen Sie zum Azure-Verwaltungs Portal.

4. Wählen Sie im Azure-Verwaltungs Portal im Menü auf der linken Seite **Ressource erstellen** aus.

5. Wählen Sie oben in der Liste Azure Marketplace die Option **alle** anzeigen aus.

6. Um die Liste einzugrenzen, verwenden Sie oben in der Marketplace-Liste Filter. Sie können z. b. **Microsoft** oder **Partner** in der Dropdown Liste **Herausgeber** auswählen, um nur Angebote von Microsoft oder von einem ISV-Verleger anzuzeigen.

7. Wählen Sie ein bestimmtes Angebot aus, und wählen Sie dann **Erstellen** aus.

## <a name="next-steps"></a>Nächste Schritte

- [Verwalten kommerzieller Marketplace-Angebote](csp-commercial-marketplace-purchase.md)