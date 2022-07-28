---
title: StartTime
second_title: Aspose.Email for .NET API 参考
description: 标识客户端请求的空闲/忙碌时间跨度的开始 协议版本为 12.1 时不支持 StartTime 如果请求中包含可用性则请求还必须包含开始时间和结束时间 如果客户端发送无效的 StartTime 值则服务器在 ResolveRecipients 命令响应中返回状态值 5
type: docs
weight: 30
url: /zh/net/aspose.email.clients.activesync.transportlayer/resolverecipientsavailabilityrequest/starttime/
---
## ResolveRecipientsAvailabilityRequest.StartTime property

标识客户端请求的空闲/忙碌时间跨度的开始。 协议版本为 12.1 时不支持 StartTime。 如果请求中包含可用性，则请求还必须包含开始时间和结束时间。 如果客户端发送无效的 StartTime 值，则服务器在 ResolveRecipients 命令响应中返回状态值 5。

```csharp
public DateTime StartTime { get; set; }
```

### 也可以看看

* class [ResolveRecipientsAvailabilityRequest](../../resolverecipientsavailabilityrequest)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../resolverecipientsavailabilityrequest)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->