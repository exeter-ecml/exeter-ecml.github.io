---
layout: paper

title: "Reconciling modern machine-learning practice and the classical bias–variance trade-off"
authors:
- Mikhail Belkin
- Daniel Hsu
- Siyuan Ma
- Soumik Mandal

venue: Proceedings of the National Academy of Sciences
year: 2019

link: https://www.pnas.org/content/116/32/15849

abstract: "
Breakthroughs in machine learning are rapidly changing science and society, yet
our fundamental understanding of this technology has lagged far behind. Indeed,
one of the central tenets of the field, the bias–variance trade-off, appears to
be at odds with the observed behavior of methods used in modern
machine-learning practice. The bias–variance trade-off implies that a model
should balance underfitting and overfitting: Rich enough to express underlying
structure in data and simple enough to avoid fitting spurious patterns.
However, in modern practice, very rich models such as neural networks are
trained to exactly fit (i.e., interpolate) the data. Classically, such models
would be considered overfitted, and yet they often obtain high accuracy on test
data. This apparent contradiction has raised questions about the mathematical
foundations of machine learning and their relevance to practitioners. In this
paper, we reconcile the classical understanding and the modern practice within
a unified performance curve. This “double-descent” curve subsumes the textbook
U-shaped bias–variance trade-off curve by showing how increasing model capacity
beyond the point of interpolation results in improved performance. We provide
evidence for the existence and ubiquity of double descent for a wide spectrum
of models and datasets, and we posit a mechanism for its emergence. This
connection between the performance and the structure of machine-learning models
delineates the limits of classical analyses and has implications for both the
theory and the practice of machine learning.
"

who_suggested: Richard Everson

status: happened
---
- [PDF](https://www.pnas.org/content/116/32/15849.full.pdf)
- [A nice blog post on Neural Network overfitting](https://lilianweng.github.io/lil-log/2019/03/14/are-deep-neural-networks-dramatically-overfitted.html)
- [Yannic Kilcher video explainer](https://www.youtube.com/watch?v=ZAW9EyNo2fw)
- [Paper summary](https://vitalab.github.io/article/2019/09/18/double-descent-curve.html)
