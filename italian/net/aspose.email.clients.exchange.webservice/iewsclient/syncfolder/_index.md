---
title: SyncFolder
second_title: Aspose.Email per riferimento all'API .NET
description: Recupera le modifiche degli elementi e delle sottocartelle in una cartella specificata.
type: docs
weight: 1430
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/syncfolder/
---
## SyncFolder(string) {#syncfolder_1}

Recupera le modifiche degli elementi e delle sottocartelle in una cartella specificata.

```csharp
public SyncFolderResult SyncFolder(string folderUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderUri | String | La cartella uri |

### Valore di ritorno

Restituisce il risultato dell'operazione SyncFolder.

### Guarda anche

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## SyncFolder(string, SyncFolderType) {#syncfolder_2}

Recupera le modifiche degli elementi e delle sottocartelle in una cartella specificata.

```csharp
public SyncFolderResult SyncFolder(string folderUri, SyncFolderType syncType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderUri | String | La cartella uri |
| syncType | SyncFolderType | Tipo di sincronizzazione delle cartelle |

### Valore di ritorno

Restituisce il risultato dell'operazione SyncFolder.

### Guarda anche

* class [SyncFolderResult](../../syncfolderresult)
* enum [SyncFolderType](../../syncfoldertype)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## SyncFolder(SyncState) {#syncfolder}

Recupera le modifiche degli elementi in una cartella specificata.

```csharp
public SyncFolderResult SyncFolder(SyncState syncState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| syncState | SyncState | Lo stato di sincronizzazione. |

### Valore di ritorno

Restituisce il risultato dell'operazione SyncFolder.

### Guarda anche

* class [SyncFolderResult](../../syncfolderresult)
* class [SyncState](../../syncstate)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## SyncFolder(string, string) {#syncfolder_3}

Recupera le modifiche degli elementi in una cartella specificata.

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderUri | String | La cartella uri |
| syncState | String | Lo stato di sincronizzazione facoltativo. Deve essere nullo per la prima sincronizzazione. |

### Valore di ritorno

Restituisce il risultato dell'operazione SyncFolder.

### Guarda anche

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## SyncFolder(string, string, IEnumerable&lt;string&gt;) {#syncfolder_4}

Recupera le modifiche degli elementi in una cartella specificata.

```csharp
public SyncFolderResult SyncFolder(string folderUri, string syncState, 
    IEnumerable<string> ignoreList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderUri | String | La cartella uri |
| syncState | String | Lo stato di sincronizzazione facoltativo. Deve essere nullo per la prima sincronizzazione. |
| ignoreList | IEnumerable`1 | L'elenco facoltativo di uri elemento da ignorare. |

### Valore di ritorno

Restituisce il risultato dell'operazione SyncFolder.

### Guarda anche

* class [SyncFolderResult](../../syncfolderresult)
* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->