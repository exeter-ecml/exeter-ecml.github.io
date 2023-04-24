---
layout: paper

title: "Double Descent Demystified: Identifying, Interpreting & Ablating the Sources of a Deep Learning Puzzle"

authors:
- Rylan Schaeffer
- Mikail Khona
- Zachary Robertson
- Akhilan Boopathy
- Kateryna Pistunova
- Jason W. Rocks
- Ila Rani Fiete
- Oluwasanmi Koyejo

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2303.14151

abstract: "
Double descent is a surprising phenomenon in machine learning, in which as the
number of model parameters grows relative to the number of data, test error
drops as models grow ever larger into the highly overparameterized (data
undersampled) regime. This drop in test error flies against classical learning
theory on overfitting and has arguably underpinned the success of large models
in machine learning. This non-monotonic behavior of test loss depends on the
number of data, the dimensionality of the data and the number of model
parameters. Here, we briefly describe double descent, then provide an
explanation of why double descent occurs in an informal and approachable
manner, requiring only familiarity with linear algebra and introductory
probability. We provide visual intuition using polynomial regression, then
mathematically analyze double descent with ordinary linear regression and
identify three interpretable factors that, when simultaneously all present,
together create double descent. We demonstrate that double descent occurs on
real data when using ordinary linear regression, then demonstrate that double
descent does not occur when any of the three factors are ablated. We use this
understanding to shed light on recent observations in nonlinear models
concerning superposition and double descent. Code is publicly available.
"

who_suggested: Tinkle Chugh
status: suggested
---
- [GitHub](https://github.com/RylanSchaeffer/Stanford-AI-Alignment-Double-Descent-Tutorial)
