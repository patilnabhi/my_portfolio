---
layout: post
title:  "Bombardier"
date:   2014-04-15 01:00:00
last_modified_at:  2015-12-16 13:00:00
excerpt: ""
categories: project
tags:  design project, abaqus, finite element analysis, composites
image:
  feature: bom.png
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
**Project Details:**

* An industry-sponsored design project as part of requirements at National University of Singapore (NUS)
* Joint collaboration between - **Bombardier (Canada), NUS, Peking University (Beijing) and University of Toronto (UoT)**

**Goal**: To design a repair process in order to repair an aircraft interior composite component such as door, cabin head and wall lining, while ensuring that the repair process meets the requirements set forth by Bombardier

**Problem Statement:**

* Bombardier’s In-Service aircraft experience minor damage to the composite interiors during operation, and replacement of these interior components (such as door liners, overhead bins, side wall and ceiling panels) is not economical as a permanent solution
* Bombardier requires development of new repair processes that are feasible with the objectives of low cost and safety - 
	* Firstly, the repairs must require lower cost to implement when compared to replacement of interior components
	* Secondly, the repairs must abide by the Federal Aviation Administration’s flammability regulations (FAR25.853)

* Model specification of an aircraft interior composite component provided by Bombardier (cross-section):

<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom01.png" width="100%" style="border: solid"/></center> 

**Approach:**

* As a group, we researched on 3 different repair processes
* Finite Element Analysis (FEA) on an aircraft interior composite structure was conducted by our team (NUS) using [Abaqus] software 
* The results from FEA were used to determine the optimal repair process
* A practical structural test was then conducted by UoT to verify the simulation results

**Snapshots of the FEA simulation**: (The detailed process of conducting FEA simulation on an aircraft composite structure is found **[here]**)

1. Original model of composite component designed using Abaqus:

	<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom02.png" width="100%" style="border: solid"/></center> 

2. Modified model:

	<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom03.png" width="100%" style="border: solid"/></center> 

3. 3-point bending modelling:

	<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom04.png" width="100%" style="border: solid"/></center> 

4. Meshing of 1 of 3 types of model:

	<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom05.png" width="100%" style="border: solid"/></center> 

5. Simulation results on entire structure:

	<center><img src="{{ site.baseurl }}/assets/images/posts/bombardier/bom06.png" width="100%" style="border: solid"/></center> 

[Abaqus]: http://www.3ds.com/products-services/simulia/products/abaqus/latest-release/
[here]: {{ site.baseurl }}/assets/docs/bombardier.pdf