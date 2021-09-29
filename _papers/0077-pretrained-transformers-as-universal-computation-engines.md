---
layout: paper

title: "Pretrained Transformers as Universal Computation Engines"
authors:
- Kevin Lu
- Aditya Grover
- Pieter Abbeel
- Igor Mordatch
venue: arXiv
year: 2021

link: https://arxiv.org/abs/2103.05247

abstract: "
We investigate the capability of a transformer pretrained on natural language
to generalize to other modalities with minimal finetuning -- in particular,
without finetuning of the self-attention and feedforward layers of the residual
blocks. We consider such a model, which we call a Frozen Pretrained Transformer
(FPT), and study finetuning it on a variety of sequence classification tasks
spanning numerical computation, vision, and protein fold prediction. In
contrast to prior works which investigate finetuning on the same modality as
the pretraining dataset, we show that pretraining on natural language can
improve performance and compute efficiency on non-language downstream tasks.
Additionally, we perform an analysis of the architecture, comparing the
performance of a random initialized transformer to a random LSTM. Combining the
two insights, we find language-pretrained transformers can obtain strong
performance on a variety of non-language tasks. 
"

who_suggested: George De Ath
status: suggested
---
- [Blog post](https://bair.berkeley.edu/blog/2021/03/23/universal-computation/)
- [github](https://github.com/kzl/universal-computation)
- [Yannic kilcher video](https://www.youtube.com/watch?v=Elxn8rS88bI)
