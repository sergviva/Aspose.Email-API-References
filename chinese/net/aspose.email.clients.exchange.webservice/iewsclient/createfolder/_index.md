---
title: CreateFolder
second_title: Aspose.Email for .NET API 参考
description: 在指定的父文件夹中创建具有指定名称的新文件夹
type: docs
weight: 500
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/createfolder/
---
## CreateFolder(string, string) {#createfolder_2}

在指定的父文件夹中创建具有指定名称的新文件夹。

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 uri。 |
| name | String | 要创建的文件夹的名称。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri*或*name*是` null` 或` 空` 。 |

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection) {#createfolder_3}

创建新文件夹

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 URI |
| name | String | 新文件夹的名称 |
| permissions | ExchangeFolderPermissionCollection | 新文件夹的权限 |

### 返回值

返回文件夹信息

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderPermissionCollection, string) {#createfolder_4}

创建新文件夹

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderPermissionCollection permissions, string folderClass)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 URI |
| name | String | 新文件夹的名称 |
| permissions | ExchangeFolderPermissionCollection | 新文件夹的权限 |
| folderClass | String | 新文件夹的类 |

### 返回值

返回文件夹信息

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateFolder(string, ExchangeFolderType) {#createfolder_1}

在根文件夹中创建新文件夹。

```csharp
public ExchangeFolderInfo CreateFolder(string name, ExchangeFolderType folderType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 新文件夹的名称 |
| folderType | ExchangeFolderType | 类型文件夹 |

### 返回值

返回文件夹信息

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateFolder(string, string, ExchangeFolderType) {#createfolder_5}

创建新文件夹

```csharp
public ExchangeFolderInfo CreateFolder(string parentFolderUri, string name, 
    ExchangeFolderType folderType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹的 URI |
| name | String | 新文件夹名称 |
| folderType | ExchangeFolderType | 文件夹类型 |

### 返回值

返回文件夹信息

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateFolder(string) {#createfolder}

在根文件夹中创建新文件夹。

```csharp
public ExchangeFolderInfo CreateFolder(string name)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 新文件夹的名称 |

### 返回值

返回文件夹信息

### 也可以看看

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->