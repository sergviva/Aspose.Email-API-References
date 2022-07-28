---
title: ResolveContacts
second_title: Referencia de la API de Aspose.Email para .NET
description: Resuelve nombres ambiguos para mostrar en los buzones. Nota el recuento máximo de contactos devueltos es 100. Esta es una restricción del comando de intercambio usado.
type: docs
weight: 1370
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/resolvecontacts/
---
## ResolveContacts(string) {#resolvecontacts}

Resuelve nombres ambiguos para mostrar en los buzones. Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción del comando de intercambio usado.

```csharp
public Contact[] ResolveContacts(string unresolvedEntry)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| unresolvedEntry | String | Un nombre de contacto para resolver. |

### Valor_devuelto

una matriz de[`Contact`](../../../aspose.email.personalinfo/contact) objetos.

### Ver también

* class [Contact](../../../aspose.email.personalinfo/contact)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## ResolveContacts(string, ExchangeListContactsOptions) {#resolvecontacts_1}

Resuelve direcciones de correo electrónico ambiguas y nombres para mostrar Nota: el recuento máximo de contactos devueltos es 100. Esta es una restricción de la operación EWS utilizada.

```csharp
public Contact[] ResolveContacts(string unresolvedEntry, ExchangeListContactsOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| unresolvedEntry | String | Un nombre de contacto para resolver |
| options | ExchangeListContactsOptions | Enumera las opciones de la lista de contactos |

### Valor_devuelto

Contactos que representa información de contactos

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *unresolvedEntry* es`nulo`o`vacío` |

### Ver también

* class [Contact](../../../aspose.email.personalinfo/contact)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->