---
title: SocksProxy
second_title: Aspose.Email för .NET API-referens
description: SOCKS proxy-klient. Stödda versioner av protokollet är SOCKS4 och SOCKS5.
type: docs
weight: 17100
url: /sv/net/aspose.email.clients/socksproxy/
---
## SocksProxy class

SOCKS proxy-klient. Stödda versioner av protokollet är SOCKS4 och SOCKS5.

```csharp
public class SocksProxy : Proxy
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SocksProxy](socksproxy#constructor)(string, int) | Initierar en ny instans av[`SocksProxy`](../socksproxy) klass för att ansluta till SOCKS4-server utan autentisering. |
| [SocksProxy](socksproxy#constructor_1)(string, int, SocksVersion) | Initierar en ny instans av[`SocksProxy`](../socksproxy) klass för att ansluta till SOCKS4- eller SOCKS5-server utan autentisering. |
| [SocksProxy](socksproxy#constructor_2)(string, int, string) | Initierar en ny instans av[`SocksProxy`](../socksproxy) klass för att ansluta till SOCKS4-server utan autentisering. |
| [SocksProxy](socksproxy#constructor_3)(string, int, string, string) | Initierar en ny instans av[`SocksProxy`](../socksproxy) klass för att ansluta till SOCKS5-servern med definierat användarnamn och lösenord. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address) { get; set; } | Domännamnet eller IP-adressen för proxyservern |
| [Password](../../aspose.email.clients/proxy/password) { get; set; } | Lösenord för proxyautentisering |
| [Port](../../aspose.email.clients/proxy/port) { get; set; } | Portnumret för proxyservern |
| [SupportedAuthenticationMethods](../../aspose.email.clients/socksproxy/supportedauthenticationmethods) { get; set; } | De autentiseringsmetoder som stöds för att ansluta till SOCKS server |
| [Username](../../aspose.email.clients/proxy/username) { get; set; } | Användarnamn för proxyautentisering |
| [Version](../../aspose.email.clients/socksproxy/version) { get; set; } | Obligatorisk SOCKS-serverversion. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose)() | Tar bort den här instansen och begär att den underliggande TCP-anslutningen ska stängas. |
| [GetStream](../../aspose.email.clients/proxy/getstream)(string, int) | Returnerar konfigurerad nätverksström för att transportera data till den nödvändiga värden via proxyservern. |
| override [SetUpStream](../../aspose.email.clients/socksproxy/setupstream)(Stream, string, int) | Konfigurerar proxyserver för att transportera data till målvärden. |

### Se även

* class [Proxy](../proxy)
* namnutrymme [Aspose.Email.Clients](../../aspose.email.clients)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->