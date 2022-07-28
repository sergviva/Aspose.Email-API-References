---
title: ResolveRecipientsCertificates
second_title: Referencia de la API de Aspose.Email para .NET
description: Contiene información sobre los certificados de un destinatario.
type: docs
weight: 1840
url: /es/net/aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/
---
## ResolveRecipientsCertificates class

Contiene información sobre los certificados de un destinatario.

```csharp
public class ResolveRecipientsCertificates
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ResolveRecipientsCertificates](resolverecipientscertificates)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CertificateCount](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/certificatecount) { get; set; } | Especifica la cantidad de certificados válidos que se encontraron para el destinatario. Si se devuelve un valor de estado de 8 con los certificados, CertificateCount especifica la cantidad de certificados de destinatario que no se devolvieron. |
| [Certificates](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/certificates) { get; } | Contiene la lista de certificados X509 como objeto binario grande (BLOB). El servidor devuelve este elemento solo si el cliente especifica un valor de 2 en CertificateRetrieval en la solicitud del comando ResolveRecipients. |
| [MiniCertificate](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/minicertificate) { get; set; } | Contiene el mini-certificado BLOB. Este elemento se devuelve solo si el cliente especifica un valor de 3 en CertificateRetrieval en la solicitud de comando ResolveRecipients y el destinatario resuelto tiene un certificado S/MIME válido. |
| [RecipientCount](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/recipientcount) { get; set; } | Especifica el número de miembros que pertenecen a una lista de distribución. Se puede utilizar para determinar si todos los destinatarios que pertenecen a una lista de distribución tienen certificados válidos comparando los valores de los elementos CertificateCount y RecipientCount. |
| [Status](../../aspose.email.clients.activesync.transportlayer/resolverecipientscertificates/status) { get; set; } | Indica el resultado de la solicitud del comando ActiveSync. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->