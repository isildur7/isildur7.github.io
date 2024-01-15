---
layout: page
title: "Research and Projects"
permalink: /research/
---
My research is focused on making new breed of task-based optical systems which are optimized in the same loop as the machine learning algorithms that process the data obtained by these systems. We are increasingly using machine learning to process the images that we take. Instead of optimizing the two components: optics and algorithms, separately and sequentially, we can treat the entire system as one neural network and develop an end-to-end optimization framework.

![Joint Optimization Figure](/assets/images/jointopt.png "Joint Optimization")

Specifically, the early layers of the network model the physical image formation, and all subsequent layers represent the computational algorithm. All the parameters are learned based on task-specific loss over a large dataset. Such a learning-based framework can potentially go beyond the limits imposed by model-based methods and create better sensor systems. A specific example of this approach is to [optimize the illumination in microscopes](./microscopes.html). I have also worked on a system to image a very high field-of-view using [overlapped imaging](./research/ovelapped_imaging.md).

Currently, I am working on seeing through highly scattering media such as tissue. I am using a technique known as variational optimization, which is a method to estimate gradients of non-differentiable functions by using differentiable bounds on them. More details to follow.
