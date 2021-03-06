---
UID: NC:d3dkmthk.PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
title: PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION (d3dkmthk.h)
description: The PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION callback function notifies the operating system that a shared primary surface was unlocked.
ms.assetid: c6a4be3f-33b5-4369-8b27-06561bf43873
ms.date: 10/19/2018
keywords: ["PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION callback function"]
req.header: d3dkmthk.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
ms.custom: RS5
tech.root: display
f1_keywords:
 - PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
 - d3dkmthk/PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3dkmthk.h
api_name:
 - PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
dev_langs:
 - c++
---

# PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION callback function


## -description

The PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION callback function notifies the operating system that a shared primary surface was unlocked.

## -parameters

### -param Arg1

Pointer to a [D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION](ns-d3dkmthk-_d3dkmt_sharedprimaryunlocknotification.md) structure.

## -returns

Returns NTSTATUS.

## -prototype

```cpp
//Declaration

PFND3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION Pfnd3dkmtSharedprimaryunlocknotification; 

// Definition

NTSTATUS Pfnd3dkmtSharedprimaryunlocknotification 
(
	const D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION *
)
{...}

```

## -remarks

## -see-also

