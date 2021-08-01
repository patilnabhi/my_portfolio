---
layout: post
title:  "Continuous Blood Pressure Monitoring using Artificial Neural Network"
date:   2014-04-30 01:00:00
last_modified_at:  2015-12-16 13:00:00
excerpt: ""
categories: project
tags:  blood pressure monitoring, neural networks
image:
  feature: bp01.png
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
**Project Details:**

* **Topic**: Investigation and Development of a Novel Continuous Blood Pressure (BP)Monitoring System Based on Artificial Neural Network (ANN)
* A final year thesis project in partial fulfilment of requirements for B.E. (Mechanical) at National University of Singapore (NUS) 
* The project involved use of knowledge from medical, computer and programming disciplines

**Motivation for Project:**

* Healthcare has become an important issue in aging countries such as Singapore
* There is a need to have such solutions where people can monitor their health themselves
* Continuous vital signs monitoring devices are needed that are economical, portable, simple and reliable
* Among these vital signs, continuous monitoring of BP is very important, especially for
elderly people with chronic cardiac conditions

**Objectives of Project:**

The main objectives of this project are:

* To develop a Peaks Detection Algorithm (PDA) for Pulse Transit TIme (PTT) calculation. 
* To develop an ANN model to obtain beat-to-beat BP values. This involves training and testing the ANN, debugging the model and incorporating the model into a vital signs monitoring device

**Tasks** - above-mentioned objectives were achieved via the following tasks:

* An integrated code consisting of following was generated:
	* User Prompt,
	* Peaks Detection Algorithm (PDA),
	* PTT Calculation, and
	* ANN Model using Levenberg-Marquardt Algorithm (LMA) 
* An ECGnPPG Unit (EPU) was developed to determine the Electrocardiogram (ECG) signals and Photoplethysmography (PPG) signals for calculating the PTT
* A preliminary study was conducted on 10 subjects to validate the objectives
* MatLab software was used as a tool for this project

The following images illustrate some of above tasks:

* **Methodology** *(A modified methodology was adopted due to unavailability of ccNexfin Finapres device):*

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp02.png" width="100%"/></center>

* **ANN Training Methodology**:

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp03.png" width="60%"/></center>

* **EPU**:

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp01.png" width="100%"/></center>

* **User Prompt** *(Input data from subjects was gathered using this prompt in MatLab):*

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp04.png" width="50%"/></center>

* **PTT Calculation**:

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp05.png" width="100%"/></center>

* **ANN Model** *(Only 1 layer was used and LMA was used to train ANN):* 

<center><img src="{{ site.baseurl }}/assets/images/posts/fyp-bp/bp06.png" width="100%"/></center>