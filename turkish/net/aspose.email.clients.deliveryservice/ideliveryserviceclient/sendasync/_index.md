---
title: SendAsync
second_title: Aspose.Email for .NET API Referansı
description: Eşzamansız olarak e-posta gönderir
type: docs
weight: 20
url: /tr/net/aspose.email.clients.deliveryservice/ideliveryserviceclient/sendasync/
---
## IDeliveryServiceClient.SendAsync method

Eşzamansız olarak e-posta gönderir

```csharp
public Task<DeliveryServiceResponse<MailMessage>> SendAsync(MailMessage message, 
    List<string> tags = null, CancellationToken? token = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |
| tags | List`1 |  |
| token | Nullable`1 |  |

### Ayrıca bakınız

* class [DeliveryServiceResponse&lt;T&gt;](../../deliveryserviceresponse-1)
* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IDeliveryServiceClient](../../ideliveryserviceclient)
* ad alanı [Aspose.Email.Clients.DeliveryService](../../ideliveryserviceclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->