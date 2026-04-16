---
layout: page
title: Dynamic Reward Agents for LLM Reinforcement Learning
description: Investigating whether dynamically regenerating an LLM-based reward rubric during RL training can sustain improvements in reasoning beyond static reward mechanisms.
img: assets/img/5.jpg
importance: 3
category: NLP & IR
---

Static reward signals in reinforcement learning for LLMs tend to plateau as the model learns to exploit fixed rubrics. This project investigates **dynamic reward rubrics** — regenerating the reward signal during training using an LLM-based judge — to sustain continued improvement in reasoning capability.

We use **Group Relative Policy Optimization (GRPO)** and the **Phi-4 (14B)** model, evaluated on the MMLU-Pro benchmark across five training conditions comparing static vs. dynamically updated reward mechanisms.

### Research Questions

- Can dynamically regenerated reward rubrics prevent reward hacking and sustain RL gains?
- How does rubric update frequency affect training stability and final reasoning performance?
- What types of reasoning tasks benefit most from dynamic reward adaptation?

### Team

Jiho Noh (PI), Raymond Carl
