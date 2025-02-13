---
layout: post
title:  "How to install Express Tools without admin rights"
date:   2014-09-17 10:30:10
author: "Royzkie"
##header-img: "/img/post-bg-rwd.jpg"
##background: "/img/post-bg-rwd.jpg"
tags:
 - App
 - Tutorial
 - Download
---

<h2>Guide on how to install Express Tools in AutoCAD without administration rights.</h2>

<p>There are other very useful tools in AutoCAD that are not installed by default. Working in a company with company owned computers gives you limited rights to install softwares or programs without administration rights. **"Express Tools"** is a built in feature in all AutoCAD releases but are not installed by default. Most of the times, your IT personnel are too busy or they don't have any idea when you come up to them and ask them to install the "Express Tools" for you and will lead to much confusion and sometimes debates.</p>

<p>To avoid those long talks and explanations, here is a guide on How to install the "Express Tools" on your AutoCAD without administration rights.This is a do it your self installation which involves downloading of files from the internet, extracting archives and a little bit of browsing your computer. I tested  this on a AutoCAD Mechanical 2014 (full version, not LT) run on Windows 7 PC. I have not tried this on other versions, but it might just work. (You can try it at your own risk, well it's not even risky at all.)</p>

<p>Here goes:</p>

<ul>
<li>1. Download <a href="https://goo.gl/gKEPIv" target="_blank">Express.zip</a>.</li>
<li>2. Extract contents to C:\Users\username\appdata\roaming\autodesk\autocad mechanical 2014\r19.1\enu\support\express (Make sure hidden files are shown in Folder Options to access "AppData" folder).</li>
<li>3. Right Click "express" folder then click "Properties" > "General" tab > "Attributes" then uncheck "Read-only" then "Apply" (Apply to subfolders as well).</li>
<li>4. Run AutoCAD Mechanical 2014.</li>
<li>5. Type in "CUI" command to open "Customize User Interface".</li>
<li>6. Go to "Customize" tab > "Customization in All Files" under "AMPP" look for "Partial Customation Files".</li>
<li>7. Right Click "Partial Customation Files" select "load partial customation files'.</li>
<li>8. Browse to your support folder C:\Users\username\appdata\roaming\autodesk\autocad mechanical 2014\r19.1\enu\support and open "acetmain.cuix", apply then close "Customize User Interface".</li>
<li>9. Go to "Tools" > "Options", under "Files" tab, expand "Support File Search Path" then add express folder path C:\Users\username\appdata\roaming\autodesk\autocad mechanical 2014\r19.1\enu\support\express.</li>
<li>10. Under "Files" tab, expand "Trusted Locations" then add express folder path C:\Users\username\appdata\roaming\autodesk\autocad mechanical 2014\r19.1\enu\support\express (If a warning says about express folder being read-only just agree and continue).</li>
<li>11. Hit "Apply" and close "Options" menu.</li>
<li>12. Go to "Tools" > "Load Applications" locate "Startup Suite", click "Contents".</li>
<li>13. Add 2 files "acettest.fas" and "acetultil.fas" which can be found inside the express folder.</li>
<li>14. Close "Load/Unload Applications" menu then restart AutoCAD.</li>
<li>15. Check "Express" menu if its loaded and try the command if they are working.</li>
</ul>

<p>And just in case you have admin rights to your computer, here's how to install AutoCAD's "Express Tools" the normal way:</p>

<ul>
<li>1. Verify that AutoCAD is already installed in your computer, go to "Control Panel".</li>
<li>2. Find AutoCAD, right click and select "Uninstall/Change".</li>
<li>3. AutoCAD install will start up, select "Add or Remove Features" from the pop-upped menu.</li>
<li>4. Click through the screen then scroll to a list of features and you would find that "Express Tools" is crossed out (Red).</li>
<li>5. Click on the cross to check it (Green) then click "Update".</li>
<li>6. Let AutoCAD finish updating the changes that you've made.</li>
<li>7. Verify that "Express Tools" is loaded ones you run AutoCAD.</li>
</ul>

<p>Why the need to install "Express Tools"? Here is a <a href="https://goo.gl/s4ckKh" target="_blank">list</a> of all the commands that can be found under "Express Tools" and how to use them.</p>

