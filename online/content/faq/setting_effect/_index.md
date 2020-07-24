---
title: When does the changed setting take effect?
date: 2017-10-17T15:26:15Z
draft: false
weight: 40
---
After you change the setting for your device on DEBUT Data Center, the new setting is saved to the server and are not applied to the device immediately. When the device communicates with the server next time, the device fetches new setting from the server and applies the new setting to its firmware. Generally speaking, after you change the setting, the new setting takes effect when the device communicates with the server **next time**.

Example:
You have a device which communicates with the server at 9:00 and 17:00 everyday. If you change the setting for this device at 12:20, the new setting will be applied at 17:00.
<img src="https://raw.githubusercontent.com/rahjuu/color/master/setting_apply.png" style="zoom:70%;" />
