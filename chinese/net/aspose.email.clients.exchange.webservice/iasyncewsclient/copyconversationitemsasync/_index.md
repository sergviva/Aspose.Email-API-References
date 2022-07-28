---
title: CopyConversationItemsAsync
second_title: Aspose.Email for .NET API 参考
description: 将位于指定文件夹中的会话项复制到指定目标文件夹
type: docs
weight: 70
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync/
---
## IAsyncEwsClient.CopyConversationItemsAsync method

将位于指定文件夹中的会话项复制到指定目标文件夹

```csharp
public Task CopyConversationItemsAsync(string conversationId, string destinationFolderId, 
    string contextFolderId = null, CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | 要复制的对话 ID |
| destinationFolderId | String | 复制项目的文件夹 ID |
| contextFolderId | String | 对话项目所在文件夹的 ID。注意:如果设置为 null（或 空），所有对话项目将被复制 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*is` null` 或` 空` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId*是` null` 或` 空` |

### 也可以看看

* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->