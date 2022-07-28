---
title: ComposeMail
second_title: Aspose.Email for .NET API 参考
description: ActiveSync 协议的 ComposeMail 命名空间
type: docs
weight: 1120
url: /zh/net/aspose.email.clients.activesync.transportlayer/composemail/
---
## ComposeMail enumeration

ActiveSync 协议的 ComposeMail 命名空间

```csharp
public enum ComposeMail
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| SendMail | `5` | SendMail 元素是 SendMail 命令请求和响应中的必需元素，它将 HTTP POST 的正文标识为包含 SendMail 命令（第 2.2.2.15 节）。 |
| SmartForward | `6` | SmartForward 元素是 SmartForward 命令请求和响应中的必需元素，它将 HTTP POST 的主体标识为包含 SmartForward 命令（第 2.2.2.17 节）。 |
| SmartReply | `7` | SmartReply 元素是 SmartReply 命令请求和响应中的必需元素，它将 HTTP POST 的正文标识为包含 SmartReply 命令（第 2.2.2.18 节）。 |
| SaveInSentItems | `8` | SaveInSentItems 元素指定消息的副本是否将存储在“已发送邮件”文件夹中。 |
| ReplaceMime | `9` | 指定客户端是否发送整个消息。 |
| Source | `11` | 包含有关源消息的信息。 |
| FolderId | `12` | 指定源消息的文件夹 ID，它在 FolderSync 命令响应消息中返回（第 2.2.2.4.2 节）。 |
| ItemId | `13` | 指定源消息的项目 ID，它在同步命令响应消息中返回（第 2.2.2.19.2 节）。 |
| LongId | `14` | 此元素指定源会议请求的长 ID，它在搜索命令响应消息中返回（第 2.2.2.14.2 节）。 |
| InstanceId | `15` | InstanceId 元素是 SmartForward 命令请求和 SmartReply 命令请求中 Source 元素的可选子元素，用于指定源项目的重复实例。 |
| Mime | `16` | 包含 MIME 编码的消息。 |
| ClientId | `17` | 指定客户端的唯一消息 ID (MID)。 |
| Status | `18` | 指示命令请求失败的原因。 |
| AccountId | `19` | 标识发送电子邮件的帐户。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->