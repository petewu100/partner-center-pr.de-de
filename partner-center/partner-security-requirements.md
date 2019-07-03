---
title: Sicherheitsanforderungen für Partner | Partner Center
ms.topic: article
ms.date: 06/25/2019
description: Erfahren Sie, bis die sicherheitsanforderungen für Berater und Partner, die Teilnahme am Cloud Solution Provider-Programm.
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, Cloud Solution Provider, Cloud Solution Provider programmieren, CSP, Hersteller des Steuerelements-Panel, CPV, Multi-Factor-Authentication, MFA, secure-Anwendungsmodell, sicher app-Modell, Sicherheit
ms.localizationpriority: medium
ms.openlocfilehash: de1452ce14c8343e2e05dcc65a7a6c05259576c5
ms.sourcegitcommit: ca7f000a58575fa9a089693256c095120dde3c5d
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/24/2019
ms.locfileid: "67346999"
---
# <a name="partner-security-requirements"></a>Sicherheitsanforderungen für Partner

**Zielgruppe**

- Alle Partner im Cloud Solution Provider-Programm
  - Online-Dienst
  - Indirekte Anbieter
  - Indirekter Wiederverkäufer
- Alle Anbieter von ASP.NET-Steuerelementen-Bereich
- Alle Ratgeber.

Sicherheit und Schutz von Kunden und Partner sind obersten Prioritäten von Microsoft. Wir weiterhin eine zunehmende Anzahl von komplexere Sicherheitsangriffe, die in erster Linie mit gefährdete Identitäten verknüpft. Wie vorbeugende Maßnahmen zu ergreifen Steuerelemente eine wichtige Rolle in einer umfassenden Defense Strategie zum Verhindern von Angriffen spielen, beginnen wir erzwingen eine Reihe von obligatorischen sicherheitsanforderungen für die von Partnern und Kunden zu schützen.

> [!NOTE]
> Es wird dringend empfohlen, dass alle Partner, die Transaktion mit einer unabhängigen Cloud (21vianet betriebene, Deutschland und US Government) reagieren und diese neuen sicherheitsanforderungen sofort übernehmen. Diese Partner sind jedoch nicht erforderlich, für die neue effektive am 1. Juli sicherheitsanforderungen. Microsoft bietet weitere Details in Bezug auf die Erzwingung von diesen sicherheitsanforderungen für sovereign Clouds in der Zukunft.

## <a name="overview-of-the-requirements"></a>Übersicht über die Anforderungen

Alle Partner, die berücksichtigt werden, in der Cloud Solution Provider-Programm, Anbieter von ASP.NET-Steuerelementen Bereich und Advisor-Partner sind zum Erzwingen der Multi-Factor Authentication (MFA) für jeden Benutzer in ihrem partnermandanten erforderlich. Dies ist möglich durch Aktivieren der zwei [Richtlinien für Azure Active Directory-Baseline](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-baseline-protection). Baseline-Richtlinien sind eine Reihe von vordefinierten Richtlinien, mit denen Organisationen mit vielen gängigen Angriffen zu schützen. Diese allgemeinen Angriffen zählen Kennwort Sprühende, Wiedergabe und Phishing. Baseline-Richtlinien stehen in allen Editionen von Azure Active Directory zur Verfügung. Microsoft stellt diese Baseline-Schutzrichtlinien für alle Benutzer zur Verfügung, da Identität basierende Angriffe nimmt in den letzten Jahren wurden.

Die zwei basisoption für Richtlinien, die aktiviert werden soll, werden in der folgenden Tabelle beschrieben.

|**Richtlinie**| |
|-----|-----|
|**Erfordern von MFA für Administratoren**|Aktivieren das erfordern von MFA für die Richtlinie für Administratoren, benötigen Benutzer in Administratorrollen für MFA über die Authenticator-App zu registrieren. Sobald MFA-Registrierung abgeschlossen ist, müssen Administratoren führen Sie die MFA jedes Mal, wenn sie sich anmelden.|
|**Endbenutzer-Schutz**|Endbenutzer-Schutz ist eine benutzerrisiko basierenden MFA Baseline-Richtlinie, die von allen Benutzern in einem Verzeichnis geschützt. Durch Aktivieren dieser Richtlinie erfordert, dass alle Benutzer für MFA über die Authenticator-App zu registrieren. Benutzer können die MFA-Registrierung Eingabeaufforderung 14 Tage lang, ignorieren, nach denen sie blockiert werden an der Anmeldung, bis sie für MFA zu registrieren. Nach der Registrierung für MFA werden Benutzern nur während der riskanten Anmeldeversuche für MFA aufgefordert. Kompromittierte Benutzerkonten werden blockiert, bis ihr Kennwort zurückgesetzt, und Risikoereignisse geschlossen wurde haben.|

