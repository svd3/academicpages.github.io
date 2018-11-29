---
title: "The Science of Mind Reading: New Inverse Optimal Control framework"
collection: publications
permalink: /publication/msthesis
download: /files/msthesis.pdf
excerpt: 'Continuous control and planning by the brain remain poorly understood and is a major challenge in the field of Neuroscience. To truly say that we understand the underlying mechanisms we should first be able to explain the behavioral actions of the animals, so that we can relate the neural activity to these explanations.'
date: 2018-11-01
venue: 'MA Thesis, Rice University'
paperurl: 'http://academicpages.github.io/files/irl.pdf' #add arxiv link
#citation: 'Daptardar, Saurabh. (2017). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
citation: 'Daptardar, Saurabh. (2018).'
---
<span style="font-size: 0.5em;">
Abstract:
Continuous control and planning by the brain remain poorly understood and is a major challenge in the field of Neuroscience. To truly say that we understand the underlying mechanisms we should first be able to explain the behavioral actions of the animals, so that we can relate the neural activity to these explanations. We hypothesize that animals choose actions rationally under possibly mistaken assumptions about the world. That is, their actions result from solving an optimal control problem. We consider a naturalistic task to study this in greater detail, under a formal optimal control framework of Partially Observable Markov Decision Processes.

In our "firefly" task, monkeys are trained to steer to catch transiently visible fireflies in a Virtual Reality environment, using motion cues to navigate. There are no spatial landmarks in this task, which introduces significant uncertainty. The animal must therefore make decisions to maximize its total reward based on beliefs about the hidden firefly location. We cannot observe this internal belief state, nor the internal model assumed by the animal, but only the actions chosen and the sensory observations the animal received. To explain the actions we need to reconstruct the internal model which results in the actions.

Using reinforcement learning algorithms, we solve the forward problem of solving for the optimal actions given a model and a given reward function. We then propose a novel framework of inverse reinforcement learning, which learns optimal policies generalized over the model space. Our proposed method is able to recover the true model of simulated agents within theoretical error bounds. Finally, we interpret our framework in a way that opens new possibilities for hierarchical inference while an animal learns.

[Download pdf](/files/mstheis.pdf) </span>
