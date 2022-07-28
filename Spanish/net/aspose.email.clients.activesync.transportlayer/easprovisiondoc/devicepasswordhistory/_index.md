---
title: DevicePasswordHistory
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica la cantidad mínima de contraseñas usadas anteriormente almacenadas para evitar que el cliente las reutilice. Los valores válidos se enumeran a continuación  0 no se requiere el almacenamiento de contraseñas usadas anteriormente. gt 0 la cantidad mínima de contraseñas usadas anteriormente que se almacenado. Si DevicePasswordHistory es nulo entonces un cliente DEBE tratar este valor como 0. Si el valor de DevicePasswordEnabled se establece en VERDADERO el cliente impide que el usuario use una contraseña anterior almacenada después de que caduque una contraseña. Si el valor de DevicePasswordEnabled se establece en FALSO el cliente DEBE ignorar esta propiedad.
type: docs
weight: 250
url: /es/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory/
---
## EASProvisionDoc.DevicePasswordHistory property

Especifica la cantidad mínima de contraseñas usadas anteriormente almacenadas para evitar que el cliente las reutilice. Los valores válidos se enumeran a continuación: = 0: no se requiere el almacenamiento de contraseñas usadas anteriormente. &gt; 0: la cantidad mínima de contraseñas usadas anteriormente que se almacenado. Si DevicePasswordHistory es nulo, entonces un cliente DEBE tratar este valor como 0. Si el valor de DevicePasswordEnabled se establece en VERDADERO, el cliente impide que el usuario use una contraseña anterior almacenada después de que caduque una contraseña. Si el valor de DevicePasswordEnabled se establece en FALSO, el cliente DEBE ignorar esta propiedad.

```csharp
public int? DevicePasswordHistory { get; set; }
```

### Ver también

* class [EASProvisionDoc](../../easprovisiondoc)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../easprovisiondoc)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->