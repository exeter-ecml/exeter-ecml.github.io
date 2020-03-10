---
layout: paper

title: "Approximate Cross-Validation in High Dimensions with Guarantees"

citation: "
William Stephenson, Tamara Broderick,
**Approximate Cross-Validation in High Dimensions with Guarantees**,
arXiv:abs/1905.13657,
2019
"

link: https://arxiv.org/abs/1905.13657

abstract: "
Leave-one-out cross validation (LOOCV) can be particularly accurate among 
cross validation (CV) variants for estimating out-of-sample error. But it is 
expensive to re-fit a model N times for a dataset of size N. Previous work has 
shown that approximations to LOOCV can be both fast and accurate -- when the 
unknown parameter is of small, fixed dimension. However, these approximations 
incur a running time roughly cubic in dimension -- and we show that, even when 
computed perfectly, their accuracy dramatically deteriorates in high 
dimensions. Authors have suggested many potential and seemingly intuitive 
solutions, but these methods have not yet been systematically evaluated or 
compared. In our analysis, we find that all but one perform so poorly as to be 
unusable for approximating LOOCV. Crucially, though, we are able to show, both 
empirically and theoretically, that one approximation can perform well in high
dimensions -- in cases where the high-dimensional parameter exhibits sparsity.
Under interpretable assumptions, our theory demonstrates that the problem can 
be reduced to working within an empirically recovered (small) support. The
corresponding algorithm is straightforward to implement, and we prove that its
running time and error depend on the (small) support size even when the full 
parameter dimension is large.
"
---