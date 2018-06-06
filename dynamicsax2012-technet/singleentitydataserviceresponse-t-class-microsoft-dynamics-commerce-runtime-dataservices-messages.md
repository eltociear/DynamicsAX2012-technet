﻿---
title: SingleEntityDataServiceResponse(T) Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SingleEntityDataServiceResponse(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SingleEntityDataServiceResponse`1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn968009(v=AX.60)
ms:contentKeyID: 65319866
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SingleEntityDataServiceResponse`1
dev_langs:
- CSharp
- C++
- VB
---

# SingleEntityDataServiceResponse(T) Class

EntityDataServiceResponse contains the data service entity response.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class SingleEntityDataServiceResponse(Of T) _
    Inherits Response
'Usage
Dim instance As SingleEntityDataServiceResponse(Of T)
```

``` csharp
[DataContractAttribute]
public class SingleEntityDataServiceResponse<T> : Response
```

``` c++
[DataContractAttribute]
generic<typename T>
public ref class SingleEntityDataServiceResponse : public Response
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SingleEntityDataServiceResponse\<T\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)
