---
layout: paper

title: One-Shot Bayes Opt with Probabilistic Population Based Training
authors:
- Jack Parker-Holder
- Vu Nguyen
- Stephen Roberts
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2002.02518

abstract: "
Selecting optimal hyperparameters is a key challenge in machine learning. An 
exciting recent result showed it is possible to learn high-performing 
hyperparameter schedules on the fly in a single training run through methods 
inspired by Evolutionary Algorithms. These approaches have been shown to 
increase performance across a wide variety of machine learning tasks, ranging 
from supervised (SL) to reinforcement learning (RL). However, since they remain
primarily evolutionary, they act in a greedy fashion, thus require a 
combination of vast computational resources and carefully selected 
meta-parameters to effectively explore the hyperparameter space. To address 
these shortcomings we look to Bayesian Optimization (BO), where a Gaussian 
Process surrogate model is combined with an acquisition function to produce a
principled mechanism to trade off exploration vs exploitation. Our approach, 
which we call Probabilistic Population-Based Training (P2BT), is able to 
transfer sample efficiency of BO to the online setting, making it possible to 
achieve these traits in a single training run. We show that P2BT is able to 
achieve high performance with only a small population size, making it useful 
for all researchers regardless of their computational resources.
"

who_suggested: George De Ath

status: suggested
---

PBT: <https://deepmind.com/blog/article/population-based-training-neural-networks>