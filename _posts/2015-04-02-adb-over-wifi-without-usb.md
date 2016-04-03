---
layout: post
title: adb over wifi without usb
date: '2015-04-02T01:41:00.000+05:30'
author: pawneshwer
categories:
- computer
tags:
- computer
- Computer Tricks
- Android
description: 
keywords: 
modified_time: '2016-02-20T06:52:55.489+05:30'
thumbnail: http://1.bp.blogspot.com/-8CjwpeiMofg/VUTKvaxb6MI/AAAAAAAAAWI/QJx2qH0HgGU/s72-c/unnamed.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-1905915439578219985
blogger_orig_url: http://www.edablogs.com/2015/04/adb-over-wifi-without-usb.html
redirect_from:
- /2015/04/adb-over-wifi-without-usb.html
---

## <span style="color: green;">adb over wifi without usb</span>

![adb over wifi without usb](http://1.bp.blogspot.com/-8CjwpeiMofg/VUTKvaxb6MI/AAAAAAAAAWI/QJx2qH0HgGU/s1600/unnamed.png "adb over wifi without usb")

Hello guys if you are using _**mobile ADB**_ instead of emulator for developing _android apps_ , or just wanna use ADB commands on mobile from [PC](http://en.wikipedia.org/wiki/Personal_computer "Personal computer") then you need to connect your mobile to PC and configure _ABD drivers_ for your mobile, without drivers you can't use  **_mobile ADB_**. that is limitation of windows that you need to configure drivers for new devices, but if you don't have drivers and not found drivers for your mobile over internet then what should you do?

So to use _**ADB over wifi**_ you only need an android app installed on your mobile which is **_54kb_** only in size. and you need to configure _**ADB on PC**_, i m sure that you have configured 

So no need of drivers to use mobile as ADB on PC, and you can build your Android app efficiently, cause ADT emulator consume a lot of RAM which may slow down your PC or laptop. Therefore solution for this is using your _**Android mobile as ADB**_.

### How to configure ?

for this procedure your mobile and PC should be connected to _**same wi-fi network**_.( if you are using Laptop and don't have wi-fi then install connectify on laptop , create hotspot using**_connectify_** and connect your mobile)

### on mobile :

*   first of all configure tool on mobile, install this app from [playstore](https://play.google.com/store/apps/details?id=bohlool.net.wifiadb)
*   After installing this app, long _press on_ homescreen and select **_widgets_**.

[](http://4.bp.blogspot.com/-YzYdK4L-bGA/VUTKzkY0ttI/AAAAAAAAAWQ/mIqWEWPfAVA/s1600/1.jpg)

*   tap on _**ADB over [Wifi](http://en.wikipedia.org/wiki/Wi-Fi "Wi-Fi")**_ to create widget on _homescreen_.

[](http://3.bp.blogspot.com/-0GWf9mroUy4/VUTK0W4-BxI/AAAAAAAAAWU/YalSmfOoN2w/s1600/2.jpg)

*   Now _settings_ will open just _scroll down_ and tap on _**OK**_

[](http://1.bp.blogspot.com/-O0rU5EvaAVM/VUTK1D6xqiI/AAAAAAAAAWg/yT-gAIw3P5g/s1600/3.png)

*   now you have configured ADB on mobile to _turn on_ ADB just _tap on_ _ABD widget_ on homescreen and this will show you _[IP address](http://en.wikipedia.org/wiki/IP_address "IP address") and Port_. (* that ip and port help us to connect to PC in my [mobile ip](http://en.wikipedia.org/wiki/Mobile_IP "Mobile IP") and port , for example that is my ip and port <span style="color: blue;">**192.168.1.103:5555**</span> )

[](http://1.bp.blogspot.com/-GH6Y4JQr5_M/VUTK3MXHyHI/AAAAAAAAAWo/xrADCnagSaQ/s1600/4.jpg)

### Now come to PC :

*   if you have configured ADB on your PC then its too good if not configured then download ADB from this [link](https://drive.google.com/file/d/0B2G6mkqvibyoZ29MU3dJcTVtVVE/view?usp=sharing) (_<span style="color: red;">* 500 kb only</span>_).
*   _Extract_ adb to files to a folder and _open that folder_.
*   now _press and hold_ _**shift key**_ and _right click_ on _empty place_ on that folder and select _**open command prompt here**_.

[](http://3.bp.blogspot.com/-PM298LrOehU/VUTK8pOzMNI/AAAAAAAAAW4/pi_pwDESPrQ/s1600/pc1.png)

*   Now CMD will open and type **_adb connect ipaddress:port_** (* for example **<span style="color: blue;">adb connect 192.168.1.103:5555</span>** )

[](http://1.bp.blogspot.com/-Uu1Y8szVylk/VUTK7imvjQI/AAAAAAAAAWw/I4WIydklfrs/s1600/pc2.png)

*   and press enter wait for few seconds and this will display message **_connected_**.

*   Thats it you have done.

if in _eclipse_ you are getting error No active device found that open CMD again and again type adb connect your ip:port command. Now enjoy ADB wirelessly no need to carry [USB cable](http://en.wikipedia.org/wiki/Universal_Serial_Bus "Universal Serial Bus") every where.