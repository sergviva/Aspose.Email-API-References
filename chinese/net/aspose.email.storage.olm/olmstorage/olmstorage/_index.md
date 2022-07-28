---
title: OlmStorage
second_title: Aspose.Email for .NET API 参考
description: 初始化OlmStorageaspose.email.storage.olm/olmstorage类的新实例 允许设置回调方法来处理 OLM 存储遍历期间发生的异常
type: docs
weight: 10
url: /zh/net/aspose.email.storage.olm/olmstorage/olmstorage/
---
## OlmStorage(TraversalExceptionsCallback) {#constructor}

初始化[`OlmStorage`](../../olmstorage)类的新实例。 允许设置回调方法来处理 OLM 存储遍历期间发生的异常。

```csharp
public OlmStorage(TraversalExceptionsCallback callback)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| callback | TraversalExceptionsCallback | 异常回调。 |

### 也可以看看

* delegate [TraversalExceptionsCallback](../../../aspose.email.exceptions/traversalexceptionscallback)
* class [OlmStorage](../../olmstorage)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmstorage)
* 部件 [Aspose.Email](../../../)

---

## OlmStorage(string) {#constructor_2}

初始化[`OlmStorage`](../../olmstorage)类的新实例。

```csharp
public OlmStorage(string fileName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | OLM 文件名。 |

### 返回值

返回从指定文件加载的 OlmStorage 实例。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果文件名为空或空则抛出 |

### 也可以看看

* class [OlmStorage](../../olmstorage)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmstorage)
* 部件 [Aspose.Email](../../../)

---

## OlmStorage(Stream) {#constructor_1}

初始化[`OlmStorage`](../../olmstorage)类的新实例。

```csharp
public OlmStorage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 源流Stream带有 OLM 存储数据。 |

### 返回值

返回从指定流加载的 OlmStorage 实例。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 如果流为空则抛出 |

### 也可以看看

* class [OlmStorage](../../olmstorage)
* 命名空间 [Aspose.Email.Storage.Olm](../../olmstorage)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->