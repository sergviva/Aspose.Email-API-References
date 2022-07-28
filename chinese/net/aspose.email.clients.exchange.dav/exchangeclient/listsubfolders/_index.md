---
title: ListSubFolders
second_title: Aspose.Email for .NET API 参考
description: 从父级
type: docs
weight: 310
url: /zh/net/aspose.email.clients.exchange.dav/exchangeclient/listsubfolders/
---
## ListSubFolders(ExchangeFolderInfo) {#listsubfolders}

从父级

```csharp
public ExchangeFolderInfoCollection ListSubFolders(ExchangeFolderInfo parentFolder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolder | ExchangeFolderInfo | 父级获取子公用文件夹的集合[`ExchangeFolderInfo`](../../../aspose.email.clients.exchange/exchangefolderinfo) |

### 返回值

Exchange。ExchangeFolderInfoCollection包含来自父文件夹

### 也可以看看

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

---

## ListSubFolders(string) {#listsubfolders_1}

从父级获取子文件夹的集合

```csharp
public ExchangeFolderInfoCollection ListSubFolders(string parentFolderUri)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的uri |

### 返回值

[`ExchangeFolderInfoCollection`](../../../aspose.email.clients.exchange/exchangefolderinfocollection) 包含来自父文件夹的子文件夹 文件夹

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri* 是 `null` 或 `empty` |

### 也可以看看

* class [ExchangeFolderInfoCollection](../../../aspose.email.clients.exchange/exchangefolderinfocollection)
* class [ExchangeClient](../../exchangeclient)
* 命名空间 [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->