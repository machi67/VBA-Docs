---
title: Application.BeforeMasterDelete event (Visio)
ms.prod: visio
api_name:
- Visio.Application.BeforeMasterDelete
ms.assetid: 65e3bbed-46f4-25c1-1e3f-af61ef61cce9
ms.date: 06/25/2019
ms.localizationpriority: medium
---


# Application.BeforeMasterDelete event (Visio)

Occurs before a master is deleted from a document.


## Syntax

_expression_.**BeforeMasterDelete** (_Master_)

_expression_ A variable that represents an **[Application](Visio.Application.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Master_|Required| **[IVMASTER]**|The master that is going to be deleted.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]