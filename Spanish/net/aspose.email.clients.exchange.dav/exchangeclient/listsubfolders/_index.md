---
title: ListSubFolders
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene la colección de carpetas públicas secundarias de parent
type: docs
weight: 310
url: /es/net/aspose.email.clients.exchange.dav/exchangeclient/listsubfolders/
---
## ListSubFolders(ExchangeFolderInfo) {#listsubfolders}

Obtiene la colección de carpetas públicas secundarias de parent

```csharp
public ExchangeFolderInfoCollection ListSubFolders(ExchangeFolderInfo parentFolder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolder | ExchangeFolderInfo | El padre[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo) |

### Valor_devuelto

[`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection) que contiene subcarpetas de la carpeta principal

### Ver también

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

---

## ListSubFolders(string) {#listsubfolders_1}

Obtiene la colección de carpetas secundarias de parent

```csharp
public ExchangeFolderInfoCollection ListSubFolders(string parentFolderUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | El uri de la carpeta principal |

### Valor_devuelto

[`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection) que contiene subcarpetas de la carpeta principal

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri* es`nulo`o`vacío` |

### Ver también

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* class [ExchangeClient](../../exchangeclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->