---
title: SyncAddServerOperation
second_title: Aspose.Email for .NET API 参考
description: 在服务器上的集合中创建一个新对象
type: docs
weight: 2150
url: /zh/net/aspose.email.clients.activesync.transportlayer/syncaddserveroperation/
---
## SyncAddServerOperation class

在服务器上的集合中创建一个新对象。

```csharp
public class SyncAddServerOperation
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SyncAddServerOperation](syncaddserveroperation)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ApplicationData](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/applicationdata) { get; } | ApplicationData 包含特定对象的数据，例如联系人、电子邮件、日历约会或任务项。 |
| [Class](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/class) { get; set; } | 标识要添加到集合中的项目的类。 |
| [ClientId](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/clientid) { get; set; } | 包含由客户端生成的唯一标识符，用于临时标识正在使用 Add 元素创建的新对象。 客户端在它发送到服务器的添加元素请求中包含 ClientId 元素。 服务器响应包含一个 Add 元素，该元素包含原始客户端 ID 和为对象分配的新服务器 ID，它将客户端 ID 替换为永久对象标识符。 ClientId 元素是一个唯一标识符，最多由 64 个数字和字母组成。客户端生成此 ID。 在将对象添加到服务器的同步请求期间，该值对于设备来说必须是唯一的。 客户端存储客户端 ID 直到同步会话成功完成，以便在同步过程失败时更容易恢复。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->