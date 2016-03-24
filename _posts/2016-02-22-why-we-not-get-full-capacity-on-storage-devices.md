---
layout: post
title: why we not get full capacity on storage devices?
date: '2016-02-22T23:34:00.000+05:30'
author: Pawneshwer Gupta
categories:
- how-to
description: logic behind storage capacity, why we get less space in storage devices,why we not get full space on storage devices,why memory leak in storage devices
keywords: logic behind storage capacity, why we get less space in storage devices,why we not get full space on storage devices,why memory leak in storage devices
modified_time: '2016-02-23T09:03:49.140+05:30'
thumbnail: https://3.bp.blogspot.com/-Ox-r-YgA52o/VstKyvXZNXI/AAAAAAAAIX4/tJaiL9hb0FU/s72-c/Untitled%2Bcopy.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-8456556453592073153
blogger_orig_url: http://www.edablogs.com/2016/02/why-we-not-get-full-capacity-on-storage-devices.html
redirect_from:
- /2016/02/why-we-not-get-full-capacity-on-storage-devices.html
---

## <span style="color: #ff6600;">Reason behind why we get less capacity in storage devices :</span>

Have you ever think that why we not got full capacity on any storage device like Pendrive,SD Card,Harddisk or any other storage device? for example if we buy a **2TB (2000GB)** harddisk then we got only **1.81TB** only. Some of us maybe thinks that this missing space is reserved by hardware or something else. but answer is really tricky. Actually here is fact behind this

[![](https://3.bp.blogspot.com/-Ox-r-YgA52o/VstKyvXZNXI/AAAAAAAAIX4/tJaiL9hb0FU/s1600/Untitled%2Bcopy.png)](https://3.bp.blogspot.com/-Ox-r-YgA52o/VstKyvXZNXI/AAAAAAAAIX4/tJaiL9hb0FU/s1600/Untitled%2Bcopy.png)

### because EVERY company counts:

> 1000 B for 1 KB  
> 1000 KB for 1 MB  
> 1000 MB for 1 GB and  
> 1000 GB for 1 TB,

while its actually (1KB have 1024 B instead of 1000B) so this will be

> 1024 B for 1 KB  
> 1024 KB for 1 MB  
> 1024 MB for 1 GB and  
> 1024 GB for 1 TB.

[![](https://2.bp.blogspot.com/-kodmd-IKyxg/VstKytpBFaI/AAAAAAAAIX8/NrShtwasHMo/s320/Untitled2%2Bcopy.png)](https://2.bp.blogspot.com/-kodmd-IKyxg/VstKytpBFaI/AAAAAAAAIX8/NrShtwasHMo/s320/Untitled2%2Bcopy.png)

So lets do the company's math: they think we need <span style="color: #ff6600;">**2*1000*1000*1000*1000**</span> = **<span style="color: #ff6600;">2.000.000.000.000 B</span>** to get **2TB.** But thats wrong! If we reverse the math with the right numbers we get this: <span style="color: #ff6600;">**2.000.000.000.000/1024/1024/10­24/1024**</span> = **1,81TB**

Thats why its only 1.81TB in 2TB harddisk. So whenever you buy new storage device you can estimate how much capacity you get in that.