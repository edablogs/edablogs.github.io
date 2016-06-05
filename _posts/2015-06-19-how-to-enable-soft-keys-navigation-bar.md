---
layout: post
title: 'How to Enable/Disable Soft Keys (Navigation Bar) on any Android Phone (4.0+)
  Without PC '
date: '2015-06-19T05:40:00.000+05:30'
author: Naved Alam
categories:
- android
tags:
- android tricks
- Asus
- zenfone 5
- Android
description: enable soft keys on any android mobile,enable soft buttons on android mobile
keywords: enable soft keys on any android mobile,enable soft buttons on android mobile
modified_time: '2016-02-20T06:52:55.580+05:30'
thumbnail: http://2.bp.blogspot.com/-qrkvqWkjaDM/VYNdu8f51xI/AAAAAAAAJJs/qzbW0_ouPks/s72-c/How-to-Enable-Soft-Keys-.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-9194086104965008946
blogger_orig_url: http://www.edablogs.com/2015/06/how-to-enable-soft-keys-navigation-bar.html
redirect_from:
- /2015/06/how-to-enable-soft-keys-navigation-bar.html
---

{% include JB/setup %}

[![](https://2.bp.blogspot.com/-qrkvqWkjaDM/VYNdu8f51xI/AAAAAAAAJJs/qzbW0_ouPks/s640/How-to-Enable-Soft-Keys-.png)](http://2.bp.blogspot.com/-qrkvqWkjaDM/VYNdu8f51xI/AAAAAAAAJJs/qzbW0_ouPks/s1600/How-to-Enable-Soft-Keys-.png)

## Pre-requisites:-

1. You need to have root access on your device.  

2. Install [Root Explorer](https://play.google.com/store/apps/details?id=com.speedsoftware.rootexplorer&hl=en) or [ES File Explorer](http://www.androidlegend.com/es-file-explorer-all-in-one-file-manager-for-android-smartphones/) or any file manager.  

3. Make sure your device is at least 70% charged to avoid complications during the process.

## Procedure

*   Open Es File Manager or Root Explorer and give root permissions to it (I'm using Es File....... but the process is same so don't worry and if you don't know how to give root permissions then see the images down below)

[![](https://1.bp.blogspot.com/-X5c8QZDmtoY/VYNFsOKNC_I/AAAAAAAAJIU/59hJ3bcqSD0/s320/1.png)](http://1.bp.blogspot.com/-X5c8QZDmtoY/VYNFsOKNC_I/AAAAAAAAJIU/59hJ3bcqSD0/s1600/1.png)

[![](https://2.bp.blogspot.com/-vxsyyFFjA_M/VYNFrtJ-tfI/AAAAAAAAJII/GeXuLd97OoM/s320/2.jpg)](http://2.bp.blogspot.com/-vxsyyFFjA_M/VYNFrtJ-tfI/AAAAAAAAJII/GeXuLd97OoM/s1600/2.jpg)

[![](https://1.bp.blogspot.com/-mAE1EkwsYbs/VYNFsk6bxcI/AAAAAAAAJIc/6y_5gyV9XAU/s320/3.jpg)](http://1.bp.blogspot.com/-mAE1EkwsYbs/VYNFsk6bxcI/AAAAAAAAJIc/6y_5gyV9XAU/s1600/3.jpg)

[![](https://1.bp.blogspot.com/-43SlUHeE3_A/VYNFtEIcCKI/AAAAAAAAJIg/Jt9iA0J5zLA/s320/4.jpg)](http://1.bp.blogspot.com/-43SlUHeE3_A/VYNFtEIcCKI/AAAAAAAAJIg/Jt9iA0J5zLA/s1600/4.jpg)

*   Open Build.prop with text editor (if you don't know how then see the images below and I'm using Asus Zenfone 5 a501cg so my build.prop is build.a501cg.prop ,many devices only have build.prop so don't get confused)

[![](https://2.bp.blogspot.com/-uPTBUhT6h8A/VYNFt83VCHI/AAAAAAAAJI4/wqTn2fTxK6M/s320/5.jpg)](http://2.bp.blogspot.com/-uPTBUhT6h8A/VYNFt83VCHI/AAAAAAAAJI4/wqTn2fTxK6M/s1600/5.jpg)

[![](https://1.bp.blogspot.com/-g07bJ1UwINI/VYNFugIxUOI/AAAAAAAAJI8/v_PX0mGk3sA/s320/6.jpg)](http://1.bp.blogspot.com/-g07bJ1UwINI/VYNFugIxUOI/AAAAAAAAJI8/v_PX0mGk3sA/s1600/6.jpg)

[![](https://1.bp.blogspot.com/-n7vmAnYuH00/VYNFvea9aMI/AAAAAAAAJJI/aLX8zWOTv_0/s320/7.jpg)](http://1.bp.blogspot.com/-n7vmAnYuH00/VYNFvea9aMI/AAAAAAAAJJI/aLX8zWOTv_0/s1600/7.jpg)

[![](https://1.bp.blogspot.com/-Qt8Rd-Ww1Pg/VYNFvyIpC2I/AAAAAAAAJJM/5ILTbicziDI/s320/8.jpg)](http://1.bp.blogspot.com/-Qt8Rd-Ww1Pg/VYNFvyIpC2I/AAAAAAAAJJM/5ILTbicziDI/s1600/8.jpg)

*   Tap on 3 dots on the right hand-side then tap on edit.

[![](https://3.bp.blogspot.com/-OEf2YHVN6fY/VYNFwjuuMVI/AAAAAAAAJJU/VPbFvHLtKFI/s320/9.jpg)](http://3.bp.blogspot.com/-OEf2YHVN6fY/VYNFwjuuMVI/AAAAAAAAJJU/VPbFvHLtKFI/s1600/9.jpg)

*   Now add the following line to this file at the end :- "**_qemu.hw.mainkeys=0_**"

[![](https://2.bp.blogspot.com/-SyCF9g0pM_E/VYNba6JI7AI/AAAAAAAAJJg/xgXzzM1_WQU/s320/Screenshot_2015-06-19-05-26-30%255B1%255D.jpg)](http://2.bp.blogspot.com/-SyCF9g0pM_E/VYNba6JI7AI/AAAAAAAAJJg/xgXzzM1_WQU/s1600/Screenshot_2015-06-19-05-26-30%255B1%255D.jpg)

*   Now press back there's pop like below

[![](https://2.bp.blogspot.com/-lXvZOGNiLAw/VYNFrhVfx5I/AAAAAAAAJIY/P5PALkNrgGM/s320/10.jpg)](http://2.bp.blogspot.com/-lXvZOGNiLAw/VYNFrhVfx5I/AAAAAAAAJIY/P5PALkNrgGM/s1600/10.jpg)

*   Reboot and Enjoy :-)

## HOW TO disable Soft Keys:-If you don't like soft keys and want to disable it 

*   so just add **#** before **qemu.hw.mainkeys=0**,
*   Ex: **#qemu.hw.mainkeys=0** <- like this
*   Reboot and Enjoy :-)

NOTE:- Don't hesitate to ask any question and if you guys want me to make a video on this then tell me in the comments section