---
title: MapiMessageFlags
second_title: Aspose.Email for .NET API 参考
description: MapiMessageFlags
type: docs
weight: 18430
url: /zh/net/aspose.email.mapi/mapimessageflags/
---
## MapiMessageFlags enumeration

MapiMessageFlags。

```csharp
[Flags]
public enum MapiMessageFlags : long
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| MSGFLAG_ZERO | `0` |  |
| MSGFLAG_READ | `1` | 消息被标记为已读。 |
| MSGFLAG_UNMODIFIED | `2` | 自第一次保存（如果未发送）或已交付（如果已发送）以来，该消息尚未被修改。 |
| MSGFLAG_SUBMIT | `4` | 由于调用 IMessage::SubmitMessage，消息被标记为发送。 消息存储提供者设置此标志；客户端具有只读访问权限。 |
| MSGFLAG_UNSENT | `8` | 消息仍在编写中。它已保存，但尚未发送。 |
| MSGFLAG_HASATTACH | `10` | 邮件至少有一个附件。 |
| MSGFLAG_FROMME | `20` | 接收消息的用户也是发送消息的用户。 |
| MSGFLAG_ASSOCIATED | `40` | MSGFLAG_ASSOCIATED。 |
| MSGFLAG_RESEND | `80` | 该消息包括一个带有未送达报告的重新发送操作请求。 |
| MSGFLAG_NOTIFYREAD | `100` | 发送消息的用户在收件人第一次阅读消息时请求通知。 |
| MSGFLAG_NOTIFYUNREAD | `200` | 当收件人在阅读之前删除它或消息对象过期时，发送消息的用户已请求通知。 |
| MSGFLAG_EVERREAD | `400` | 消息至少被阅读过一次。只要设置或清除MSGFLAG_READ标志，服务器就会设置或清除此标志。 |
| MSGFLAG_ORIGIN_X400 | `1000` | 传入消息通过 X.400 链接到达。 |
| MSGFLAG_ORIGIN_INTERNET | `2000` | 传入消息通过 Internet 到达。 |
| MSGFLAG_ORIGIN_MISC_EXT | `8000` | 传入消息通过 X.400 或 Internet 以外的外部链接到达。 |

### 也可以看看

* 命名空间 [Aspose.Email.Mapi](../../aspose.email.mapi)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->