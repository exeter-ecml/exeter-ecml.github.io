---
layout: paper

title: Local optima networks for continuous fitness landscapes
authors:
- Jason Adair
- Gabriela Ochoa
- Katherine Malan
venue: Genetic and Evolutionary Computation Conference (Workshop)
year: 2019

link: https://dl.acm.org/doi/10.1145/3319619.3326852

abstract: "
Local Optima Networks (LONs) have been proposed as a coarse-grained model of 
discrete (combinatorial) fitness landscapes, where nodes are local optima and
edges are search transitions based on an exploration search operator. This
paper presents one of the first complex network analysis of continuous fitness
landscapes. We use benchmark functions with well-known global structure, and
an existing implementation of a Basin-Hopping algorithm to extract the
networks. We also explore the impact of varying the Basin-Hopping perturbation
step-size. Our results suggest that the landscape's connectivity pattern
(global structure) strongly varies with the perturbation step-size, with
extreme values of this parameter being detrimental to search and fragmenting
the global structure. Our LON visualisations strikingly illustrate the
landscape's global (funnel) structure, indicating that LONs serve as a tool
for visualising high-dimensional functions.
"

who_suggested: Tinkle Chugh

status: suggested
---