---
layout: post
title:  "What Keeps Spinning Tops Upright?"
date:   2015-12-10 01:00:00
last_modified_at:  2015-12-16 13:00:00
excerpt: ""
categories: project
tags: machine dynamics, ME314, tops, spin, spinning tops
image:
  feature: top.jpg
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
This was a final project for Theory of Machine Dynamics course at Northwestern University (NU). The **goal** of this project was to simulate and animate the behavior of a spinning top using [Mathematica] software. 

**Project Objectives**:

* Develop a mathematical model to simulate behavior of spinning top using **[lagrangian mechanics]**
* Deduce the precession and nutation behavior of the top, in turn answering the classic question - *'What keeps spinning tops upright?'*
* Generate a 3D graphics model in Mathematica
* Use Mathematica to animate the 3D model to illustrate various behaviors of spinning top

*Precession* refers to revolution of top about vertical axis.
*Nutation* refers to changes in lean angle of top (bobbing up and down)

**Drawing of system**:

<center><img src="{{ site.baseurl }}/assets/images/top-system.png" width="80%"/></center>

To keep the project feasible, following **assumptions** were made:

* Top modelled as a 'heavy' top that remains fixed to the ground
* Geometry of top simplified; it is modelled as a wheel on a thin stem as shown in above figure

**Results Summary**:

<!-- Full report available here: **[Project Report]** -->

Here I present animation of top and the resulting trajectory for 3 different cases:

A. Initial precession rate is **equal** to zero:

*Animation:*

<center><img src="{{ site.baseurl }}/assets/images/top001.gif" width="70%"/></center>

*Trajectory:*

<center><img src="{{ site.baseurl }}/assets/images/top0001.png" width="70%"/></center>

B. Initial precession rate is **greater** than zero

*Animation:*

<center><img src="{{ site.baseurl }}/assets/images/top002.gif" width="70%"/></center>

*Trajectory:*

<center><img src="{{ site.baseurl }}/assets/images/top0002.png" width="70%"/></center>

C. Initial precession rate is **less** than zero

*Animation:*

<center><img src="{{ site.baseurl }}/assets/images/top003.gif" width="70%"/></center>

*Trajectory:*

<center><img src="{{ site.baseurl }}/assets/images/top0003.png" width="70%"/></center>

**References:**

* Thumbnail image of tops: Adapted from [http://linoit.com/users/jarjon/canvases/Spinning%20Top%20Activity%20Research]

[Mathematica]: https://www.wolfram.com/mathematica/
[lagrangian mechanics]: https://en.wikipedia.org/wiki/Lagrangian_mechanics
[http://linoit.com/users/jarjon/canvases/Spinning%20Top%20Activity%20Research]: http://linoit.com/users/jarjon/canvases/Spinning%20Top%20Activity%20Research
<!-- [Project Report]: {{ site.baseurl }}/assets/me314_report.pdf -->