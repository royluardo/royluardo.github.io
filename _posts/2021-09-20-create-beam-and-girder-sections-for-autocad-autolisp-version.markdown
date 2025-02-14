---
layout: post
title: "Create beam and girder sections for AutoCAD - AutoLISP version"
subtitle: "a continuation to my beam and girder section maker"
date: 2021-09-20 00:00:00
author: "royzkie"
##background: "/img/post-bg-unix-linux.jpg"
##header-img: "/img/post-bg-unix-linux.jpg"
tags:
    - App
    - Download
    - Tutorial
---

<p>This is an AutoLISP for AutoCAD to create beam sections effortlessly. I had already created a similar project before but using excel sheets and formulas to automate commands for AutoCAD. This is a continuation or an upgrade to that project. The output is seamless and very easy.</p>
	
<p>How to load?</p>
{% assign version =  "now" | date: "%Y%m%d%H%M"  %}
<ol>
<li>Download <a href="{{'/download/create_beam_v1.0.1.zip?v=0X' | append: version | relative_url }}" target="_blank">creatbeam.lsp</a> (in zip archive need to extract).</li>
<li>Go to Tools > Load Application then browse for creatbeam.lsp and click load.</li>
<li>To load the AutoLISP file when AutoCAD startup add it to the StartUp Suite case.</li>
</ol>

<p>How to use?</p>
	
<ol>
<li>Type "zbeam" on the AutoCAD commandline.</li>
<li>Enter value for "Beam Height".</li>
<li>Enter value for "Flange Width".</li>
<li>Enter value for "Web Thickness".</li>
<li>Enter value for "Flange Thickness".</li>
<li>Enter value for "Root Radius".</li>
<li>Then click for Insertion Point.</li>
</ol>

<p>For beam sizes and dimension reference download <a href="{{'/download/SteelUK001202-.zip?v=0X' | append: version | relative_url }}" target="_blank">UK Steel Sections</a>.</p>
	
<p>To draw a PG (Plate Girder) or built up section instead of a standard beams, follow the instructions then input zero on the root radius. The zbeam will draw plate girder section 3 separate rectangles for the top and bottom flanges and web.</p>
	
<p>The created section is a closed polygon for the beam sections and for the plate girder it's 3 rectangles.</p>
	
<p>The AutoLISP code has been heavily commented with notes so you can follow or study what or how the program is working or what this particular code does. It only has 2 if commands used and many a few coordinates locating points.</p>
	
<p>The concept of the code is select an insertion point (IP) then from there trace the beam sections using the values given for its beam height, flange width, thickness, etc and draw a polyline along those points.</p>

<p>Tested and working on AutoCAD 2019. Will work on other versions of AutoCAD but your millage may vary. This program is provided as is. The coding I have done is very simple and is based on available tutorials and references.</p>

<p>TL;DR: You can download all the steel section in AutoCAD <a href="{{'/download/all steel sections.zip?v=0X' | append: version | relative_url }}" target="_blank">here</a>.</p>
