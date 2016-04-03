---
layout: post
title: Easiest way to Solve windows Installation error
date: '2015-05-16T00:50:00.000+05:30'
author: pawneshwer
categories:
- windows
tags:
- Computer Tricks
- Windows
description: windows cant install to this hard disk space the selected disk has the maximum number of partitions of this type windows installation error solution
keywords: windows cant install to this hard disk space the selected disk has the maximum number of partitions of this type windows installation error solution
modified_time: '2016-02-20T06:52:55.535+05:30'
thumbnail: http://1.bp.blogspot.com/-Qzgsf-WpyoQ/VVZE1zfw33I/AAAAAAAAADM/W3iMF8y8azE/s72-c/3-526x372.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-5171929102246965935
blogger_orig_url: http://www.edablogs.com/2015/05/easiest-way-to-solve-windows-Installation-error.html
redirect_from:
- /2015/05/easiest-way-to-solve-windows-Installation-error.html
---

## <span style="color: green;">Easiest way to Solve windows Installation error</span>

![windows cant install to this hard disk space the selected disk has the maximum number of partitions of this type](http://1.bp.blogspot.com/-Qzgsf-WpyoQ/VVZE1zfw33I/AAAAAAAAADM/W3iMF8y8azE/s320/3-526x372.png "windows cant install to this hard disk space the selected disk has the maximum number of partitions of this type")

Hello guys if you are going to [dual boot](http://en.wikipedia.org/wiki/Multi_boot "Multi boot") windows 7 after windows 8.1 then sometime you will get error "**_windows cant install to this hard [disk space](http://en.wikipedia.org/wiki/Disk_space "Disk space") the selected disk has the maximum number of partitions of this type"._**Mainly this error occurs when you have unpartitioned disk space and you want to use this unallocated disk space to install new windows. This error not comes every time. this will come sometimes. <span style="color: red;">I m sharing this method cause today i face this issue and haven't find perfect solution for this issue. and i don't want to format my whole</span> [Hard Disk](http://en.wikipedia.org/wiki/Hard_disk_drive "Hard disk drive") <span style="color: red;">or any older windows.</span> You may have searched this error on google and you will got some solution like to need to convert your partitions from _**[GPT](http://en.wikipedia.org/wiki/GUID_Partition_Table "GUID Partition Table") to [MBR](http://en.wikipedia.org/wiki/Master_boot_record "Master boot record")**_ format. but this conversion will delete your all data. And this is not exact solution for this problem. cause you may also read that windows 7 install on MBR partition but windows 8 using latest format which is GPT. So now you may got confused if windows 8 can only install on GPT and windows 7 only on MBR then how you can dual boot both windows. cause its impossible to use both GPT and MBR on same disk. So do you need to buy an extra Disk?  

### No here is solution

You can solve this problem by creating different partition before windows installation.  

### How?

*   If you can boot into any windows then download and install "_**MiniTool Partition Wizard**_" from link below.

[Download](http://www.minitool.com/partition-manager/partition-wizard-home.html)

*   but if you have formatted your windows then you can download Bootable version of minitool partiton wizard from link below. and burn to _**[USB](http://en.wikipedia.org/wiki/Universal_Serial_Bus "Universal Serial Bus") or CD**_.

[Download](http://www.minitool.com/partition-manager/partition-wizard-bootable.html)

*   So now you have configured "_**MiniTool Partition Wizard**_", open main page of partition wizard. this will open new window with two options, select Partition wizard as show in below image.

[](http://4.bp.blogspot.com/-0OIRn2vb884/VVZE3DZ2FCI/AAAAAAAAADU/Um3HhieJ1SU/s1600/1.png)

*   Now select your Unpartitioned space, **_[Right click](http://en.wikipedia.org/wiki/Context_menu "Context menu")_** on it and select "_**Create**_".

[](http://4.bp.blogspot.com/-hI94WJq59_M/VVZE4VPHy2I/AAAAAAAAADk/YSBqAQDllvM/s1600/2.png)

*   Now in next window select "_**Logical**_" in create as, File system as _**[NTFS](http://en.wikipedia.org/wiki/NTFS "NTFS")**_, select any drive letter and click on _**OK**_ button.

*   Now you have new partition added, click on _**Apply**_ button on top to apply these changes to disk.

[](http://1.bp.blogspot.com/-vKIb6MQdVD0/VVZE5IJWcyI/AAAAAAAAADo/oCxCXM214b4/s1600/4.png)

*   After completing Operation **_restart windows_** and boot from your bootable media this can be "_**USB or DVD**_" and install your new windows on Newly created Partition.

### That's it. If you are getting any other problem related to windows then comment below i ll give you best and easy solution.