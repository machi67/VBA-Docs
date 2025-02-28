---
title: Resource.Flag9 property (Project)
ms.prod: project-server
api_name:
- Project.Resource.Flag9
ms.assetid: f01bb999-4b23-cd2e-a817-141ec157ad7e
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# Resource.Flag9 property (Project)

 **True** if the flag associated with a **Resource** is set. Read/write **Variant**.


## Syntax

_expression_. `Flag9`

_expression_ A variable that represents a [Resource](./Project.Resource.md) object.


## Example

The following example deletes all the tasks that have the **Flag1** set to **True**.


```vb
Sub DeleteNonEssentialTasks() 
 
 Dim T As Task ' Task object used in For Each loop 
 
 ' Delete nonessential tasks in the active project. 
 For Each T In ActiveProject.Tasks 
 If Not (T Is Nothing) Then 
 If T.Flag1 = True Then T.Delete 
 End If 
 Next T 
 
End Sub
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]