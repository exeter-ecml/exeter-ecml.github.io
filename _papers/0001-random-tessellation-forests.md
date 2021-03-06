---
layout: paper

title: Random tessellation forests
authors:
- Shufei Ge
- Shijia Wang
- Yee Whye Teh
- Liangliang Wang
- Lloyd Elliott
venue: Advances in Neural Information Processing Systems (NeurIPS)
year: 2019
link: http://papers.nips.cc/paper/9153-random-tessellation-forests

abstract: "
Space partitioning methods such as random forests and the Mondrian process are
powerful machine learning methods for multi-dimensional and relational data, 
and are based on recursively cutting a domain. The flexibility of these methods
is often limited by the requirement that the cuts be axis aligned. The 
Ostomachion process and the self-consistent binary space partitioning-tree 
process were recently introduced as generalizations of the Mondrian process for
space partitioning with non-axis aligned cuts in the plane. Motivated by the 
need for a multi-dimensional partitioning tree with non-axis aligned cuts, we
propose the Random Tessellation Process, a framework that includes the Mondrian
process as a special case. We derive a sequential Monte Carlo algorithm for 
inference, and provide random forest methods. Our methods are self-consistent 
and can relax axis-aligned constraints, allowing complex inter-dimensional 
dependence to be captured. We present a simulation study and analyze gene 
expression data of brain tissue, showing improved accuracies over other 
methods.
"

who_suggested: George De Ath

status: suggested
---
Reviews: <http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips32/reviews/5087.html>

Slides: <https://www.sfu.ca/~lloyde/Ge2019a-talk.pdf>