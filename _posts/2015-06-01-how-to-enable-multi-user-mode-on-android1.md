---
layout: post
title: How to enable Multi user mode on Android
date: '2015-06-01T07:58:00.000+05:30'
author: pawneshwer
categories:
- android
- root
tags:
- Multi-user
- root
- Android (operating system)
description: enable multi user mode by editing build.prop, without any app, create multiple profile on android, enable guest mode on android mobile. supports on all
keywords: enable multi user mode by editing build.prop, without any app, create multiple profile on android, enable guest mode on android mobile. supports on all
modified_time: '2016-02-20T06:52:55.574+05:30'
thumbnail: http://2.bp.blogspot.com/-P8eaZe-Acig/VWu_MKbN_bI/AAAAAAAAGhc/O6-Xpw8FcDo/s72-c/1.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-8617575011139701742
blogger_orig_url: http://www.edablogs.com/2015/05/how-to-enable-multi-user-mode-on-android1.html
redirect_from:
- /2015/05/how-to-enable-multi-user-mode-on-android1.html
---

{% include JB/setup %}

## How to enable Multi user mode on Android

[![How to enable Multi user mode on Android](http://2.bp.blogspot.com/-P8eaZe-Acig/VWu_MKbN_bI/AAAAAAAAGhc/O6-Xpw8FcDo/s1600/1.jpg "How to enable Multi user mode on Android")](http://2.bp.blogspot.com/-P8eaZe-Acig/VWu_MKbN_bI/AAAAAAAAGhc/O6-Xpw8FcDo/s1600/1.jpg)

Hello guys Android 5.0 Lollipop is coming with Multi users support and officially provided by google. But in some devices due to there product venders [Multi user](http://en.wikipedia.org/wiki/Multi-user "Multi-user") mode is not available, like Asus Zenfone 5\. So you can enable multi user mode on that devices without any software. You need to just edit build.prop file in system. and Done. But you need to Root your mobile. Read here how to Root Android Mobile & Tablet This method will also work on Android 4.4 Kitkat. and you can also try on Android 4.2 Jelly Bean or other Android version.  

### Requirements:

*   Rooted Mobile (<span style="color: red;">*</span> [how to root](http://www.edablogs.com/2015/02/what-is-root-advantages-and.html))
*   any Root Explorer ( <span style="color: red;">* we used ES</span> [File manager](http://en.wikipedia.org/wiki/File_manager "File manager"))

### How to :

*   First of all Root your mobile if you haven't Rooted yet.  (<span style="color: red;">* Read [here](http://www.xdablogs.com/2015/02/what-is-root-advantages-and.html) Advantages and Disadvantages of Root</span> )
*   Now Install ES File manager in your mobile from [Play store](https://play.google.com/store/apps/details?id=com.estrongs.android.pop&hl=en "ES File manager")
*   Goto **<span style="color: blue;">/system</span>** and you will get file name build.prop
*   Open that file in [text editor](http://en.wikipedia.org/wiki/Text_editor "Text editor") and add this line at botton of file

> <span style="color: blue;">fw.max_users=3</span>  
> <span style="color: blue;">fw.show_multiuserui=1</span>

[](http://2.bp.blogspot.com/-2qHsNGTMRTs/VWu_On1_lrI/AAAAAAAAGh4/h286i8wEkz0/s1600/Screenshot_2015-03-26-18-12-25.png)

*   Now Restart you mobile and done.

You can change fw.max_users=3 to 4 or more it depends on How much user profile you want in your mobile.  

[](http://3.bp.blogspot.com/-5n5I7ujhfm0/VWu_Mfgx2sI/AAAAAAAAGhg/hh7nf0OfAWk/s1600/Screenshot_2015-03-26-17-45-33.png)[](http://2.bp.blogspot.com/-XBISUaVamsE/VWu_M0Dk_cI/AAAAAAAAGho/U7Mk3xrQfEY/s1600/Screenshot_2015-03-26-18-05-55.png)

[](http://4.bp.blogspot.com/-KGBtROlVnPs/VWu_OYFBPWI/AAAAAAAAGh0/8tDDrmDKMLw/s1600/Screenshot_2015-03-26-18-06-23.png)

Credits to [arpanbag1996](http://forum.xda-developers.com/member.php?s=c4796d11de17e65b7deaba774d6bc4c5&u=6200498)