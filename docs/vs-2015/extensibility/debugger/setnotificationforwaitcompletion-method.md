---
title: "SetNotificationForWaitCompletion Method | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "SetNotificationForWaitCompletion method, Task class [.NET Framework debug engines]"
ms.assetid: da149c9a-20f4-4543-a29e-429c8c1d2e19
caps.latest.revision: 6
ms.author: "gregvanl"
manager: "ghogen"
---
# SetNotificationForWaitCompletion Method
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [SetNotificationForWaitCompletion Method](https://docs.microsoft.com/visualstudio/extensibility/debugger/setnotificationforwaitcompletion-method).  
  
Sets or clears the TASK_STATE_WAIT_COMPLETION_NOTIFICATION state bit.  
  
 **Namespace:** <xref:System.Threading.Tasks?displayProperty=fullName>  
  
 **Assembly:** mscorlib (in mscorlib.dll)  
  
## Syntax  
  
```vb  
internal void SetNotificationForWaitCompletion(bool enabled)  
```  
  
#### Parameters  
 `enabled`  
  
 `true` to set the bit; `false` to unset the bit.  
  
## Exceptions  
  
## Remarks  
 The debugger sets this bit to help step out of an async method body. If `enabled` is `true`, this method must be called only on a task that has not yet been completed. If `enabled` is `false`, this method may be called on completed tasks. In either event, it should only be used for promise-style tasks.  
  
## Requirements  
  
## See Also  
 [Task Class](../../extensibility/debugger/task-class-internal-members.md)

