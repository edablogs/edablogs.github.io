---
layout: post
title: Install Xposed framework on Zenfone Lollipop (Updated)
date: '2015-06-03T10:26:00.000+05:30'
author: Pawneshwer Gupta
categories:
- android
- zenfone
- xpose
tags:
- xpose
- Android (operating system)
description: Install xposed framework on Zenfone 5, 6, 4.5 Lollipop rom , if you are getting Bootloop while installing Xposed on lollipop then follow this procedure
keywords: Install xposed framework on Zenfone 5, 6, 4.5 Lollipop rom , if you are getting Bootloop while installing Xposed on lollipop then follow this procedure
modified_time: '2016-02-20T06:52:55.514+05:30'
thumbnail: http://2.bp.blogspot.com/-_X_PXWGkQfs/VW6GP-I7v8I/AAAAAAAAAFM/eLcZCiUGez4/s72-c/logo.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-3964683605522846059
blogger_orig_url: http://www.edablogs.com/2015/06/install-xposed-framework-on-zenfone-lollipop.html
redirect_from:
- /2015/06/install-xposed-framework-on-zenfone-lollipop.html
---

[![Install Xposed framework on Zenfone Lollipop](http://2.bp.blogspot.com/-_X_PXWGkQfs/VW6GP-I7v8I/AAAAAAAAAFM/eLcZCiUGez4/s320/logo.jpg "Install Xposed framework on Zenfone Lollipop")](http://2.bp.blogspot.com/-_X_PXWGkQfs/VW6GP-I7v8I/AAAAAAAAAFM/eLcZCiUGez4/s1600/logo.jpg)

Hello **Asus Zenfone** users, Recently Lollipop is officially launched by Asus for all **zenfone** models. so there is big change from **Kitkat to Lollipop**, And compatibility of some apps has gone. In same way **xposed framework** also not supporting on lollipop. So Developer of **_xposed framework_** has release [Alpha version](http://en.wikipedia.org/wiki/Software_release_life_cycle "Software release life cycle") to make it compatible on **Lollipop ROM** too. but unfortunatly some zenfone series have x86 (32 bit) processor. So xposed framework not working on zenfone mobiles. So **Shakalaka** has made it working on Zenfone too. he has compiled it from xposed framework Sources.  

_<span style="color: red; font-size: large;">Latest updated on 20-june-2015 to fix bootloop problem after uninstalling xposed. (</span><span style="color: #38761d; font-size: large;">* Now you can uninstall xposed anytime</span><span style="color: red; font-size: large;">).</span>_

### How to install :

## <span style="font-weight: normal;"><span style="font-size: large;"><span style="color: red;">Also read :</span> [install Xposed framework using custom recovery without PC](http://www.xdablogs.com/2015/07/install-xposed-framework-zenfoen-5-lollipop.html)</span></span>

#### For [Windows](http://en.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows") users :

*   first of all Download xposed Installer Alpha from link below

[Download](https://userscloud.com/ahfz6utqm8aw)

*   After Downloading extract all files into a folder anywhere on your [PC](http://en.wikipedia.org/wiki/Personal_computer "Personal computer"). as shown below

[](http://1.bp.blogspot.com/-i5GMBMx37I8/VW6HLf_dWjI/AAAAAAAAAFU/bNO77z8CBXU/s1600/1.png)

*   Now double click on "**_<span style="color: red;">InstallxposedInstaller.bat</span>_**", this will install xposed app on your mobile.
*   After Successful install double click on "<span style="color: red;">**_InstallxposedFramework.bat_**</span>" file, this will install framework files in system.
*   To uninstall simply double click on "_**<span style="color: red;">RemovexposedFramework.bat</span>**_" and done.

#### For MAC users :

*   You need to only run "**_<span style="color: red;">install.sh</span>_**" file and done.
*   To remove xposed run "<span style="color: red;">**_remove.sh_**</span>"

## <span style="font-size: large; font-weight: normal;"><span style="color: red;">Check</span> [here](http://www.xdablogs.com/2015/06/list-of-working-xposed-modules-for-asus-zenfone-lollipop.html) <span style="color: red;">some working and Non working xposed modules in Zenfone Lollipop</span></span>

### How to prevent from Bootloop After xposed :

if you have enable some xposed module which is not supported with xposed alpha or your mobile, then your mobile will be stuck on Asus LOGO. and is latest Lollipop ROM recovery is inside system partition, means if your mobile not starting then you also unable to go into recovery mode. So you cant reset your mobile. (<span style="color: red;">* to make recovery to work on Lollipop when you are unable to start recovery, just flash recovery.img from old Kitkat rom</span>).

So to recover from Bootloop without factory reset just install "**_TWRP recovery_**" on your mobile.   

*   Download TWRP recovery for Zenfone 5 from below link. How to install TWRP recovery read here  (<span style="color: red;">* this method is for installing Philz recovery, method is same the only difference of recovery name</span>)

[Read this thread](http://www.xdablogs.com/2015/06/twrp-recovery-for-zenfone-5-stable.html)

*   After installing TWRP recovery go into recovery mode by going into **Bootloader** mode and select "**Recovery**".
*   after selecting recovery you will be unable to start recovery, so just reboot your mobile and you will into TWRP recovery.
*   Now you are in TWRP recovery goto "**_File Manager_**" and open "**_data_**" folder then again open "**_data_**" folder then  open "**_de.robv.android.xposedd.installer_**" there will be folder name "**_shared_prefs_**" open that folder and delete "**_enabled_modules.xml_**" file.
*   now restart your mobile and your mobile will start normally and you need to enable xposed modules again. so now be careful before enabling modules.