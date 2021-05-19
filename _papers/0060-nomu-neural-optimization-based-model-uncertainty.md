---
layout: paper

title: "NOMU: Neural Optimization-based Model Uncertainty"
authors:
- Jakob Heiss
- Jakob Weissteiner
- Hanna Wutte
- Sven Seuken
- Josef Teichmann

venue: arXiv
year: 2021

link: https://arxiv.org/abs/2102.13640

abstract: "
We introduce a new approach for capturing model uncertainty for neural networks
(NNs) in regression, which we call Neural Optimization-based Model Uncertainty
(NOMU). The main idea of NOMU is to design a network architecture consisting of
two connected sub-networks, one for the model prediction and one for the model
uncertainty, and to train it using a carefully designed loss function. With
this design, NOMU can provide model uncertainty for any given (previously
trained) NN by plugging it into the framework as the sub-network used for model
prediction. NOMU is designed to yield uncertainty bounds (UBs) that satisfy
four important desiderata regarding model uncertainty, which established
methods often do not satisfy. Furthermore, our UBs are themselves
representable as a single NN, which leads to computational cost advantages in
applications such as Bayesian optimization. We evaluate NOMU experimentally in
multiple settings. For regression, we show that NOMU performs as well as or
better than established benchmarks. For Bayesian optimization, we show that
NOMU outperforms all other benchmarks. 
"

who_suggested: Richard Everson

status: happened
---
- [Code](https://github.com/marketdesignresearch/NOMU)
