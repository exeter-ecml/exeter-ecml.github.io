---
layout: paper

title: "Meta-Learning Acquisition Functions for Transfer Learning in Bayesian Optimization"

citation: "
Michael Volpp, Lukas P. Fröhlich, Kirsten Fischer, Andreas Doerr, Stefan Falkner, Frank Hutter, Christian Daniel,
Meta-Learning Acquisition Functions for Transfer Learning in Bayesian Optimization,
to appear in International Conference on Learning Representations (ICLR), 
2020
"

link: https://openreview.net/pdf?id=ryeYpJSKwr

abstract: "
Transferring knowledge across tasks to improve data-efficiency is one of the
open key challenges in the field of global black-box optimization. Readily
available algorithms are typically designed to be universal optimizers and,
therefore, often suboptimal for specific tasks. We propose a novel transfer
learning method to obtain customized optimizers within the well-established
framework of Bayesian optimization, allowing our algorithm to utilize the
proven generalization capabilities of Gaussian processes. Using reinforcement
learning to meta-train an acquisition function (AF) on a set of related tasks,
the proposed method learns to extract implicit structural information and to
exploit it for improved data-efficiency. We present experiments on a
simulation-to-real transfer task as well as on several synthetic functions and
on two hyperparameter search problems. The results show that our
algorithm (1) automatically identifies structural properties of objective
functions from available source tasks or simulations, (2) performs favourably
in settings with both scarse and abundant source data, and (3) falls back to
the performance level of general AFs if no particular structure is present.
"

who_suggested: George De Ath

status: suggested
---

To appear at ICLR 2020 (spotlight talk).

Reviews: <https://openreview.net/forum?id=ryeYpJSKwr>

Code: <https://github.com/metabo-iclr2020/MetaBO>
