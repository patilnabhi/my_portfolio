---
layout: post
title:  "Ball Tracking"
date:   2015-09-29 01:00:00
last_modified_at:  2015-12-16 13:00:00
excerpt: ""
categories: project
tags:  robotics
image:
  feature: ball-tracking.gif
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
**Project Objectives**:

* Build a servo controlled pan-tilt camera system
* Program the camera to track target objects

**Project Details**:

* A servo controller was assembled to mount a webcam
* A `ROS` node was developed to control the pan-tilt servo mechanism
* Image processing using `OpenCV` script was written to filter out the target object (a red ball was chosen)
* Using data from above processing, a `ROS` node was developed to get the location of the red ball

**Project Demo**:  
<p><center><iframe src="https://player.vimeo.com/video/173001455" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe></center></p>

