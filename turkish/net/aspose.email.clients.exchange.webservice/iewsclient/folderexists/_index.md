---
title: FolderExists
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen klasörün var olup olmadığını kontrol eder.
type: docs
weight: 870
url: /tr/net/aspose.email.clients.exchange.webservice/iewsclient/folderexists/
---
## FolderExists(string, string) {#folderexists}

Belirtilen klasörün var olup olmadığını kontrol eder.

```csharp
public bool FolderExists(string parentFolderUri, string folderName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün bir uri'si. |
| folderName | String | Bir klasör adı. |

### Geri dönüş değeri

`doğru` belirtilen klasör, belirtilen üst klasörde mevcutsa; aksi halde,`yanlış`.

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*veya*folderName* dır-dir`hükümsüz`veya`boş` |

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## FolderExists(string, string, out ExchangeFolderInfo) {#folderexists_1}

Belirtilen klasörün var olup olmadığını kontrol eder.

```csharp
public bool FolderExists(string parentFolderUri, string folderName, out ExchangeFolderInfo folder)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parentFolderUri | String | Üst klasörün bir uri'si. |
| folderName | String | Bir klasör adı. |
| folder | ExchangeFolderInfo& | A[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo) klasör varsa, bulunan klasör bilgilerini temsil eder. |

### Geri dönüş değeri

`doğru` belirtilen klasör, belirtilen üst klasörde mevcutsa; aksi halde,`yanlış`.

### Ayrıca bakınız

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->