---
layout: post
title: Replace system files using CMD unbricking method
date: '2015-02-22T22:33:00.000+05:30'
author: pawneshwer
categories:
- android
- asus
- zenfone-5
tags:
- kitkat
- Asus
- zenfone 5
- Android
modified_time: '2016-02-20T06:52:55.533+05:30'
thumbnail: http://3.bp.blogspot.com/-xV1zs-AJgcc/VU3iNpZvukI/AAAAAAAAAn4/_FAXm6DGS58/s72-c/cmd.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-5083698206046016127
blogger_orig_url: http://www.edablogs.com/2015/02/replace-system-files-using-cmd.html
redirect_from:
- /2015/02/replace-system-files-using-cmd.html
---

{% include JB/setup %}

<div dir="ltr" style="text-align: left;" trbidi="on"><h2><span style="color: #339966;">Replace system files using CMD unbricking method</span></h2><div class="separator" style="clear: both; text-align: center;"><img alt="Replace system files using CMD unbricking method" border="0" src="http://3.bp.blogspot.com/-xV1zs-AJgcc/VU3iNpZvukI/AAAAAAAAAn4/_FAXm6DGS58/s1600/cmd.jpg" title="Replace system files using CMD unbricking method" /></div>Hello friends if you want to replace <b>Systemui.apk</b> , <b>framework-res.apk</b> or other <b>system file</b> to your mobile. But you want a safe method to replace files without getting <b>bootloop</b> or <b>bricked</b>. Then follow my steps.<br />These steps helps you when you are not using <a href="http://www.xdablogs.com/search/label/Custom%20recovery" target="_blank" title="Latest philZ recovery for Asus zenfone 5"><b>custom recovery</b></a> to flash updates. And you have replaced any system file using <b>root explorer</b> or any <b>other app</b>, and you got <b>force close</b> and you want to revert back or want to flash again.<br />In this example i'm telling how to replace <b>SystemUI.apk</b> and delete <b>SystemUI.odex</b> file from your mobile.<br /><h3><div class="alert alert-info" role="alert">Follow these steps:-</div></h3><ul><li>If you have configured <b>ADB</b> to your computer then its easy to follow these steps.</li><li>Copy <b>SystemUI.apk</b> into a folder anywhere on your pc.</li><li>Now press "<b>Shift</b>" key and <b>right click</b> on blank page and select "<b>Open command window here</b>".</li></ul><div class="separator" style="clear: both; text-align: center;"><a target="_blank" href="http://3.bp.blogspot.com/-zcqSxlc8OJg/VU3jXvIZAaI/AAAAAAAAAoE/vuiJI2GJqbc/s1600/p1.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img alt="Replace system files using CMD unbricking method" border="0" class="lazy" data-src="http://3.bp.blogspot.com/-giUfAtacyFQ/VU3jt1EbLBI/AAAAAAAAAoU/2RbxEngZ19Y/s1600/p1-300x200.jpg" title="Replace system files using CMD unbricking method" /></a></div><ul></ul><br /><ul><li>open <b>cmd</b> and type following</li><li>In <b>CMD</b> type <span style="color: blue;"><b>adb shell</b></span></li></ul><span style="color: blue;"><b><div class="separator" style="clear: both; text-align: center;"><a target="_blank" href="http://2.bp.blogspot.com/-0VLk48xUWnw/VU3jXvw2UyI/AAAAAAAAAoA/A1p-3PFbWrI/s1600/p2.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img alt="Replace system files using CMD unbricking method" border="0" class="lazy" data-src="http://2.bp.blogspot.com/-taSpuj9QGF0/VU3jt8aWZJI/AAAAAAAAAoQ/byRc0VjJ_mA/s1600/p2-300x200.jpg" title="Replace system files using CMD unbricking method" /></a></div></b></span><div><ul></ul><br /><ul><li>Now type <b><span style="color: blue;">su</span></b> (<span style="color: red;">to get superuser permissions</span>)</li><li>Now type <span style="color: blue;"><b>mount -o rw,remount /system</b></span> (<span style="color: red;">to mount system as Read/Write</span>)</li><li>Now type <span style="color: blue;"><b>cp /sdcard/SystemUI.apk /system/priv-app</b></span> (<span style="color: red;">to copy and replace systemui in system</span>)</li><li>if you want to copy <b>framework-res.apk</b> then type <span style="color: blue;"><b>cp /sdcard/framework-res.apk /system/framework</b></span> (<span style="color: red;">to copy and replace framework-res in framework</span>)</li><li>Now type <span style="color: blue;"><b>rm /system/SystemUI.odex</b></span> (<span style="color: red;">to delete odex file of systemui</span>)</li><li>Now type <span style="color: blue;"><b>reboot</b></span> (<span style="color: red;">to reboot yor mobile</span>)</li><li>That’s it.</li></ul></div></div>