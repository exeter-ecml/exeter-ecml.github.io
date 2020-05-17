---
layout: paper

title: "You Only Train Once: Loss-Conditional Training of Deep Networks"
authors:
- Alexey Dosovitskiy
- Josip Djolonga
venue: International Conference on Learning Representations (ICLR)
year: 2020

link: https://openreview.net/pdf?id=HyxY6JHKwr

abstract: "
In many machine learning problems, loss functions are weighted sums of several
terms. A typical approach to dealing with these is to train multiple separate
models with different selections of weights and then either choose the best one
according to some criterion or keep multiple models if it is desirable to 
maintain a diverse set of solutions. This is inefficient both at training and 
at inference time. We propose a method that allows replacing multiple models 
trained on one loss function each by a single model trained on a distribution 
of losses. At test time a model trained this way can be conditioned to generate
outputs corresponding to any loss from the training distribution of losses.
We demonstrate this approach on three tasks with parametrized 
losses: β-VAE, learned image compression, and fast style transfer.
"

who_suggested: Richard Everson

status: happened
---

Author presentation: <https://iclr.cc/virtual_2020/poster_HyxY6JHKwr.html>

Reviews: <https://openreview.net/forum?id=HyxY6JHKwr>

Blog: <https://ai.googleblog.com/2020/04/optimizing-multiple-loss-functions-with.html>
