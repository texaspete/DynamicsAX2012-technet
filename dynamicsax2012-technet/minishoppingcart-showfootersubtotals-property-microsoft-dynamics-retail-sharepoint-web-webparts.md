﻿---
title: MiniShoppingCart.ShowFooterSubtotals Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterSubtotals Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterSubtotals
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showfootersubtotals(v=AX.60)
ms:contentKeyID: 62206635
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterSubtotals
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterSubtotals Property

Gets or sets whether to show the footer summery sub-total row. Default is true.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebPartStorageAttribute(Storage.Shared)> _
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterSubtotals")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterSubtotals")> _
Public Property ShowFooterSubtotals As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowFooterSubtotals

instance.ShowFooterSubtotals = value
```

``` csharp
[WebPartStorageAttribute(Storage.Shared)]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterSubtotals")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterSubtotals")]
public bool ShowFooterSubtotals { get; set; }
```

``` c++
[WebPartStorageAttribute(Storage::Shared)]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowFooterSubtotals")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowFooterSubtotals")]
public:
property bool ShowFooterSubtotals {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)
