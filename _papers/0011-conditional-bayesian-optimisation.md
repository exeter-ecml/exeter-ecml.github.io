---
layout: paper

title: "ConBO: Conditional Bayesian Optimization"
authors:
- Michael Pearce
- Janis Klaise
- Matthew Groves
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2002.09996

abstract: "
Bayesian optimization is a class of data efficient model based algorithms
typically focused on global optimization. We consider the more general case
where a user is faced with multiple problems that each need to be optimized
conditional on a state variable, for example we optimize the location of
ambulances conditioned on patient distribution given a range of cities with
different patient distributions. Similarity across objectives boosts
optimization of each objective in two ways: in modelling by data sharing across
objectives, and also in acquisition by quantifying how all objectives benefit
from a single point on one objective. For this we propose ConBO, a novel
efficient algorithm that is based on a new hybrid Knowledge Gradient method,
that outperforms recently published works on synthetic and real world problems,
and is easily parallelized to collecting a batch of points.
"

who_suggested: Tinkle Chugh

status: suggested
---
