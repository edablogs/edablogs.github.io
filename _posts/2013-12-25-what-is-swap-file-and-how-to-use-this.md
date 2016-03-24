---
layout: post
title: What is swap file and how to use this to increase RAM
date: '2013-12-25T01:44:00.000+05:30'
author: Pawneshwer Gupta
categories:
- tutorial
- root
tags:
- tutorial
- root
modified_time: '2016-02-20T06:51:59.267+05:30'
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-4801768043020180370
blogger_orig_url: http://www.edablogs.com/2013/12/what-is-swap-file-and-how-to-use-this.html
redirect_from:
- /2013/12/what-is-swap-file-and-how-to-use-this.html
---

<div dir="ltr" style="text-align: left;" trbidi="on"><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">Swap file is a memory partition in your sdcard which can be used as RAM. Actually its not a partition but it allocate memory on sdcard. By using swap file you dont need create partition of your sdcard. Because android is Linux and linux need swap partition on harddrive to use as a RAM and increase performance of your PC. And same this method is used in android mobiles. So if you create swap partition in sbcard then you are unable to create another ext4 partition in your sdcard. Ext4 partition is used to install your apps. Means we mount that ext4 drive as intetnal memory and install apps in that memory by using link2sd app. Read this post to use link2sd app to increase internal memory.&nbsp;</span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">So swap file works as RAM in our android mobiles.</span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;"><br /></span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">How it works?</span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">So when we play hd games in our mobile then it will play that game in swap file and not use your RAM. Means no low RAM problem.occurring while playing games. But it work fine in some devices. In some devices its not working. So try on yout device and comment below its working or not.</span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">For better performance use high speed memory card. I recommends you to use class 10 memory card. It havr faster than other classes. But its costly.</span></div><div class="MsoNormal"><span class="Apple-style-span" style="font-family: Georgia, serif;"><span class="Apple-style-span" style="font-size: 17px; line-height: 18px;"><br /></span></span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">To check that swap file in working in your mobile then download terminal emulator from playstore. In terminal emulator type "free" if it shows swap **** some value. It means swap file is working and you can check free swap file in current swapfile.</span></div><div class="MsoNormal"><span style="font-family: &quot;Georgia&quot;,&quot;serif&quot;; font-size: 13.0pt; line-height: 107%;">For example if you have created 512 mb swapfile, then it will show 512 mb in kbs and after that free swap size that should be 510 md or else.</span></div></div>