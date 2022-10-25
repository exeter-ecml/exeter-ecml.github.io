---
layout: paper

title: "Targeted active learning for probabilistic models"

authors:
- Christopher Tosh
- Mauricio Tec
- Wesley Tansey

venue: "arXiv"

year: 2022

link: https://arxiv.org/abs/2210.12122

abstract: "
A fundamental task in science is to design experiments that yield valuable
insights about the system under study. Mathematically, these insights can be
represented as a utility or risk function that shapes the value of conducting
each experiment. We present PDBAL, a targeted active learning method that
adaptively designs experiments to maximize scientific utility. PDBAL takes a
user-specified risk function and combines it with a probabilistic model of the
experimental outcomes to choose designs that rapidly converge on a high-utility
model. We prove theoretical bounds on the label complexity of PDBAL and provide
fast closed-form solutions for designing experiments with common exponential
family likelihoods. In simulation studies, PDBAL consistently outperforms
standard untargeted approaches that focus on maximizing expected information
gain over the design space. Finally, we demonstrate the scientific potential of
PDBAL through a study on a large cancer drug screen dataset where PDBAL quickly
recovers the most efficacious drugs with a small fraction of the total number
of experiments.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/tansey-lab/pdbal)
