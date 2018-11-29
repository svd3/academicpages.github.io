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
  * Proposed _novel_ approach to explain and detect change of mind/decision using the control framework.
  * Developed _novel_ framework for Inverse Reinforcement Learning in POMDPs with continuous states and continuous actions.
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
* Parameter Space Inverse Reinforcement Learning: Master's Thesis, (2016 - 2018)   
_Dr. Xaq Pitkow_
  * Developed a novel generalized framework for Inverse Reinforcement Learning to recover true parameters accurately within error bounds.

* Control and Reinforcement Learning (RL)
  * Implemented and trained various control and deep RL algorithms: LQR, Iterative LQG, deep Q Networks (DQN), Double DQN, deep deterministic Policy gradient (DDPG), Advantage Actor Critic (A2C) etc.

* Decoding neural activity to estimate control target (_Neural Signal Processing_)
  * Decoded reach targets with 84% accuracy using the plan period and movement period signals from the dorsal pre-motor cortex.

* Neural decoding: ECOG data to speech (_Statistical Learning_)
  * Implemented ensemble methods to classify the neural recordings into dictionary of words with an accuracy of 74%.

* Image Captioning with RNNs
  * Implemented and trained a RNN (LSTM) model to caption images on COCO dataset.

* Character Sequence RNNs
  * Implemented and trained a single layer RNN (LSTM) char by char model to generate text.

* Single Frame Image Super Resolution: B.Tech Thesis, (2013 - 2014)   
_Prof. Devendra Jalihal_
  * Implemented the kernel Hebbian algorithm for single frame image super resolution.
  * Integrated algorithm into a web application for medical/agricultural advisory.

Skills
======
---
* Programming Languages:
  * Python, C, C++, R, MATLAB
* Deep learning frameworks:
  * PyTorch, Keras

Publications
======
---
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>




Honors & Awards
======
---
* (2016 - 2018) **Fellowship**, Rice ECE Department


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
