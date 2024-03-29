---
layout: paper

title: "Random Features for Kernel Approximation: A Survey on Algorithms, Theory, and Beyond"
authors:
- Fanghui Liu
- Xiaolin Huang
- Yudong Chen
- Johan A. K. Suykens

venue: "IEEE TPAMI"
year: 2021

link: https://arxiv.org/abs/2004.11154

abstract: "
Random features is one of the most popular techniques to speed up kernel
methods in large-scale problems. Related works have been recognized by the
NeurIPS Test-of-Time award in 2017 and the ICML Best Paper Finalist in 2019.
The body of work on random features has grown rapidly, and hence it is
desirable to have a comprehensive overview on this topic explaining the
connections among various algorithms and theoretical results. In this survey,
we systematically review the work on random features from the past ten years.
First, the motivations, characteristics and contributions of representative
random features based algorithms are summarized according to their sampling
schemes, learning procedures, variance reduction properties and how they
exploit training data. Second, we review theoretical results that center around
the following key question: how many random features are needed to ensure a
high approximation quality or no loss in the empirical/expected risks of the
learned estimator. Third, we provide a comprehensive evaluation of popular
random features based algorithms on several large-scale benchmark datasets and
discuss their approximation quality and prediction performance for
classification. Last, we discuss the relationship between random features and
modern over-parameterized deep neural networks (DNNs), including the use of
high dimensional random features in the analysis of DNNs as well as the gaps
between current theoretical and empirical results. This survey may serve as a
gentle introduction to this topic, and as a users' guide for practitioners
interested in applying the representative algorithms and understanding
theoretical results under various technical assumptions. We hope that this
survey will facilitate discussion on the open problems in this topic, and more
importantly, shed light on future research directions.
"

who_suggested: George De Ath
status: suggested
---
[TPAMI version (shorter)](https://ieeexplore.ieee.org/document/9495136)
