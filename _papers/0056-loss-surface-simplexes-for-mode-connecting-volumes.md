---
layout: paper

title: "Loss Surface Simplexes for Mode Connecting Volumes and Fast Ensembling"
authors:
- Gregory W. Benton
- Wesley J. Maddox
- Sanae Lotfi
- Andrew Gordon Wilson

venue: arXiv
year: 2021

link: https://arxiv.org/abs/2102.13042

abstract: "
With a better understanding of the loss surfaces for multilayer networks, we
can build more robust and accurate training procedures. Recently it was
discovered that independently trained SGD solutions can be connected along
one-dimensional paths of near-constant training loss. In this paper, we show
that there are mode-connecting simplicial complexes that form multi-dimensional
manifolds of low loss, connecting many independently trained models. Inspired
by this discovery, we show how to efficiently build simplicial complexes for
fast ensembling, outperforming independently trained deep ensembles in
accuracy, calibration, and robustness to dataset shift. Notably, our approach
only requires a few training epochs to discover a low-loss simplex, starting
from a pre-trained solution.
"

who_suggested: Melike Karatas

status: suggested
---
- [Github](hhttps://github.com/g-benton/loss-surface-simplexes)
