---
title: Saved Settings
author: windows-driver-content
description: Saved Settings
ms.assetid: fa3eb2c9-b0ae-4872-b0f4-13fdd3745265
keywords: ["saved registry settings WDK joysticks"]
---

# Saved Settings


## <a href="" id="ddk-saved-settings-di"></a>


When the current joystick settings are saved, the REGSTR\_VAL\_JOYNCONFIG saved under the REGSTR\_KEY\_JOYCURR key is also written under the REGSTR\_KEY\_JOYSETTINGS key in a subkey with the same name as that from which the OEM-defined settings are taken (non-OEM settings are saved in a subkey "predef" plus the type number). When a joystick is replaced, the saved settings remain so that if the joystick is restored, the saved settings are put back into the current settings. These registry values are used only by Control Panel.

 

 




