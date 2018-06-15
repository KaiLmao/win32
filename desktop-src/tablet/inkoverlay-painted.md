---
Description: Occurs when the InkOverlay object or InkPicture control has completed redrawing itself.
ms.assetid: de3c69de-4a33-46e4-96e5-462805681bda
title: InkOverlay.Painted event
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# InkOverlay.Painted event

Occurs when the [**InkOverlay**](https://msdn.microsoft.com/en-us/library/ms698599(v=VS.85).aspx) object or [InkPicture](inkpicture-control-reference.md) control has completed redrawing itself.

## Syntax


```C++
void Painted(
  [in] long         hDC,
  [in] InkRectangle *Rect
);
```



## Parameters

<dl> <dt>

*hDC* \[in\]
</dt> <dd>

The device context on which the event occurred.

</dd> <dt>

*Rect* \[in\]
</dt> <dd>

The [**InkRectangle**](https://msdn.microsoft.com/en-us/library/ms700607(v=VS.85).aspx) that was repainted.

</dd> </dl>

## Return value

This event does not return a value.

## Remarks

This event method is defined in the \_IInkOverlayEvents and \_IInkPictureEvents dispatch-only interfaces (dispinterfaces) with an ID of DISPID\_IOEPainted.

## Requirements



|                                     |                                                                                                                     |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP Tablet PC Edition \[desktop apps only\]<br/>                                                       |
| Minimum supported server<br/> | None supported<br/>                                                                                           |
| Header<br/>                   | <dl> <dt>Msinkaut.h (also requires Msinkaut\_i.c)</dt> </dl> |
| Library<br/>                  | <dl> <dt>InkObj.dll</dt> </dl>                               |



## See also

<dl> <dt>

[**InkOverlay Class**](https://msdn.microsoft.com/en-us/library/ms698599(v=VS.85).aspx)
</dt> </dl>

 

 



