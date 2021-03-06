---
title: "IEnumDebugThreads2::Reset | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IEnumDebugThreads2::Reset"
helpviewer_keywords: 
  - "IEnumDebugThreads2::Reset"
ms.assetid: 88980d9a-c4d6-4de4-a9ab-fb56fa71394a
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IEnumDebugThreads2::Reset
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IEnumDebugThreads2::Reset](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/ienumdebugthreads2-reset).  
  
Resets the enumeration to the first element.  
  
## Syntax  
  
```cpp#  
HRESULT Reset(  
   void  
);  
```  
  
```csharp  
int Reset();  
```  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 After this method is called, the next call to the [Next](../../../extensibility/debugger/reference/ienumdebugthreads2-next.md) method returns the first element of the enumeration.  
  
## See Also  
 [IEnumDebugThreads2](../../../extensibility/debugger/reference/ienumdebugthreads2.md)

