---
title: ImapMessageFlags
second_title: Aspose.Email for .NET API 参考
description: 表示与消息关联的标志
type: docs
weight: 16360
url: /zh/net/aspose.email.clients.imap/imapmessageflags/
---
## ImapMessageFlags class

表示与消息关联的标志。

```csharp
public class ImapMessageFlags : IEquatable<ImapMessageFlags>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Answered](../../aspose.email.clients.imap/imapmessageflags/answered) { get; } | 消息已得到答复。 |
| static [Deleted](../../aspose.email.clients.imap/imapmessageflags/deleted) { get; } | 消息被“删除”以供以后删除。 |
| static [Draft](../../aspose.email.clients.imap/imapmessageflags/draft) { get; } | 邮件已被标记为草稿。 |
| static [Empty](../../aspose.email.clients.imap/imapmessageflags/empty) { get; } | 未设置标志 |
| static [Flagged](../../aspose.email.clients.imap/imapmessageflags/flagged) { get; } | 消息被“标记”为紧急/特别注意。 |
| static [IsRead](../../aspose.email.clients.imap/imapmessageflags/isread) { get; } | 消息已被读取。 |
| static [Recent](../../aspose.email.clients.imap/imapmessageflags/recent) { get; } | 邮件“最近”到达此邮箱。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [BitwiseAnd](../../aspose.email.clients.imap/imapmessageflags/bitwiseand)(ImapMessageFlags, ImapMessageFlags) | 实现运算符 &amp;。 |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor)(ImapMessageFlags, ImapMessageFlags) | 实现运算符 &#x7C;。 |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor_1)(ImapMessageFlags, string) | 实现运算符 &#x7C;。 |
| static [BitwiseOr](../../aspose.email.clients.imap/imapmessageflags/bitwiseor#bitwiseor_2)(string, ImapMessageFlags) | 实现运算符 &#x7C;。 |
| static [Keyword](../../aspose.email.clients.imap/imapmessageflags/keyword)(string) | 消息已被自定义标志标记。 |
| virtual [Equals](../../aspose.email.clients.imap/imapmessageflags/equals#equals)(ImapMessageFlags) | 判断指定对象是否等于当前对象。 |
| override [Equals](../../aspose.email.clients.imap/imapmessageflags/equals#equals_1)(object) | 确定指定的Object是否等于此实例。 |
| override [GetHashCode](../../aspose.email.clients.imap/imapmessageflags/gethashcode)() | 返回此实例的哈希码。 |
| [HasFlag](../../aspose.email.clients.imap/imapmessageflags/hasflag)(ImapMessageFlags) | 如果“谁”包含“标志”，则返回真 |
| [IsEmpty](../../aspose.email.clients.imap/imapmessageflags/isempty)() | 确定此实例是否为空。 |
| [Split](../../aspose.email.clients.imap/imapmessageflags/split)() | 拆分为数组。 |
| override [ToString](../../aspose.email.clients.imap/imapmessageflags/tostring)() | 返回代表此实例的String。 |
| [operator &amp;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseand) | 实现运算符 &amp;。 |
| [operator &#x7C;](../../aspose.email.clients.imap/imapmessageflags/op_bitwiseor#op_bitwiseor) | 实现运算符 &#x7C;。 (3 operators) |
| [operator ==](../../aspose.email.clients.imap/imapmessageflags/op_equality) | 实现运算符 ==。 |
| [implicit operator](../../aspose.email.clients.imap/imapmessageflags/op_implicit) | 执行从Int64到ImapMessageFlags的隐式转换。 |
| [operator !=](../../aspose.email.clients.imap/imapmessageflags/op_inequality) | 实现运算符 !=。 |

### 也可以看看

* 命名空间 [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->