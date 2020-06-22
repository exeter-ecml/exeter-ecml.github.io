---
layout: paper

title: "Explaining The Behavior Of Black-Box Prediction Algorithms With Causal Learning"
authors:
- Numair Sani
- Daniel Malinsky
- Ilya Shpitser
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2006.02482

abstract: "
We propose to explain the behavior of black-box prediction methods (e.g., deep
neural networks trained on image pixel data) using causal graphical models.
Specifically, we explore learning the structure of a causal graph where the
nodes represent prediction outcomes along with a set of macro-level
\"interpretable\" features, while allowing for arbitrary unmeasured confounding
among these variables. The resulting graph may indicate which of the
interpretable features, if any, are possible causes of the prediction outcome
and which may be merely associated with prediction outcomes due to confounding.
The approach is motivated by a counterfactual theory of causal explanation
wherein good explanations point to factors which are \"difference-makers\" in
an interventionist sense. The resulting analysis may be useful in algorithm
auditing and evaluation, by identifying features which make a causal difference
to the algorithm's output.
"

who_suggested: George De Ath

status: suggested
---
