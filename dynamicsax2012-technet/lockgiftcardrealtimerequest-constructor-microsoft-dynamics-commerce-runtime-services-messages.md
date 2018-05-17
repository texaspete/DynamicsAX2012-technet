﻿---
title: LockGiftCardRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LockGiftCardRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockGiftCardRealtimeRequest.#ctor(System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.lockgiftcardrealtimerequest.lockgiftcardrealtimerequest(v=AX.60)
ms:contentKeyID: 65322721
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockGiftCardRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# LockGiftCardRealtimeRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    giftCardId As String, _
    channelId As Long, _
    terminalId As String _
)
'Usage
Dim giftCardId As String
Dim channelId As Long
Dim terminalId As String

Dim instance As New LockGiftCardRealtimeRequest(giftCardId, _
    channelId, terminalId)
```

``` csharp
public LockGiftCardRealtimeRequest(
    string giftCardId,
    long channelId,
    string terminalId
)
```

``` c++
public:
LockGiftCardRealtimeRequest(
    String^ giftCardId, 
    long long channelId, 
    String^ terminalId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[LockGiftCardRealtimeRequest Class](lockgiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)
