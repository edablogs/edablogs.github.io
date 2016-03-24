---
layout: post
title: 'How To Disable Multi/Guest User Without PC '
date: '2015-06-19T03:27:00.000+05:30'
author: Naved Alam
categories:
- android
- asus
- zenfone-5
tags:
- android tricks
- Asus
- zenfone 5
- Android
- Android (operating system)
description: enable guest mode in asus zenfone 5,enable multi user mode in asus zenfone 5,enable multi user in asus zenfone 5
keywords: enable guest mode in asus zenfone 5,enable multi user mode in asus zenfone 5,enable multi user in asus zenfone 5
modified_time: '2016-02-20T06:52:55.571+05:30'
thumbnail: http://4.bp.blogspot.com/-J9gnPJTYEcg/VYNAQ16pGXI/AAAAAAAAJH8/PUnaBQeNosY/s72-c/coollogo_com-1705127.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-7994477647724858079
blogger_orig_url: http://www.edablogs.com/2015/06/how-to-disable-multiguest-user-without.html
redirect_from:
- /2015/06/how-to-disable-multiguest-user-without.html
---

[![](https://4.bp.blogspot.com/-J9gnPJTYEcg/VYNAQ16pGXI/AAAAAAAAJH8/PUnaBQeNosY/s320/coollogo_com-1705127.png)](http://4.bp.blogspot.com/-J9gnPJTYEcg/VYNAQ16pGXI/AAAAAAAAJH8/PUnaBQeNosY/s1600/coollogo_com-1705127.png)

## Follow Steps Carefully :

*   Before proceeding remove all accounts from Multi/Guest User otherwise anything can be happened to your device.
*   Open Es File Manager or Root Explorer and give root permissions to it ,(I'm using Es File....... but the process is same so don't worry and if you don't know how to give root permissions then see the images down below)

[![](https://3.bp.blogspot.com/-QvGcuckcQ88/VYM8CKBVVHI/AAAAAAAAJGw/Zz-NBmu_vkc/s320/1.png)](http://3.bp.blogspot.com/-QvGcuckcQ88/VYM8CKBVVHI/AAAAAAAAJGw/Zz-NBmu_vkc/s1600/1.png)

[![](https://1.bp.blogspot.com/-mpqpyNbFT9U/VYM8A1r3zRI/AAAAAAAAJGk/bHbh9vaL6bY/s320/2.jpg)](http://1.bp.blogspot.com/-mpqpyNbFT9U/VYM8A1r3zRI/AAAAAAAAJGk/bHbh9vaL6bY/s1600/2.jpg)

[![](https://4.bp.blogspot.com/-Z9qz_L-A-jw/VYM8Ccz6xRI/AAAAAAAAJG4/4m0f3-gYyNg/s320/3.jpg)](http://4.bp.blogspot.com/-Z9qz_L-A-jw/VYM8Ccz6xRI/AAAAAAAAJG4/4m0f3-gYyNg/s1600/3.jpg)

[![](https://2.bp.blogspot.com/-xqezmdAluCg/VYM8DOMiCBI/AAAAAAAAJHA/uFsmLXbHEsw/s320/4.jpg)](http://2.bp.blogspot.com/-xqezmdAluCg/VYM8DOMiCBI/AAAAAAAAJHA/uFsmLXbHEsw/s1600/4.jpg)

*   Open Build.prop with text editor (if you don't know how then see the images below and I'm using Asus Zenfone 5 a501cg so my build.prop is build.a501cg.prop ,many devices only have build.prop so don't get confused)

[![](https://2.bp.blogspot.com/-jkBL5KRrqsc/VYM8D7aagPI/AAAAAAAAJHU/ksQiTt2d7Rw/s320/5.jpg)](http://2.bp.blogspot.com/-jkBL5KRrqsc/VYM8D7aagPI/AAAAAAAAJHU/ksQiTt2d7Rw/s1600/5.jpg)

[![](https://1.bp.blogspot.com/-04u3GkQ3Ioc/VYM8ED2xshI/AAAAAAAAJHc/U1g0fSVnKGM/s320/6.jpg)](http://1.bp.blogspot.com/-04u3GkQ3Ioc/VYM8ED2xshI/AAAAAAAAJHc/U1g0fSVnKGM/s1600/6.jpg)

[![](https://2.bp.blogspot.com/-V6gU6iLu0TY/VYM8EsMkwXI/AAAAAAAAJHg/VcTbYE1sAiI/s320/7.jpg)](http://2.bp.blogspot.com/-V6gU6iLu0TY/VYM8EsMkwXI/AAAAAAAAJHg/VcTbYE1sAiI/s1600/7.jpg)

[![](https://3.bp.blogspot.com/-eAUXdq1pRd4/VYM8Fbe5thI/AAAAAAAAJHo/OWHQ0AL7cs0/s320/8.jpg)](http://3.bp.blogspot.com/-eAUXdq1pRd4/VYM8Fbe5thI/AAAAAAAAJHo/OWHQ0AL7cs0/s1600/8.jpg)

*   Tap on 3 dots on the right hand-side then tap on edit.

[![](https://1.bp.blogspot.com/-88CLenBprkU/VYM8GGHxu_I/AAAAAAAAJHw/3WlHASixyLI/s320/9.jpg)](http://1.bp.blogspot.com/-88CLenBprkU/VYM8GGHxu_I/AAAAAAAAJHw/3WlHASixyLI/s1600/9.jpg)

*   Find these 2 lines:- 

> fw.max_users=3  
> fw.show_multiuserui=1

*   Just add # before these two lines =

> #fw.max_users=3  
> #fw.show_multiuserui=1

*   Now press back there's pop like below

[![](https://2.bp.blogspot.com/-lTLKR3Bhv_E/VYM8B6OnAvI/AAAAAAAAJG0/WPbLYNH4GtE/s320/10.jpg)](http://2.bp.blogspot.com/-lTLKR3Bhv_E/VYM8B6OnAvI/AAAAAAAAJG0/WPbLYNH4GtE/s1600/10.jpg)

*   Reboot and Enjoy :-)

### Note :

I've made a video on this so if you don't want to read you can watch video [FROM HERE](https://www.youtube.com/watch?v=i6KchPMYVNs)  

<iframe allowfullscreen="" frameborder="0" height="450px" src="https://www.youtube.com/embed/i6KchPMYVNs" width="95%"></iframe>  
 
Don't hesitate to ask any question.