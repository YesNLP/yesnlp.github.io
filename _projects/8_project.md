---
layout: page
title: ADAS — Automated Discourse Analysis for Science Classrooms
description: Joint multi-task learning with LLM-based data augmentation to classify utterance types and reasoning components in science classroom dialogue, with temporal analysis of cognitive complexity across lessons.
img: assets/img/proj_adas_cci.png
importance: 1
category: AI in Education
related_publications: true
---

High-quality classroom discourse — where students engage in knowledge construction rather than mere recall — is a strong predictor of learning outcomes. Yet teachers receive little real-time support for recognizing and promoting productive reasoning patterns. **ADAS (Automated Discourse Analysis System)** addresses this gap.

ADAS jointly classifies teacher and student utterances along two dimensions: **Utterance Type** (e.g., questions, feedback, prompts) and **Reasoning Component** (e.g., inferential vs. descriptive reasoning). To address severe label imbalance in annotated classroom transcripts, the system combines corpus re-stratification with **LLM-based synthetic data augmentation** for minority classes, and trains a **dual-probe RoBERTa-base** classifier under a multi-task learning framework.

Beyond classification, ADAS reveals how cognitive complexity evolves within a lesson. The Cognitive Complexity Index (CCI) trajectory — shown above — rises through the development phase, dips during procedural activity, and rebounds sharply at lesson close, reflecting the pedagogical arc of Initiation → Development → Procedural → Synthesis. Lag-sequential analysis further shows that teacher **Feedback-with-Question (Fq)** moves are the strongest antecedents of student inferential reasoning.

This project is funded by the **Interdisciplinary Seed Grant, Kennesaw State University**.

### Key Contributions

- Dual-probe RoBERTa classifier for joint Utterance Type and Reasoning Component classification
- LLM-based synthetic data augmentation pipeline for low-resource discourse annotation
- Temporal CCI analysis revealing the cognitive arc of science lessons
- Lag-sequential and IRF chain analyses linking teacher moves to student reasoning quality

### Publications

{% cite noh2025adas %}

### Team

Jiho Noh (PI), Mukhesh Raghava Katragadda, Raymond Carl, Dr. Soon Lee
