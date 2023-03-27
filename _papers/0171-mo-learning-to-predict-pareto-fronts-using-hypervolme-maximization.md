---
layout: paper

title: "Multi-Objective Learning to Predict Pareto Fronts Using Hypervolume Maximization"

authors:
- Timo M. Deist
- Monika Grewal
- Frank J.W.M. Dankers
- Tanja Alderliesten
- Peter A.N. Bosman

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2102.04523

abstract: "
Real-world problems are often multi-objective with decision-makers unable to
specify a priori which trade-off between the conflicting objectives is
preferable. Intuitively, building machine learning solutions in such cases
would entail providing multiple predictions that span and uniformly cover the
Pareto front of all optimal trade-off solutions. We propose a novel approach
for multi-objective training of neural networks to approximate the Pareto front
during inference. In our approach, the neural networks are trained
multi-objectively using a dynamic loss function, wherein each network's losses
(corresponding to multiple objectives) are weighted by their hypervolume
maximizing gradients. We discuss and illustrate why training processes to
approximate Pareto fronts need to optimize on fronts of individual training
samples instead of on only the front of average losses. Experiments on three
multi-objective problems show that our approach returns outputs that are
well-spread across different trade-offs on the approximated Pareto front
without requiring the trade-off vectors to be specified a priori. Further,
results of comparisons with the state-of-the-art approaches highlight the added
value of our proposed approach, especially in asymmetric Pareto fronts.
"

who_suggested: Tinkle Chugh
status: suggested
---
- [GitHub](https://github.com/timodeist/multi_objective_learning)
