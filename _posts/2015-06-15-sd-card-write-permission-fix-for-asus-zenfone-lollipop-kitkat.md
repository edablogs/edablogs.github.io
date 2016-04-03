---
layout: post
title: SD card write permission fix for Asus Zenfone Lollipop Kitkat
date: '2015-06-15T12:04:00.000+05:30'
author: pawneshwer
categories:
- asus
- zenfone-5
tags:
- root
- Asus
- zenfone 5
- Android (operating system)
description: SD card write permission fix for Asus Zenfone Lollipop Kitkat, sd card write permission fix for zenfone 5 lollipop, fix sdcard permission zenfone all mobile
keywords: SD card write permission fix for Asus Zenfone Lollipop Kitkat, sd card write permission fix for zenfone 5 lollipop, fix sdcard permission zenfone all mobile
modified_time: '2016-02-20T06:52:55.486+05:30'
thumbnail: http://2.bp.blogspot.com/-NgR86_dF2gc/VX5u4AlwD9I/AAAAAAAAAGY/Cw3R_HNcnvQ/s72-c/unnamed.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-1551051095848384140
blogger_orig_url: http://www.edablogs.com/2015/06/sd-card-write-permission-fix-for-asus-zenfone-lollipop-kitkat.html
redirect_from:
- /2015/06/sd-card-write-permission-fix-for-asus-zenfone-lollipop-kitkat.html
---

## SD card write permission fix for Asus Zenfone Lollipop Kitkat

[![SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,SD card write permission fix for Asus Zenfone Lollipop Kitkat,](http://2.bp.blogspot.com/-NgR86_dF2gc/VX5u4AlwD9I/AAAAAAAAAGY/Cw3R_HNcnvQ/s1600/unnamed.png "SD card write permission fix for Asus Zenfone Lollipop Kitkat")](http://2.bp.blogspot.com/-NgR86_dF2gc/VX5u4AlwD9I/AAAAAAAAAGY/Cw3R_HNcnvQ/s1600/unnamed.png)

Hello guys as you know after Kitkat version update from Google, google has revokes sdcard write permission for third party apps, by that you can't paste data into sdcard if you are using other file manager or any other app which uses to store data in sdcard.  
This create problem that all files will be copied to Phone memory which decreases Internal memory space. You can only write to sdcard from Stock file manager. Rest of other apps doesn't have permission to write into sdcard.  
To fix this issue i m writing this post.  

No need of PC, but for better experience you can use PC.  
st method will work on All android devices which have Android Kitkat or Lollipop. and 2nd methos will only work on Zenfone 5 Lollipop.  
and 3rd option is wait we are making Android app to make it easier.  

#### Caution : This requires Root permission in your mobile. ( Don't know how to Root ??? Read [here](http://www.edablogs.com/2015/02/what-is-root-advantages-and.html) )

### <span style="color: red;">So lets start :</span>

### Method 1 :

*  Download any Root Explorer from playstore.
*  Grant Root permission to that Root Explorer.

[](http://4.bp.blogspot.com/-r1HTFX5E0zs/VX5u9zaNjqI/AAAAAAAAAGo/6nGr4zcntuk/s1600/Screenshot_2015-06-15-11-22-46.png)

*  Mount system as Read/write (**<span style="color: red;">* depends on which Rootexplorer you are using</span>**).
*  Now goto "<span style="color: blue; font-size: large;">_system/etc/permissions/_</span>" folder.
*  here you will find a file name "<span style="color: blue; font-size: large;">_platform.xml_</span>"

[](http://2.bp.blogspot.com/-msbtRXs3xPY/VX5u9y1do3I/AAAAAAAAAGw/3zF-KQq2id8/s1600/Screenshot_2015-06-15-11-23-19.png)

*  open this file in text editor and find below line :

{% highlight xml %}

<permission name="android.permission.WRITE_EXTERNAL_STORAGE" >

{% endhighlight %}

*  and add this line before closing <span style="color: blue;"></permission></span> tag 

{% highlight xml %}

<group gid="media_rw" />

{% endhighlight %}

*  As shown in below screenshot.

[](http://1.bp.blogspot.com/-jjiZXXmpt1Q/VX5u-BwWPfI/AAAAAAAAAGs/yV7Nh8fSrJc/s1600/Screenshot_2015-06-15-11-24-14.png)

*  Now restart your mobile and done.

### Method 2 :

*  This method is only for zenfone 5 Lollipop rom.
*  just download this file and replace in "<span style="color: blue; font-size: large;">/system/etc/permissions/</span>" folder

[Download](http://sh.st/vB2Pw)

### Method 3:

*  If you are unable to understand first 2 methods then wait we are developing Android app which make this task easy just single click.

### if this really helps you then use any below button to share and support us. Thank you.