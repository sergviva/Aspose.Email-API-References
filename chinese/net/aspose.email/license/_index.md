---
title: License
second_title: Aspose.Email for .NET API 参考
description: 提供许可组件的方法
type: docs
weight: 17630
url: /zh/net/aspose.email/license/
---
## License class

提供许可组件的方法。

```csharp
public class License
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [License](license)() | 初始化此类的新实例。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.email/license/setlicense#setlicense)(FileInfo) | 许可组件。 |
| [SetLicense](../../aspose.email/license/setlicense#setlicense_1)(Stream) | 许可组件。 |
| [SetLicense](../../aspose.email/license/setlicense#setlicense_2)(string) | 许可组件。 |

### 例子

在本例中，将尝试查找名为 MyLicense.lic 的许可证文件 在包含 的文件夹中 组件，在包含调用程序集的文件夹中, 在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

组件jar文件:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 也可以看看

* 命名空间 [Aspose.Email](../../aspose.email)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->