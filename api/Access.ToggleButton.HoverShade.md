---
title: ToggleButton.HoverShade property (Access)
keywords: vbaac10.chm14614
f1_keywords:
- vbaac10.chm14614
ms.prod: access
api_name:
- Access.ToggleButton.HoverShade
ms.assetid: a9e98d48-95a1-64d0-77ba-f2cd8dadc4f8
ms.date: 03/05/2019
ms.localizationpriority: medium
---


# ToggleButton.HoverShade property (Access)

Gets or sets the shade that is applied to the theme color in the **HoverColor** property of the specified object. Read/write **Single**.


## Syntax

_expression_.**HoverShade**

_expression_ A variable that represents a **[ToggleButton](Access.ToggleButton.md)** object.


## Remarks

The **HoverShade** property contains a numeric expression that can be used to darken the theme color in the **HoverColor** property. The default value of the **HoverShade** property is 100, which is neutral, and does not change the theme color. 

To darken the color, first determine the percentage by which to darken from 1 to 100, and then subtract that value as a whole number from 100 and store the remainder. For example, to darken the theme color shade by 75%, subtract 75 from 100 and store the remainder, which is 25.

This property is not surfaced in the property sheet.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]