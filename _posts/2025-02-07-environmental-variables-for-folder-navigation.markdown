---
layout: post
title: "Environmental Variables For Folder Navigation"
subtitle: "Environmental Variables"
date: 2025-02-06 14:30:00
author: "royzkie"
##header-img: "/img/post-bg-unix-linux.jpg"
##background: "/img/post-bg-unix-linux.jpg"
tags:
    - Tutorial
    - Reference
---

<h2>List of most commonly used environmental variables for folder navigation in Windows:</h2>

<p>Copy the variables (%xxxx%) into the windows explorer address bar and hit enter.</p>

<p>%AppData% - "C:\Users\{username}\AppData\Roaming"</p>
<p>%ALLUSERSPROFILE% or %PROGRAMDATA% - "C:\ProgramData"</p>
<p>%CommonProgramFiles(x86)% or %CommonProgramW6432% - "C:\Program Files (x86)\Common Files"</p>
<p>%LOCALAPPDATA% - "C:\Users\{username}\AppData\Local"</p>
<p>%OneDrive% -  access your OneDrive folder</p>
<p>%ProgramFiles% - "C:\Program Files"</p>
<p>%SystemRoot% - "C:\Windows"</p>
<p>%TEMP% or \%TMP\% - "C:\Users\{username}\AppData\Local\Temp"</p>
<p>%SystemDrive% - "C:\"</p>
<p>%USERPROFILE% - "C:\Users\{username}"</p>
<p>%windir% - "C:\Windows"</p>

<p>There are other environmental variables, but the ones listed above are the most common I remembered from the top of my head. </p>
    
<p>For more examples and more information about environmental variables, <a href="http://tiny.cc/jp59001" target="_blank">check this out.</a></p>

<p> </p>
<p> </p>
<p>Additional:</p>
<p>I recently found out that shell can also open folder locations.</p>
<p>Typing "Shell:Startup" to the windows explorer address bar opens up the start up folder. You can paste a link or any executables here and it will run on windows startup.</p>

