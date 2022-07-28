---
title: GetMailboxesAsync
second_title: Aspose.Email for .NET API 参考
description: 列出具有 smtp 地址的邮箱 注意返回联系人的最大数量为 100这是使用 EWS 操作的限制
type: docs
weight: 360
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getmailboxesasync/
---
## IAsyncEwsClient.GetMailboxesAsync method

列出具有 smtp 地址的邮箱。 注意:返回联系人的最大数量为 100。这是使用 EWS 操作的限制。

```csharp
public Task<Contact[]> GetMailboxesAsync(CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cancellationToken | CancellationToken | 取消令牌 |

### 返回值

代表联系信息的联系人

### 也可以看看

* class [Contact](../../../aspose.email.personalinfo/contact)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->