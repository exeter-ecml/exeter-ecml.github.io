---
layout: paper

title: "Convexifying Transformers: Improving optimization and understanding of transformer networks"

authors:
- Tolga Ergen
- Behnam Neyshabur
- Harsh Mehta

venue: "arXiv (ICLR 2023 submission)"

year: 2022

link: https://openreview.net/forum?id=PJVZCd4Dn2w

abstract: "
Understanding the fundamental mechanism behind the success of transformer
networks is still an open problem in the deep learning literature. Although
their remarkable performance has been mostly attributed to the self-attention
mechanism, the literature still lacks a solid analysis of these networks and
interpretation of the functions learned by them. To this end, we study the
training problem of attention/transformer networks and introduce a novel convex
analytic approach to improve the understanding and optimization of these
networks. Particularly, we first introduce a convex alternative to the
self-attention mechanism and reformulate the regularized training problem of
attention/transformer networks. Then, we cast the reformulation as a convex
optimization problem that is interpretable and easier to optimize. Moreover, as
a byproduct of our convex analysis, we reveal an implicit regularization
mechanism, which promotes sparsity across tokens. Therefore, we not only improve
the optimization of attention/transformer networks but also provide a solid
theoretical understanding of the functions learned by them. We also demonstrate
the effectiveness of our theory through several numerical experiments.
"

who_suggested: George De Ath
status: suggested
---
- [Twitter thread](https://twitter.com/tolgaergen_/status/1594894707028787200)
