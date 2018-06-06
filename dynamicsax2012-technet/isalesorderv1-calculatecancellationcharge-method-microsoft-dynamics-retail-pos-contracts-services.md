﻿---
title: ISalesOrderV1.CalculateCancellationCharge Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateCancellationCharge Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateCancellationCharge(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.calculatecancellationcharge(v=AX.60)
ms:contentKeyID: 47343815
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateCancellationCharge
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCancellationCharge Method

Calculates the cancellation charge for this sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CalculateCancellationCharge ( _
    retailTransaction As IRetailTransaction _
) As Decimal
'Usage
Dim instance As ISalesOrderV1
Dim retailTransaction As IRetailTransaction
Dim returnValue As Decimal

returnValue = instance.CalculateCancellationCharge(retailTransaction)
```

``` csharp
decimal CalculateCancellationCharge(
    IRetailTransaction retailTransaction
)
```

``` c++
Decimal CalculateCancellationCharge(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns the cancellation charge for the sales order  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)
