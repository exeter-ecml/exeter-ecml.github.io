---
layout: paper

title: Near-linear Time Gaussian Process Optimization with Adaptive Batching and Resparsification
authors:
- Daniele Calandriello
- Luigi Carratino
- Alessandro Lazaric
- Michal Valko
- Lorenzo Rosasco
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2002.09954

abstract: "
Gaussian processes (GP) are one of the most successful frameworks to model
uncertainty. However, GP optimization (e.g. GP-UCB) suffers from major
scalability issues. Experimental time grows linearly with the number of
evaluations, unless candidates are selected in batches (e.g., using GP-BUCB)
and evaluated in parallel. Furthermore, computational cost is often prohibitive
since algorithms such as GP-BUCB require a time at least quadratic in the
number of dimensions and iterations to select each batch. In this paper, we
introduce BBKB (Batch Budgeted Kernel Bandits), the first no-regret GP
optimization algorithm that provably runs in near-linear time and selects
candidates in batches. This is obtained with a new guarantee for the tracking
of the posterior variances that allows BBKB to choose increasingly larger
batches, improving over GP-BUCB. Moreover, we show that the same bound can be
used to adaptively delay costly updates to the sparse GP approximation used by
BBKB, achieving a near-constant per-step amortized cost. These findings are
then confirmed in several experiments, where BBKB is much faster than 
state-of-the-art methods.
"

who_suggested: George De Ath

status: suggested
---
Accepted to ICML 2020: <https://icml.cc/Conferences/2020/ScheduleMultitrack?event=6521>