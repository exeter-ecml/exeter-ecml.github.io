---
layout: paper

title: "Prediction-oriented Bayesian active learning"

authors:
- Freddie Bickford Smith
- Andreas Kirsch
- Sebastian Farquhar
- Yarin Gal
- Adam Foster
- Tom Rainforth

venue: "AISTATS"

year: 2023

link: https://proceedings.mlr.press/v206/smith23a.html

abstract: "
Information-theoretic approaches to active learning, such as BALD, typically
focus on maximising the information gathered about the model parameters. We
highlight that this can be suboptimal from the perspective of predictive
performance. In particular, BALD fails to account for the input distribution
and thus is prone to prioritise data that is of low relevance to prediction.
Addressing this shortfall, we propose the expected predictive information gain
(EPIG), an acquisition function that measures information gain in the space of
predictions rather than parameters. We find that using EPIG leads to stronger
predictive performance compared with BALD across a range of datasets and
models, and thus provides an appealing drop-in replacement.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/fbickfordsmith/epig)
