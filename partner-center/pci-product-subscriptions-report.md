---
title: Bericht über Partner Center Insights-Abonnements
ms.topic: article
ms.date: 05/19/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Sehen Sie sich an, was Sie gut machen und wo Sie die cloudabonnements verbessern können, die Sie für Ihre Kunden verkaufen oder verwalten.
author: shthota77
ms.author: shthota
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: 8df91ec4072b1873a240d42fa2382ebcc00b9bc5
ms.sourcegitcommit: 5f31146f50e01dc4c1922e0a5bc369f0a3cd8162
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/01/2020
ms.locfileid: "89220328"
---
# <a name="product-subscriptions-report-available-from-the-partner-center-insights-dashboard"></a>Bericht "Produkt Abonnements" im Partner Center Insights-Dashboard verfügbar

**Geeignete Rollen**
- Globaler Administrator
- Administrator-Agent
- Berichtanzeige
- Executive Report Viewer

Der Bericht zu den Produkt Abonnements enthält Analysen zu cloudabonnements, die Sie verkauft haben oder die Sie für Ihre Kunden verwalten. Dabei handelt es sich um einen produktspezifischen Bericht, der die Leistung von Abonnements umfasst, die cloudprodukten wie Office 365, Azure, Dynamics usw. zugeordnet sind.

Die folgenden Abschnitte finden Sie im Bericht zu Produkt Abonnements.

- Zusammenfassung
- Geografische Verteilung von Abonnements
- Trend zum Hinzufügen/Abgleichen von Abonnements
- Abonnement Verteilung nach Partnerstandorten, Vertriebskanal, SKUs, anfügetyp für Partner, Segment
- Trend nach Abonnement Zuständen
- Produkt Trend

 > [!NOTE]
 > Dieser Bericht ist über das Insights-Dashboard verfügbar. Zum Anzeigen dieses Berichts müssen Sie eine bestimmte Rolle im Partner Center zuweisen, z. b. globaler Administrator, Konto Administrator, Berichts-Viewer oder Executive Report Viewer. Weitere Informationen finden Sie unter der globale Administrator Ihres Unternehmens. bestimmte Datentypen in diesem Bericht sind möglicherweise auch nur für Benutzer verfügbar, die über Administratorrechte für Berichte verfügen.

## <a name="summary"></a>Zusammenfassung

Der Abschnitt Zusammenfassung enthält eine Momentaufnahme Ansicht der KPIs (Key Performance Indicator), die sich auf Abonnements beziehen, die von Ihnen für Ihre Kunden verkauft oder verwaltet werden.  

:::image type="content" source="images/pci/pci-sub-report-summary-1.png" alt-text="Zusammenfassung der Abonnement Berichte":::

Weitere Informationen zu den einzelnen Abschnitten der Zusammenfassung finden Sie unten.

- Abonnements:
  - Aktuelle Anzahl der cloudproduktabonnements, die von Ihnen verkauft oder verwaltet werden.
  - Prozentualer Zuwachs oder ablehnen von Abonnements während des ausgewählten Datums Bereichs.
  - Das Micro-Diagramm zeigt einen Monat-für-Monat-Trend der Abonnement Anzahl während des ausgewählten Datums Bereichs.

- Aktive Abonnements:
  - Aktuelle Anzahl der cloudabonnements, bei der die aktive Verwendung basierend auf Produkt Telemetrie gemessen wird. Dies schließt alle Test Abonnements im Fall von Azure-Abonnements aus.
  - Prozentualer Zuwachs oder Rückgang aktiver Abonnements im ausgewählten Zeitraum.
  - Das Micro-Diagramm zeigt einen Monat-für-Monat-Trend aktiver Abonnements während des ausgewählten Datums Bereichs.

- Hinzugefügte Abonnements:
  - Gesamte Kunden Abonnements, die während des ausgewählten Datums Bereichs von Ihnen hinzugefügt (verkauft oder verwaltet) werden. Neue Abonnements mit dem Status " **aktiv** " oder " **erneuert** " werden als Abonnements gezählt.
  - Der Prozentsatz der im letzten vollen Monat hinzugefügten Abonnements im Vergleich zum ersten vollen Monat.
  - Das Micro-Diagramm zeigt einen monatlichen Trend der Abonnements, die während des ausgewählten Datums Bereichs hinzugefügt wurden.

- Abonnements:
  - Gesamtanzahl der Kunden Abonnements, die während des ausgewählten Datums Bereichs über den Zeitraum Abonnements, deren Status in diesem Monat **aufgeh** oben oder **angeh** alten wurde, werden als ein Änderungs Abonnement gezählt.  
  - Prozentsatz der Abonnements, die im ausgewählten Datumsbereich angegeben wurden.
  - Das Micro-Diagramm zeigt einen monatlichen Trend der Abonnements, die im ausgewählten Datumsbereich angezeigt werden.

- Abonnements nach Produkten: Aufschlüsselung der aktuellen Abonnement Anzahl nach cloudprodukten.

## <a name="geographical-spread-of-subscriptions"></a>Geografische Verteilung von Abonnements

