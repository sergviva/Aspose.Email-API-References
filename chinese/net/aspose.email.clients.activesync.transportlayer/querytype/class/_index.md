---
title: Class
second_title: Aspose.Email for .NET API 参考
description: 标识项目的类别 有效的 airsyncClass 元素值为 - 任务 - 电子邮件 - 日历 - 联系人 - 备注 - SMS 当协议版本为 12.1 时邮箱搜索支持以下类电子邮件日历联系人任务 SMS 和 Notes 类仅在协议版本为 14.0 或 14.1 时可用 Search 请求可以在请求中包含一个或多个 Class 元素以限制 Search 响应中包含的数据类型 如果 Search 请求中没有包含一个或多个 Class 元素则服务器将返回所有支持的类 如果 Class 作为 And 元素以外的任何元素的子元素包含则服务器以 Status 值 8 SearchTooComplex 进行响应
type: docs
weight: 20
url: /zh/net/aspose.email.clients.activesync.transportlayer/querytype/class/
---
## QueryType.Class property

标识项目的类别。 有效的 airsync:Class 元素值为: - 任务 - 电子邮件 - 日历 - 联系人 - 备注 - SMS 当协议版本为 12.1 时，邮箱搜索支持以下类:电子邮件、日历、联系人、任务。 SMS 和 Notes 类仅在协议版本为 14.0 或 14.1 时可用。 Search 请求可以在请求中包含一个或多个 Class 元素，以限制 Search 响应中包含的数据类型。 如果 Search 请求中没有包含一个或多个 Class 元素，则服务器将返回所有支持的类。 如果 Class 作为 And 元素以外的任何元素的子元素包含，则服务器以 Status 值 8 (SearchTooComplex) 进行响应。

```csharp
public List<AirsyncClass> Class { get; }
```

### 也可以看看

* enum [AirsyncClass](../../airsyncclass)
* class [QueryType](../../querytype)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../querytype)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->