---
title: CreatePublicFolderAsync
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: إنشاء المجلد العام المحدد في المجلد العام الجذر
type: docs
weight: 130
url: /ar/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createpublicfolderasync/
---
## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, ExchangeFolderType, string, CancellationToken) {#createpublicfolderasync}

إنشاء المجلد العام المحدد في المجلد العام الجذر

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, ExchangeFolderType folderType, 
    string parentFolderUri = null, CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم المجلد الجديد |
| permissions | ExchangeFolderPermissionCollection | إذن على مجلد جديد |
| folderType | ExchangeFolderType | نوع المجلد |
| parentFolderUri | String | URI للمجلد الأصل |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

إرجاع معلومات المجلد

### أنظر أيضا

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* enum [ExchangeFolderType](../../../aspose.email.clients.exchange/exchangefoldertype)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

---

## CreatePublicFolderAsync(string, ExchangeFolderPermissionCollection, string, CancellationToken) {#createpublicfolderasync_1}

إنشاء المجلد العام المحدد في المجلد العام الجذر

```csharp
public Task<ExchangeFolderInfo> CreatePublicFolderAsync(string name, 
    ExchangeFolderPermissionCollection permissions, string parentFolderUri = null, 
    CancellationToken cancellationToken = default)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم المجلد الجديد |
| permissions | ExchangeFolderPermissionCollection | إذن على مجلد جديد |
| parentFolderUri | String | URI للمجلد الأصل |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

إرجاع معلومات المجلد

### أنظر أيضا

* class [ExchangeFolderInfo](../../../aspose.email.clients.exchange/exchangefolderinfo)
* class [ExchangeFolderPermissionCollection](../../../aspose.email.clients.exchange/exchangefolderpermissioncollection)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* مساحة الاسم [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* المجسم [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->