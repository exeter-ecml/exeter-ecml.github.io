---
layout: paper

title: "Combining Gaussian Processes with Neural Networks for Active Learning in Optimization"
authors:
- Jiří Růžička
- Jan Koza
- Jiří Tumpach
- Zbyněk Pitra
- Martin Holena
venue: International Workshop on Interactive Adaptive Learning (IAL2021)
year: 2021

link: https://www.activeml.net/ial2021/pdf/ialatecml_paper9.pdf

abstract: "
One area where active learning plays an important role is black-box optimization of objective functions with expensive evaluations. To deal with such evaluations, continuous black-box optimization has adopted an approach called surrogate modelling or metamodelling, which consists in replacing the true black-box objective in some of its evaluations with a suitable regression model, the selection of evaluations for replacement being an active learning task. This paper concerns surrogate modelling in the context of a surrogate-assisted variant of the continuous black-box optimizer Covariance Matrix Adaptation Evolution Strategy. It reports the experimental investigation of surrogate models combining artificial neural networks with Gaussian processes, for which it considers six different covariance functions. The experiments were performed on the set of $$24$$ noiseless benchmark functions of the platform Comparing Continuous Optimizers COCO with $$5$$ different dimensionalities. Their results revealed that the most suitable covariance function for this combined kind of surrogate models is the rational quadratic followed by the Mat́ern $$\\tfrac{5}{2}$$ and squared exponential. Moreover, the rational quadratic and squared exponential covariances were found interchangeable in the sense that for no function, no group of functions, no dimension and combination of them, the performance of the respective surrogate models was significantly different.
"

who_suggested: Tinkle Chugh
status: suggested
---
- [14 min presentation](https://www.youtube.com/watch?v=575zxhiCtus)
