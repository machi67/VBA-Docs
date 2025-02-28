---
title: Application.Modules property (Access)
keywords: vbaac10.chm12565
f1_keywords:
- vbaac10.chm12565
ms.prod: access
api_name:
- Access.Application.Modules
ms.assetid: eb99e25f-9a31-82cd-1b61-41c8a227b859
ms.date: 02/05/2019
ms.localizationpriority: medium
---


# Application.Modules property (Access)

Use the **Modules** property to access the **[Modules](Access.Modules.md)** collection and its related properties. Read-only **Modules** object.


## Syntax

_expression_.**Modules**

_expression_ A variable that represents an **[Application](Access.Application.md)** object.


## Remarks

Use the properties of the **Modules** collection in Visual Basic to refer to all open standard modules and class modules.


## Example

The following example uses the **Module** property to insert the **Beep** method in a form's **Open** event.

```vb
Dim strFormOpenCode As String 
Dim mdl As Module 
 
Set mdl = Forms!MyForm.Module 
strFormOpenCode = "Sub Form_Open(Cancel As Integer)" _ 
 & vbCrLf & "Beep" & vbCrLf & "End Sub" 
 With mdl 
 .InsertText strFormOpenCode 
 End With
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]