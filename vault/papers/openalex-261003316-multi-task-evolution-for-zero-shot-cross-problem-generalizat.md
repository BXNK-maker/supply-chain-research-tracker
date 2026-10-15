---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs"
description: "This paper introduces MECo, an LLM-driven multi-task evolutionary framework that achieves zero-shot cross-problem generalization for combinatorial optimization heuristics. MECo maintains task-conditioned heuristic populations, utilizing a transfer gap based on cross-task population performance to guide heuristic transfer and recombination. A complementary selection criterion then constructs a compact heuristic set that is directly applied to target problems without further search or adaptation. Experiments across 32 vehicle routing and flexible job-shop scheduling problem variants demonstrate that MECo outperforms existing automated heuristic design baselines in both in-domain and out-of-domain settings."
resource: "https://arxiv.org/abs/2610.03316"
tags:
  - "combinatorial-optimization"
  - "evolutionary-algorithms"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-15T09:33:35Z"

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
    description: "An LLM-driven multi-task evolutionary framework that maintains task-conditioned heuristic populations and uses a transfer gap to guide heuristic transfer and recombination for zero-shot cross-problem generalization."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:33:35Z"
created_at: "2026-10-15T09:33:35Z"
---

# Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs

**Authors**: Zhouliang Xie, Changliang Zhou, Genghui Li, Zhenkun Wang
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03316](https://arxiv.org/abs/2610.03316)

## Summary

This paper introduces MECo, an LLM-driven multi-task evolutionary framework that achieves zero-shot cross-problem generalization for combinatorial optimization heuristics. MECo maintains task-conditioned heuristic populations, utilizing a transfer gap based on cross-task population performance to guide heuristic transfer and recombination. A complementary selection criterion then constructs a compact heuristic set that is directly applied to target problems without further search or adaptation. Experiments across 32 vehicle routing and flexible job-shop scheduling problem variants demonstrate that MECo outperforms existing automated heuristic design baselines in both in-domain and out-of-domain settings.

## Key Contributions

- Introduces MECo, an LLM-driven multi-task evolutionary framework that maintains task-conditioned heuristic populations for zero-shot cross-problem generalization.
- Proposes a transfer gap mechanism based on cross-task population performance to guide heuristic transfer and recombination.
- Applies a complementary selection criterion to construct a compact heuristic set that maximizes coverage of source combinations without requiring target-task search or adaptation.
- Achieves the lowest mean costs compared with eight automated heuristic design baselines across 32 problem variants in vehicle routing and flexible job-shop scheduling.

## Limitations

Evaluated primarily on vehicle routing and flexible job-shop scheduling problem variants; future work could explore scaling to a wider range of disparate combinatorial optimization domains.

## Key Concepts

- [[meco]]: An LLM-driven multi-task evolutionary framework that maintains task-conditioned heuristic populations and uses a transfer gap to guide heuristic transfer and recombination for zero-shot cross-problem generalization.

## Archivist Review

The concept 'meco' is already present in the vault and is appropriately approved and reused. The open question candidate was rejected as too generic, and no specific named dataset was identified.

### Approved Concepts
- MECo: It represents the core algorithmic contribution of the paper, introducing task-conditioned heuristic populations and transfer gap-guided interactions for zero-shot generalization across combinatorial optimization problems.

### Rejected Candidates
- [open_question] Zero-Shot Cross-Problem Generalization (`zero-shot-cross-problem-generalization`) - generic: Too broad and general as an open question, and closely overlaps with standard zero-shot generalization challenges in optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.03316)
- [PDF](https://arxiv.org/pdf/2610.03316)

