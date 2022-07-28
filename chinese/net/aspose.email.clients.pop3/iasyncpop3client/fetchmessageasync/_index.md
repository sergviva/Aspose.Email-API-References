---
title: FetchMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 获取消息
type: docs
weight: 40
url: /zh/net/aspose.email.clients.pop3/iasyncpop3client/fetchmessageasync/
---
## FetchMessageAsync(string, IConnection, CancellationToken) {#fetchmessageasync_1}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, IConnection connection = null, 
    CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | String | 连接到服务器 |
| uniqueId | IConnection | 消息的唯一 ID |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

消息

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* 部件 [Aspose.Email](../../../)

---

## FetchMessageAsync(int, IConnection, CancellationToken) {#fetchmessageasync}

获取消息

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, IConnection connection = null, 
    CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | Int32 | 连接到服务器 |
| sequenceNumber | IConnection | 消息的序列号 |
| token | CancellationToken | 传播应该取消操作的通知。 |

### 返回值

消息

### 也可以看看

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* 命名空间 [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->