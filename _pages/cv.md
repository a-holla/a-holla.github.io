---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
A compact PDF version of the CV can be found [here](/files/CV_new.pdf). (Current upto first semester, senior year at IIT-D)

Education
======
* B.Tech. in Electrical Engineering, Indian Institute of Technology Delhi, 2024 
  * GPA: 9.15/10, ranked 4/192
  * Honoured with IIT Delhi Merit Prize (Top 7% in the department) in semesters 3, 5, 6 and 7
  
Selected Research Projects
======
* Spiking Neural Networks for Visual Memory Consolidation, with Prof. Debanjan Bhowmik, _IIT Bombay_ (Spring 2024)
  * Implemented the visuospatial sketchpad of working memory (a division of short term memory) using a network of spiking neurons. Three 'high-level' psychological phenomena associated with the visuospatial sketchpad, namely retention, recapitulation and interference were explained using 'low-level' networks of neurons. The network was divided into three sections: the sensory memory which 'sees' the input image, the visuospatial sketchpad, and the long-term memory. Repeated exposure to input images results in learning of the long-term memory to distinguish different inputs. Analog circuitry was designed and simulated to implement our proposed network in hardware. The github repo and the thesis for this project can be found [here](https://github.com/a-holla/SNN-WM)
  
* Spiking Neural Networks for Edge-AI datasets, with Prof. Debanjan Bhowmik, _IIT Bombay_ (Fall 2023)
  * Proposed a SNN for discriminating electromyography (EMG) signals corresponding to different gestures (based on the ROSHAMBO dataset). The SNN learns through surrogate gradient descent. A hardware implementation of the model in inference only mode was proposed, and the performance degradation due to the non-idealities of the underlying non-volatile memory device that stores the weights was studied. 
 
*  Analog Neural Network, with Prof. Debanjan Bhowmik, _IIT Bombay_ (Fall 2021 - Spring 2023)
  * Designed hardware accelerators for non-spiking artificial neural networks using non-volatile emerging memory devices. Used crossbar arrays to perform vector multiplications in O(1) time, using spintronic devices that store network weights or parameters. A custom learning algorithm involving quantization and thresholding was devised due to limited device memory. Effect of the non-ideal behaviour of the memory device on training and inference of a FCNN and CNN was studied. Circuit level simulation was performed on Cadence Virtuoso, behavioral simulation was done on python. The papers based on this work can be found [here](/_publications/demonstration_synaptic_behavior.md) and [here](/_publications/impact_of_defects.md).
  
* Virtual Brain Simulation, with Prof. Saurabh Gandhi, _IIT Delhi_ (Fall 2023)
  * Aimed to investigate brain structural connectivity changes in patients with Alzheimer’s Disease. The goal was to virtually stimulate a brain model with transcranial magnetic stimulation (TMS) and check for differences in EEG responses between healthy individuals and those afflicted with Alzheimer's disease. We concluded that significant differences emerge in the EEG response of certain channels, when subjected to TMS of the temporal lobe.

* Random Forests for Medical Applications, with Prof. Can Li, _HKU_ (Summer 2022)
  * Semantic segmentation of tumor regions in human kidneys using random forests as a viable alternative to CNNs. Utilized advanced image processing algorithms to extract useful features, and performed selection of best features. Explored using random forests combined with CNNs for increasing segmentation accuracy. Random Forests train faster than CNNs at the cost of accuracy, the hybrid RF-CNN seemed to be the best solution in resource constrained situations.

<span style="color: red;">Work</span> and Research Experience
======
* December 2021 - June 2024: Research Assistant, NAITS Group
  * IIT Delhi/Bombay
  * Supervisor: Prof. Debanjan Bhowmik

* July 2023 - December 2023: Research Assistant, CSNDL Lab
  * IIT Delhi
  * Supervisor: Prof. Saurabh Gandhi

* Summer 2022: Research Assistant, CANlab
  * Hong Kong University
  * Supervisor: Prof. Can Li
 
* <span style="color: red;"> Summer 2023: Data Scientist, Ripik AI </span>

* <span style="color: red;"> Winter 2023: Hardware Engineer Intern, Aeronautical Development Establishment, DRDO</span>
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
