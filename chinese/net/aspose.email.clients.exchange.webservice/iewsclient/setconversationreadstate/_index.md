---
title: SetConversationReadState
second_title: Aspose.Email for .NET API 参考
description: 将会话项的读取状态设置为指定值
type: docs
weight: 1410
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/setconversationreadstate/
---
## SetConversationReadState(string, bool) {#setconversationreadstate}

将会话项的读取状态设置为指定值

```csharp
public void SetConversationReadState(string conversationId, bool isRead)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | 要更改的对话 ID |
| isRead | Boolean | 启用设置对话中项目的读取状态的标志。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*is` null` 或` 空` |

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## SetConversationReadState(string, string, bool) {#setconversationreadstate_1}

将位于指定文件夹中的对话项目的读取状态设置为指定值

```csharp
public void SetConversationReadState(string conversationId, string contextFolderId, bool isRead)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| conversationId | String | 要更改的对话 ID |
| contextFolderId | String | 对话项目所在文件夹的 ID。注意:如果设置为 null（或为空），所有对话项目都将被复制 |
| isRead | Boolean | 一个允许设置对话中项目的读取状态的标志。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId*is` null` 或` 空` |

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->