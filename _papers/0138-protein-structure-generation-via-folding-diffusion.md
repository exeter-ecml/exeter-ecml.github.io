---
layout: paper

title: "Protein structure generation via folding diffusion"
authors:
- Kevin E. Wu
- Kevin K. Yang
- Rianne van den Berg
- James Y. Zou
- Alex X. Lu
- Ava P. Amini

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.15611

abstract: "
The ability to computationally generate novel yet physically foldable protein
structures could lead to new biological discoveries and new treatments
targeting yet incurable diseases. Despite recent advances in protein structure
prediction, directly generating diverse, novel protein structures from neural
networks remains difficult. In this work, we present a new diffusion-based
generative model that designs protein backbone structures via a procedure that
mirrors the native folding process. We describe protein backbone structure as
a series of consecutive angles capturing the relative orientation of the
constituent amino acid residues, and generate new structures by denoising from
a random, unfolded state towards a stable folded structure. Not only does this
mirror how proteins biologically twist into energetically favorable
conformations, the inherent shift and rotational invariance of this
representation crucially alleviates the need for complex equivariant networks.
We train a denoising diffusion probabilistic model with a simple transformer
backbone and demonstrate that our resulting model unconditionally generates
highly realistic protein structures with complexity and structural patterns
akin to those of naturally-occurring proteins. As a useful resource, we
release the first open-source codebase and trained models for protein
structure diffusion.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/microsoft/foldingdiff)
- [Twitter thread](https://twitter.com/KevinKaichuang/status/1576917631659307009)
