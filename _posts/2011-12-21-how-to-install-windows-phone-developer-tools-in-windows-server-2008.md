---
title: How to install Windows Phone Developer tools in Windows Server 2008
author: arul
layout: post
permalink: /?p=73
categories:
  - Personal
---
&nbsp; 

Windows Phone Developer Tools is not officially supported in the Windows Server 2008 .&nbsp; I used Windows Server 2008 as my development machine and use hyper-v to install client OS etc. I wanted to have my Windows Phone development environment also in my server machine.&nbsp; I learned the following from a friend of mine which allows you to install Windows Phone developer tools in your Windows Server 2008 machine. 

Remember 

***<font color="#ff0000" size="4">Please note that this is not officially supported, so if you try these steps, you are doing so at your own risk.</font>*** 

&nbsp; 

**<font size="3">Steps</font>** 

**1. **Download the [**Windows Phone Developer Tools web bootstrapper**][1] and save it to your hard drive 

**2. **Extract the contents of the setup package by running **vm_web.exe /x** and choosing a path to extract to 

**3. **Go to the folder you extracted to in step 2 and open the file **baseline.dat** in notepad 

**4. **Look for the section named **[gencomp7788]** 

Note – you have to change this exact section – this is the one that controls the OS version blocking behavior in Windows Phone Developer Tools setup. 

**5. **Now the change the values of the matching statements below(change from 1 to 0 – hi-lighted in bold).  


> **InstallOnAMD64=0 **( turns of the check for AMD64 machines)** ** 
> 
> InstallOnFutureNT=0 
> 
> InstallOnVista=0 
> 
> InstallOnWin7=0 
> 
> **InstallOnLHS=0** ( turns of the check for Windows Server 2008) 
> 
> InstallOnIA64=1 
> 
> **InstallOnNetServer=0 **( turns of the check for Windows Server 2003) 
> 
> InstallOnWin2k=1 
> 
> InstallOnWinNT4=1 
> 
> **InstallOnWinXP=0 **( turns of the check for Windows XP)** ** 
> 
> InstallOnx86=0 
> 
> **InstallOnWin7Server=0 **( turns of the check for Windows Server 2008 R2 )** **</blockquote> 
> 
> **6. **Save and close **baseline.dat** 
> 
> **7. **Run **setup.exe /web** from the folder you extracted to in step 2 
> 
> &nbsp; 
> 
> Enjoy and have fun creating new Windows Phone Application.

 [1]: http://www.microsoft.com/downloads/en/details.aspx?FamilyID=04704acf-a63a-4f97-952c-8b51b34b00ce