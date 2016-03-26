---
layout: post
title: Error flashing Xposed and got Bootloop TWRP Zenfone
date: '2016-02-04T14:45:00.000+05:30'
author: Pawneshwer Gupta
categories:
- asus
- zenfone-5
- Lollipop
- xpose
description: got error after flashing xposed framework from TWRP error updating system binary, got into bootloop after xposed failed to install through TWRP, recovery without reset
keywords: got error after flashing xposed framework from TWRP error updating system binary, got into bootloop after xposed failed to install through TWRP, recovery without reset
modified_time: '2016-02-20T06:50:40.998+05:30'
thumbnail: https://3.bp.blogspot.com/-F3pWnoqjJ3g/VrMTDzbejdI/AAAAAAAAIN8/rdlZVa-lZ_I/s72-c/11693041_852473011509890_599249428_n%2Bcopy.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-6983287656675358096
blogger_orig_url: http://www.edablogs.com/2016/02/error-flashing-xposed-and-got-bootloop-twrp-zenfone.html
redirect_from:
- /2016/02/error-flashing-xposed-and-got-bootloop-twrp-zenfone.html
---

<span style="color: #ff6600;">**For Zenfone 5 users :**</span> if you are on Latest Lollipop rom and using my method to install Xposed framework on your mobile using TWRP. But when you trying to flash suddenly you got an [error](http://en.wikipedia.org/wiki/Error_%28baseball%29 "Error (baseball)").

> ### <span style="color: #ff0000;">Error [Flashing](http://en.wikipedia.org/wiki/Flashing_%28technology%29 "Flashing (technology)") file : error executing updater binary.</span>

And when you try to restart your mobile normally then your mobile got into bootloop. And you tried to factory reset, but same your mobile still in bootloop.

[![](https://3.bp.blogspot.com/-F3pWnoqjJ3g/VrMTDzbejdI/AAAAAAAAIN8/rdlZVa-lZ_I/s320/11693041_852473011509890_599249428_n%2Bcopy.jpg)](https://3.bp.blogspot.com/-F3pWnoqjJ3g/VrMTDzbejdI/AAAAAAAAIN8/rdlZVa-lZ_I/s1600/11693041_852473011509890_599249428_n%2Bcopy.jpg)

### <span style="color: #ff0000;">So there are some questions in your mind :</span>

*   Why i got this error?
*   Why my mobile got into Bootloop?
*   Why my mobile not starting even after factory reset?
*   How i can recover my mobile?

### <span style="color: #339966;">So here is answer :</span>

*   You got this error because your mobile's System memory is full. (**cause latest lollipop firmware is bigger in size**).
*   Your mobile got into bootloop cause Xposed replaced some system [files](http://en.wikipedia.org/wiki/Computer_file "Computer file") but unable to replace all files due to low [memory space](http://en.wikipedia.org/wiki/Computational_resource "Computational resource") in system memory.
*   Your mobile not starting even you factory reset your mobile because Xposed replaced system files, And factory reset will only erase **DATA**, and **CACHE** partitions. System partition will remain same.
*   So to recovery your mobile without factory reset, just delete some system apps and [Install](http://en.wikipedia.org/wiki/Install_%28Unix%29 "Install (Unix)") Xposed framework again and restart your mobile.

## <span style="color: #ff6600;">How to do this ?</span>

### <span style="color: #339966;">If you are in bootloop then follow below procedure :</span>

*   Long Press power button to completely turn off your mobile.
*   Now press and hold volume up and power button to open [Fastboot](http://en.wikipedia.org/wiki/Android_software_development "Android software development") (**[Bootloader](http://en.wikipedia.org/wiki/Booting "Booting")**).
*   Select recovery an press Power button (**to restart your mobile into TWRP recovery**).
*   Now in TWRP recovery goto "**Mount**" and "**Tick/check**" system (**to mount [system partition](http://en.wikipedia.org/wiki/System_partition_and_boot_partition "System partition and boot partition")**).
*   Now come back and goto "**Advance**" and then goto "**file manager**".
*   Now you are in root with Root permissions.
*   Scroll down and select "**system**", then select "**apps**".
*   And delete any unwanted app from here , for example delete "**Google+**" app. which consume 40+ mb of system memory.
*   So now 40+ [MB](http://en.wikipedia.org/wiki/Megabyte "Megabyte") free in system.
*   So come back. And flash Xposed again from **TWRP**. (**no need to restart TWRP to flash Xposed**).
*   After flashing Xposed , you will get successfull message.
*   Now restart your mobile normally.
*   Done.

### [How to install Xposed framework on Asus Zenfone.](https://www.edablogs.com/2016/02/install-xposed-framework-asus-zenfone-lollipop.html "How to install xposed framework on Asus zenfone")

### <span style="color: #ff6600;">Share this post if it helps you to come out from Bootloop.</span>