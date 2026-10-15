---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs"
description: "The paper introduces MECo, an LLM-driven multi-task evolutionary framework designed for zero-shot cross-problem generalization in combinatorial optimization. MECo maintains task-conditioned heuristic populations and leverages a transfer gap metric to guide heuristic transfer, recombination, and selection across source tasks. Evaluated on 32 problem variants across vehicle routing and flexible job-shop scheduling, MECo outperforms multiple automated heuristic design baselines in both in-domain and out-of-domain settings."
resource: "https://arxiv.org/abs/2610.03316"
tags:
  - "machine-learning"
timestamp: "2026-10-15T04:43:46Z"

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
processed_at: "2026-10-15T04:43:46Z"
created_at: "2026-10-15T04:43:46Z"
---

# Multi-Task Evolution for Zero-Shot Cross-Problem Generalization using LLMs

**Authors**: Zhouliang Xie, Changliang Zhou, Genghui Li, Zhenkun Wang
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03316](https://arxiv.org/abs/2610.03316)

## Summary

The paper introduces MECo, an LLM-driven multi-task evolutionary framework designed for zero-shot cross-problem generalization in combinatorial optimization. MECo maintains task-conditioned heuristic populations and leverages a transfer gap metric to guide heuristic transfer, recombination, and selection across source tasks. Evaluated on 32 problem variants across vehicle routing and flexible job-shop scheduling, MECo outperforms multiple automated heuristic design baselines in both in-domain and out-of-domain settings.

## Key Contributions

- Introduces MECo, an LLM-driven multi-task evolutionary framework that uses task-conditioned heuristic populations and a transfer gap-based guidance mechanism for zero-shot cross-problem generalization.
- Applies a complementary selection criterion based on source combination coverage to construct a compact heuristic set for direct transfer to target problems without further search.
- Achieves the lowest mean costs compared to eight automated heuristic design baselines across 32 problem variants in vehicle routing and flexible job-shop scheduling under identical budgets.

## Limitations

The paper evaluates generalization across vehicle routing and flexible job-shop scheduling variants, but further scaling to wider problem families and evaluating computational overhead remain areas for future exploration.

## Key Concepts

- [[meco]]: An LLM-driven multi-task evolutionary framework that maintains task-conditioned heuristic populations and uses a transfer gap to guide heuristic transfer and recombination for zero-shot cross-problem generalization.

## Archivist Review

Approved the core framework concept 'MECo' as it introduces a novel transfer-gap-guided multi-task evolutionary approach for zero-shot cross-problem generalization. Rejected 'Automated Heuristic Design' because it is a broad existing field term rather than a novel concept. No standalone datasets or open questions met the strict vault criteria.

### Approved Concepts
- MECo: It is the core methodological contribution of the paper, introducing task-conditioned heuristic populations and transfer gap-guided evolution for zero-shot cross-problem generalization.

### Rejected Candidates
- [concept] Automated Heuristic Design (`automated-heuristic-design`) - not_novel: A broad existing domain/field rather than a novel specific concept introduced by the paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.03316)
- [PDF](https://arxiv.org/pdf/2610.03316)

