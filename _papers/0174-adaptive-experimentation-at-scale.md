---
layout: paper

title: "Adaptive Experimentation at Scale: Bayesian Algorithms for Flexible Batches"

authors:
- Ethan Che
- Hongseok Namkoong

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2303.11582

abstract: "
Standard bandit algorithms that assume continual reallocation of measurement
effort are challenging to implement due to delayed feedback and
infrastructural/organizational difficulties. Motivated by practical instances
involving a handful of reallocation epochs in which outcomes are measured in
batches, we develop a new adaptive experimentation framework that can flexibly
handle any batch size. Our main observation is that normal approximations
universal in statistical inference can also guide the design of scalable
adaptive designs. By deriving an asymptotic sequential experiment, we formulate
a dynamic program that can leverage prior information on average rewards. State
transitions of the dynamic program are differentiable with respect to the
sampling allocations, allowing the use of gradient-based methods for planning
and policy optimization. We propose a simple iterative planning method,
Residual Horizon Optimization, which selects sampling allocations by optimizinga planning objective via stochastic gradient-based methods. Our
method significantly improves statistical power over standard adaptive
policies, even when compared to Bayesian bandit algorithms (e.g., Thompson
sampling) that require full distributional knowledge of individual rewards.
Overall, we expand the scope of adaptive experimentation to settings which are
difficult for standard adaptive policies, including problems with a small
number of reallocation epochs, low signal-to-noise ratio, and unknown reward
distributions.
"

who_suggested: George De Ath
status: suggested
---
- NeurIPS 2022 Workshop: [Paper](https://gp-seminar-series.github.io/neurips-2022/assets/camera_ready/38.pdf) & [Poster](https://gp-seminar-series.github.io/neurips-2022/assets/camera_ready/38_poster.pdf)
