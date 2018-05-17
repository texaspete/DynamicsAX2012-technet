﻿---
title: ChannelConfiguration.PriceIncludesSalesTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceIncludesSalesTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.PriceIncludesSalesTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.priceincludessalestax(v=AX.60)
ms:contentKeyID: 49820771
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.PriceIncludesSalesTax
dev_langs:
- CSharp
- C++
- VB
---

# PriceIncludesSalesTax Property

Gets a value indicating whether prices include sales tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEINCLUDESSALESTAX")> _
<DataMemberAttribute> _
Public Property PriceIncludesSalesTax As Boolean
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Boolean

value = instance.PriceIncludesSalesTax
```

``` csharp
[ColumnAttribute("PRICEINCLUDESSALESTAX")]
[DataMemberAttribute]
public bool PriceIncludesSalesTax { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICEINCLUDESSALESTAX")]
[DataMemberAttribute]
public:
property bool PriceIncludesSalesTax {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
If true, prices include sales tax; otherwise, false.  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
