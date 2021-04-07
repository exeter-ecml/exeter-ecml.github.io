---
layout: paper

title: "Visualizing the Loss Landscape of Neural Nets"
authors:
- Hao Li
- Zheng Xu
- Gavin Taylor
- Christoph Studer
- Tom Goldstein

venue: NeurIPS
year: 2018

link: https://papers.nips.cc/paper/2018/hash/a41b3bb3e6b050b6c9067c67f663b915-Abstract.html

abstract: "
Neural network training relies on our ability to find *good* minimizers of
highly non-convex loss functions. It is well known that certain network
architecture designs (e.g., skip connections) produce loss functions that train
easier, and well-chosen training parameters (batch size, learning rate,
optimizer) produce minimizers that generalize better. However, the reasons for
these differences, and their effect on the underlying loss landscape, is not
well understood. In this paper, we explore the structure of neural loss
functions, and the effect of loss landscapes on generalization, using a range
of visualization methods. First, we introduce a simple *filter normalization*
method that helps us visualize loss function curvature, and make meaningful
side-by-side comparisons between loss functions. Then, using a variety of
visualizations, we explore how network architecture affects the loss landscape,
and how training parameters affect the shape of minimizers.
"

who_suggested: Melike Karatas

status: suggested
---
- [Code](https://github.com/tomgoldstein/loss-landscape)
- Quick overviews of the paper: 
    [1](https://jithinjk.github.io/blog/nn_loss_visualized.md.html),
    [2](https://vitalab.github.io/article/2020/05/01/lossLandscape.html)
