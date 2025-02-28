---
title: Application.VBE property (Access)
keywords: vbaac10.chm12572
f1_keywords:
- vbaac10.chm12572
ms.prod: access
api_name:
- Access.Application.VBE
ms.assetid: b9ce562e-cfb1-4b39-a287-2c0629f38c7b
ms.date: 02/05/2019
ms.localizationpriority: medium
---


# Application.VBE property (Access)

Use the **VBE** property to return a reference to the current **VBE** object and its related properties. The **VBE** property of the **[Application](Access.Application.md)** object represents the Microsoft Visual Basic for Applications editor. Read-only **VBE** object.


## Syntax

_expression_.**VBE**

_expression_ A variable that represents an **[Application](Access.Application.md)** object.


## Remarks

After you establish a reference to the **VBE** object, you can access all the properties and methods of the object. You can set a reference to the **VBE** object by choosing **References** on the **Tools** menu while in module Design view. You can then set a reference to the Microsoft Visual Basic for Applications Extensibility 5.3 Object Library in the **References** dialog box by selecting the appropriate check box. 

Microsoft Access can set this reference for you if you use a Microsoft Visual Basic for Applications Extensibility 5.3 Object Library constant to set a **VBE** object's property or as an argument to a **VBE** object's method.


## Example

This example displays the number of references available for the active project.


```vb
MsgBox "Number of References = " & VBE.ActiveVBProject _ 
 .References.Count
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]