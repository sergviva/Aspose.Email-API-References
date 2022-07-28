---
title: UpdateDelegate
second_title: Aspose.Email per riferimento all'API .NET
description: Aggiorna le impostazioni dellutente delegato a cui è concesso laccesso alla cassetta postale specificata.
type: docs
weight: 1460
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/updatedelegate/
---
## IEWSClient.UpdateDelegate method

Aggiorna le impostazioni dell'utente delegato a cui è concesso l'accesso alla cassetta postale specificata.

```csharp
public void UpdateDelegate(ExchangeDelegateUser delegateUser, string mailbox)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| delegateUser | ExchangeDelegateUser | Nuove impostazioni dell'utente delegato. |
| mailbox | String | Una cassetta postale a cui è concesso l'accesso all'utente delegato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *delegateUser* è`nullo`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *mailbox* è`nullo`o`vuoto`. |

### Guarda anche

* class [ExchangeDelegateUser](../../exchangedelegateuser)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->