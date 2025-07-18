---
title: Enum HtmlFormatOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.HtmlFormatOptions enum. Enumerates the Html format options
type: docs
weight: 17690
url: /net/aspose.email/htmlformatoptions/
---
## HtmlFormatOptions enumeration

Enumerates the Html format options.

```csharp
[Flags]
public enum HtmlFormatOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No specific settings are specified. |
| WriteHeader | `1` | Indicates that header information should be written. |
| WriteCompleteEmailAddress | `2` | Indicates that complete e-mail address should be written in all email headers. |
| WriteCompleteToEmailAddress | `4` | Indicates that complete e-mail address should be written in 'To' header. |
| WriteCompleteFromEmailAddress | `8` | Indicates that complete e-mail address should be written in 'From' header. |
| WriteCompleteCcEmailAddress | `10` | Indicates that complete e-mail address should be written in 'Cc' header. |
| WriteCompleteBccEmailAddress | `20` | Indicates that complete e-mail address should be written in 'Bcc' header. |
| DisplayAsOutlook | `40` | Indicates that From header will be displayed as in Outlook. |
| RenderCalendarEvent | `80` | Indicates that text from calendar event should be written in output mhtml. |
| RenderVCardInfo | `100` | Indicates that text from VCard AlternativeView should be written in output html. |
| RenderTaskFields | `200` | Indicates that the specific Task fields should be written in output html. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


