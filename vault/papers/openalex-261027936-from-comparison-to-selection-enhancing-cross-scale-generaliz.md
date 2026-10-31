---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization limitations of reinforcement learning-trained Pointer Networks on the Capacitated Vehicle Routing Problem (CVRP), identifying shifts in node density, attention dispersion, and mean-pooled graph context dilution as primary causes. To address these issues, the authors propose a learned, permutation-invariant graph-context aggregation mechanism and entropy-based attention scaling. Combining these insights into an approach selector dynamically chooses the best model per size pair, reducing routing cost by up to 3.2% across seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
timestamp: "2026-10-31T10:41:36Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Sofiene Lassoued"
  - literal: "Devara Tertia"
  - literal: "Stefan Lier"
  - literal: "Andreas Schwung"
issued:
  date-parts:
    - [2026, 10, 20]

# Domain-specific custom fields
paper_id: "2610.27936"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "combined-multi-scale-nco-training"
    description: "Develop unified multi-scale reinforcement learning frameworks that simultaneously combine attention rescaling techniques (such as entropy-based or learnable scaling factors) and permutation-invariant graph-context aggregation mechanisms (such as Set2Set or weighted averaging), enabling robust performance when trained and deployed across mixed and dynamic problem scales."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:41:36Z"
created_at: "2026-10-31T10:41:36Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization limitations of reinforcement learning-trained Pointer Networks on the Capacitated Vehicle Routing Problem (CVRP), identifying shifts in node density, attention dispersion, and mean-pooled graph context dilution as primary causes. To address these issues, the authors propose a learned, permutation-invariant graph-context aggregation mechanism and entropy-based attention scaling. Combining these insights into an approach selector dynamically chooses the best model per size pair, reducing routing cost by up to 3.2% across seen and unseen problem sizes.

## Key Contributions

- Identified three key contributing factors to cross-scale generalization degradation in Pointer Networks for CVRP: node density shifts, attention dispersion, and graph context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism using weighted averages and Set2Set to improve cross-scale generalization.
- Introduced an approach selector that chooses the optimal model for each training-target size pair, reducing routing costs by up to 3.2% across seen and unseen problem sizes.

## Open Questions & Future Work

- [[combined-multi-scale-nco-training]]

## Archivist Review

Applied strict filtering against the vault. No new concepts met the high bar for permanent standalone notes, as they are specific to vehicle routing or represent minor architectural variants. The open question 'combined-multi-scale-nco-training' addresses a distinct bottleneck regarding joint multi-scale training for neural combinatorial optimization, whereas 'instance-aware-model-selector' was rejected as a duplicate of 'instance-feature-aware-approach-selection'.

### Approved Open Questions
- Combined Multi-Scale NCO Training: Combining complementary upscaling and downscaling mechanisms into a single training regime addresses the core cross-scale generalization bottleneck in neural combinatorial optimization without requiring separate models for different problem sizes.

### Rejected Candidates
- [open_question] Instance-Aware Model Selector (`instance-aware-model-selector`) - duplicate_existing: Nearly identical to existing vault question 'instance-feature-aware-approach-selection' which covers instance-feature-driven dynamic model selection.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

