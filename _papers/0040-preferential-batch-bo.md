---
layout: paper

title: "Preferential Batch Bayesian Optimization"
authors:
- Eero Siivola
- Akash Kumar Dhaka
- Michael Riis Andersen
- Javier González
- Pablo Garcia Moreno
- Aki Vehtari

venue: arXiv (Under review at AISTATS)
year: 2020

link: https://arxiv.org/abs/2003.11435

abstract: "
Most research in Bayesian optimization (BO) has focused on direct feedback 
scenarios, where one has access to exact, or perturbed, values of some 
expensive-to-evaluate objective. This direction has been mainly driven by the 
use of BO in machine learning hyper-parameter configuration problems. However, 
in domains such as modelling human preferences, A/B tests or recommender 
systems, there is a need of methods that are able to replace direct feedback 
with preferential feedback, obtained via rankings or pairwise comparisons. In 
this work, we present Preferential Batch Bayesian Optimization (PBBO), a new 
framework that allows to find the optimum of a latent function of interest, 
given any type of parallel preferential feedback for a group of two or more 
points. We do so by using a Gaussian process model with a likelihood specially
designed to enable parallel and efficient data collection mechanisms, which are
key in modern machine learning. We show how the acquisitions developed under
this framework generalize and augment previous approaches in Bayesian
optimization, expanding the use of these techniques to a wider range of
domains. An extensive simulation study shows the benefits of this approach,
both with simulated functions and four real data sets. 
"

who_suggested: George De Ath

status: happened
---
[Source code](https://github.com/EmuKit/emukit/tree/master/emukit/examples/preferential_batch_bayesian_optimization)