---
layout: post
title: Lock/unlock bootloader in asus zenfone
date: '2015-07-05T18:29:00.000+05:30'
author: Pawneshwer Gupta
categories:
- asus
- zenfone
tags:
- Asus
- Android (operating system)
description: how to lock bootloader in asus zenfone, how to unlock bootloader in asus zenfone,easy way to relock bootloader in asus zenfone,unlock bootloader easily zenfone
keywords: how to lock bootloader in asus zenfone, how to unlock bootloader in asus zenfone,easy way to relock bootloader in asus zenfone,unlock bootloader easily zenfone
modified_time: '2016-02-20T06:52:40.015+05:30'
thumbnail: http://4.bp.blogspot.com/-36rBExUNfF4/VZkoJHDaMBI/AAAAAAAAGws/PLOY_7vxxI0/s72-c/Lock-unlock-bootloader-in-asus-zenfone-logo.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-9210853131149599029
blogger_orig_url: http://www.edablogs.com/2015/07/Lock-unlock-bootloader-in-asus-zenfone.html
redirect_from:
- /2015/07/Lock-unlock-bootloader-in-asus-zenfone.html
---

## <span style="text-align: justify;">How to Lock / Unlock Bootloader in asus zenfone</span>

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-36rBExUNfF4/VZkoJHDaMBI/AAAAAAAAGws/PLOY_7vxxI0/s1600/Lock-unlock-bootloader-in-asus-zenfone-logo.png "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-36rBExUNfF4/VZkoJHDaMBI/AAAAAAAAGws/PLOY_7vxxI0/s1600/Lock-unlock-bootloader-in-asus-zenfone-logo.png)

