---
layout: paper

title: "Meta-Surrogate Benchmarking for Hyperparameter Optimization"
authors:
- Aaron Klein
- Zhenwen Dai
- Frank Hutter
- Neil Lawrence
- Javier Gonzalez

venue:  Advances in Neural Information Processing Systems 32
year: 2019

link: http://papers.nips.cc/paper/8857-meta-surrogate-benchmarking-for-hyperparameter-optimization

abstract: "
Despite the recent progress in hyperparameter optimization (HPO), available 
benchmarks that resemble real-world scenarios consist of a few and very large 
problem instances that are expensive to solve. This blocks researchers and 
practitioners no only from systematically running large-scale comparisons 
that are needed to draw statistically significant results but also from 
reproducing experiments that were conducted before. This work proposes a method
to alleviate these issues by means of a meta-surrogate model for HPO tasks 
trained on off-line generated data. The model combines a probabilistic encoder
with a multi-task model such that it can generate inexpensive and realistic 
tasks of the class of problems of interest. We demonstrate that benchmarking 
HPO methods on samples of the generative model allows us to draw more coherent
and statistically significant conclusions that can be reached orders of
magnitude faster than using the original tasks. We provide evidence of our
findings for various HPO methods on a wide class of problems. 
"

who_suggested: George De Ath

status: suggested
---
