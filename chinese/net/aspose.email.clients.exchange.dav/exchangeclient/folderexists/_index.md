---
title: FolderExists
second_title: Aspose.Email for .NET API 参考
description: 检查指定文件夹是否存在
type: docs
weight: 190
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/folderexists/
---
## FolderExists(string, string) {#folderexists}

检查指定文件夹是否存在。

```csharp
public bool FolderExists(string parentFolderUri, string folderName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 uri。 |
| folderName | String | 文件夹名称。 |

### 返回值

` true` 如果指定的文件夹存在于指定的父文件夹中；否则，` false` 。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*或*folderName*是` null` 或` 空` |

### 也可以看看

* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## FolderExists(string, string, out ExchangeFolderInfo) {#folderexists_1}

检查指定文件夹是否存在。

```csharp
public bool FolderExists(string parentFolderUri, string folderName, out ExchangeFolderInfo folder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 uri。 |
| folderName | String | 文件夹名称。 |
| folder | ExchangeFolderInfo& | A[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo)表示找到的文件夹信息（如果文件夹存在）。 |

### 返回值

` true` 如果指定的文件夹存在于指定的父文件夹中；否则，` false` 。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*或*folderName*是` null` 或` 空` |

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->