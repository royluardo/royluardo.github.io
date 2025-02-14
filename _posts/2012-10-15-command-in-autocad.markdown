---
layout:     post
title:      "Create New Command in AutoCAD"
date:       2012-10-15 00:00:00
author:     "royzkie"
##header-img: "/img/post-bg-rwd.jpg"
##background: "/img/post-bg-rwd.jpg"
tags:
    - App
    - Programming
    - Engineering
---

<h2>Steps on how to create new command in AutoCAD</h2>

<p>Objective</p>

As a sample (let’s make it as simple as possible), say you want to create a new command that “Create 2 Vertical viewports” (See my other post “AutoCAD Macros” for other sample command macro).

<p>Steps</p>

<ul>
<li>1. Open CUI by accessing menu tools > customize > interface (or by typing “CUI” on commandline). You will find a menu with 3 areas (see fugure below).</li>
<li>2. Click on “Create a new command” button.</li>
<li>3. Provide the name of command and the macro.</li>
<li>4. Above the properties, select/create/edit a command icon of your choice.</li>
<li>5. Drag the newly created command to any tootlbar of your choice. You can also drag it outside the CUI menu to any existing tool bar on your workspace.</li>
<li>6. Click “Apply” and “OK” to close CUI menu.</li>
</ul>

<p>You’re done here. Try the new command by clicking the icon you created.</p>

<p>Tested on AutoCAD 2011 classic workspace enabled, it should work on all other version of AutoCAD specially on newer versions.</p>
