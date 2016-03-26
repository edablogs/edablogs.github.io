---
layout: post
title: Execution failed for task ':app:clean' unable to delete jars\classes.jar
date: '2015-12-03T01:45:00.000+05:30'
author: Pawneshwer Gupta
categories:
- Android-Studio
- android
description: android studio unable to delete jars\classes.jar while cleaning or rebuilding project,to solve unable to delete jars\classes.jar issue just follow given steps
keywords: android studio unable to delete jars\classes.jar while cleaning or rebuilding project,to solve unable to delete jars\classes.jar issue just follow given steps
modified_time: '2016-02-20T06:52:39.883+05:30'
thumbnail: http://3.bp.blogspot.com/-nY8JF-h6bYA/Vl9PEXANMGI/AAAAAAAAIEs/LzufjSab2vA/s72-c/unable%2Bto%2Bdelete%2Bjars-classes.jar-thumb.png
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-2008105190626003212
blogger_orig_url: http://www.edablogs.com/2015/12/execution-failed-for-task-app-clean-unable-to-delete-jars-classes-jar.html
redirect_from:
- /2015/12/execution-failed-for-task-app-clean-unable-to-delete-jars-classes-jar.html
---

_[error](http://en.wikipedia.org/wiki/Error_%28baseball%29 "Error (baseball)"):execution failed for task ':app:clean'. > unable to delete file: \app\build\intermediates\exploded-aar\com.android.support\appcompat-v7\23.1.1\[jars](http://en.wikipedia.org/wiki/Jar "Jar")\classes.jar_

Hello guys and coders as Android studio got 2.0 Preview released,and with this new release their is problem while Cleaning or Rebuilding Project. So when you clean your project you got an awesome error says <span style="color: #008000;">("_error:execution failed for task ':app:clean'. > unable to delete file: \app\build\intermediates\exploded-aar\com.android.support\appcompat-v7\23.1.1\jars\classes.jar_")</span>, or something like this which ends with "**Unable to delete jars\classes.jar**") file.

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://3.bp.blogspot.com/-nY8JF-h6bYA/Vl9PEXANMGI/AAAAAAAAIEs/LzufjSab2vA/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-thumb.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://3.bp.blogspot.com/-nY8JF-h6bYA/Vl9PEXANMGI/AAAAAAAAIEs/LzufjSab2vA/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-thumb.png)

So if you goto that directory manually and delete that classes.[jar file](http://en.wikipedia.org/wiki/JAR_%28file_format%29 "JAR (file format)") then you get same error "_Unable to delete jars\classes.jar_".

## <span style="color: #000080;">So there are two methods to resolve this problem as of now :</span>

### <span style="color: #ff0000;">Method 1 :</span>

*   Just read the path where you got that error.

**in my Android studio i got**

> _error:execution failed for task ':app:clean'. > unable to delete file: \app\build\intermediates\exploded-aar\com.android.support\**<span style="color: #000080;">appcompat-v7</span>\23.1.1\jars\classes.jar**_

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://1.bp.blogspot.com/-jBPXpPaCeGA/Vl9O-l3xBjI/AAAAAAAAIEU/RLLRsTcrHLU/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-1.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://1.bp.blogspot.com/-jBPXpPaCeGA/Vl9O-l3xBjI/AAAAAAAAIEU/RLLRsTcrHLU/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-1.png)

*   as you can see i got this error due to appcompat-v7, So i will simply remove appcompat library from my project and Sync my project.

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://1.bp.blogspot.com/--rGLzteXE-E/Vl9O-mratdI/AAAAAAAAIEQ/zF0AVfHYQXo/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-2.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://1.bp.blogspot.com/--rGLzteXE-E/Vl9O-mratdI/AAAAAAAAIEQ/zF0AVfHYQXo/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-2.png)

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://2.bp.blogspot.com/-EiPJLYxXdVU/Vl9O-dwHIkI/AAAAAAAAIEM/Mg_J1fqQaoo/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-3.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://2.bp.blogspot.com/-EiPJLYxXdVU/Vl9O-dwHIkI/AAAAAAAAIEM/Mg_J1fqQaoo/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-3.png)

(to remove library simply remove Gradle dependency from **build.gradle** file inside you app. )

*   After Sync Gradle you can see that error was gone and my project build successfully.

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://1.bp.blogspot.com/-MlEJ7a7gaYI/Vl9PD8maCkI/AAAAAAAAIEk/GnoAPiCzCg0/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-4.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://1.bp.blogspot.com/-MlEJ7a7gaYI/Vl9PD8maCkI/AAAAAAAAIEk/GnoAPiCzCg0/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-4.png)

*   <span style="text-align: justify;">Now add Gradle dependency of that library to your project and Sync Gradle again.</span>

[![Execution failed for task ':app:clean' unable to delete jars\classes.jar](http://4.bp.blogspot.com/-Enll8yRDA7Y/Vl9PEeT9zbI/AAAAAAAAIEo/sghiu6eIPd0/s320/unable%2Bto%2Bdelete%2Bjars-classes.jar-5.png "Execution failed for task ':app:clean' unable to delete jars\classes.jar")](http://4.bp.blogspot.com/-Enll8yRDA7Y/Vl9PEeT9zbI/AAAAAAAAIEo/sghiu6eIPd0/s1600/unable%2Bto%2Bdelete%2Bjars-classes.jar-5.png)

Viola !!! Your project build successfully and their is no more error.

**<span style="color: #ff0000;">Note : if in your case problem arise with any custom jar file which you have loaded into your app, then simply delete that jar [file Sync](http://en.wikipedia.org/wiki/File_synchronization "File synchronization") Gradle, after successful build add your jar file again into your project.)</span>**

### <span style="color: #ff0000;">Method 2:</span>

This method is not recommended because this method take long time.

*   In this method simply Restart Android Studio (close and start again).

And error was gone.

So i prefer 1st method.