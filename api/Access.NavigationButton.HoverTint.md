---
title: NavigationButton.HoverTint property (Access)
keywords: vbaac10.chm14613
f1_keywords:
- vbaac10.chm14613
ms.prod: access
api_name:
- Access.NavigationButton.HoverTint
ms.assetid: 90ecba49-8922-193a-7fde-228b342b4eff
ms.date: 03/05/2019
ms.localizationpriority: medium
---


# NavigationButton.HoverTint property (Access)

Gets or sets the tint applied to the theme color in the **HoverColor** property of the specified object. Read/write **Single**.


## Syntax

_expression_.**HoverTint**

_expression_ A variable that represents a **[NavigationButton](Access.NavigationButton.md)** object.


## Remarks

The **HoverTint** property contains a numeric expression that can be used to lighten the theme color in the **HoverColor** property. The default value of the **HoverTint** property is 100, which is neutral, and does not change the theme color. 

To lighten the color, first determine the percentage by which to lighten from 1 to 100, and then subtract that value as a whole number from 100 and use the remainder. For example, to lighten the theme color tint by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]