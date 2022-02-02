---
layout: paper

title: "Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains"
authors:
- Matthew Tancik
- Pratul Srinivasan
- Ben Mildenhall
- Sara Fridovich-Keil
- Nithin Raghavan
- Utkarsh Singhal
- Ravi Ramamoorthi
- Jonathan Barron
- Ren Ng

venue: "NeurIPS"
year: 2020

link: https://proceedings.neurips.cc/paper/2020/hash/55053683268957697aa39fba6f231c68-Abstract.html

abstract: "
We show that passing input points through a simple Fourier feature mapping
enables a multilayer perceptron (MLP) to learn high-frequency functions in
low-dimensional problem domains. These results shed light on recent advances
in computer vision and graphics that achieve state-of-the-art results by
using MLPs to represent complex 3D objects and scenes. Using tools from the
neural tangent kernel (NTK) literature, we show that a standard MLP has
impractically slow convergence to high frequency signal components. To
overcome this spectral bias, we use a Fourier feature mapping to transform
the effective NTK into a stationary kernel with a tunable bandwidth. We
suggest an approach for selecting problem-specific Fourier features that
greatly improves the performance of MLPs for low-dimensional regression
tasks relevant to the computer vision and graphics communities.
"

who_suggested: George De Ath
status: suggested
---
- [10min NeurIPS talk](https://www.youtube.com/watch?v=iKyIJ_EtSkw)
- [45min talk](https://www.youtube.com/watch?v=h0SXP6lJxak)
- [project website](https://bmild.github.io/fourfeat/)
- [github](https://github.com/tancik/fourier-feature-networks)
