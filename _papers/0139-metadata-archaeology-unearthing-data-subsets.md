---
layout: paper

title: "Metadata Archaeology: Unearthing Data Subsets by Leveraging Training Dynamics"
authors:
- Shoaib Ahmed Siddiqui
- Nitarshan Rajkumar
- Tegan Maharaj
- David Krueger
- Sara Hooker

venue: "ICML (Workshop)"
year: 2022

link: https://arxiv.org/abs/2209.10015

abstract: "
Modern machine learning research relies on relatively few carefully curated
datasets. Even in these datasets, and typically in `untidy' or raw data,
practitioners are faced with significant issues of data quality and diversity
which can be prohibitively labor intensive to address. Existing methods for
dealing with these challenges tend to make strong assumptions about the
particular issues at play, and often require a priori knowledge or metadata
such as domain labels. Our work is orthogonal to these methods: we instead
focus on providing a unified and efficient framework for Metadata Archaeology
-- uncovering and inferring metadata of examples in a dataset. We curate
different subsets of data that might exist in a dataset (e.g. mislabeled,
atypical, or out-of-distribution examples) using simple transformations, and
leverage differences in learning dynamics between these probe suites to infer
metadata of interest. Our method is on par with far more sophisticated
mitigation methods across different tasks: identifying and correcting
mislabeled examples, classifying minority-group samples, prioritizing points
relevant for training and enabling scalable human auditing of relevant
examples.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/shoaibahmed/metadata_archaeology)
- [ICML 2022 Presentation](https://slideslive.com/38986353/metadata-archaeology-unearthing-data-subsets-by-leveraging-training-dynamics)
