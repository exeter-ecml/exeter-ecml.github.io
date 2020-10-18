---
layout: paper

title: "Controllable Pareto Multi-Task Learning"
authors:
- Xi Lin
- Zhiyuan Yang
- Qingfu Zhang
- Sam Kwong

venue: arXiv
year: 2020

link: https://arxiv.org/abs/2010.06313

abstract: "
A multi-task learning (MTL) system aims at solving multiple related tasks at
the same time. With a fixed model capacity, the tasks would be conflicted with
each other, and the system usually has to make a trade-off among learning all
of them together. Multiple models with different preferences over tasks have to
be trained and stored for many real-world applications where the trade-off has
to be made online. This work proposes a novel controllable Pareto multi-task 
learning framework, to enable the system to make real-time trade-off switch 
among different tasks with a single model. To be specific, we formulate the MTL
as a preference-conditioned multiobjective optimization problem, for which 
there is a parametric mapping from the preferences to the optimal Pareto 
solutions. A single hypernetwork-based multi-task neural network is built to 
learn all tasks with different trade-off preferences among them, where the
hypernetwork generates the model parameters conditioned on the preference. At
the inference time, MTL practitioners can easily control the model performance
based on different trade-off preferences in real-time. Experiments on different
applications demonstrate that the proposed model is efficient for solving 
various multi-task learning problems. 
"

who_suggested: Tinkle Chugh

status: suggested
---
Rejected from NeurIPS 2020, submitted to ICLR 2021.

[ICLR Version](https://openreview.net/pdf?id=5mhViEOQxaV)

[Code](https://openreview.net/attachment?id=5mhViEOQxaV&name=supplementary_material)
