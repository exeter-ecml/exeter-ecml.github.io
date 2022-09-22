---
layout: paper

title: "Pre-Train Your Loss: Easy Bayesian Transfer Learning with Informative Prior"
authors:
- Ravid Shwartz-Ziv
- Micah Goldblum
- Hossein Souri
- Sanyam Kapoor
- Chen Zhu
- Yann LeCun
- Andrew Gordon Wilson

venue: "ICML "
year: 2022

link: https://openreview.net/forum?id=ao30zaT3YL

abstract: "
Deep learning is increasingly moving towards a transfer learning paradigm
whereby large *foundation models* are fine-tuned on downstream tasks,
starting from an initialization learned on the source task. But an
initialization contains relatively little information about the source task.
Instead, we show that we can learn highly informative posteriors from the
source task, which serves as the basis for priors that modify the whole loss
surface on the downstream task. This simple modular approach enables
significant performance gains and more data-efficient learning on various
downstream classification and segmentation tasks, serving as a drop-in
replacement for standard pre-training strategies.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/hsouri/BayesianTransferLearning)
- [Twitter thread](https://twitter.com/andrewgwils/status/1528750566389780482)
- [ICML Talk (18min)](https://slideslive.com/38988200/pretrain-your-loss-easy-bayesian-transfer-learning-with-informative-prior)
