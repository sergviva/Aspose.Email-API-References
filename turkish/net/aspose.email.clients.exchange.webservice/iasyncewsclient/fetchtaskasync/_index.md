---
title: FetchTaskAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen görevi getirir.
type: docs
weight: 280
url: /tr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync/
---
## IAsyncEwsClient.FetchTaskAsync method

Belirtilen görevi getirir.

```csharp
public Task<ExchangeTask> FetchTaskAsync(string taskUri, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| taskUri | String | Bir görev uri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Geri dönüş değeri

bir getirildi[`ExchangeTask`](../../exchangetask)

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *taskUri* dır-dir`hükümsüz`veya`boş`. |

### Ayrıca bakınız

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->