Wenn diese Richtlinien aktiviert sind, werden jeder Benutzer in Azure MFA ohne zusätzliche Kosten nutzen können. Wenn Sie eine Drittanbieter-Lösung verwenden, müssen Sie MFA für jeden Benutzer zu erzwingen, wenn Microsoft Commercial-Cloud-Dienste zugreifen.

> [!IMPORTANT]
> Da der MFA für jeden Benutzer im Partnerverzeichnis erzwungen wird, werden Auswirkungen auf Automatisierung oder Integration, die Anmeldeinformationen des Benutzers verwendet. Um diese Auswirkungen zu beheben, die Sie benötigen, ändern Sie die Methode verbindet sich Ihre Automatisierung oder die Integration mit kommerziellen Microsoft-Clouddiensten. Wenn der Dienst, der Sie eine Verbindung mit unterstützt tokenbasierte Authentifizierung, es wird empfohlen, die Sie implementieren die [Secure-Anwendungsmodell-Framework](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model).

## <a name="what-actions-do-i-need-to-take"></a>Welche Aktionen werden benötigen? 

Um sicherzustellen, dass jeder Benutzer in der Partner geschützt ist, müssen Sie aktivieren die [erfordern von MFA für Administratoren](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-administrators) und [Endbenutzer Protection](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-end-users) basisoption für Richtlinien. Vor dem Aktivieren dieser Richtlinien, ist es wichtig zu verstehen, was sie tun und wie sie Automatisierung oder Integration und Ihre Benutzer auswirken.

### <a name="considerations"></a>Überlegungen

Da die sicherheitsanforderungen für alle Benutzer in einem Partnerverzeichnis angewendet werden, müssen verschiedene Aspekte im Zusammenhang vorgenommen werden, um sicherzustellen, dass eine reibungslose Bereitstellung ein. Diese Überlegungen gehört das Identifizieren von Benutzern in Azure Active Directory, die nicht oder sollten nicht ausführen, MFA, als auch Anwendungen und Clients, die von Ihrer Organisation verwendet, die keine modernen Authentifizierung unterstützen.

#### <a name="legacy-protocols"></a>Ältere Protokolle

Ältere Authentifizierungsprotokolle (IMAP, SMTP, POP3, usw.) werden von e-Mail-Clients verwendet, um authentifizierungsanforderungen zu machen. Diese Protokolle bieten keine Unterstützung für MFA. Die meisten der kompromittierten Konten angezeigt, die von Microsoft werden durch risikoteilnehmer ausführen Angriffe auf ältere Protokolle, die versuchen, die MFA zu umgehen, verursacht. Um sicherzustellen, dass die MFA erforderlich ist, bei der Anmeldung an einem Konto in ein Partnerverzeichnis und risikoteilnehmer sind nicht in der Lage, die MFA zu umgehen, werden diese sicherheitsanforderungen alle authentifizierungsanforderungen über ältere Protokolle blockiert.

### <a name="enabling-the-baseline-policies"></a>Aktivieren die basisoption für Richtlinien

Finden Sie unter den [implementieren die Partner Sicherheit Anforderungen Tutorial](tutorials/partner-security-requirements.yml) für eine Einführung in Bezug auf die Implementierung der Baselinerichtlinien.  

#### <a name="require-mfa-for-admins"></a>Erfordern von MFA für Administratoren

Die *erfordern von MFA für Administrator* Basisrichtlinie erfordert MFA für die folgenden verzeichnisrollen, als die am häufigsten privilegierten Azure Active Directory-Rollen:

- Globaler Administrator
- SharePoint-administrator
- Exchange-administrator
- Administrator für bedingten Zugriff
- Sicherheitsadministrator
- Helpdesk-Administrator / kennwortadministrator
- Rechnungsadministrator
- Benutzeradministrator

