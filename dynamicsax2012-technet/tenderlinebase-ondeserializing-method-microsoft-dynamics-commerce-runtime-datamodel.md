﻿---
title: TenderLineBase.OnDeserializing Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OnDeserializing Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.OnDeserializing(System.Runtime.Serialization.StreamingContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.ondeserializing(v=AX.60)
ms:contentKeyID: 65323121
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.OnDeserializing
dev_langs:
- CSharp
- C++
- VB
---

# OnDeserializing Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<OnDeserializingAttribute> _
Public Sub OnDeserializing ( _
    context As StreamingContext _
)
'Usage
Dim instance As TenderLineBase
Dim context As StreamingContext

instance.OnDeserializing(context)
```

``` csharp
[OnDeserializingAttribute]
public void OnDeserializing(
    StreamingContext context
)
```

``` c++
[OnDeserializingAttribute]
public:
void OnDeserializing(
    StreamingContext context
)
```

#### Parameters

  - context  
    Type: [System.Runtime.Serialization.StreamingContext](https://technet.microsoft.com/en-us/library/t16abws5\(v=ax.60\))  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
