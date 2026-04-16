---
layout: page
title: Adversarial Robustness of Deep Networks
description: Investigating the transferability and robustness of adversarial attacks across CNN architectures.
img: assets/img/1.jpg
importance: 2
category: NLP & IR
related_publications: true
---

As deep neural networks are deployed in safety-critical applications, understanding their vulnerabilities to adversarial examples becomes essential. This project investigates the **transferability of adversarial attacks** between standard and dilated CNN architectures.

We systematically craft adversarial examples for one CNN architecture and measure how effectively they fool architecturally different models. Our findings reveal that dilation-induced receptive field differences create notable robustness asymmetries — with implications for defensive model design and architecture selection in sensitive domains.

### Key Contributions

- Systematic cross-architecture adversarial transferability study
- Analysis of how dilation patterns affect adversarial susceptibility
- Practical guidelines for more robust CNN architecture selection

### Publications

{% cite sharma2025adversarial %}

### Team

Jiho Noh (PI), Sachin Sharma, Michael S. Alexiou