So you know [custom recovery](http://www.edablogs.com/2015/06/twrp-recovery-for-zenfone-5-stable.html) for **_asus zenfone 5_** is out, and you can install on your mobile to take some advantages. but there is 1 disadvantage of installing **_TWRP custom recovery_** is that you will not receive [OTA update](http://en.wikipedia.org/wiki/Over-the-air_programming "Over-the-air programming"). if you got **_OTA_** update then this will give error while installing.  

### In this Example i am using Zenfone 5

## Why we need to unlock bootloader :

1.  The basic need of **_unlocking bootloader_** is to **_flash custom recovery_**.
2.  To **_Root_** your mobile.
3.  And for other modification.

## Why we need to Relock again :

1.  To get official **_OTA_** we need to **_re-lock bootloader_** , if you have **_unlocked bootloader_** and you are trying to update mobile through _**OTA**_ you will get error while installing Updates. Thats why we need to **_Re-lock bootloader_**.

## So what to do now?

So solution for this is install stock recovery and **_relock your Bootloader_**.After installing _**OTA**_ again install **_TWRP recovery_**.You don't need to download [files](http://en.wikipedia.org/wiki/Computer_file "Computer file") to _**relock bootloader**_.Cause unlock and **relock files** are inside **stock ROM**.So just extract that files to any folder to start **unlocking** procedure. But to start relocking you need to take attention on some aspects as follow:

### Requirements :

1.  ADB files. (<span style="color: red;">* if you don't have then download from below button )</span>

[Download ADB](https://dl.dropboxusercontent.com/u/55163217/adb.zip)

1.  current rom installed on your mobile. (<span style="color: red;">* to get relocking files</span>)
2.  [PC](http://en.wikipedia.org/wiki/Personal_computer "Personal computer") (<span style="color: red;">windows / [<span style="color: red;">Linux</span>](http://en.wikipedia.org/wiki/Linux "Linux") or MAC</span>)

## How to Relock bootloader in Zenfone :

1.  First of all extract **ADB files** in a folder.

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-WxwE8PFhyi4/VZkoMpB2fyI/AAAAAAAAGw4/AGv7LrW8yBE/s320/Lock-unlock-bootloader-in-asus-zenfone-1.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-WxwE8PFhyi4/VZkoMpB2fyI/AAAAAAAAGw4/AGv7LrW8yBE/s1600/Lock-unlock-bootloader-in-asus-zenfone-1.jpg)

1.  Now extract **<span style="color: blue;">ifwi.zip</span>** file from stock rom. as show below.

[![How to Lock / Unlock Bootloader in asus zenfone](http://2.bp.blogspot.com/-vfsXk2cRE6s/VZkoNNVC4aI/AAAAAAAAGxA/unbMfA3Ka8c/s320/Lock-unlock-bootloader-in-asus-zenfone-2.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://2.bp.blogspot.com/-vfsXk2cRE6s/VZkoNNVC4aI/AAAAAAAAGxA/unbMfA3Ka8c/s1600/Lock-unlock-bootloader-in-asus-zenfone-2.jpg)

1.  Now extract all contents from **ifwi.zip** to **ADB** folder.

[![How to Lock / Unlock Bootloader in asus zenfone](http://3.bp.blogspot.com/-Q7qrSVcZqJs/VZkoN6YK6iI/AAAAAAAAGxE/HOQ64hlONZI/s320/Lock-unlock-bootloader-in-asus-zenfone-3.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://3.bp.blogspot.com/-Q7qrSVcZqJs/VZkoN6YK6iI/AAAAAAAAGxE/HOQ64hlONZI/s1600/Lock-unlock-bootloader-in-asus-zenfone-3.jpg)

1.  And also extract **recovery.img** file from **ROM** to **ADB** folder.
2.  Now reboot your mobile into **Fastboot** (<span style="color: red;">Droidboot</span>).
3.  Now press **Shift key** and **Right click** any where in **ADB folder** and select "**Open command window here"**, and use following commands 1 by 1.

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-c3EtTp_HXxw/VZkoO3ki7zI/AAAAAAAAGxY/32BCvKlK_TM/s320/Lock-unlock-bootloader-in-asus-zenfone-4.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-c3EtTp_HXxw/VZkoO3ki7zI/AAAAAAAAGxY/32BCvKlK_TM/s1600/Lock-unlock-bootloader-in-asus-zenfone-4.jpg)

> <span style="color: blue; font-size: large;">[fastboot](http://en.wikipedia.org/wiki/Android_software_development "Android software development") flash recovery recovery.img  
> fastboot flash dnx dnx_fwr_ctp_a500cg.bin  
> fastboot flash ifwi ifwi_ctp_a500cg.bin</span>

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-ZP8j8Z5FSbw/VZkoO6Wbw1I/AAAAAAAAGxU/JclntbnIEnc/s320/Lock-unlock-bootloader-in-asus-zenfone-5.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-ZP8j8Z5FSbw/VZkoO6Wbw1I/AAAAAAAAGxU/JclntbnIEnc/s1600/Lock-unlock-bootloader-in-asus-zenfone-5.jpg)

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-eqbQERfrG0Y/VZkoPOBJD6I/AAAAAAAAGxc/6oNh2c9PCY0/s320/Lock-unlock-bootloader-in-asus-zenfone-6.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-eqbQERfrG0Y/VZkoPOBJD6I/AAAAAAAAGxc/6oNh2c9PCY0/s1600/Lock-unlock-bootloader-in-asus-zenfone-6.jpg)

[![How to Lock / Unlock Bootloader in asus zenfone](http://4.bp.blogspot.com/-xKn2SiaDvH0/VZkoRT0-nuI/AAAAAAAAGxk/qCJ6Ne871es/s320/Lock-unlock-bootloader-in-asus-zenfone-7.jpg "How to Lock / Unlock Bootloader in asus zenfone")](http://4.bp.blogspot.com/-xKn2SiaDvH0/VZkoRT0-nuI/AAAAAAAAGxk/qCJ6Ne871es/s1600/Lock-unlock-bootloader-in-asus-zenfone-7.jpg)

1.  And you have **_locked bootloader_** successfully.

## How to unlock bootloader in Zenfone :

1.  Follow **1 to 5** steps above (<span style="color: red;">* as given for relocking but we don't need recovery.img</span>)
2.  Now use these commands:

> <span style="color: blue; font-size: large;">fastboot flash dnx dnx_fwr_ctp_a500cg.bin  
> fastboot flash ifwi ifwi_ctp_a500cg_unlock.bin</span>

1.  Done now **_bootloader unlocked_** successfully.

### <span style="color: red;">Like us on facebook and share with your friends if this post helpful for you.</span>