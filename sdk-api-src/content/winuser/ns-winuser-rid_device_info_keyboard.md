---
UID: NS:winuser.tagRID_DEVICE_INFO_KEYBOARD
title: RID_DEVICE_INFO_KEYBOARD (winuser.h)
description: Defines the raw input data coming from the specified keyboard.helpviewer_keywords: ["*PRID_DEVICE_INFO_KEYBOARD","PRID_DEVICE_INFO_KEYBOARD","PRID_DEVICE_INFO_KEYBOARD structure pointer [Keyboard and Mouse Input]","RID_DEVICE_INFO_KEYBOARD","RID_DEVICE_INFO_KEYBOARD structure [Keyboard and Mouse Input]","_win32_RID_DEVICE_INFO_KEYBOARD_str","_win32_rid_device_info_keyboard_str_cpp","inputdev.rid_device_info_keyboard","winui._win32_rid_device_info_keyboard_str","winuser/PRID_DEVICE_INFO_KEYBOARD","winuser/RID_DEVICE_INFO_KEYBOARD"]
old-location: inputdev\rid_device_info_keyboard.htm
tech.root: inputdev
ms.assetid: VS|winui|~\winui\windowsuserinterface\userinput\rawinput\rawinputreference\rawinputstructures\rid_device_info_keyboard.htm
ms.date: 12/05/2018
ms.keywords: '*PRID_DEVICE_INFO_KEYBOARD, PRID_DEVICE_INFO_KEYBOARD, PRID_DEVICE_INFO_KEYBOARD structure pointer [Keyboard and Mouse Input], RID_DEVICE_INFO_KEYBOARD, RID_DEVICE_INFO_KEYBOARD structure [Keyboard and Mouse Input], _win32_RID_DEVICE_INFO_KEYBOARD_str, _win32_rid_device_info_keyboard_str_cpp, inputdev.rid_device_info_keyboard, winui._win32_rid_device_info_keyboard_str, winuser/PRID_DEVICE_INFO_KEYBOARD, winuser/RID_DEVICE_INFO_KEYBOARD'
f1_keywords:
- winuser/RID_DEVICE_INFO_KEYBOARD
dev_langs:
- c++
req.header: winuser.h
req.include-header: Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Winuser.h
api_name:
- RID_DEVICE_INFO_KEYBOARD
targetos: Windows
req.typenames: RID_DEVICE_INFO_KEYBOARD, *PRID_DEVICE_INFO_KEYBOARD
req.redist: 
ms.custom: 19H1
---

# RID_DEVICE_INFO_KEYBOARD structure


## -description


Defines the raw input data coming from the specified keyboard. 


## -struct-fields




### -field dwType

Type: <b>DWORD</b>

The type of the keyboard. 


### -field dwSubType

Type: <b>DWORD</b>

The subtype of the keyboard. 


### -field dwKeyboardMode

Type: <b>DWORD</b>

The  scan code mode. 


### -field dwNumberOfFunctionKeys

Type: <b>DWORD</b>

The number of function keys on the keyboard.


### -field dwNumberOfIndicators

Type: <b>DWORD</b>

The number of LED indicators on the keyboard.


### -field dwNumberOfKeysTotal

Type: <b>DWORD</b>

The total number of keys on the keyboard. 


## -remarks



For the keyboard, the Usage Page is 1 and the Usage is 6. 




## -see-also




<b>Conceptual</b>



<a href="https://docs.microsoft.com/windows/desktop/api/winuser/ns-winuser-rid_device_info">RID_DEVICE_INFO</a>



<a href="https://docs.microsoft.com/windows/desktop/inputdev/raw-input">Raw Input</a>



<b>Reference</b>
 

 

