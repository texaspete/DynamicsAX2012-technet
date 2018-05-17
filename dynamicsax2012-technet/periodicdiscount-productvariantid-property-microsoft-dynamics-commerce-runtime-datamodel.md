﻿---
title: PeriodicDiscount.ProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ProductVariantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.productvariantid(v=AX.60)
ms:contentKeyID: 65320540
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariantId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTINCTPRODUCTVARIANT")> _
<DataMemberAttribute> _
Public Property ProductVariantId As Long
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Long

value = instance.ProductVariantId
```

``` csharp
[ColumnAttribute("DISTINCTPRODUCTVARIANT")]
[DataMemberAttribute]
public long ProductVariantId { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISTINCTPRODUCTVARIANT")]
[DataMemberAttribute]
public:
property long long ProductVariantId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
