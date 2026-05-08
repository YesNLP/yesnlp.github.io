---
layout: page
title: Question-Driven Knowledge Mapping and Learner Engagement Analysis in Education
description: Using questions as a unifying lens to map knowledge structure from educational materials and decode cognitive engagement patterns in online learning.
img: assets/img/proj_dqm_graph.png
importance: 2
category: AI in Education
related_publications: true
---

Questions are a fundamental unit of both knowledge representation and learner cognition. This project investigates questions from two complementary perspectives: (1) automatically constructing structured knowledge maps from educational materials by generating and organizing questions aligned with learning objectives, and (2) analyzing the cognitive complexity of learner-generated questions in online educational videos to understand engagement and learning patterns.

**Domain Question Maps (DQMs)** address the challenge of representing multi-level pedagogical knowledge from unstructured educational content. Rather than mapping concepts directly, DQMs formulate questions aligned with learning objectives and infer hierarchical relationships among them — spanning low-order to high-order thinking — to produce structured question graphs that support personalized and adaptive learning.

**YouLeQD** approaches questions from the learner's side. Using a large-scale dataset of questions posed by learners in online educational videos, the framework annotates cognitive complexity via Bloom's Taxonomy, builds transformer-based classifiers, and reveals connections between question complexity and viewer engagement patterns.

Together, these two lines of work establish a question-centric view of educational knowledge — from content structure to learner cognition.

### Key Contributions

- Automated pipeline for constructing Domain Question Maps from raw educational text
- Hierarchical question graph generation spanning low-order to high-order thinking
- YouLeQD: a large-scale dataset of learner questions with cognitive complexity labels
- Transformer-based question complexity classifiers
- Engagement analysis linking question complexity to view and interaction metrics

### Publications

{% cite noh2026dqm %}
{% cite ming2025youleqd %}

### Team

Jiho Noh (PI), Mukhesh Raghava Katragadda, Dabae Lee, Nong Ming, Sachin Sharma
