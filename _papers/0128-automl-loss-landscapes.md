---
layout: paper

title: "AutoML Loss Landscapes"
authors:
- Yasha Pushak
- Holger H. Hoos

venue: "ACM Transactions on Evolutionary Learning and Optimization"
year: 2022

link: https://dl.acm.org/doi/10.1145/3558774

abstract: "
As interest in machine learning and its applications becomes more widespread,
how to choose the best models and hyper-parameter settings becomes more
important. This problem is known to be challenging for human experts, and
consequently, a growing number of methods have been proposed for solving it,
giving rise to the area of automated machine learning (AutoML). Many of the
most popular AutoML methods are based on Bayesian optimization, which makes
only weak assumptions about how modifying hyper-parameters effects the loss of
a model. This is a safe assumption that yields robust methods, as the AutoML
loss landscapes that relate hyper-parameter settings to loss are poorly
understood. We build on recent work on the study of one-dimensional slices of
algorithm configuration landscapes by introducing new methods that test
n-dimensional landscapes for statistical deviations from uni-modality and
convexity, and we use them to show that a diverse set of AutoML loss landscapes
are highly structured. We introduce a method for assessing the significance of
hyper-parameter partial derivatives, which reveals that most (but not all)
AutoML loss landscapes only have a small number of hyper-parameters that
interact strongly. To further assess hyper-parameter interactions, we introduce
a simplistic optimization procedure that assumes each hyper-parameter can be
optimized independently, a single time in sequence, and we show that it obtains
configurations that are statistically tied with optimal in all of the
n-dimensional AutoML loss landscapes that we studied. Our results suggest many
possible new directions for substantially improving the state of the art in
AutoML.
"

who_suggested: George De Ath
status: suggested
---
- [Project page](https://www.cs.ubc.ca/labs/algorithms/Projects/ACLandscapes/)
