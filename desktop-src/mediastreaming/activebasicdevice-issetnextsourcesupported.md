---
title: ActiveBasicDevice IsSetNextSourceSupported property
description: Gets a value that indicates if setting the next source is supported.
ms.assetid: 0888A737-D2CC-4259-BC60-9D2B8E8302A0
keywords:
- IsSetNextSourceSupported property Media Streaming API
- IsSetNextSourceSupported property Media Streaming API , ActiveBasicDevice interface
- ActiveBasicDevice interface Media Streaming API , IsSetNextSourceSupported property
topic_type:
- apiref
api_name:
- ActiveBasicDevice.IsSetNextSourceSupported
- ActiveBasicDevice.get_IsSetNextSourceSupported
api_location:
- playtodevice.dll
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ActiveBasicDevice::IsSetNextSourceSupported property

Gets a value that indicates if setting the next source is supported.

This property is read-only.

## Syntax


```C++
HRESULT get_IsSetNextSourceSupported(
  [out] boolean *value
);
```



## Property value

A pointer to a**boolean** that indicates if setting the next source is supported.

**true** if setting the next source is supported; otherwise, **false**.

## Requirements



|                                     |                                                                                             |
|-------------------------------------|---------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8.1 \[desktop apps only\]<br/>                                                |
| Minimum supported server<br/> | Windows Server 2012 R2 \[desktop apps only\]<br/>                                     |
| Header<br/>                   | <dl> <dt>PlayToDevice.h</dt> </dl>   |
| IDL<br/>                      | <dl> <dt>PlayToDevice.idl</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Playtodevice.dll</dt> </dl> |



## See also

<dl> <dt>

[**ActiveBasicDevice**](https://msdn.microsoft.com/en-us/library/Dn385755(v=VS.85).aspx)
</dt> </dl>

 

 




