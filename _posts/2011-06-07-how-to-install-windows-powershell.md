---
title: How to install Windows PowerShell ?
author: arul
layout: post
permalink: /?p=77
blogger_blog:
  - www.poshtutorial.com
blogger_author:
  - amags
blogger_permalink:
  - /2011/06/how-to-install-windows-powershell.html
categories:
  - Personal
---
<div>
  <p>
    <span><span>In this first blog, we will look into how install PowerShell on your machine.   If you have Windows Server 2008 R2 </span></span>
  </p>
  
  <p>
    <span><span>or Windows 7, Windows PowerShell is integrated as part of the operating system and you don’t have to do anything to install it.  This is mainly for folks who are in earlier operating system.</span></span>
  </p>
  
  <p>
    <span><span></span></span>
  </p>
  
  <p>
    <span><span>Windows PowerShell 2.0 is distributed as part of  Windows Management Framework.  The details of this can be found in the following kb article Described in</span></span><span> <a href="http://support.microsoft.com/kb/968929/en-us"><span>http://support.microsoft.com/kb/968929/en-us</span></a>  .  </span>
  </p>
  
  <p>
    <span><span></span></span>
  </p>
  
  <p>
    <span><span>Windows Management Framework consists of  the following three components</span></span>
  </p>
  
  <p>
    <span><span><span>·<span>         </span></span></span></span><span><span>Windows PowerShell 2.0</span></span>
  </p>
  
  <p>
    <span><span><span>·<span>         </span></span></span></span><span><span>Windows Remote Management (WinRM)</span></span>
  </p>
  
  <p>
    <span><span><span>·<span>         </span></span></span></span><span><span>BITS (Background Intelligent Transfer service)</span></span>
  </p>
  
  <p>
    <span><span></span></span>
  </p>
  
  <p>
    <span><span>WMF is supported in the following operating system</span></span>
  </p>
  
  <table border="1">
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>OS</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>WinRM 2.0</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Windows PowerShell 2.0</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>BITS 4.0</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows Server 2008 R2</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows 7</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Integrated into OS</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows Server 2008 SP2</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported </span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows Server 2008 SP1</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Supported </span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Not supported</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows Server 2003 SP2</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Not Suported</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows Vista SP1 +</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Suppported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
    </tr>
    
    <tr>
      <td valign="top" width="181">
        <p>
          <span><span>Windows XP SP3</span></span>
        </p>
      </td>
      
      <td valign="top" width="138">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Supported</span></span>
        </p>
      </td>
      
      <td valign="top" width="160">
        <p>
          <span><span>Not Supported</span></span>
        </p>
      </td>
    </tr>
  </table>
  
  <p>
    <span><span></span></span>
  </p>
  
  <p>
    <span><span></span></span>
  </p>
  
  <p>
    <span><span>You can install  WMF from the Microsoft download site  using the KB968929 to download appropriate installation package.   You need to have .Net Framework 2.0 SP1  for the installation to work.  It is recommended that you install .Net Framework 3.5 if you want to use PowerShell ISE.</span></span>
  </p></p>
</div>