---
layout: paper

title: "How Much Data Are Augmentations Worth? An Investigation into Scaling Laws, Invariance, and Implicit Regularization"
authors:
- Jonas Geiping
- Micah Goldblum
- Gowthami Somepalli
- Ravid Shwartz-Ziv
- Tom Goldstein
- Andrew Gordon Wilson

venue: "arXiv"

year: 2022

link: https://arxiv.org/abs/2210.06441

abstract: "
Despite the clear performance benefits of data augmentations, little is known
about why they are so effective. In this paper, we disentangle several key
mechanisms through which data augmentations operate. Establishing an exchange
rate between augmented and additional real data, we find that in
out-of-distribution testing scenarios, augmentations which yield samples that
are diverse, but inconsistent with the data distribution can be even more
valuable than additional training data. Moreover, we find that data
augmentations which encourage invariances can be more valuable than invariance
alone, especially on small and medium sized training sets. Following this
observation, we show that augmentations induce additional stochasticity during
training, effectively flattening the loss landscape.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/JonasGeiping/dataaugs)
