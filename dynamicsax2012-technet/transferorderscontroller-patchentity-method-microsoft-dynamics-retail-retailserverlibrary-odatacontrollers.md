﻿---
title: TransferOrdersController.PatchEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PatchEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.PatchEntity(System.String,System.Web.Http.OData.Delta{Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.transferorderscontroller.patchentity(v=AX.60)
ms:contentKeyID: 62203427
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.PatchEntity
dev_langs:
- CSharp
- C++
- VB
---

# PatchEntity Method

Saves a transfer order to the local database.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
Protected Overrides Function PatchEntity ( _
    key As String, _
    patch As Delta(Of TransferOrder) _
) As TransferOrder
'Usage
Dim key As String
Dim patch As Delta(Of TransferOrder)
Dim returnValue As TransferOrder

returnValue = Me.PatchEntity(key, _
    patch)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
protected override TransferOrder PatchEntity(
    string key,
    Delta<TransferOrder> patch
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
protected:
virtual TransferOrder^ PatchEntity(
    String^ key, 
    Delta<TransferOrder^>^ patch
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - patch  
    Type: Delta\<TransferOrder\>  

#### Return Value

Type: TransferOrder  
The saved transfer order.  

## See Also

#### Reference

[TransferOrdersController Class](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)
