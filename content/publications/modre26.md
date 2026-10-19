---
title: "Safety First! Modelling Requirements from GPT-5 System Card using Lightweight Safety Models"
date: 2025-08-17
draft: false
# github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Kalvin Thuan-Phong Khuu, Nicolas Lacroix, Mireille Blay–Fornarino, Sébastien Mosser"
tags:
  - Requirements Engineering
  - Safety Engineering
  - Model Cards
  - Machine Learning
# image: /images/post.jpg
description: ""
toc: 
---

MoDRE'26

### Abstract

Requirements engineering for Machine Learning~(ML) models is gaining renewed importance as organizations increasingly publish model cards and system cards to document the behaviour, capabilities, and limitations of their models. These artifacts have become a de facto standard for communicating model properties to downstream developers and auditors.

However, the claims made in such cards are rarely linked to explicit requirements, and they are often expressed in vague or imprecise language, particularly with respect to safety. This makes it difficult to determine which requirements a card actually addresses, or whether the supporting evidence is adequate.

We propose an approach based on argumentation modelling, drawing on Toulmin's model in the form of justification models, to systematically capture the claims made in model and system cards and trace them back to upfront requirements. The resulting diagrams make each claim's grounds and warrants explicit and establish traceability links between documented assertions and the requirements they are intended to satisfy.

We evaluate the approach on the model and system card for GPT-5, identifying 74 claims and tracing them to 22 implicit requirements. The analysis surfaces unspecified requirements and gaps in evidence, showing that argumentation-based traceability can expose weaknesses obscured by current documentation practices.

### Paper

https://hal.science/hal-05681913/document

### Cite

```
@inproceedings{khuu2026safety,
  title={Safety First! Modelling Requirements from GPT-5 System Card using Lightweight Safety Models},
  author={Khuu, Kalvin Thuan-Phong and Lacroix, Nicolas and Blay-Fornarino, Mireille and Mosser, S{\'e}bastien},
  booktitle={2026 IEEE 34th International Requirements Engineering Conference Workshops (REW)},
  pages={351--360},
  year={2026},
  organization={IEEE}
}
```
