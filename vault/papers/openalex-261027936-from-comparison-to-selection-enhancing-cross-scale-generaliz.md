---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three key failure modes—node density shifts, attention dispersion, and graph-context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. By combining these complementary techniques via an approach selector, the method reduces routing costs by up to 3.2% across both seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
  - "demand-forecasting"
timestamp: "2026-10-26T10:41:40Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:41:40Z"
created_at: "2026-10-26T10:41:40Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization degradation of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify three key failure modes—node density shifts, attention dispersion, and graph-context dilution—and propose targeted modifications including entropy-based attention scaling and permutation-invariant graph-context aggregation. By combining these complementary techniques via an approach selector, the method reduces routing costs by up to 3.2% across both seen and unseen problem sizes.

## Key Contributions

- Identified three core factors degrading cross-scale generalization in Pointer Networks for CVRP: node density shifts, attention dispersion, and mean-pooled graph context dilution.
- Demonstrated that entropy-based attention scaling reduces the CVRP20-to-CVRP100 performance gap by 1.41 percentage points.
- Proposed learned, permutation-invariant graph-context aggregation mechanisms (weighted average and Set2Set) that improve CVRP100-to-CVRP20 transfer by approximately 0.9 percentage points.
- Introduced an approach selector combining complementary architectural modifications, reducing cost relative to the reference model by up to 3.2% across seen and unseen sizes.

## Archivist Review

Applied strict standards for the ML vault. The proposed concept (Approach Selector) is a paper-local meta-selection mechanism for vehicle routing model variants rather than a broadly recurring foundational concept. The open questions concern specialized vehicle routing training and instance selection extensions, which lack the broad theoretical weight required for permanent standalone vault notes.

### Rejected Candidates
- [concept] Approach Selector (CVRP Routing) (`approach-selector-cvrp`) - paper_local: Approach selector is a paper-local system/meta-heuristic for combining specific model variants, lacking broad reusability outside of this specific combinatorial optimization pipeline.
- [open_question] Unified Multi-Size Training Framework (`unified-multisize-training-pointer-networks`) - low_impact: This open question is a fairly routine request to combine architectural tweaks and train on multiple sizes within pointer networks.
- [open_question] Instance-Aware Neural Model Selection (`instance-aware-model-selection-routing`) - low_impact: Instance-level feature conditioning for model selection is a narrow routing-specific extension rather than a fundamental vault-level bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

