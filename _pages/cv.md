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
---
* B.Tech. in Electrical Engineering, Indian Institute of Technology Madras, 2014
* M.S. in Electrical Engineering (Neuroscience), Rice University, 2016 - 2018
<!-- * Ph.D in Electrical Engineering (Neuroscience), Rice University, Ongoing (expected) -->

Work experience
======
---
* Xaq Lab: Research Assistant, (2016 - 2018)
  * Designed experiments to study decision making/control in the animal brain.
  * Formulated, modeled, and solved the control problem for the designed experiments.
  * Proposed novel approach to explain and detect change of mind/decision using the control framework.
  * Developed novel framework for Inverse Reinforcement Learning in POMDPs with continuous states and continuous actions.
  * Applied the framework to recover the internal latent parameters for the brains' control model.
  * Predicted the choices made by monkey's with 96% accuracy with our model with the recovered parameters.
  * Predicted change of mind ~100 ms prior to the intended actions using our model.
  * Culminated the research in my Master's Thesis "The Science of Mind Reading: New Inverse Optimal Control framework".

* Samsung R&D India: Senior Software Engineer
  * Samsung Auto Connect: Car and Driver Analytics
    - Developed a solution for driver profiling and scoring.
    - Trained algorithms for detection and classification of driving maneuvers with 92% accuracy.
    - Modeled and developed dynamic context based fuel estimation.
  * Samsung Gear Smartwatches: Sports Analytics
    - Developed application for smart self tutoring for Tennis and Badminton in 'Gear S2' device.
    - Engineered data collection (from professionals), preprocessing, and storing pipeline.
    - Worked on providing smart recommendations, feedback and action matching based on professional players' strokes.
  * Samsung Smart Glove (research)
    - Designed wearable gloves (with sensors) to control Samsung devices.
    - Built gesture recognition and user command interpretation based on sensor signals from the gloves with 82% accuracy.

Projects
======
---
* Parameter Space Inverse Reinforcement Learning: Master's Thesis (2016 - 2018)
_Dr. Xaq Pitkow_
  * abcd
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
---
* Programming Languages:
  * C, C++, Python, R, MATLAB
* Deep learning frameworks:
  * PyTorch, Tensorflow, Keras

Publications
======
---
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>




Honors & Awards
======
---
* (2016) **Fellowship**, Rice ECE Department Fellowship


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
