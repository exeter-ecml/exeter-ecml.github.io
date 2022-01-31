---
layout: paper

title: "Bayesian Modeling and Uncertainty Quantification for Learning to Optimize: What, Why, and How"
authors:
- Yuning You
- Yue Cao
- Tianlong Chen
- Zhangyang Wang
- Yang Shen

venue: "ICLR"
year: 2022

link: https://openreview.net/forum?id=EVVadRFRgL7

abstract: "
Optimizing an objective function with uncertainty awareness is well-known to 
improve the accuracy and confidence of optimization solutions. Meanwhile,
another relevant but very different question remains yet open: how to model and
quantify the uncertainty of an optimization algorithm (a.k.a., optimizer)
itself? To close such a gap, the prerequisite is to consider the optimizers as
sampled from a distribution, rather than a few prefabricated and fixed update
rules. We first take the novel angle to consider the algorithmic space of
optimizers, and provide definitions for the optimizer prior and likelihood,
that intrinsically determine the posterior and therefore uncertainty. We then
leverage the recent advance of learning to optimize (L2O) for the space
parameterization, with the end-to-end training pipeline built via variational
inference, referred as uncertainty-aware L2O (UA-L2O). Our study represents the
first effort to recognize and quantify the uncertainty of the optimization
algorithm. The extensive numerical results show that, UA-L2O achieves superior
optimization performances in two out of three test functions, the loss function
in data privacy attack, and the energy function in docking four out of five
protein pairs, with the most accurate posterior estimation. Besides, the
optimized solutions close to the real solution are of a larger population and
tighter confidence intervals, demonstrating a better calibration capability.
"

who_suggested: George De Ath
status: suggested
---
- [github](https://github.com/Shen-Lab/Bayesian-L2O)
