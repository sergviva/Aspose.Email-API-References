---
title: Enum AccessRole
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.AccessRole enum. The effective access role that the authenticated user has on the calendar
type: docs
weight: 15600
url: /net/aspose.email.clients.google/accessrole/
---
## AccessRole enumeration

The effective access role that the authenticated user has on the calendar.

```csharp
public enum AccessRole
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| none | `0` | Not defined |
| freeBusyReader | `1` | Provides read access to free/busy information. |
| reader | `2` | Provides read access to the calendar. Private events will appear to users with reader access, but event details will be hidden. |
| writer | `3` | Provides read and write access to the calendar. Private events will appear to users with writer access, and event details will be visible. |
| owner | `4` | Provides ownership of the calendar. This role has all of the permissions of the writer role with the additional ability to see and manipulate ACLs. |

### See Also

* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


