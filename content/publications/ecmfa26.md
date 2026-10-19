---
title: "A Model-Driven Approach To Support The Understanding Of Machine Learning Pipelines"
date: 2026-06-30
draft: false
# github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Nicolas Lacroix, Mireille Blay-Fornarino, Philippe Collet, Frédéric Precioso, Sébastien Mosser"
tags:
  - Model-Driven Engineering
  - Machine Learning Pipelines
  - Domain-Specific Language
  - Pattern Matching
# image: /images/post.jpg
description: ""
toc: 
---

ECMFA'26

### Abstract

Artificial Intelligence in general and Machine Learning in particular is a very dynamic field, with evolving technologies  and practices. Key decisions, from dataset preparation methods to model architecture and evaluation metrics, are made in an exploratory way, diverging from standard software engineering practices and guided by the data scientist’s empirical knowledge and experience. In this context, (i) some practices work, while others do not; (ii) some unexpected approaches perform better than the regular ones; (iii) some anti-patterns are accidentally used, leading to model contamination and biases. Developers and data scientists have to work on code artifacts (e.g., Jupyter notebooks) to identify key differences across multiple variations of the same machine learning pipelines, which is confusing and error-prone because it is only syntactic. In this paper, we defend a model-driven approach that reifies semantic information about machine learning pipelines to improve their understanding. Based on this metamodel, which captures essential steps in a given pipeline and links them to code artifacts, we define a pattern-matching language that supports data scientists in exploring corpora of machine learning artifacts. We validate the approach by identifying real-world use cases in collaboration with data scientists and applying them to the qualitative analysis of 105 Kaggle notebooks (a popular competition platform where participants submit pipelines to solve similar tasks). This work opens the door to transferring program understanding techniques to machine learning while accounting for its intrinsic exploratory nature. By relying on explicit models and a dedicated pattern language, we provide a foundation that supports systematic analysis of ML pipelines—such as pipeline comparison, practices identification, and anti-pattern detection—while remaining robust to the evolution of libraries, frameworks, and implementation technologies

### Paper

https://www.jot.fm/issues/issue_2026_03/a10.pdf

### Cite

```
@article{JOT:issue_2026_03/a10,
  author = {Nicolas Lacroix and Mireille Blay-Fornarino and Philippe Collet and Frédéric Precioso and Sébastien Mosser},
  title = {A Model-Driven Approach To Support The Understanding Of Machine Learning Pipelines},
  journal = {Journal of Object Technology},
  volume = {25},
  number = {3},
  issn = {1660-1769},
  year = {2026},
  month = march,
  editor = {},
  note = {ECMFA 2026 Journal First},
  pages = {3:127-140},
  doi = {10.5381/jot.2026.25.3.a10},
  url = {http://www.jot.fm/contents/issue_2026_03/a10.html}
}
```
