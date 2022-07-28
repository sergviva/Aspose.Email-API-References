---
title: UndeleteMessageAsync
second_title: Aspose.Email for .NET API 参考
description: 将具有指定序列号的消息标记为未删除
type: docs
weight: 400
url: /zh/net/aspose.email.clients.imap/iasyncimapclient/undeletemessageasync/
---
## UndeleteMessageAsync(int, long, IConnection, CancellationToken) {#undeletemessageasync}

将具有指定序列号的消息标记为未删除

```csharp
public Task UndeleteMessageAsync(int sequenceNumber, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | Int32 | 连接到服务器 |
| sequenceNumber | Int64 | 消息的序列号 |
| modificationSequence | IConnection | 修改序列。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* 部件 [Aspose.Email](../../../)

---

## UndeleteMessageAsync(string, long, IConnection, CancellationToken) {#undeletemessageasync_1}

将具有指定序列号的消息标记为未删除。

```csharp
public Task UndeleteMessageAsync(string uniqueId, long modificationSequence = 0, 
    IConnection connection = null, CancellationToken token = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| connection | String | 连接到服务器 |
| uniqueId | Int64 | 唯一 ID消息的 |
| modificationSequence | IConnection | 修改序列。请阅读更多 https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | 传播应取消操作的通知。 |

### 也可以看看

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* 命名空间 [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->