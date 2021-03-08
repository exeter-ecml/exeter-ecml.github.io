---
layout: paper

title: "Accounting for Variance in Machine Learning Benchmarks"
authors:
- Xavier Bouthillier
- Pierre Delaunay
- Mirko Bronzi
- Assya Trofimov
- Brennan Nichyporuk
- Justin Szeto
- Naz Sepah
- Edward Raff
- Kanika Madan
- Vikram Voleti
- Samira Ebrahimi Kahou
- Vincent Michalski
- Dmitriy Serdyuk
- Tal Arbel
- Chris Pal
- Gaël Varoquaux
- Pascal Vincent

venue: arXiv
year: 2021

link: https://arxiv.org/abs/2103.03098

abstract: "
Strong empirical evidence that one machine-learning algorithm A outperforms 
another one B ideally calls for multiple trials optimizing the learning
pipeline over sources of variation such as data sampling, data augmentation,
parameter initialization, and hyperparameters choices. This is prohibitively
expensive, and corners are cut to reach conclusions. We model the whole
benchmarking process, revealing that variance due to data sampling, parameter
initialization and hyperparameter choice impact markedly the results. We
analyze the predominant comparison methods used today in the light of this
variance. We show a counter-intuitive result that adding more sources of
variation to an imperfect estimator approaches better the ideal estimator at a
51 times reduction in compute cost. Building on these results, we study the
error rate of detecting improvements, on five different deep-learning
tasks/architectures. This study leads us to propose recommendations for
performance comparisons. 
"

who_suggested: George De Ath

status: suggested
---
- [Twitter thread](https://twitter.com/gaelvaroquaux/status/1367839174469029899)
