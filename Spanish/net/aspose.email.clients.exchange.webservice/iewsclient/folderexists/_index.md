---
title: FolderExists
second_title: Referencia de la API de Aspose.Email para .NET
description: Comprueba si existe la carpeta especificada.
type: docs
weight: 870
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/folderexists/
---
## FolderExists(string, string) {#folderexists}

Comprueba si existe la carpeta especificada.

```csharp
public bool FolderExists(string parentFolderUri, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | Un uri de la carpeta principal. |
| folderName | String | Un nombre de carpeta. |

### Valor_devuelto

`verdadero` si la carpeta especificada existe en la carpeta principal especificada; de lo contrario,`falso`.

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*o*folderName* es`nulo`o`vacío` |

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## FolderExists(string, string, out ExchangeFolderInfo) {#folderexists_1}

Comprueba si existe la carpeta especificada.

```csharp
public bool FolderExists(string parentFolderUri, string folderName, out ExchangeFolderInfo folder)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| parentFolderUri | String | Un uri de la carpeta principal. |
| folderName | String | Un nombre de carpeta. |
| folder | ExchangeFolderInfo& | A[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo) que representa la información de la carpeta encontrada, si la carpeta existe. |

### Valor_devuelto

`verdadero` si la carpeta especificada existe en la carpeta principal especificada; de lo contrario,`falso`.

### Ver también

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->