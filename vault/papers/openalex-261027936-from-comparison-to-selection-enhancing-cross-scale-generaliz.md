---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three root causes—node density shifts, attention dispersion, and graph context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph context aggregation. By combining these complementary approaches via an approach selector, the method achieves improved routing costs across both seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-02T13:00:08Z"

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
  - name: "approach-selector-for-cross-scale-generalization"
    description: "A meta-selection framework that chooses the optimal routing model for each train-test size pair to enhance cross-scale generalization."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:00:08Z"
created_at: "2026-11-02T13:00:08Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three root causes—node density shifts, attention dispersion, and graph context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph context aggregation. By combining these complementary approaches via an approach selector, the method achieves improved routing costs across both seen and unseen problem sizes.

## Key Contributions

- Identified three key factors contributing to cross-scale performance degradation in Pointer Networks for CVRP: node density shifts, attention dispersion, and mean-pooled graph context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) to improve downscaling transfer (CVRP100-to-CVRP20).
- Showed that entropy-based attention scaling reduces the CVRP20-to-CVRP100 upscaling performance gap by 1.41 percentage points.
- Introduced an approach selector that chooses the best model for each training-target size pair, achieving cost improvements of up to 3.2% across seen and unseen sizes.

## Key Concepts

- [[approach-selector-for-cross-scale-generalization]]: A meta-selection framework that chooses the optimal routing model for each train-test size pair to enhance cross-scale generalization.

## Archivist Review

Approved the overarching approach-selector concept which is already tracked in the vault. Rejected the open questions as incremental architectural extensions and routine model selection variations rather than major vault-worthy bottlenecks.

### Approved Concepts
- Approach Selector for Cross-Scale Generalization: Introduces a meta-selection framework across complementary cross-scale routing models to enhance generalization across varied problem scales.

### Rejected Candidates
- [open_question] Joint Attention Scaling and Context Aggregation (`joint-attention-scaling-context-aggregation`) - subcomponent_of_broader_mechanism: Routine combination of submodules within an architecture rather than a distinct foundational research bottleneck.
- [open_question] Instance-Feature-Driven Model Selection (`instance-feature-driven-model-selection`) - paper_local: Paper-local extension of model selection using instance-level features.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

