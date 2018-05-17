﻿---
title: IPrintingV2.PrintDefault Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintDefault Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV2.PrintDefault(System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv2.printdefault(v=AX.60)
ms:contentKeyID: 49837450
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV2.PrintDefault
dev_langs:
- CSharp
- C++
- VB
---

# PrintDefault Method

Print directly to the default (or fallback) printer using the printText provided

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintDefault ( _
    allowFallback As Boolean, _
    printText As String _
)
'Usage
Dim instance As IPrintingV2
Dim allowFallback As Boolean
Dim printText As String

instance.PrintDefault(allowFallback, _
    printText)
```

``` csharp
void PrintDefault(
    bool allowFallback,
    string printText
)
```

``` c++
void PrintDefault(
    bool allowFallback, 
    String^ printText
)
```

#### Parameters

  - allowFallback  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - printText  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV2 Interface](iprintingv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)
