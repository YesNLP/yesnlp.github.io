---
layout: page
title: Dynamic Reward Agents for LLM Reinforcement Learning
description: Investigating whether periodically regenerating LLM-based reward criteria during GRPO training sustains reasoning improvements beyond static reward mechanisms.
img: assets/img/proj_dynamic_reward.png
importance: 3
category: LLM Reasoning & Alignment
---

When training language models with reinforcement learning, the reward signal typically stays fixed — the same rubric judges early, clumsy reasoning the same way it judges near-expert reasoning. This project asks a simple question: **what if the reward signal grew stricter as the model got better?**

We explore **dynamic reward regeneration**, where an LLM-based evaluator periodically revises its own scoring criteria during training, raising the bar as the policy improves. This mirrors how a good teacher adjusts expectations over a course — not because the student failed, but because they are ready for harder challenges.

The central hypothesis is that progressively tightening evaluation criteria can prevent reward saturation and sustain reasoning gains beyond what static reward mechanisms achieve.

### Research Questions

- Can a dynamically evolving reward signal prevent plateau effects in LLM reasoning?
- Does raising the evaluative bar during training lead to better generalization?
- How much of any improvement is due to LLM-based evaluation versus dynamic updating?

### Team

Jiho Noh (PI), Raymond Carl
