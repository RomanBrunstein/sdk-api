---
UID: NF:d3d12video.ID3D12VideoEncoderHeap.GetCodecProfile
tech.root: mf
title: ID3D12VideoEncoderHeap::GetCodecProfile
ms.date: 06/22/2021
targetos: Windows
description: Gets the codec profile associated with the video encoder heap.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: d3d12video.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - d3d12video.h
api_name:
 - ID3D12VideoEncoderHeap::GetCodecProfile
f1_keywords:
 - ID3D12VideoEncoderHeap::GetCodecProfile
 - d3d12video/ID3D12VideoEncoderHeap::GetCodecProfile
dev_langs:
 - c++
---

## -description

Gets the codec profile associated with the video encoder heap.

## -parameters

### -param dstProfile

Receives a [D3D12_VIDEO_ENCODER_PROFILE_DESC](ns-d3d12video-d3d12_video_encoder_profile_desc.md) structure representing the codec profile specified in the [D3D12_VIDEO_ENCODER_HEAP_DESC](ns-d3d12video-d3d12_video_encoder_heap_desc.md) passed into [ID3D12VideoDevice3::CreateVideoEncoderHeap](nf-d3d12video-id3d12videodevice3-createvideoencoderheap.md).

## -returns

Returns S_OK on success.

## -remarks

## -see-also

