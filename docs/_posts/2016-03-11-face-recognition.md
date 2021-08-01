---
layout: post
title:  "Face Recognition"
date:   2016-03-11 13:00:00
last_modified_at:  2016-03-15 14:00:00
excerpt: ""
categories: project
tags:  face recognition, face detection, OpenCv, fisherfaces, eigenfaces, robotics, ROS
image:
  feature: face_recog.png
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
<h4>Goal:</h4>

* Using a webcam, OpenCV and ROS, develop an API to recognize people in real-time

<h4>Overview:</h4>

* The following flow-chart shows how the interface functions:

<center><img style="border: solid" src="{{ site.baseurl }}assets/images/posts/face-recog/flow_chart.png" width="100%"/></center>

<h4>Demo:</h4>

<p><center><iframe width="1920" height="1080" src="https://www.youtube.com/embed/nvPzOo8tyUs" frameborder="0" allowfullscreen></iframe></center></p>

<h4>Project Website:</h4>  

* This project was integrated into another bigger project on TurtleBot navigation and can be viewed at - [http://patilnabhi.github.io/portfolio/tbotnav] 

<h4>Project Details:</h4>
<!-- 1. **Detect faces:**   
<br>
2. **Capture faces:**    
<br>
3. **Train face data using Fisher's Linear Discriminant Algorithm (LDA):**  
<br>
4. **Recognize faces:**  
<br>
5. **Create a simple GUI to capture and recognize faces:**  
<br>
6. **Integrate with ROS:**  -->

* Fisherfaces algorithm is implemented to train and recognize faces. The algorithm can be summarized as follows:

<center><img style="border: solid" src="{{ site.baseurl }}assets/images/posts/face-recog/fisher.png" width="100%"/></center>
* *The code (integrated with ROS & the TurtleBot project) is available on GitHub - [http://github.com/patilnabhi/tbotnav]*

<h4>Future work:</h4>
    
* Improve accuracy of classification by combining various classifiers such as Principal Component Analysis (PCA), Independent Component Analysis (ICA) and LDA; this could be done using a Radial Basis Function (RBF)-based interpolation

*This project was completed as part of the MS in Robotics [(MSR)] program at Northwestern University.*

<!-- **References:** -->

[http://github.com/patilnabhi/tbotnav]: http://github.com/patilnabhi/tbotnav
[http://patilnabhi.github.io/portfolio/tbotnav]: {{ site.baseurl }}/tbotnav
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[OpenCV]: http://opencv.org/
[Rviz]: http://wiki.ros.org/rviz
[(MSR)]: http://www.mccormick.northwestern.edu/robotics/meet-students/profiles-2015-2016/patil-abhishek.html