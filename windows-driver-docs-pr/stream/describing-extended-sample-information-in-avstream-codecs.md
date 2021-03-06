---
title: Describing Extended Sample Information in AVStream Codecs
author: windows-driver-content
description: Describing Extended Sample Information in AVStream Codecs
ms.assetid: 04447525-78f5-4c77-9a41-4e6e4729f729
keywords:
- AVStream hardware codec support WDK , extended sample information
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Describing Extended Sample Information in AVStream Codecs


Decoder filters can find extended sample information in the extended [**KSSTREAM\_HEADER**](https://msdn.microsoft.com/library/windows/hardware/ff567138) structure [**KS\_FRAME\_INFO**](https://msdn.microsoft.com/library/windows/hardware/ff567645), which follows KSSTREAM\_HEADER in memory.

The driver must propagate information specified in KSSTREAM\_HEADER.OptionsFlags from input (source) to output (destination) KS pins.

Encoders should include extended sample information in the extended KSSTREAM\_HEADER structure, KS\_FRAME\_INFO. Specifically, an encoder should update the member **dwFrameFlags** to indicate KS\_VIDEO\_FLAG\_I\_FRAME and KS\_VIDEO\_FLAG\_P\_FRAME, as applicable.

Surface stride is specified in KS\_FRAME\_INFO's lSurfacePitch member (union with **Reserved1** member). For more information about surface stride, see [Handling Stride in AVStream Codecs](handling-stride-in-avstream-codecs.md).

 

 