Beim Aktivieren der erfordern von MFA für Administratoren Richtlinie, die oben genannten neun Administratorrollen müssen für die Authenticator-App mit MFA zu registrieren. Sobald MFA-Registrierung abgeschlossen ist, müssen Administratoren, die MFA jedes Mal auszuführen, das Sie sich, das anmelden.

Verfügt Ihre Organisation diese Konten in Skripts oder Code verwendet, beachten Sie, und Ersetzen Sie dabei mit [verwaltet Identitäten](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview).

So aktivieren Sie diese Richtlinie, und schützen Ihre Administratoren:

1. Melden Sie sich bei der **Azure-Portal** als globaler Administrator, Sicherheitsadministrator oder Administrator für bedingten Zugriff.
2. Navigieren Sie zu **Azure Active Directory** > **für den bedingten Zugriff**.
3. Wählen Sie in der Liste der Richtlinien, **Basisrichtlinie: Erfordern von MFA für Administratoren**.
4. Legen Sie **Richtlinie aktivieren** zu **Richtlinie sofort verwenden**.
5. Klicken Sie auf **speichern**.

    ![Erfordern von MFA für Administratoren](images/security/baseline-policy-require-mfa-for-admins.png)

> [!WARNING]
> Bevor Sie diese Richtlinie aktivieren, stellen Sie sicher, dass die Benutzer die ältere Authentifizierungsprotokolle nicht verwenden. Finden Sie im Artikel [Vorgehensweise: Block ältere Authentifizierung mit Azure Active Directory mit dem bedingten Zugriff](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use) für Weitere Informationen.

