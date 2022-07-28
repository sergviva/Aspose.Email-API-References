---
title: CreateConnection
second_title: Référence de l'API Aspose.Email pour .NET
description: Crée une nouvelle connexion indépendante pour les opérations non liées aux threads pas de connexion par défaut. Lappel de cette méthode est similaire à lappel de CreateConnectioncreateAsDefaultConnection  false Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode.
type: docs
weight: 280
url: /fr/net/aspose.email.clients/emailclient/createconnection/
---
## CreateConnection() {#createconnection}

Crée une nouvelle connexion indépendante pour les opérations non liées aux threads (pas de connexion par défaut). L'appel de cette méthode est similaire à l'appel de CreateConnection(createAsDefaultConnection = false) Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode.

```csharp
public virtual IConnection CreateConnection()
```

### Return_Value

Renvoie l'objet de connexion

### Voir également

* interface [IConnection](../../iconnection)
* class [EmailClient](../../emailclient)
* espace de noms [Aspose.Email.Clients](../../emailclient)
* Assemblée [Aspose.Email](../../../)

---

## CreateConnection(bool) {#createconnection_1}

Crée une nouvelle connexion (par défaut ou indépendante) pour les opérations. Veuillez consulter la documentation pour la propriété EmailClient.ConnectionAsgmtMode.

```csharp
public virtual IConnection CreateConnection(bool createAsDefaultConnection)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createAsDefaultConnection | Boolean | Indique si la connexion doit être créée par défaut pour le thread actuel |

### Return_Value

Renvoie l'objet de connexion

### Voir également

* interface [IConnection](../../iconnection)
* class [EmailClient](../../emailclient)
* espace de noms [Aspose.Email.Clients](../../emailclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->