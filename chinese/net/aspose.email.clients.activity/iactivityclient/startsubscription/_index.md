---
title: StartSubscription
second_title: Aspose.Email for .NET API 参考
description: 开始订阅指定的内容类型 如果已存在对指定内容类型的订阅则此操作用于 - 更新活动 webhook 的属性 - 启用 webhook由于过多的失败通知而被禁用 - 通过指定较晚的或空的到期日期重新启用过期的 webhook - 删除 webhook
type: docs
weight: 110
url: /zh/net/aspose.email.clients.activity/iactivityclient/startsubscription/
---
## IActivityClient.StartSubscription method

开始订阅指定的内容类型。 如果已存在对指定内容类型的订阅，则此操作用于: - 更新活动 webhook 的属性 - 启用 webhook由于过多的失败通知而被禁用 - 通过指定较晚的或空的到期日期重新启用过期的 webhook - 删除 webhook

```csharp
public Subscription StartSubscription(string contentType, Webhook webhook)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contentType | String | 表示内容类型。 |
| webhook | Webhook | 表示已配置的 webhook |

### 返回值

当前状态订阅

### 也可以看看

* class [Subscription](../../subscription)
* class [Webhook](../../webhook)
* interface [IActivityClient](../../iactivityclient)
* 命名空间 [Aspose.Email.Clients.Activity](../../iactivityclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->