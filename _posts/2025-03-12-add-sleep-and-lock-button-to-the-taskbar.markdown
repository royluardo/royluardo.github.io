---
layout: post
title: "Add "Sleep" and "Lock" button to the taskbar"
subtitle: "One click lock / sleep"
date: 2025-03-12 08:30:00
##header-img: "/img/post-bg-unix-linux.jpg"
##background: "/img/post-bg-unix-linux.jpg"
tags:
    - Tutorial
    - Reference
---

<h2>Add "Sleep" and "Lock" button to the taskbar</h2>

<p>Yes you can easily access the Sleep and Lock toggle from the start menu by clicking windows icon then the power icon then lock or sleep. That is easy and all but I'm just lazy like that. I want to add this 2 toggles directly on the taskbar.</p>

<p>Also you can use keyboard shortcut for lock which is "Windows Key + L". That is easy enough. But for sleep, it is a combination of keys. It's "Windows Key + X" then "U" then "S". That is easy and all but like I ssaid I'm just lazy like that.</p>

<p>So here is how to add this 2 toggles on the taskbar for easy access.</p>

<p>For the "Lock" Toggle:</p>
<ul>
<li>1. Right click on the desktop and choose "New" then "Shortcut".</li>
<li>2. Below the "Type the location of the item:" space, copy and paste this "rundll32.exe User32.dll,LockWorkStation" then clic "Next".</li>
<li>3. Type the name of the shortcut, name it "Lock" instead of rundll32.exe then clic "Finish".</li>
<li>4. Right click on the newly created shortcut icon and select "Properties" (in win 11, click "Show more options" first).</li>
<li>5. Click on "Change Icon" button. It might say "Choose an icon from the list or spicify a different file", just click "Okay".</li>
<li>6. You should see a bunch of icons to choose from. Select any and click "Okay".</li>
{% assign version =  "now" | date: "%Y%m%d%H%M"  %}
<li>7. (Optional) You can use your own icons too. Try download <a href="{{'/download/shortcut/lock.ico?v=0X' | append: version | relative_url }}" target="_blank">this icon file</a> (.ico file) save it anywhere in your computer. Instead of using the common icons, while choosing the icons, click on "Browse" and look for the ico file that you have downloaded. Select it and click "Open" then "Okay". Click "Apply" then "Okay".</li>
<li>8. You shortcut should have a new look using the icon you choose.</li>
<li>9. Drag the shortcut anywhere on the taskbar.</li>
<li>10.  If you want to lock you computer just click on that icon.</li>
</ul>

<p>For the "Sleep" Toggle:</p>
<ul>
<li>1. Right click on the desktop and choose "New" then "Shortcut".</li>
<li>2. Below the "Type the location of the item:" space, copy and paste this "rundll32.exe powrprof.dll,SetSuspendState 0,1,0" then clic "Next".</li>
<li>3. Type the name of the shortcut, name it "Sleep" instead of rundll32.exe then clic "Finish".</li>
<li>4. Right click on the newly created shortcut icon and select "Properties" (in win 11, click "Show more options" first).</li>
<li>5. Click on "Change Icon" button. It might say "Choose an icon from the list or spicify a different file", just click "Okay".</li>
<li>6. You should see a bunch of icons to choose from. Select any and click "Okay".</li>
<li>7. (Optional) You can use your own icons too. Try download <a href="{{'/download/shortcut/sleep.ico?v=0X' | append: version | relative_url }}" target="_blank">this icon file</a> (.ico file) save it anywhere in your computer. Instead of using the common icons, while choosing the icons, click on "Browse" and look for the ico file that you have downloaded. Select it and click "Open" then "Okay". Click "Apply" then "Okay".</li>
<li>8. You shortcut should have a new look using the icon you choose.</li>
<li>9. Drag the shortcut anywhere on the taskbar.</li>
<li>10.  If you want to put your computer to sleep, just click on that icon.</li>
</ul>

<p><strong>TL;DR</strong></p>
<p>If you don't want to go into all that trouble, download <a href="{{'/download/shortcut/shortcut.zip?v=0X' | append: version | relative_url }}" target="_blank">this zip file</a> which contains the shortcuts with the icons. Save and extract to your desktop. Change the icons then drag the shortcuts to your tak bar. EASY.</p>
