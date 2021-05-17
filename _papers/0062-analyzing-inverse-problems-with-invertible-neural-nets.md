---
layout: paper

title: "Analyzing Inverse Problems with Invertible Neural Networks"
authors:
- Lynton Ardizzone
- Jakob Kruse
- Sebastian Wirkert
- Daniel Rahner
- Eric Pellegrini
- Ralf Klessen
- Lena Maier-Hein
- Carsten Rother
- Ullrich Köthe

venue: ICLR
year: 2019

link: https://openreview.net/forum?id=rJed6j0cKX

abstract: "
In many tasks, in particular in natural science, the goal is to determine
hidden system parameters from a set of measurements. Often, the forward
process from parameter- to measurement-space is a well-defined function,
whereas the inverse problem is ambiguous: one measurement may map to multiple
different sets of parameters. In this setting, the posterior parameter
distribution, conditioned on an input measurement, has to be determined. We
argue that a particular class of neural networks is well suited for this
task -- so-called Invertible Neural Networks (INNs). Although INNs are not new,
they have, so far, received little attention in literature. While classical
neural networks attempt to solve the ambiguous inverse problem directly, INNs
are able to learn it jointly with the well-defined forward process, using
additional latent output variables to capture the information otherwise lost.
Given a specific measurement and sampled latent variables, the inverse pass of
the INN provides a full distribution over parameter space. We verify
experimentally, on artificial data and real-world problems from astrophysics
and medicine, that INNs are a powerful analysis tool to find multi-modalities
in parameter space, to uncover parameter correlations, and to identify
unrecoverable parameters. 
"

who_suggested: Tim Dodwell
status: suggested
---
- [Blog post](https://hci.iwr.uni-heidelberg.de/vislearn/inverse-problems-invertible-neural-networks/)
- [Code](https://github.com/VLL-HD/analyzing_inverse_problems)
- [55min Talk and slides](https://indico.cern.ch/event/852553/contributions/4059583/)
