---
layout: paper

title: "A Unifying Perspective on Neighbor Embeddings along the Attraction-Repulsion Spectrum"
authors:
- Jan Niklas Böhm
- Philipp Berens
- Dmitry Kobak

venue: arXiv
year: 2020

link: https://arxiv.org/abs/2007.08902

abstract: "
Neighbor embeddings are a family of methods for visualizing complex 
high-dimensional datasets using kNN graphs. To find the low-dimensional
embedding, these algorithms combine an attractive force between neighboring
pairs of points with a repulsive force between all points. One of the most
popular examples of such algorithms is t-SNE. Here we show that changing the
balance between the attractive and the repulsive forces in t-SNE yields a
spectrum of embeddings, which is characterized by a simple trade-off: stronger
attraction can better represent continuous manifold structures, while stronger
repulsion can better represent discrete cluster structures. We show that UMAP
embeddings correspond to t-SNE with increased attraction; this happens because
the negative sampling optimisation strategy employed by UMAP strongly lowers
the effective repulsion. Likewise, ForceAtlas2, commonly used for visualizing
developmental single-cell transcriptomic data, yields embeddings corresponding
to t-SNE with the attraction increased even more. At the extreme of this
spectrum lies Laplacian Eigenmaps, corresponding to zero repulsion. Our results
demonstrate that many prominent neighbor embedding algorithms can be placed
onto this attraction-repulsion spectrum, and highlight the inherent trade-offs
between them.
"

who_suggested: George De Ath

status: suggested
---
Twitter thread: <https://twitter.com/hippopedoid/status/1285154214147235840>

![animation](https://j.gifs.com/yoG3VR.gif)

![Image](https://pbs.twimg.com/media/EdXAUMTWAAA-ohJ?format=png&name=large)
