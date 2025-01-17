---
title: "CloseSession"
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
ms.localizationpriority: medium
ms.assetid: 2c2371c8-b0e0-4992-b7ac-3949eadf1ebe
description: "Applies to: Excel 2013 | Office 2013 | Visual Studio"
---

# CloseSession

**Applies to**: Excel 2013 | Office 2013 | Visual Studio 
  
Ends a session with a cluster.
  
```cpp
int CloseSession(int SessionId)
```

## Parameters

_SessionId_
  
> The ID of the session to close. This value must match the value returned by [OpenSession](opensession.md).
    
## Return value

**xlHpcRetSuccess** if the session closed; **xlHpcRetInvalidSessionId** if the  _SessionId_ argument is invalid; **xlHpcRetCallFailed** on other failures. 
  
## See also

- [OpenSession](opensession.md)
- [Excel Cluster Connector Functions](excel-cluster-connector-functions.md)

