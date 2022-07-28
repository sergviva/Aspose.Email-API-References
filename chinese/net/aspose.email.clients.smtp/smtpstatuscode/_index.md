---
title: SmtpStatusCode
second_title: Aspose.Email for .NET API 参考
description: Smtp 状态码
type: docs
weight: 17080
url: /zh/net/aspose.email.clients.smtp/smtpstatuscode/
---
## SmtpStatusCode enumeration

Smtp 状态码

```csharp
public enum SmtpStatusCode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| NotDefined | `0` | 未定义 |
| GeneralFailure | `-1` | 一般故障 |
| SystemStatus | `211` | 系统状态，或系统帮助回复。 SMTP 状态 211 是一条消息，提供有关邮件服务器状态的详细信息。 在系统帮助回复的情况下，它是给用户请求帮助信息的消息。 |
| HelpMessage | `214` | 后面会出现人类读者的帮助信息。 SMTP 214 通常作为对“HELP”命令的响应而提供。 用户通常会收到此作为邮件服务器信息显示的信息，并且很可能是以指向邮件服务器上运行的特定 SMTP 软件的 FAQ 页面的链接的形式. 由于此错误的性质以及电子邮件服务器的响应方式，通常称为回复，如 SMTP 回复 214。 |
| ServiceReady | `220` | SMTP 服务就绪。 |
| ServiceClosingTransmissionChannel | `221` | 服务关闭传输通道 |
| AuthenticationSucceeded | `235` | 认证成功 |
| Ok | `250` | 请求采取并完成的行动。 |
| UserNotLocalWillForward | `251` | 收件人不是服务器本地的，但服务器会接受并转发消息。 |
| CannotVerifyUserWillAttemptDelivery | `252` | 收件人无法 VRFYed，但服务器接受邮件并尝试传递。 |
| Base64Response | `334` | 包含 [BASE64] 编码字符串 |
| StartMailInput | `354` | 开始消息输入并结束。这表明服务器已准备好接受消息本身 |
| ServiceNotAvailable | `421` | 服务不可用，连接将被关闭。 |
| PasswordTransitionNeeded | `432` | 需要密码转换 |
| MailboxBusy | `450` | 请求的命令失败，因为用户的邮箱不可用（例如已满）。稍后再试。 |
| LocalErrorInProcessing | `451` | 由于服务器错误，该命令已中止。 （在他们这边） |
| InsufficientStorage | `452` | 由于服务器系统存储空间不足，该命令已中止。 |
| ClientNotPermitted | `454` | 客户端没有权限。 TLS 由于临时原因不可用。 请求的身份验证机制需要加密。 |
| CommandUnrecognized | `500` | 由于语法错误，服务器无法识别该命令。 |
| SyntaxError | `501` | 在命令参数中遇到语法错误。 |
| CommandNotImplemented | `502` | 该命令未实现。 |
| CommandNotPermitted | `503` | 邮件事务期间不允许使用Сommand |
| UnrecognizedAuthenticationType | `504` | 无法识别的身份验证类型 |
| AuthenticationRequired | `530` | SMTP 服务器需要安全连接或客户端未通过身份验证。 但有时是因为收件人的服务器将您的服务器列入黑名单，或者电子邮件地址无效。 |
| AuthenticationMechanismIsToWeak | `534` | 认证机制是弱 |
| CredentialsInvalid | `535` | 身份验证凭据无效 |
| EncryptionRequiredRequestedMechanism | `538` | 请求的身份验证机制所需的加密 |
| MailboxUnavailable | `550` | 它通常在远程定义一个不存在的电子邮件地址。 |
| UserNotLocalTryAlternatePath | `551` | “用户不是本地或无效地址 - 中继被拒绝”。 意思是，如果您的地址和收件人的地址都不是由服务器本地托管，则中继可能会中断。 |
| ExceededStorageAllocation | `552` | "Requested mail actions aborted – Exceeded storage allocation":简而言之，收件人的邮箱已超出其限制。 |
| MailboxNameNotAllowed | `553` | “未采取请求的操作 – 邮箱名称无效”。 也就是说，收件人行中的电子邮件地址不正确。 |
| TransactionFailed | `554` | 这意味着事务已经失败。 这是一个永久性错误，服务器不会再次尝试发送消息。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->