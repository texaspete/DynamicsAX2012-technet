﻿---
title: SalesLine.QuantityInvoiced Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityInvoiced Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityInvoiced
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.quantityinvoiced(v=AX.60)
ms:contentKeyID: 62208210
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityInvoiced
dev_langs:
- CSharp
- C++
- VB
---

# QuantityInvoiced Property

Gets or sets the quantity that has been previously invoiced (either picked or shipped) for a Customer Order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QTYINVOICED")> _
Public Property QuantityInvoiced As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Nullable(Of Decimal)

value = instance.QuantityInvoiced

instance.QuantityInvoiced = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QTYINVOICED")]
public Nullable<decimal> QuantityInvoiced { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QTYINVOICED")]
public:
property Nullable<Decimal> QuantityInvoiced {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
