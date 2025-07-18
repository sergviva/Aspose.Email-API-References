---
title: Enum ImapSpecialFolderTypes
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapSpecialFolderTypes enum. Represents enumeration of specialuse mailboxes More details see in RFC6154 http//tools.ietf.org/html/rfc6154
type: docs
weight: 16650
url: /net/aspose.email.clients.imap/imapspecialfoldertypes/
---
## ImapSpecialFolderTypes enumeration

Represents enumeration of special-use mailboxes More details see in RFC6154 http://tools.ietf.org/html/rfc6154

```csharp
public enum ImapSpecialFolderTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NotSpecified | `0` | If IMAP LIST Extension for Special-Use Mailboxes (RFC6154) is supported, this means that mailbox is regular and does not used for special purposes. |
| All | `1` | This mailbox presents all messages in the user's message store. Implementations MAY omit some messages, such as, perhaps, those in \Trash and \Junk. When this special use is supported, it is almost certain to represent a virtual mailbox. |
| Archive | `2` | This mailbox is used to archive messages. The meaning of an "archival" mailbox is server-dependent; typically, it will be used to get messages out of the inbox, or otherwise keep them out of the user's way, while still making them accessible. |
| Drafts | `3` | This mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\Draft" message flag. Alternatively, this might just be advice that a client put drafts here. |
| Flagged | `4` | This mailbox presents all messages marked in some way as "important". When this special use is supported, it is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "\Flagged" message flag. |
| Junk | `5` | This mailbox is where messages deemed to be junk mail are held. Some server implementations might put messages here automatically. Alternatively, this might just be advice to a client-side spam filter. |
| Sent | `6` | This mailbox is used to hold copies of messages that have been sent. Some server implementations might put messages here automatically. Alternatively, this might just be advice that a client save sent messages here. |
| Trash | `7` | This mailbox is used to hold messages that have been deleted or marked for deletion. In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\Deleted" message flag. Alternatively, this might just be advice that a client that chooses not to use the IMAP "\Deleted" model should use this as its trash location. In server implementations that strictly expect the IMAP "\Deleted" model, this special use is likely not to be supported. |
| Important | `8` | This mailbox is used to hold messages that have been marked as important. The "\Important" mailbox attribute is a signal that the mailbox contains messages that are likely important to the user. In an implementation that also supports the "$Important" keyword, this special use is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "$Important" keyword. In other implementations, the system might automatically put messages there based on the same sorts of heuristics that are noted for the "$Important" keyword. The distinctions between "\Important" and "\Flagged" for mailboxes are similar to those between "$Important" and "\Flagged" for messages. https://tools.ietf.org/html/rfc8457 |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


