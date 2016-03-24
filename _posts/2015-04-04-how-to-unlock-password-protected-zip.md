---
layout: post
title: How to unlock password protected zip files
date: '2015-04-04T06:00:00.000+05:30'
author: Pawneshwer Gupta
categories:
- linux
tags:
- Linux
description: 
keywords: 
modified_time: '2016-02-20T06:52:55.538+05:30'
thumbnail: http://4.bp.blogspot.com/-EseseyDFe_s/VUTGtsTETOI/AAAAAAAAAVc/RSU8AKhra0U/s72-c/Zip-File.jpg
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-5805356079556153347
blogger_orig_url: http://www.edablogs.com/2015/04/how-to-unlock-password-protected-zip.html
redirect_from:
- /2015/04/how-to-unlock-password-protected-zip.html
---

## <span style="color: green;">Unlock password protected zip</span>

<span lang="en-US">Hello guys, you are here because you all are suffering from protected [zip files](http://en.wikipedia.org/wiki/Zip_%28file_format%29 "Zip (file format)") and you are</span> <span lang="en-US">trying</span> <span lang="en-US">to complete</span> _<span lang="en-US">survey</span>_ <span lang="en-US">to get [password](http://en.wikipedia.org/wiki/Password "Password") of **_protected zip_** [file](http://en.wikipedia.org/wiki/Computer_file "Computer file") but failed. You have download any [cracked software](http://en.wikipedia.org/wiki/Software_cracking "Software cracking") or anything expensive but you got _**protected zip**_ file and owner of that file said that complete a</span> _<span lang="en-US">survey</span>_ <span lang="en-US">to get password. Owner have protected zip files so users try to complete survey and owner of file got high amount of money. Yes survey site gives money when visitors complete there survey.</span>  
<span lang="en-US">So this is headache for you all, also for me but I have found solution for this. But this is working on **Linux** only. You can use any [Linux operating system](http://en.wikipedia.org/wiki/Linux "Linux") like</span> <span lang="en-US">[Ubuntu](http://en.wikipedia.org/wiki/Ubuntu_%28operating_system%29 "Ubuntu (operating system)")</span><span lang="en-US">,</span><span lang="en-US">[Kali](http://en.wikipedia.org/wiki/Kali "Kali")</span><span lang="en-US">,backtrack, fedora,red hat or else. In this tutorial I am using **Ubuntu** cause I love Ubuntu and using it from past 4 years. Therefore I m more friendly with Ubuntu. But of you don't want to [install](http://en.wikipedia.org/wiki/Install_%28Unix%29 "Install (Unix)") Linux on your System then you can use</span> <span lang="en-US">Linux</span> <span lang="en-US">on</span> <span lang="en-US">live</span> <span lang="en-US">mode. Means no need to install</span> <span lang="en-US">Linux</span> <span lang="en-US">just burn _**.**_</span>_**<span lang="en-US">ISO</span>**_ <span lang="en-US">to **disk** or **[USB](http://en.wikipedia.org/wiki/Universal_Serial_Bus "Universal Serial Bus")** and directly run into your</span> <span lang="en-US">system.</span>  

![How to unlock password protected zip files](http://4.bp.blogspot.com/-EseseyDFe_s/VUTGtsTETOI/AAAAAAAAAVc/RSU8AKhra0U/s1600/Zip-File.jpg "How to unlock password protected zip files")

### So if you have configured Linux on your system then follow these procedure:

*   <span lang="en-US">First of all install _**fcrackzip**_ software on your</span> <span lang="en-US">Linux</span><span lang="en-US">, if you are using Ubuntu then you can install _**fcrackzip**_ directly doing into [Ubuntu Software Center](http://en.wikipedia.org/wiki/Ubuntu_Software_Center "Ubuntu Software Center"). And search for _**fcrackzip**_</span>
*   <span lang="en-US">But if in your</span> <span lang="en-US">Linux</span> <span lang="en-US">there is no software center then you have to use commands to install.</span>
*   <span lang="en-US">So open **terminal** and type the following command.</span>

### <span lang="en-US" style="color: blue;">sudo apt-get install fcrackzip</span>

### <span lang="en-US" style="color: blue;">  

[](http://3.bp.blogspot.com/-40ySqaYyc9A/VUTHAVsm8dI/AAAAAAAAAVk/T7P3ueZ1P0c/s1600/Screenshot-from-2015-04-03-235446.png)

</span>

*   <span lang="en-US">Now this will ask you to enter admin password. Fill your password and press enter.</span>

[](http://4.bp.blogspot.com/--7eOitIWHF4/VUTHAvL5D9I/AAAAAAAAAVo/KnfkL75dxxg/s1600/Screenshot-from-2015-04-03-235455.png)

*   <span lang="en-US">So now you have completely installed _**fcrackzip**_</span>
*   <span lang="en-US">So again in terminal type the following command to get password of zip file.</span>
*   <span lang="en-US">Use cd command to goto folder where your protected zip file is stored. </span>

[](http://3.bp.blogspot.com/-XeeMX4giYtw/VUTHjMYUIpI/AAAAAAAAAV0/pAwNhDULmcY/s1600/Screenshot-from-2015-04-03-235626.png)

*   <span lang="en-US">And type</span>

### <span lang="en-US" style="color: blue;">fcrackzip -b -c 'aA1!' -l 1-5 -u filename.zip</span>

*   <span lang="en-US">Now wait for few seconds and terminal will return a message with password of that protected zip file.</span>

*   In this example i have set "**<span style="color: red;">pawn</span>**" as password for zip file. and see the result.

## How it works?

<span lang="en-US">So in our command we have passed</span>  

1.  <span lang="en-US"><span style="color: magenta;">**-b**</span> to apply brute force</span>
2.  <span lang="en-US"><span style="color: magenta;">**-c 'aA1!'**</span> means this will use <span style="color: magenta;">**a-z**</span>, **<span style="color: magenta;">A-Z</span>**, **<span style="color: magenta;">0-9</span>**, and all **<span style="color: magenta;">symbols</span>** to match with that protected zip file.</span>

<span lang="en-US">So when match found</span> <span lang="en-US">using</span> <span lang="en-US">that symbols this will return password for that zip file.</span>  
<span lang="en-US">If your password is in simple alphabet them this will take only 2-4 minutes, but if your protected zip file uses all possible symbols them this will take time and it depends on length of password. So sit back and wait for terminal to guess password for you. At this time you can do your work and check after sometime that password is guessed by terminal or not.</span>  
<span lang="en-US">Hope you enjoy this post. If it's really helpful for you then also share with your friends and help then you unlock their password protected zip files.</span>  

### Note: this will guess password only for zip files. Not tested on other compressed file type.