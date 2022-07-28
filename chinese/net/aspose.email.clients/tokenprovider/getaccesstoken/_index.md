---
title: GetAccessToken
second_title: Aspose.Email for .NET API 参考
description: 获取 oAuth 访问令牌 如果令牌存在且其过期日期未过期则返回当前令牌否则从服务器请求新令牌
type: docs
weight: 110
url: /zh/net/aspose.email.clients/tokenprovider/getaccesstoken/
---
## GetAccessToken() {#getaccesstoken}

获取 oAuth 访问令牌。 如果令牌存在且其过期日期未过期，则返回当前令牌，否则从服务器请求新令牌。

```csharp
public virtual OAuthToken GetAccessToken()
```

### 返回值

返回 oAuth 访问令牌

### 也可以看看

* class [OAuthToken](../../oauthtoken)
* class [TokenProvider](../../tokenprovider)
* 命名空间 [Aspose.Email.Clients](../../tokenprovider)
* 部件 [Aspose.Email](../../../)

---

## GetAccessToken(bool) {#getaccesstoken_1}

获取 oAuth 访问令牌。

```csharp
public virtual OAuthToken GetAccessToken(bool ignoreExistingToken)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ignoreExistingToken | Boolean | 如果 ignoreExistingToken 为真，则从服务器请求新令牌。否则行为取决于令牌是否存在。 如果令牌存在且其过期日期未过期，则返回当前令牌，否则从服务器请求新令牌。 |

### 返回值

返回 oAuth 访问令牌

### 也可以看看

* class [OAuthToken](../../oauthtoken)
* class [TokenProvider](../../tokenprovider)
* 命名空间 [Aspose.Email.Clients](../../tokenprovider)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->