In der Ansicht " **Abonnements nach Geografie** " wird die geografische Verteilung der Gesamt Abonnements nach kundenmärkten angezeigt. Der gesamte Abonnement Betrag umfasst sowohl verkaufte Abonnements als auch aktive Abonnements.

In der Tabelle " **Länder/Region** " werden die Gesamtanzahl der Länder/Regionen, in denen Sie Abonnements haben, sowie der Betrag pro Land der Gesamt-und aktiven Abonnements angezeigt.

Sie können ein Land im Raster suchen und auswählen, um an den Ort in der Karte zu zoomen. Drücken Sie die **Start** Option in der Karte, um zur ursprünglichen Ansicht zurückzukehren. Zeigen Sie auf die Karte, um alle Abonnements und aktiven Abonnements nach Land anzuzeigen. Beide Felder im Raster sind sortierbar.

:::image type="content" source="images/pci/pci-sub-report-sub-by-geography-2.png" alt-text="Abonnements nach Geografie":::

## <a name="subscription-addschurns"></a>Hinzufügungen/Abwanderung von Abonnements

Diese Ansicht zeigt einen Trend von Abonnements. Diese werden für den ausgewählten Datumsbereich in verschiedene Kategorien unterteilt (neu, vorhandene, Änderungen). Die X-Achse stellt Monate des ausgewählten Datums Bereichs dar. Die Y-Achse stellt die Anzahl der Abonnements dar. Versennte Abonnements werden auf der negativen Skala der Y-Achse dargestellt. 

Das gestapelte Säulendiagramm zeigt eine Aufschlüsselung neuer, vorhandener und Änderungs Abonnements für den Monat. Sie können das Säulendiagramm neu erstellen, wobei Sie mit bestimmten Stapel Elementen aufgeschlüsselt sind. Wählen Sie zu diesem Zweck die einzelnen Elemente in der Legende aus. Sie können auch den Schieberegler oberhalb des Diagramms nutzen, um einen bestimmten Zeitraum zu vergrößern.

:::image type="content" source="images/pci/pci-sub-report-sub-adds-churns-3.png" alt-text="Hinzufügungen und Änderungen von Abonnements":::

## <a name="subscription-distribution"></a>Abonnement Verteilung

Diese Ansicht zeigt eine Aufschlüsselung Ihrer aktuellen Abonnements durch ihre MPN-Standorte, Kundensegmente, Vertriebskanäle/Azure-Preismodell und den Zuweisungs Typen (z. b. dpor, DAP usw.). Klicken Sie auf die entsprechenden Registerkarten, um die Aufteilung nach diesen Kategorien anzuzeigen. Um das Kreis Diagramm mit einer Aufschlüsselung bestimmter Element Kategorien zu erstellen, wählen Sie die Element Kategorien in der Legende aus.

:::image type="content" source="images/pci/pci-sub-report-distribution-4.png" alt-text="Abonnement Verteilung":::

## <a name="subscription-state-distribution"></a>Verteilung des Abonnement Status

Diese Ansicht zeigt die Verteilung Ihrer aktuellen Kunden Abonnements nach Abonnement Zustand oder-Status. Dies schließt die folgenden Abonnement Zustände ein: **aktiv**, deaktiviert **, bereitgestellt,** **offen**, **ingraceperiod**, **Closed**und **andere**. **Disabled**

:::image type="content" source="images/pci/pci-sub-report-sub-states-5.png" alt-text="Verteilung des Abonnement Status":::

## <a name="products-trend"></a>Produkt Trend

In dieser Ansicht werden ein Balkendiagramm und zwei Kreis Diagramme angezeigt. Das Balkendiagramm zeigt einen monatlichen Trend von Abonnements, die von kommerziellen Produkten wie Azure, Office, Dynamics usw. aufgeschlüsselt sind.

In den beiden Kreis Diagrammen wird eine Aufschlüsselung Ihrer aktuellen Kunden Abonnements angezeigt. Das erste Kreis Diagramm gliedert Abonnements nach Produkten. Das zweite Kreis Diagramm gliedert Abonnements nach SKUs oder Plänen. Wenn Sie im Kreis Diagramm "Aufschlüsselung **nach Produkten** " ein Produkt auswählen, wird im angrenzenden Kreis Diagramm eine Aufschlüsselung der Abonnements dieses Produkts nach SKUs angezeigt.

:::image type="content" source="images/pci/pci-sub-report-prods-trend-6.png" alt-text="Produkt Trend":::

> [!NOTE]
 > Die von SKUs aufgeschlüsselt Abonnement Anzahl entspricht möglicherweise nicht immer der Gesamtanzahl der Abonnements für dieses Produkt. Dies kann vorkommen, wenn ein Kunde mehrere SKUs im gleichen Produkt Abonnement gekauft hat.

## <a name="next-steps"></a>Nächste Schritte

- Weitere Berichte finden Sie unter [Partner Center Insights](partner-center-insights.md).

>[!NOTE] 
> Sie können die Rohdaten, die diesen Bericht über den Abschnitt Berichte herunterladen im Insights-Dashboard herunterladen. [Weitere Informationen](pci-download-reports.md) 
