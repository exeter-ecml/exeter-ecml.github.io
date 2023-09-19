---
layout: paper

title: "A Bayesian Active Learning Approach to Comparative Judgement"

authors:
- Andy Gray
- Alma Rahat
- Tom Crick
- Stephen Lindsay

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2308.13292

abstract: "
Assessment is a crucial part of education. Traditional marking is a source of inconsistencies and unconscious bias, placing a high cognitive load on the assessors. An approach to address these issues is comparative judgement (CJ). In CJ, the assessor is presented with a pair of items and is asked to select the better one. Following a series of comparisons, a rank is derived using a ranking model, for example, the BTM, based on the results. While CJ is considered a reliable method for marking, there are concerns around transparency, and the ideal number of pairwise comparisons to generate a reliable estimation of the rank order is not known. Additionally, there have been attempts to generate a method of selecting pairs that should be compared next in an informative manner, but some existing methods are known to have created their own bias within results inflating the reliability metric used. As a result, a random selection approach is usually deployed.

We propose a novel Bayesian approach to CJ (BCJ) for determining the ranks of compared items alongside a new way to select the pairs to present to the marker(s) using active learning (AL), addressing the key shortcomings of traditional CJ. Furthermore, we demonstrate how the entire approach may provide transparency by providing the user insights into how it is making its decisions and, at the same time, being more efficient. Results from our experiments confirm that the proposed BCJ combined with entropy-driven AL pair-selection method is superior to other alternatives. We also find that the more comparisons done, the more accurate BCJ becomes, which solves the issue the current method has of the model deteriorating if too many comparisons are performed. As our approach can generate the complete predicted rank distribution for an item, we also show how this can be utilised in devising a predicted grade, guided by the assessor.
"

who_suggested: Tinkle Chugh
status: suggested
---
