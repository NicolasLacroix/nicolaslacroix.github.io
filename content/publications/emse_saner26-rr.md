---
title: "Using Small Language Models to Reverse-Engineer Machine Learning Pipelines Structures"
date: 2026-10-07
draft: false
# github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Nicolas Lacroix, Mireille Blay-Fornarino, Sébastien Mosser, Frederic Precioso"
tags:
  - Reverse Engineering
  - Machine Learning Pipelines
  - Small Language Models
  - Jupyter Notebooks
  - Empirical Research
# image: /images/post.jpg
description: ""
toc: 
---

EMSE (in review) / SANER'26 (RR)

### Abstract

**Context**: Once defined a taxonomy of stages structuring Machine Learning (ML) pipelines (e.g. Data Preprocessing, Modeling...), extracting these stages from source code is key for better understanding ML practices. However, the diversity caused by the constant evolution of ML (\eg~algorithms, datasets) makes this task challenging. Existing approaches either rely on non-scalable manual labeling or on classifiers that do not properly support domain's diversity. These limitations call for more reliable solutions.

**Objective**: We evaluate whether Small Language Models (SLMs) can leverage their code understanding and classification abilities to address these limitations, and enhance our understanding of practices in ML.

**Method**: We conduct a confirmatory study based on two relevant reference works representing current limitations in the state-of-the-art. We first compare several SLMs using Cochran's Q test, then evaluate the best-performing model against reference studies via two McNemar's tests. An additional Cochran's Q test examines how taxonomy definition variations affect the SLM performance. Finally, goodness-of-fit tests compare ML practice insights from SLM classification with those from prior studies.

**Results**: First, we found that the taxonomy wording significantly impacts classification performance. Second, the best performing SLM yielded good results, yet, without outperforming other classifiers. Third, the three classification methods led to significantly different insights, with varying effect sizes, when exploring practices of data scientists.

**Conclusions**: Limitations of existing classification methods bias our understanding of ML practices. While current SLMs show promising results without prior fine-tuning, they still exhibit common limitations, in addition to inference high costs challenging their applicability in large-scale studies.


### Paper

Registered Report: https://hal.science/hal-05466464v1/document

Full paper: https://arxiv.org/pdf/2610.10261

### Cite

```
@article{lacroix2026using,
  title={Using small language models to reverse-engineer machine learning pipelines structures},
  author={Lacroix, Nicolas and Precioso, Fr{\'e}d{\'e}ric and Blay-Fornarino, Mireille and Mosser, S{\'e}bastien},
  journal={arXiv preprint arXiv:2610.10261},
  year={2026}
}
```
