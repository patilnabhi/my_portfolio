---
title: "Baxter Pick 'n' Place"
video:
  vimeoId: 172662439
categories:
  - project
tags:
  - baxter, robotics
last_modified_at: 2015-12-11 01:00:00
---

**Project Website:** [https://github.com/patilnabhi/baxter_two]

This is a [ROS] project developed as part of ME495 - Embedded Systems in Robotics course at Northwestern University ([NU]).
(ROS stands for Robot Operating System).

The **goal** of this project was to use [baxter] robot to pick and place objects from one location to another.

The following video shows our project in action:

{% include responsive-embed url="https://player.vimeo.com/video/172662439" %}

**Summary**:

* Baxter robot is used to pick and place different sized square blocks from one location to another
* Our group not only got baxter to pick & place the square blocks, but also stack larger of the cubes on top of each other
* The project consists of 3 major elements:
    * **Image processing**: [OpenCv] is used as a tool to detect objects & process images from baxter's camera. A transformation of the objects in the image frame is obtained.
    * **Moving baxter's arms**: [MoveIt!] is used as a tool to move baxter's arms to pick and place objects. 
    * **Planning scene**: MoveIt! is also used to visualize the planning scene in [Rviz] - a 3D visualization tool for ROS. Planning scene consisted of objects present around baxter. The main purpose was not only to visualize the scene, but also to prevent baxter from colliding with these objects

**Future work**:
    
* Improved camera calibration
* GUI development: A Graphical User Interface (GUI) that allows user to click an object in the virtual world (e.g in [Gazebo]), and pick and place that particular object.

**References:**

* Thumbnail image of baxter: Adapted from [http://www.4erevolution.com/en/robots-youtube/] 

[https://github.com/patilnabhi/baxter_two]: https://github.com/patilnabhi/baxter_two
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[baxter]: http://www.rethinkrobotics.com/baxter/
[OpenCv]: http://opencv.org/
[MoveIt!]: http://moveit.ros.org/
[Rviz]: http://wiki.ros.org/rviz
[Gazebo]: http://www.gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros
[http://www.4erevolution.com/en/robots-youtube/]: http://www.4erevolution.com/en/robots-youtube/

