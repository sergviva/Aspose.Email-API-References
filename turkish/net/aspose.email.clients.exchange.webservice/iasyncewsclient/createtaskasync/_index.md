---
title: CreateTaskAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen klasörde verilen görevi oluşturur.
type: docs
weight: 140
url: /tr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync/
---
## IAsyncEwsClient.CreateTaskAsync method

Belirtilen klasörde verilen görevi oluşturur.

```csharp
public Task<string> CreateTaskAsync(ExchangeTask task, string folder = null, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| task | ExchangeTask | Yaratmak için bir görev. |
| folder | String | Görevin oluşturulması gereken bir klasör. Dosya[`TasksUri`](../../../aspose.email.clients.exchange/exchangemailboxinfo/tasksuri) is varsayılan olarak kullanılır. |
| cancellationToken | CancellationToken | İptal belirteci. |

### istisnalar

| istisna | şart |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->