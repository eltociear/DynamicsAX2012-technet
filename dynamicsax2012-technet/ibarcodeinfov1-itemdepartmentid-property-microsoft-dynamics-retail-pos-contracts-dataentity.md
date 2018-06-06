﻿---
title: IBarcodeInfoV1.ItemDepartmentId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemDepartmentId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.ItemDepartmentId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov1.itemdepartmentid(v=AX.60)
ms:contentKeyID: 47129153
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV1.ItemDepartmentId
dev_langs:
- CSharp
- C++
- VB
---

# ItemDepartmentId Property

Gets or sets the retail department for the item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemDepartmentId As String
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV1
Dim value As String

value = instance.ItemDepartmentId

instance.ItemDepartmentId = value
```

``` csharp
string ItemDepartmentId { get; set; }
```

``` c++
property String^ ItemDepartmentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IBarcodeInfoV1 Interface](ibarcodeinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)
