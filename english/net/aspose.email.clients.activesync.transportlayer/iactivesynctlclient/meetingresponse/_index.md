---
title: MeetingResponse
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 110
url: /net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## IActiveSyncTLClient.MeetingResponse method (1 of 4)

Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userResponse | UserResponse | Indicates whether the meeting is being accepted, tentatively accepted, or declined. |
| collectionId | String | Specifies the folder that contains the meeting request. Optional if LongId is included. The CollectionId value can be up to 64 characters in length. |
| requestId | String | Specifies the server ID of the meeting request message item. Optional if LongId is included. The RequestId value can be up to 64 characters in length. |

## Return Value

Returns MeetingResponseResult object.

### See Also

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.MeetingResponse method (2 of 4)

Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userResponse | UserResponse | Indicates whether the meeting is being accepted, tentatively accepted, or declined. |
| collectionId | String | Specifies the folder that contains the meeting request. Optional if LongId is included. The CollectionId value can be up to 64 characters in length. |
| requestId | String | Specifies the server ID of the meeting request message item. Optional if LongId is included. The RequestId value can be up to 64 characters in length. |
| longId | String | Specifies the long ID for the source meeting request, which is returned in the Search command response message. If the LongId is present, the CollectionId, InstanceId, and RequestId are not present. The LongId value can be up to 256 characters in length. |
| instanceId | String | Specifies the instance of the recurring meeting to be modified. The InstanceId is not supported when the protocol version is 12.1 or 14.0. A Status value of 2 is returned if the InstanceId element is included in requests in which the protocol version is 12.1 or 14.0. The InstanceId contains the start time of the appointment or meeting instance to be modified. If the InstanceId is not included in the MeetingResponse request, then the action is to be taken on every instance of the recurring item. The InstanceId can specify the start time of an exception to a recurring appointment or meeting. The InstanceId can be used with the LongId to identify a calendar item, or it can be used with the CollectionId and RequestId to identify a calendar item. The format of the InstanceId value is a string in dateTime format with the punctuation separators, for example, 2010-04-08T18:16:00.000Z. If the InstanceId value specified is not in the proper format, the server responds with a Status element value of 104. If the InstanceId value specifies a non-recurring meeting, the server responds with a Status element value of 146. |

## Return Value

Returns MeetingResponseResult object.

### See Also

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.MeetingResponse method (3 of 4)

Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Array of MeetingResponseRequest objects |

## Return Value

Returns array of MeetingResponseResult objects.

### See Also

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

---

## IActiveSyncTLClient.MeetingResponse method (4 of 4)

Accepts, tentatively accepts, or declines a meeting request in the user's Inbox folder or Calendar folder.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | IEnumerable`1 | Enumeration of MeetingResponseRequest objects |

## Return Value

Returns array of MeetingResponseResult objects.

### See Also

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->