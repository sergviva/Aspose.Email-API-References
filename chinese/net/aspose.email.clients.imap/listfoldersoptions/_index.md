---
title: ListFoldersOptions
second_title: Aspose.Email for .NET API 参考
description: 文件夹列表选择选项 请注意如果服务器支持 RFC 5258 IMAP LIST Command Extensions 则支持此选项 在 https//tools.ietf.org/html/rfc5258
type: docs
weight: 16510
url: /zh/net/aspose.email.clients.imap/listfoldersoptions/
---
## ListFoldersOptions enumeration

文件夹列表选择选项 请注意，如果服务器支持 RFC 5258 "IMAP LIST Command Extensions" 则支持此选项 在 https://tools.ietf.org/html/rfc5258

```csharp
[Flags]
public enum ListFoldersOptions
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 未定义 |
| Subscribed | `1` | SUBSCRIBED - 导致 LIST 命令列出订阅的名称 而不是现有邮箱。 这通常是实际邮箱的子集。 此列表也可能包含不存在的邮箱的名称。 在任何情况下，列表必须准确包含那些与规范列表模式匹配并被订阅的邮箱名称。 此选项旨在补充 LSUB 命令。 特别值得注意的是此选项返回的邮箱属性，与 LSUB 返回的相比。 使用后者，返回的属性可能无法反映邮箱名称上的实际属性状态， 并且 \NoSelect 属性还有第二个特殊含义（它表示该邮箱是不是，它本身，订阅，但它有后代邮箱）。 使用这里描述的 SUBSCRIBED 选择选项，属性准确完整，没有特殊含义。 "LSUB" 和 "LIST (SUBSCRIBED)" 因此不是一回事，一些服务器必须做大量额外的工作来响应 "LIST (SUBSCRIBED)"。 因此，客户应该继续使用“LSUB”，除非他们特别想要“LIST (SUBSCRIBED)”提供的附加信息。 此选项定义了一个新的邮箱属性“\Subscribed”，它表示订阅了邮箱名称。 必须支持“\Subscribed”属性，并且必须在指定 SUBSCRIBED 选择选项时准确计算。 请注意，SUBSCRIBED 选择选项意味着 SUBSCRIBED 返回选项（见下文）。 |
| Remote | `2` | REMOTE - 使 LIST 命令显示远程邮箱以及本地邮箱，如 [MBRef] 中所述。 此选项旨在替换 RLIST 命令，并与 SUBSCRIBED 选择选项一起替换 RLSUB 命令。 该选项定义了一个新的邮箱属性“\Remote”，它表示一个邮箱是一个远程邮箱。 当指定 REMOTE 选项时，必须准确计算“\Remote”属性。 REMOTE 选择选项与其他选项没有交互。 它的作用是告诉服务器将其他选项（如果有）应用于远程邮箱，除了本地邮箱。 特别是，它与 RECURSIVEMATCH 没有交互（见下文）。 (REMOTE RECURSIVEMATCH) 请求无效，因为 (RECURSIVEMATCH) 请求无效。 (REMOTE RECURSIVEMATCH SUBSCRIBED) 请求请求所有订阅的邮箱，包括本地和远程。 |
| RecursiveMatch | `4` | RECURSIVEMATCH - 此选项强制服务器返回有关与其他选择选项不匹配但有一些子邮箱匹配的父邮箱的信息。 在 CHILDINFO 扩展数据项中返回有关子项的信息。 注意 1:为了返回父邮箱，它仍然必须匹配规范的 LIST 模式。 注2:返回CHILDINFO扩展数据项时，子邮箱是否匹配规范的LIST模式无关紧要。 RECURSIVEMATCH 选项不得作为唯一的选择选项出现（或仅与 REMOTE 一起出现），因为它仅在同时使用其他选择选项时才有意义。 在这种情况下，服务器必须返回 BAD 标记响应。 请注意，即使指定了 RECURSIVEMATCH 选项， 客户端仍然必须能够处理返回 CHILDINFO 扩展数据项且没有子邮箱的情况 满足后续 LIST 命令的选择标准， 因为它们可以在发送 LIST 响应之后但在客户端有机会访问它们之前被删除/重命名。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->