---
title: SecurityOptions
second_title: Aspose.Email for .NET API 参考
description: 邮件客户端的安全模式
type: docs
weight: 16950
url: /zh/net/aspose.email.clients/securityoptions/
---
## SecurityOptions enumeration

邮件客户端的安全模式

```csharp
[Flags]
public enum SecurityOptions
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `1` | 连接不安全。 |
| SSLExplicit | `2` | 使用 STARTTLS 命令启动 SSL/TLS 连接。 |
| SSLImplicit | `4` | 首先建立 SSL/TLS 连接。 |
| SSLAuto | `6` | 自动使用 SSL/TLS 隐式或 SSL/TLS 显式模式。 |
| Auto | `7` | 自动选择模式 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients](../../aspose.email.clients)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->