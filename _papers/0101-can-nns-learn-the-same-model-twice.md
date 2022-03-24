---
layout: paper

title: "Can Neural Nets Learn the Same Model Twice? Investigating Reproducibility and Double Descent from the Decision Boundary Perspective"
authors:
- Gowthami Somepalli
- Liam Fowl
- Arpit Bansal
- Ping Yeh-Chiang
- Yehuda Dar
- Richard Baraniuk
- Micah Goldblum
- Tom Goldstein

venue: "CVPR"
year: 2022

link: https://arxiv.org/abs/2203.08124

abstract: "
We discuss methods for visualizing neural network decision boundaries and
decision regions. We use these visualizations to investigate issues related to
reproducibility and generalization in neural network training. We observe that
changes in model architecture (and its associate inductive bias) cause visible
changes in decision boundaries, while multiple runs with the same architecture
yield results with strong similarities, especially in the case of wide
architectures. We also use decision boundary methods to visualize double
descent phenomena. We see that decision boundary reproducibility depends
strongly on model width. Near the threshold of interpolation, neural network
decision boundaries become fragmented into many small decision regions, and
these regions are non-reproducible. Meanwhile, very narrows and very wide
networks have high levels of reproducibility in their decision boundaries with
relatively few decision regions. We discuss how our observations relate to the
theory of double descent phenomena in convex models.
"

who_suggested: George De Ath
status: happened
---
- [github](https://github.com/somepago/dbViz)
- [twitter thread](https://mobile.twitter.com/gowthami_s/status/1503931615734812676)
