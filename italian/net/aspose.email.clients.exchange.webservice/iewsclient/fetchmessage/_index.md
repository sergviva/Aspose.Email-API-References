---
title: FetchMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera il messaggio.
type: docs
weight: 810
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/fetchmessage/
---
## FetchMessage(string) {#fetchmessage}

Recupera il messaggio.

```csharp
public MailMessage FetchMessage(string messageUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageUri | String | L'URI del messaggio. |

### Valore di ritorno

Restituisce un messaggio

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## FetchMessage(string, IEnumerable&lt;PropertyDescriptor&gt;) {#fetchmessage_1}

Recupera il messaggio dal server

```csharp
public MailMessage FetchMessage(string messageUri, 
    IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageUri | String | L'URI del messaggio |
| extendedProperties | IEnumerable`1 | Un'enumerazione di proprietà estese |

### Valore di ritorno

[`MailMessage`](../../../aspose.email/mailmessage) che rappresenta il messaggio di posta elettronica, se sono state trovate e impostate proprietà personalizzate è possibile accedervi utilizzando[`Headers`](../../../aspose.email/mailmessage/headers) collezione.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *messageUri* è`nullo`o`vuoto` |
| [ExchangeException](../../../aspose.email/exchangeexception) | Impossibile recuperare il messaggio |

### Guarda anche

* class [MailMessage](../../../aspose.email/mailmessage)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->