> [!IMPORTANT]
> Es ist ein bekanntes Problem, die Ihre Fähigkeit zum Verbinden mit Exchange Online-PowerShell mit Administratorrechten für delegierte wirkt sich auf. Finden Sie unter den [Exchange Online-PowerShell](#exchange-online-powershell) bekanntes Problem, bevor Sie diese Richtlinie aktivieren, wenn Sie die Verwendung dieses PowerShell-Moduls.

#### <a name="end-user-protection"></a>Endbenutzer-Schutz

Die Endbenutzer Baseline Schutzrichtlinie schützt alle Benutzer in einem Verzeichnis. Durch Aktivieren dieser Richtlinie erfordert, dass alle Benutzer innerhalb von 14 Tagen für Azure MFA registriert. Nach der Registrierung werden Benutzern nur während der riskanten Anmeldeversuche für MFA aufgefordert. Kompromittierte Benutzerkonten werden blockiert, bis das Kennwort zurücksetzen und Kündigung besteht das Risiko.

Die Richtlinie **Basisrichtlinie: Schutz der Endbenutzer** ist vorkonfiguriert und wird am Anfang angezeigt, wenn Sie zum Blatt für den bedingten Zugriff im Azure-Portal navigieren.

So aktivieren Sie diese Richtlinie, und Ihre Benutzer schützen:

1. Melden Sie sich bei der **Azure-Portal** als globaler Administrator, Sicherheitsadministrator oder Administrator für bedingten Zugriff.
2. Navigieren Sie zu **Azure Active Directory** > **für den bedingten Zugriff**.
3. Wählen Sie in der Liste der Richtlinien, **Basisrichtlinie: Endbenutzer Protection (Vorschau)** .
4. Legen Sie **Richtlinie aktivieren** zu **Richtlinie sofort verwenden**.
5. Klicken Sie auf **speichern**.

    ![Endbenutzer-Schutz](images/security/baseline-policy-end-user-protection.png)

> [!WARNING]
> Bevor Sie diese Richtlinie aktivieren, stellen Sie sicher, dass die Benutzer die ältere Authentifizierungsprotokolle nicht verwenden. Finden Sie im Artikel [Vorgehensweise: Block ältere Authentifizierung mit Azure Active Directory mit dem bedingten Zugriff](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-baseline-protect-legacy-auth#identify-legacy-authentication-use) für Weitere Informationen.

> [!IMPORTANT]
> Es gibt eine bekannte Probleme, die Ihre Fähigkeit zum Verbinden mit Exchange Online-PowerShell mit Administratorrechten für delegierte wirkt sich auf. Finden Sie unter den [Exchange Online-PowerShell](#exchange-online-powershell) bekanntes Problem, bevor Sie diese Richtlinie aktivieren, wenn Sie die Verwendung dieses PowerShell-Moduls.

## <a name="common-issues"></a>Allgemeine Probleme

### <a name="azure-active-directory"></a>Azure Active Directory

#### <a name="aadsts50076"></a>AADSTS50076

Nach der Aktivierung die basisoption für Richtlinien, können Sie feststellen, dass Ihre Automatisierung oder Integration ähnlich der folgenden Ausnahme aufgetreten ist

    AADSTS50076: Due to a configuration change made by your administrator, or because you moved to a new location, you must use multi-factor authentication to access 'MyApp'.

Der Grund für diese Ausnahme ist, dass Sie die Authentifizierung mit Benutzeranmeldeinformationen und MFA jetzt ist erforderlich. Um diese Ausnahme zu beheben, müssen Sie ein Zugriffstoken für die Authentifizierung zu verwenden. Finden Sie unter den [Secure-Anwendungsmodell-Handbuch](http://assetsprod.microsoft.com/secure-application-model-guide.pdf) für Weitere Informationen.

>[!IMPORTANT]
>Die meisten modernen-APIs und PowerShell-Module unterstützt die Möglichkeit, ein Zugriffstoken für die Authentifizierung zu verwenden. Es gibt jedoch einige, die diese Funktion derzeit nicht unterstützt. Hiermit wird eine Nachricht bei Bedarf bei der Entscheidung, wenn das Modul-API oder PowerShell Sie versuchen, nutzen Sie unterstützt die Verwendung eines Zugriffstokens für die Authentifizierung, klicken Sie dann auf die [Partner Center Anleitungen Sicherheitsgruppe](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) Community.

#### <a name="aadsts700082"></a>AADSTS700082

Nachdem Sie das Anwendungsmodell Secure-Framework implementiert haben besteht die Möglichkeit, die Sie die folgende Ausnahme erhalten 90 Tage nach dem Generieren des ursprünglichen aktualisierungstokens, das

    The refresh token has expired due to inactivity. The token was issued on 2019-01-02T09:19:53.5422744Z and was inactive for 90.00:00:00

In Bezug auf Azure Active Directory ist die maximale Lebensdauer für eine Aktualisierung Token 90 Tage. Um diesen Fehler zu beheben, müssen Sie zum Generieren und ein neues Aktualisierungstoken sicher zu speichern. Beachten Sie, dass es ist möglich, das Aktualisierungstoken, das programmgesteuert aktualisiert werden, da mit jeder Anforderung an Azure Active Directory für ein Zugriffstoken für den ein neues Aktualisierungstoken zurückgegeben wird. Sie können die entsprechende Logik, um das sicher gespeicherte Aktualisierungstoken, das zu aktualisieren, bevor es abläuft, implementieren.

Finden Sie unter [konfigurierbare tokengültigkeitsdauern in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) für Weitere Informationen.

## <a name="known-issues"></a>Bekannte Probleme

### <a name="exchange-online-powershell"></a>Exchange Online-PowerShell

Wenn MFA aktiviert ist werden Partner nicht ihre delegierte Administratorrechte mit Exchange Online-PowerShell zum Ausführen von Aktionen für ihre Kunden nutzen können. Finden Sie unter [Herstellen einer Verbindung mit Exchange Online-PowerShell Multi-Factor Authentication](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell) für Weitere Informationen zu dieser Einschränkung.

## <a name="resources-and-support"></a>Ressourcen und support

Durch die [Partner Center Anleitungen Sicherheitsgruppe Community](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) können Sie zusätzliche Ressourcen finden und erfahren Sie mehr über bevorstehende Ereignisse wie z. B. technische Office Stunden. Finden Sie unter den [häufig gestellte Fragen](http://assetsprod.microsoft.com/security-requirements-faq.pdf) Dokument Weitere Informationen zu den Anforderungen.

### <a name="developers"></a>Entwickler

- [Aktivieren das Modell für die sichere Anwendung](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)
- [Partner Center-Beispiele für .NET](https://github.com/microsoft/partner-center-dotnet-samples)
- [Partner Center-Java-Beispiele](https://github.com/microsoft/partner-center-java-samples)
- [Implementieren das Modell für die sichere Anwendung Partner Center-PowerShell](https://docs.microsoft.com/powershell/partnercenter/secure-app-model)