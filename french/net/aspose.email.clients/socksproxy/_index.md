---
title: SocksProxy
second_title: Référence de l'API Aspose.Email pour .NET
description: Client proxy SOCKS. Les versions prises en charge du protocole sont SOCKS4 et SOCKS5.
type: docs
weight: 17100
url: /fr/net/aspose.email.clients/socksproxy/
---
## SocksProxy class

Client proxy SOCKS. Les versions prises en charge du protocole sont SOCKS4 et SOCKS5.

```csharp
public class SocksProxy : Proxy
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SocksProxy](socksproxy#constructor)(string, int) | Initialise une nouvelle instance du[`SocksProxy`](../socksproxy) classe pour se connecter au serveur SOCKS4 sans authentification. |
| [SocksProxy](socksproxy#constructor_1)(string, int, SocksVersion) | Initialise une nouvelle instance du[`SocksProxy`](../socksproxy) classe pour se connecter au serveur SOCKS4 ou SOCKS5 sans authentification. |
| [SocksProxy](socksproxy#constructor_2)(string, int, string) | Initialise une nouvelle instance du[`SocksProxy`](../socksproxy) classe pour se connecter au serveur SOCKS4 sans authentification. |
| [SocksProxy](socksproxy#constructor_3)(string, int, string, string) | Initialise une nouvelle instance du[`SocksProxy`](../socksproxy) classe pour se connecter au serveur SOCKS5 avec un nom d'utilisateur et un mot de passe définis. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Address](../../aspose.email.clients/proxy/address) { get; set; } | Le nom de domaine ou l'adresse IP du serveur proxy |
| [Password](../../aspose.email.clients/proxy/password) { get; set; } | Mot de passe pour l'authentification proxy |
| [Port](../../aspose.email.clients/proxy/port) { get; set; } | Le numéro de port du serveur proxy |
| [SupportedAuthenticationMethods](../../aspose.email.clients/socksproxy/supportedauthenticationmethods) { get; set; } | Les méthodes d'authentification prises en charge pour se connecter au serveur SOCKS |
| [Username](../../aspose.email.clients/proxy/username) { get; set; } | Nom d'utilisateur pour l'authentification proxy |
| [Version](../../aspose.email.clients/socksproxy/version) { get; set; } | Version du serveur SOCKS requise. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/proxy/dispose)() | Supprime cette instance et demande la fermeture de la connexion TCP sous-jacente. |
| [GetStream](../../aspose.email.clients/proxy/getstream)(string, int) | Renvoie le flux réseau configuré pour transporter les données vers l'hôte requis via le serveur proxy. |
| override [SetUpStream](../../aspose.email.clients/socksproxy/setupstream)(Stream, string, int) | Configure le serveur proxy pour transporter les données vers l'hôte cible. |

### Voir également

* class [Proxy](../proxy)
* espace de noms [Aspose.Email.Clients](../../aspose.email.clients)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->