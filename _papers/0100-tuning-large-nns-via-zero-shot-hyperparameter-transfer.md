---
layout: paper

title: "Tuning Large Neural Networks via Zero-Shot Hyperparameter Transfer"
authors:
- Shereen Elsayed
- Daniela Thyssens
- Ahmed Rashed
- Hadi Samer Jomaa
- Lars Schmidt-Thieme

venue: "NeurIPS"
year: 2021

link: https://www.microsoft.com/en-us/research/publication/tuning-large-neural-networks-via-zero-shot-hyperparameter-transfer/

abstract: "
Hyperparameter (HP) tuning in deep learning is an expensive process,
prohibitively so for neural networks (NNs) with billions of parameters. We show
that, in the recently discovered Maximal Update Parametrization ($$\\mu$$P),
many optimal HPs remain stable even as model size changes. This leads to a new
HP tuning paradigm we call *$$\\mu$$Transfer*: parametrize the target model in
$$\\mu$$P, tune the HP indirectly on a smaller model, and *zero-shot transfer*
them to the full-sized model, i.e., without directly tuning the latter at all.
We verify $$\\mu$$Transfer on Transformer and ResNet. For example, 1) by
transferring pretraining HPs from a model of 13M parameters, we outperform
published numbers of BERT-large (350M parameters), with a total tuning cost
equivalent to pretraining BERT-large once; 2) by transferring from 40M
parameters, we outperform published numbers of the 6.7B GPT-3 model, with
tuning cost only 7% of total pretraining cost. A Pytorch implementation of our
technique can be found at [github.com/microsoft/mup](github.com/microsoft/mup)
and installable via `pip install mup`.
"

who_suggested: George De Ath
status: suggested
---
- [Blog post](https://www.microsoft.com/en-us/research/blog/%C2%B5transfer-a-technique-for-hyperparameter-tuning-of-enormous-neural-networks/)
- [GitHub](http://github.com/microsoft/mup)
- [NeurIPS reviews](https://openreview.net/forum?id=Bx6qKuBM2AD)
