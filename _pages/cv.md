---
layout: archive
title: "CV"
permalink: /cv/
download: /files/resume.pdf
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech. in Electrical Engineering, Indian Institute of Technology Madras, 2014
<!--- * M.S. in Electrical Engineering (Neuroscience), Rice University, 2016 - 2018 (expected) --->
* Ph.D in Electrical Engineering (Neuroscience), Rice University, Ongoing (expected)

Work experience
======
* Xaq Labs: Research Assistant, (2016 - )
  * Working on the Firefly project: Understanding the control algorithms of the brain
  * Working on POMDPs, Reinforcement Learning to solve similar tasks in much broader and general framework.
  * Working on Inverse Reinforcement Learning problem and graphical models to do inference on the assumed dynamics and latent variables of the brain
  * Implemented Iterative LQG algorithm and Deep Q Network with experience replay to solve the firefly task.
  * Developed OpenAI Gym environment with rendering for the firefly task.

* Samsung R&D India: Senior Software Engineer
  * Worked on the Car Analytics Engine and Smart Glove Gestures project
  * Developed algorithms for the Samsung connect auto.
  * Worked on user/driver profiling, context based dynamic fuel estimation modeling, maneuver detection, event detection, and gesture recognition based on IMU sensors.
  * Worked on high-dimensional clustering algorithm and statistical learning methods.

Projects
======
* Single Frame Image Super Resolution: B.Tech Final Project, (2013 - 2014)
_Prof. Devendra Jalihal_
  * Implemented the kernel Hebbian algorithm for single frame image super resolution
  * Integrated algorithm into a web application for medical/agricultural advisory.
  * Presented a paper poster on the idea at Indo-UK meet.

* Image Captioning with RNNs
  * Implemented a single layer RNN (LSTM) model to caption images on Microsoft COCO dataset.
  * Working to train it on SVHN dataset to recognize numbers in images.

* Decoding neural activity to estimate control target (_Neural Signal Processing_)
  * Successfully decoded reach targets with the plan period and movement period signals from the dorsal pre-motor cortex.
  * Also implemented and reproduced the results in the paper "Improving neural prosthetic system performance by combining plan and peri-movement activity", Yu et. al.
  * Wrote a code to convert data from Python compatible .npz format to R compatible .rds format and made it available for the project.

* Neural decoding: ECOG data to speech (_Statistical Learning_)
  * Implemented ensemble methods to classify the signals into limited dictionary of words.
  * Identified few brain areas, and frequencies which were important for decoding.

Skills
======
* Programming Languages:
  * C, C++, Python, R, MATLAB
* Deep learning frameworks:
  * PyTorch, Tensorflow, Keras

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & Awards
======
(2016) **Fellowship**, Rice ECE Department Fellowship 

<!---
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams

--->
