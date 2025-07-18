---
title: Enum MapiCalendarClientIntent
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarClientIntent enum. Enumerates the actions the user can taken on the Meeting object
type: docs
weight: 18110
url: /net/aspose.email.mapi/mapicalendarclientintent/
---
## MapiCalendarClientIntent enumeration

Enumerates the actions the user can taken on the Meeting object

```csharp
[Flags]
public enum MapiCalendarClientIntent
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Manager | `1` | The user is the owner of the meeting object. |
| Delegate | `2` | The user is a delegate acting on a meeting object in a delegator's calendar folder. |
| DeletedWithNoResponse | `4` | The user deleted the meeting object with no response sent to the organizer. |
| DeletedExceptionWithNoResponse | `8` | The user deleted an exception to a recurring series with no response sent to the organizer. |
| RespondedTentative | `10` | The user tentatively accepted the meeting request. |
| RespondedAccept | `20` | The user accepted the meeting request. |
| RespondedDecline | `40` | The user declined the meeting request. |
| ModifiedStartTime | `80` | The user modified the start time. |
| ModifiedEndTime | `100` | The user modified the end time. |
| ModifiedLocation | `200` | The user changed the location of the meeting. |
| RespondedExceptionDecline | `400` | The user declined an exception to a recurring series. |
| Canceled | `800` | The user canceled a meeting request. |
| ExceptionCanceled | `1000` | The user canceled an exception to a recurring series. |

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


