---
title: UpdateDelegate
second_title: Referencia de la API de Aspose.Email para .NET
description: Actualiza la configuración del usuario delegado a quien se le otorga acceso en el buzón especificado.
type: docs
weight: 1460
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/updatedelegate/
---
## IEWSClient.UpdateDelegate method

Actualiza la configuración del usuario delegado a quien se le otorga acceso en el buzón especificado.

```csharp
public void UpdateDelegate(ExchangeDelegateUser delegateUser, string mailbox)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| delegateUser | ExchangeDelegateUser | Una nueva configuración de usuario delegado. |
| mailbox | String | Un buzón en el que se concede acceso al usuario delegado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *delegateUser* es`nulo`. |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *mailbox* es`nulo`o`vacío`. |

### Ver también

* class [ExchangeDelegateUser](../../exchangedelegateuser)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->