---
layout: post
title: Enable init.d support on any Android Mobile
date: '2015-04-14T02:37:00.000+05:30'
author: pawneshwer
categories:
- android
- root
tags:
- root
- Android
description: enable init.d support on any android mobile using terminal, init.d tweaks for all android version. easy way to enable init.d support, more free RAM using init.d
keywords: enable init.d support on any android mobile using terminal, init.d tweaks for all android version. easy way to enable init.d support, more free RAM using init.d
modified_time: '2016-02-20T06:52:55.502+05:30'
thumbnail: https://3.bp.blogspot.com/--D8b__r-25s/VUSy2IgFjeI/AAAAAAAAATs/kc6J6EQF4HA/s72-c/init.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-3059719377235245799
blogger_orig_url: http://www.edablogs.com/2015/04/enable-initd-support-on-any-android.html
redirect_from:
- /2015/04/enable-initd-support-on-any-android.html
---

{% include JB/setup %}

## <span style="color: green;">Enable init.d support on any Android Mobile</span>

![](https://3.bp.blogspot.com/--D8b__r-25s/VUSy2IgFjeI/AAAAAAAAATs/kc6J6EQF4HA/s1600/init.jpg)

Hello guys, I m here with another tweak for [Android](http://en.wikipedia.org/wiki/Android_%28operating_system%29 "Android (operating system)") mobiles. This post is only for Super users. Means proceed to this post if you are rooted your mobile, or if you are thinking about rooting your mobile then read [this post](http://xdablogs.com/android/root-advantages-disadvantages-root/2542/ "What is Root, Advantages and Disadvantages of Root") to Root your mobile. If you don't interested in rooting your mobile then leave this post. Thank you.

So let me explain about _**[init](http://en.wikipedia.org/wiki/Init "Init").d support**_. init.d is basically a trick to support _**sh scripts**_ on your android mobile on start-up. When any android mobile starts first of all it loads _**init.d scripts**_ if exists, and then proceed to booting process. So if you have enabled _**init.d support**_ and you have put init script to speed-up startup process of your mobile. then when your mobile start android will search for _**init.d**_ folder, if OS found _**init.d**_ folder then this will search for any script installed in _**init.d**_ folder and execute that script. In this way you can enable many tweaks without using any app. init scripts run on background and doesn't consume _**[RAM](http://en.wikipedia.org/wiki/Random-access_memory "Random-access memory")**_ and its only in bytes in size, that is main benefit of using _**init scripts**_ instead of Apps.

Now you are thinking about what is sh script and how it works, sh scripts are Linux scripts with commands. you can found many _**init scripts**_ on internet and I ll also provide you some _**init scripts**_. _**init scripts**_ are more effective than any app. if you are using any app to speed up startup time of your mobile then that app start running when your mobile start. but if you use _**init script**_ to speed-up startup time then init script execute first.

### Which init scripts are available :

1.  RAM booster
2.  Cache cleaner
3.  Startup speed optimizer.
4.  Touch Response optimizer
5.  swap system partition. (that is awesome script which swap system memory to your SDCARD, so if you have less phone storage in you mobile then use this script and use sdcard and phone storage. this is more useful for old mobiles which have only 100mb inter memory and 200mb system memory. so by using this script you can increase Internal memory from 100 mb to 1GB or more according to your need.)
6.  [WIFI](http://en.wikipedia.org/wiki/Wi-Fi "Wi-Fi") optimizer.
7.  wi-fi sleeper.
8.  Battery optimizer.
9.  free up more memory.
10.  [GPU](http://en.wikipedia.org/wiki/Graphics_processing_unit "Graphics processing unit") Rendering
11.  SDCard boost.
12.  Increase SD card Read/Write speed
13.  loopy smoothness tweaks
14.  Zipalign
15.  Sqlite optimize.
16.  [DNS](http://en.wikipedia.org/wiki/Domain_Name_System "Domain Name System") optimizer
17.  Governor tweaks
18.  Kill media server.

### So how to enable init.d support ?

*   So now you are rooted, and install [_**busybox**_](https://play.google.com/store/apps/details?id=stericson.busybox&hl=en "busybox"), and [_**Terminal**_](https://play.google.com/store/apps/details?id=jackpal.androidterm&hl=en "terminal for mobile") in your mobile. and proceed to next step

*   Download _**init.sh.zip**_ file from link below and extract into _sdcard_.

[](http://1.bp.blogspot.com/-E1BrYreCcXk/VUS0yzPZb7I/AAAAAAAAAT4/pUyta-6sUrY/s1600/Screenshot_2015-04-13-19-47-23.jpg)

[Download](https://www.dropbox.com/s/390n53lwx4ji3wm/init.sh.zip?dl=1 "init.sh")

*   Now copy _**init.sh**_ file to "<span style="color: blue;">_**/system**_</span>" partition as shown above.
*   Now open **Terminal app** which you have downloaded earlier, and type

[](http://4.bp.blogspot.com/-DCBLvdPQq7Q/VUS03e9MrNI/AAAAAAAAAUA/GLrWSWZIHgw/s1600/Screenshot_2015-04-13-19-47-31.jpg)

<span id="goog_953327378"></span><span id="goog_953327379"></span>  

> <span style="color: blue;">_**su**_</span> and press enter  
> then allow superuser permissions.  
> now type " <span style="color: blue;">_**cd system**_</span>"  
> now you are in system folder so type " <span style="color: blue;">_**sh ./init.sh**_</span>" and press enter

[](http://2.bp.blogspot.com/-Gl3RkLJGl1E/VUS0-17tQ5I/AAAAAAAAAUQ/wcLxP34nWkg/s1600/Screenshot_2015-04-13-19-48-00.jpg)[](http://2.bp.blogspot.com/-OHUfzXYu3JE/VUS09G7rbjI/AAAAAAAAAUI/cLmvQI_Kuts/s1600/Screenshot_2015-04-13-19-48-15.jpg)

*   Now follow On screen Instructions
*   And done.

[](http://4.bp.blogspot.com/-wZrL1KOPzQo/VUS1AEflIOI/AAAAAAAAAUY/cG2PeEME6vA/s1600/Screenshot_2015-04-13-19-48-41.jpg)

Now you have enabled _**init.d support**_ in your mobile and you can find _**init.d**_ folder in "_**<span style="color: blue;">/system/etc/</span>**_" folder. So if you found any _**init.d script**_ then paste this _**init.d**_ folder and set its permission to "**_<span style="color: blue;">777</span>_**" means check all permissions. and Restart your mobile and your script is enabled now.  
But if you don't set right permission and restarted your mobile then correct permissions will set automatically because in _**init.d**_ folder there is a script called fixperms which set correct permission on every restart.  
So Enjoy tweaks on your mobile. here is my collection of **init.d** Download from below link.  

[Download](https://www.dropbox.com/s/1dussrg6ne4tsxm/init.d%20tweaks.zip?dl=1 "init tweaks")

Great thanks to Ryuinferno @ XDA member for making this script.

### Note : use these scripts on your own risk, if you have used any script which disable boot or any app which requires at startup this may cause bootloop.