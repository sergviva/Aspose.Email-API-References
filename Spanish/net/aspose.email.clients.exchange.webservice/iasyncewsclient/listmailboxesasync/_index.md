---
title: ListMailboxesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Enumera los buzones que tienen direcciones smtp. Nota el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada.
type: docs
weight: 440
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listmailboxesasync/
---
## IAsyncEwsClient.ListMailboxesAsync method

Enumera los buzones que tienen direcciones smtp. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada.

```csharp
public Task<MapiContactCollection> ListMailboxesAsync(string filter = null, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filter | String | Filtrar cadena |
| cancellationToken | CancellationToken | El token de cancelación |

### Valor_devuelto

A[`MapiContactCollection`](../../../aspose.email.mapi/mapicontactcollection) que representa la información de contacto

### Ver también

* class [MapiContactCollection](../../../aspose.email.mapi/mapicontactcollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->