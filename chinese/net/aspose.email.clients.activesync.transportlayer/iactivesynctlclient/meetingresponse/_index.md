---
title: MeetingResponse
second_title: Aspose.Email for .NET API 参考
description: 接受暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求
type: docs
weight: 110
url: /zh/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userResponse | UserResponse | 指示会议是被接受、暂时接受还是被拒绝。 |
| collectionId | String | 指定包含会议请求的文件夹。 如果包含 LongId，则可选。 CollectionId 值最长可达 64 个字符。 |
| requestId | String | 指定会议请求消息项的服务器 ID。 如果包含 LongId，则可选。 RequestId 值最长可达 64 个字符。 |

### 返回值

返回 MeetingResponseResult 对象。

### 也可以看看

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userResponse | UserResponse | 指示会议是被接受、暂时接受还是被拒绝。 |
| collectionId | String | 指定包含会议请求的文件夹。 如果包含 LongId，则可选。 CollectionId 值最长可达 64 个字符。 |
| requestId | String | 指定会议请求消息项的服务器 ID。 如果包含 LongId，则可选。 RequestId 值最长可达 64 个字符。 |
| longId | String | 指定源会议请求的长 ID，在搜索命令响应中返回信息。 如果 LongId 存在，则 CollectionId、InstanceId 和 RequestId 不存在。 LongId 值最长可达 256 个字符。 |
| instanceId | String | 指定要修改的定期会议的实例。 协议版本为 12.1 或 14.0 时不支持 InstanceId。 如果 InstanceId 元素包含在协议版本为 12.1 或 14.0 的请求中，则返回 Status 值 2。 InstanceId 包含要修改的约会或会议实例的开始时间。 如果 InstanceId 未包含在 MeetingResponse 请求中，则将对重复项的每个实例执行操作。 InstanceId 可以指定重复约会或会议的异常开始时间。 InstanceId 可以与 LongId 一起使用来标识日历项，也可以与 CollectionId 和 RequestId 一起使用来标识日历项。 InstanceId 值的格式是带有标点分隔符的 dateTime 格式的字符串，例如 2010-04-08T18:16:00.000Z。 如果指定的 InstanceId 值格式不正确，则服务器以状态元素值 104 进行响应。 如果 InstanceId 值指定非重复会议，则服务器响应状态元素值为 146。 |

### 返回值

返回 MeetingResponseResult 对象。

### 也可以看看

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| request | MeetingResponseRequest[] | MeetingResponseRequest 对象数组 |

### 返回值

返回 MeetingResponseResult 对象数组.

### 也可以看看

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

接受、暂时接受或拒绝用户收件箱文件夹或日历文件夹中的会议请求。

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| request | IEnumerable`1 | MeetingResponseRequest 对象的枚举 |

### 返回值

返回 MeetingResponseResult 对象的数组.

### 也可以看看

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* 命名空间 [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->