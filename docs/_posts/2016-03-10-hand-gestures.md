---
layout: post
title:  "Hand Gesture Recognition"
date:   2016-03-10 13:00:00
last_modified_at:  2016-03-15 13:00:00
excerpt: ""
categories: project
tags:  hand gesture recognition, OpenCv, robotics, ROS
image:
  feature: hand_1.png
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
<h4>Goal:</h4>

* Using a depth camera, OpenCV and ROS, develop an API to recognize number of fingers from 0 to 5

<h4>Demo:</h4>

<p><center><iframe width="560" height="315" src="https://www.youtube.com/embed/8xGBM5BMlHA" frameborder="0" allowfullscreen></iframe></center></p>

<h4>Project Website:</h4>  

* This project was integrated into another bigger project on TurtleBot navigation and can be viewed at - [http://patilnabhi.github.io/portfolio/tbotnav] 

<h4>Project Details:</h4>

* The project can be summarized in the following **5 steps**:

	1. Extract hand region from *raw* depth data  
	2. Determine convex hull and convexity defects of extracted hand region 
	3. Detect no. of fingers using the convexity defects from (2) 
	4. Create a custom image window to show the recognition in real-time  
	5. Integrate with ROS  
* *The code (integrated with ROS & the TurtleBot project) is available on GitHub - [http://github.com/patilnabhi/tbotnav]*

<h4>Future work:</h4>
    
* Improve the fingers recognition results by combining with skin-color segmentation and machine learning

*This project was completed as part of the MS in Robotics [(MSR)] program at Northwestern University.*

<h4>References:</h4>

* [http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/]
* [http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/]
* [http://euanfreeman.co.uk/openkinect-python-and-opencv/]


[http://patilnabhi.github.io/portfolio/tbotnav]: http://patilnabhi.github.io/portfolio/tbotnav
[http://github.com/patilnabhi/tbotnav]: http://github.com/patilnabhi/tbotnav
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[OpenCV]: http://opencv.org/
[Rviz]: http://wiki.ros.org/rviz
[http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/]: http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/
[http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/]: http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/
[http://euanfreeman.co.uk/openkinect-python-and-opencv/]: http://euanfreeman.co.uk/openkinect-python-and-opencv/
[(MSR)]: http://www.mccormick.northwestern.edu/robotics/meet-students/profiles-2015-2016/patil-abhishek.html