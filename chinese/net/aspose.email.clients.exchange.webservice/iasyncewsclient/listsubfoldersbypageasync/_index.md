---
title: ListSubFoldersByPageAsync
second_title: Aspose.Email for .NET API 参考
description: 使用分页搜索给定父文件夹中的指定文件夹 方法支持分页
type: docs
weight: 490
url: /zh/net/aspose.email.clients.exchange.webservice/iasyncewsclient/listsubfoldersbypageasync/
---
## IAsyncEwsClient.ListSubFoldersByPageAsync method

使用分页搜索给定父文件夹中的指定文件夹 方法支持分页。

```csharp
public Task<ExchangeFolderPageInfo> ListSubFoldersByPageAsync(string parentFolderUri, 
    PageInfo page, CancellationToken cancellationToken = default)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentFolderUri | String | 父文件夹 URI |
| page | PageInfo | 页面信息 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 返回值

A[`ExchangeFolderPageInfo`](../../../aspose.email.clients.exchange/exchangefolderpageinfo)包含找到的文件夹，如果文件夹名称已指明；否则， 返回所有子文件夹

### 也可以看看

* class [ExchangeFolderPageInfo](../../../aspose.email.clients.exchange/exchangefolderpageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->