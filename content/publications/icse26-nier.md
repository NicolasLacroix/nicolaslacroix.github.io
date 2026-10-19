---
title: "Model Cards for Responsible AI: Stop Carding, Start Modelling"
date: 2026-04-16
draft: false
# github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Kalvin Thuan-Phong Khuu, Nicolas Lacroix, Baptiste Lacroix, Richard Paige, Mireille Blay-Fornarino, Sébastien Mosser"
tags:
  - Safety Engineering
  - Artificial Intelligence
  - Model Cards
# image: /images/post.jpg
description: ""
toc: 
---

ICSE'26 (NIER)

### Abstract

Artificial intelligence and Machine Learning models are increasingly deployed in systems, which, despite not being safety-critical per se, may ultimately harm people. A recent tragedy involving the death of a sixteen-year-old teenager and ChatGPT shone a light on how (un)safe such systems can be.

Safety engineering is a well-established discipline for ensuring the safety of safety-critical systems. However, AI Safety, closer to what a software engineer would call “validation” than “assurance”, is still addressed on entirely different grounds.

In this paper, we propose to pull engineering methods (argumentation model, templates and operations) coming from system safety into AI Safety. By doing so, we hope to align both practices so that AI Safety can consider the potential for harm of AI systems from a broader and safer perspective.

We validated our approach by reframing Model Cards, a de facto standard in the AI industry, to describe the countermeasures applied to ensure that an AI model is safe to use. We analyzed state-of-the-art Large Language Models (GPT–OSS, Claude3, Gemma3N), to demonstrate that one can (i) identify safety templates in such artifacts, (ii) express them as argumentation models using justification diagrams, and (iii) operationalize the models to provide immediate feedback to AI developers when concrete evidence stops supporting their safety claims.

### Paper

https://hal.science/hal-05679580v1/document

### Cite

```
@inproceedings{khuu2026model,
  title={Model cards for responsible ai: Stop carding, start modelling},
  author={Khuu, Kalvin Thuan-Phong and Lacroix, Nicolas and Lacroix, Baptiste and Paige, Richard and Blay-Fornarino, Mireille and Mosser, S{\'e}bastien},
  booktitle={Proceedings of the IEEE/ACM 48th International Conference on Software Engineering},
  pages={26--30},
  year={2026}
}
```
