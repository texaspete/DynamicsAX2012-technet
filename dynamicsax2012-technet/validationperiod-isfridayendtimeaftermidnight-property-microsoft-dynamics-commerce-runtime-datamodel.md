﻿---
title: ValidationPeriod.IsFridayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsFridayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsFridayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.isfridayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49855559
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsFridayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsFridayEndTimeAfterMidnight Property

Gets whether ending time wraps around after midnight for Fridays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FRIDAYENDINGTIMEAFTERMIDNIGHT")> _
<DataMemberAttribute> _
Public Property IsFridayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsFridayEndTimeAfterMidnight
```

``` csharp
[ColumnAttribute("FRIDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public int IsFridayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[ColumnAttribute(L"FRIDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public:
property int IsFridayEndTimeAfterMidnight {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
