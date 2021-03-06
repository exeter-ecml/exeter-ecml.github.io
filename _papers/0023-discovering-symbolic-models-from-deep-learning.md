---
layout: paper

title: "Discovering Symbolic Models from Deep Learning with Inductive Biases"
authors:
- Miles Cranmer
- Alvaro Sanchez-Gonzalez
- Peter Battaglia
- Rui Xu
- Kyle Cranmer
- David Spergel
- Shirley Ho
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2006.11287

abstract: "
We develop a general approach to distill symbolic representations of a learned
deep model by introducing strong inductive biases. We focus on Graph Neural
Networks (GNNs). The technique works as follows: we first encourage sparse
latent representations when we train a GNN in a supervised setting, then we
apply symbolic regression to components of the learned model to extract
explicit physical relations. We find the correct known equations, including
force laws and Hamiltonians, can be extracted from the neural network. We then
apply our method to a non-trivial cosmology example-a detailed dark matter
simulation-and discover a new analytic formula which can predict the 
concentration of dark matter from the mass distribution of nearby cosmic
structures. The symbolic expressions extracted from the GNN using our technique
also generalized to out-of-distribution data better than the GNN itself. Our 
approach offers alternative directions for interpreting neural networks and
discovering novel physical principles from the representations they learn.
"

who_suggested: George De Ath

status: suggested
---
Video review of the paper: <https://www.youtube.com/watch?v=LMb5tvW-UoQ>

Blog: <https://astroautomata.com/paper/symbolic-neural-nets/>

Github: <https://github.com/MilesCranmer/symbolic_deep_learning>

Twitter thread: <https://twitter.com/MilesCranmer/status/1275241300829384704>