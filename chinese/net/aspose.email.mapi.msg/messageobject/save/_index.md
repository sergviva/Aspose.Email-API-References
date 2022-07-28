---
title: Save
second_title: Aspose.Email for .NET API 参考
description: 将当前消息对象保存到指定文件
type: docs
weight: 70
url: /zh/net/aspose.email.mapi.msg/messageobject/save/
---
## Save(string, MessageObjectSaveFormat) {#save_1}

将当前消息对象保存到指定文件。

```csharp
public void Save(string fileName, MessageObjectSaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 文件名。 |
| format | MessageObjectSaveFormat | 输出数据的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 如果*format*值无效。 |

### 评论

此外，可能会引发与String)调用。

### 也可以看看

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* 命名空间 [Aspose.Email.Mapi.Msg](../../messageobject)
* 部件 [Aspose.Email](../../../)

---

## Save(Stream, MessageObjectSaveFormat) {#save}

将当前消息对象保存到指定流。

```csharp
public void Save(Stream stream, MessageObjectSaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要写入的流。 |
| format | MessageObjectSaveFormat | 输出数据的格式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果*stream*为空。 |
| ArgumentOutOfRangeException | 如果*format*值无效。 |

### 也可以看看

* enum [MessageObjectSaveFormat](../../messageobjectsaveformat)
* class [MessageObject](../../messageobject)
* 命名空间 [Aspose.Email.Mapi.Msg](../../messageobject)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->