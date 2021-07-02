---
layout: paper

title: "Kernel Identification Through Transformers"
authors:
- Fergus Simpson
- Ian Davies
- Vidhi Lalchand
- Alessandro Vullo
- Nicolas Durrande
- Carl Rasmussen

venue: arXiv
year: 2021

link: https://arxiv.org/abs/2106.08185

abstract: "
Kernel selection plays a central role in determining the performance of
Gaussian Process (GP) models, as the chosen kernel determines both the
inductive biases and prior support of functions under the GP prior. This work
addresses the challenge of constructing custom kernel functions for
high-dimensional GP regression models. Drawing inspiration from recent progress
in deep learning, we introduce a novel approach named KITT: Kernel
Identification Through Transformers. KITT exploits a transformer-based
architecture to generate kernel recommendations in under 0.1 seconds, which is
several orders of magnitude faster than conventional kernel search algorithms.
We train our model using synthetic data generated from priors over a vocabulary
of known kernels. By exploiting the nature of the self-attention mechanism,
KITT is able to process datasets with inputs of arbitrary dimension. We
demonstrate that kernels chosen by KITT yield strong performance over a diverse
collection of regression benchmarks. 
"

who_suggested: George De Ath
status: suggested
---
