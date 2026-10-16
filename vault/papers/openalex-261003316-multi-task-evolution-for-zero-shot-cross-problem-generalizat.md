---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs"
description: "The paper introduces MECo, an LLM-driven multi-task evolutionary framework designed for zero-shot cross-problem generalization in combinatorial optimization. MECo maintains task-conditioned heuristic populations, guided by a transfer gap metric, to transfer and recombine heuristics across tasks using only source-task feedback. A complementary selection criterion then constructs a compact heuristic set capable of achieving superior performance on unseen target problems without additional search. Experiments across vehicle routing and flexible job-shop scheduling demonstrate that MECo outperforms existing automated heuristic design baselines under identical search budgets."
resource: "https://arxiv.org/abs/2610.03316"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-10-16T09:26:23Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zhouliang Xie"
  - literal: "Changliang Zhou"
  - literal: "Genghui Li"
  - literal: "Zhenkun Wang"
issued:
  date-parts:
    - [2026, 10, 2]

# Domain-specific custom fields
paper_id: "2610.03316"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "meco"
    description: "An LLM-driven multi-task evolutionary framework for zero-shot cross-problem generalization of combinatorial optimization heuristics."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:26:23Z"
created_at: "2026-10-16T09:26:23Z"
---

# Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs

**Authors**: Zhouliang Xie, Changliang Zhou, Genghui Li, Zhenkun Wang
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03316](https://arxiv.org/abs/2610.03316)

## Summary

The paper introduces MECo, an LLM-driven multi-task evolutionary framework designed for zero-shot cross-problem generalization in combinatorial optimization. MECo maintains task-conditioned heuristic populations, guided by a transfer gap metric, to transfer and recombine heuristics across tasks using only source-task feedback. A complementary selection criterion then constructs a compact heuristic set capable of achieving superior performance on unseen target problems without additional search. Experiments across vehicle routing and flexible job-shop scheduling demonstrate that MECo outperforms existing automated heuristic design baselines under identical search budgets.

## Key Contributions

- Introduced MECo, an LLM-driven multi-task evolutionary framework maintaining task-conditioned heuristic populations for zero-shot cross-problem generalization.
- Utilized a transfer gap based on cross-task population performance to guide heuristic transfer and recombination without target-task feedback.
- Employed a complementary selection criterion rewarding source combination coverage to construct a compact heuristic set applied directly to target problems.
- Demonstrated lower mean costs across 32 problem variants in vehicle routing and flexible job-shop scheduling compared with eight automated heuristic design baselines.

## Limitations

While MECo successfully generalizes zero-shot across in-domain and out-of-domain problems within vehicle routing and scheduling, its performance relies on the initial quality and diversity of source-task populations and LLM prompt generation capabilities.

## Key Concepts

- [[meco]]: An LLM-driven multi-task evolutionary framework for zero-shot cross-problem generalization of combinatorial optimization heuristics.

## Archivist Review

Approved the central framework 'meco' since it provides a distinct, reusable multi-task evolutionary approach for zero-shot cross-problem generalization using LLMs. Rejected 'automated-heuristic-design' because it is a broad umbrella term describing a whole subfield rather than a specific standalone technical artifact. No open questions or datasets met the strict novelty and standalone reusability criteria.

### Approved Concepts
- MECo: MECo introduces a novel multi-task evolutionary framework using LLMs to achieve zero-shot cross-problem generalization for combinatorial optimization heuristics without requiring target-task feedback.

### Rejected Candidates
- [concept] Automated Heuristic Design (`automated-heuristic-design`) - not_novel: Automated heuristic design is an established broad field/task category rather than a specific novel mechanism or method introduced by the paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.03316)
- [PDF](https://arxiv.org/pdf/2610.03316)

