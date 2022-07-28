---
title: CopyItem
second_title: Aspose.Email for .NET API 参考
description: 将项目复制到指定文件夹
type: docs
weight: 450
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/copyitem/
---
## IEWSClient.CopyItem method

将项目复制到指定文件夹

```csharp
public string CopyItem(string itemUri, string destinationFolderUri)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| itemUri | String | 项目 URI |
| destinationFolderUri | String | 目标文件夹 URI |

### 返回值

复制消息的 uri

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *itemUri*是` null` 或` 空` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderUri*is` null` 或` 空` |

### 也可以看看

* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->