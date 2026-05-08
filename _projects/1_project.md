---
layout: page
title: Scientific Creativity Scoring with Large Language Models
description: Automated creativity assessment for student responses using fine-tuned models and LLM-as-Judge strategies on the Scientific Creative Thinking Test.
img: assets/img/proj_creativity_scoring.png
importance: 1
category: AI in Education
related_publications: true
---

Evaluating scientific creativity in student-generated ideas requires expert annotation that is expensive and hard to scale. This project develops **automated creativity assessment** using two complementary approaches: (1) fine-tuned language models — including Poly-Encoder, LLM-based regression, and pairwise comparison ranking — and (2) prompt engineering strategies for **LLM-as-Judge** evaluation.

Both approaches are grounded in established creativity frameworks from cognitive and learning science and validated against human rater judgments on the Scientific Creative Thinking Test (SCTT).

This project is funded by the **Interdisciplinary Seed Grant, Kennesaw State University**.

### Key Contributions

- Poly-Encoder and LLM-based regression models for creativity scoring
- Pairwise comparison ranking as an alternative to absolute scoring
- Systematic comparison of zero-shot, few-shot, chain-of-thought, and rubric-based LLM prompting
- Human-in-the-loop evaluation protocols and inter-rater agreement analysis

### Research Questions

- Which model architecture or prompting strategy best aligns with human creativity scores?
- Do chain-of-thought explanations improve rubric adherence or introduce scoring drift?
- Can automated scoring replace multi-rater consensus for formative feedback?

### Publications

{% cite noh2026creativity %}

### Team

Jiho Noh (PI), Phillip Gregory, Sam Grouchnikov, Stanley Nurnberger
