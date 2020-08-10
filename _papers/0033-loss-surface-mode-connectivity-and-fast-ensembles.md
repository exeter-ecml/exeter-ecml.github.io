---
layout: paper

title: "Loss Surfaces, Mode Connectivity, and Fast Ensembling of DNNs"
authors:
- Timur Garipov
- Pavel Izmailov
- Dmitrii Podoprikhin
- Dmitry Vetrov
- Andrew Gordon Wilson

venue: Advances in Neural Information Processing Systems 31 (NeurIPS 2018)
year: 2018

link: https://papers.nips.cc/paper/8095-loss-surfaces-mode-connectivity-and-fast-ensembling-of-dnns

abstract: "
The loss functions of deep neural networks are complex and their geometric 
properties are not well understood. We show that the optima of these complex
loss functions are in fact connected by simple curves, over which training
and test accuracy are nearly constant. We introduce a training procedure to
discover these high-accuracy pathways between modes. Inspired by this new
geometric insight, we also propose a new ensembling method entitled Fast
Geometric Ensembling (FGE). Using FGE we can train high-performing ensembles
in the time required to train a single model. We achieve improved performance
compared to the recent state-of-the-art Snapshot Ensembles, on CIFAR-10,
CIFAR-100, and ImageNet.
"

who_suggested: George De Ath

status: suggested
---
Blog <https://izmailovpavel.github.io/curves_blogpost/>

Author presentation: <https://youtu.be/d37VHhPILAU?t=3228>

Poster: <https://drive.google.com/file/d/1ujK1EDKN53cGB8jvBlrbAZrm0zFSuhfi/view>

Code: <https://github.com/timgaripov/dnn-mode-connectivity>