---
title: SyncFolder
second_title: Aspose.Email for .NET API 参考
description: 检索指定文件夹中项目和子文件夹的更改
type: docs
weight: 1430
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/syncfolder/
---
## SyncFolder(string) {#syncfolder_1}

检索指定文件夹中项目和子文件夹的更改。

```csharp
public SyncFolderResult SyncFolder(string folderUri)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 文件夹 uri |

### 返回值

返回 SyncFolder 操作的结果。

### 也可以看看

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## SyncFolder(string, SyncFolderType) {#syncfolder_2}

检索指定文件夹中项目和子文件夹的更改。

```csharp
public SyncFolderResult SyncFolder(string folderUri, SyncFolderType syncType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 文件夹 uri |
| syncType | SyncFolderType | 文件夹同步类型 |

### 返回值

返回 SyncFolder 操作的结果。

### 也可以看看

* class [SyncFolderResult](../../syncfolderresult)
* enum [SyncFolderType](../../syncfoldertype)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## SyncFolder(SyncState) {#syncfolder}

检索指定文件夹中项目的更改。

```csharp
public SyncFolderResult SyncFolder(SyncState syncState)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| syncState | SyncState | 同步状态。 |

### 返回值

返回 SyncFolder 操作的结果。

### 也可以看看

* class [SyncFolderResult](../../syncfolderresult)
* class [SyncState](../../syncstate)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## SyncFolder(string, string) {#syncfolder_3}

检索指定文件夹中项目的更改。

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 文件夹 uri |
| syncState | String | 可选同步状态.第一次同步必须为空。 |

### 返回值

返回 SyncFolder 操作的结果。

### 也可以看看

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## SyncFolder(string, string, IEnumerable&lt;string&gt;) {#syncfolder_4}

检索指定文件夹中项目的更改。

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState, 
    IEnumerable<string> ignoreList)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderUri | String | 文件夹 uri |
| syncState | String | 可选同步状态.第一次同步必须为空。 |
| ignoreList | IEnumerable`1 | 应忽略的项目 uri 的可选列表。 |

### 返回值

返回 SyncFolder 操作的结果。

### 也可以看看

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->