---
layout: paper

title: "Change Detection for Local Explainability in Evolving Data Streams"
authors:
- Johannes Haug
- Alexander Braun
- Stefan Zürn
- Gjergji Kasneci

venue: "ACM International Conference on Information & Knowledge"

year: 2022

link: https://dl.acm.org/doi/abs/10.1145/3511808.3557257

abstract: "
As complex machine learning models are increasingly used in sensitive
applications like banking, trading or credit scoring, there is a growing demand
for reliable explanation mechanisms. Local feature attribution methods have
become a popular technique for post-hoc and model-agnostic explanations.
However, attribution methods typically assume a stationary environment in which
the predictive model has been trained and remains stable. As a result, it is
often unclear how local attributions behave in realistic, constantly evolving
settings such as streaming and online applications. In this paper, we discuss
the impact of temporal change on local feature attributions. In particular, we
show that local attributions can become obsolete each time the predictive model
is updated or concept drift alters the data generating distribution.
Consequently, local feature attributions in data streams provide high
explanatory power only when combined with a mechanism that allows us to detect
and respond to local changes over time. To this end, we present CDLEEDS, a
flexible and model-agnostic framework for detecting local change and concept
drift. CDLEEDS serves as an intuitive extension of attribution-based
explanation techniques to identify outdated local attributions and enable more
targeted recalculations. In experiments, we also show that the proposed
framework can reliably detect both local and global concept drift. Accordingly,
our work contributes to a more meaningful and robust explainability in online
machine learning.
"

who_suggested: Ayah Helal
status: happened
---
- [GitHub](https://github.com/haugjo/cdleeds)
