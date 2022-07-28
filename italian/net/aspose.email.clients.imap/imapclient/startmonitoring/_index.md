---
title: StartMonitoring
second_title: Aspose.Email per riferimento all'API .NET
description: Avvia il monitoraggio delle modifiche ai messaggi per la cartella specificata.
type: docs
weight: 1170
url: /it/net/aspose.email.clients.imap/imapclient/startmonitoring/
---
## ImapClient.StartMonitoring method

Avvia il monitoraggio delle modifiche ai messaggi per la cartella specificata.

```csharp
public void StartMonitoring(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, string folderName = "Inbox")
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | La funzione di richiamata per il monitoraggio del funzionamento. |
| errorCallback | ImapMonitoringErrorEventHandler | La funzione di callback per il monitoraggio della gestione degli errori. Il monitoraggio della cartella specificata viene interrotto quando viene chiamato questo callback. Il callback fornisce anche un detentore dello stato in modo che il monitoraggio della cartella possa essere ripreso utilizzando[`ResumeMonitoring`](../resumemonitoring) metodo. |
| folderName | String | La cartella per il monitoraggio del funzionamento. |

### Guarda anche

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->