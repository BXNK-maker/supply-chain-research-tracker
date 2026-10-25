---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization limitations of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify shifts in node density, attention dispersion, and graph context dilution as key factors hindering zero-shot transfer across problem sizes. To address these issues, they propose entropy-based attention scaling for upscaling and permutation-invariant graph-context aggregation mechanisms (such as Set2Set) for downscaling. By combining these complementary techniques into an approach selector, the method achieves robust routing cost reductions of up to 3.2% across various seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "autoregressive-models"
timestamp: "2026-10-25T09:32:33Z"

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
processed_at: "2026-10-25T09:32:33Z"
created_at: "2026-10-25T09:32:33Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization limitations of attention-based Pointer Networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem (CVRP). The authors identify shifts in node density, attention dispersion, and graph context dilution as key factors hindering zero-shot transfer across problem sizes. To address these issues, they propose entropy-based attention scaling for upscaling and permutation-invariant graph-context aggregation mechanisms (such as Set2Set) for downscaling. By combining these complementary techniques into an approach selector, the method achieves robust routing cost reductions of up to 3.2% across various seen and unseen problem sizes.

## Key Contributions

- Identified three contributing factors to cross-scale degradation in pointer networks trained with reinforcement learning for the Capacitated Vehicle Routing Problem: shifts in node density, attention dispersion, and dilution of mean-pooled graph context.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) improving downscaling transfer from CVRP100 to CVRP20 by approximately 0.9 percentage points.
- Introduced an entropy-based attention scaling method that reduces the CVRP20-to-CVRP100 upscaling performance gap by 1.41 percentage points.
- Developed an approach selector combining complementary transfer techniques that reduces routing costs by up to 3.2% across seen and unseen training-target size pairs.

## Limitations

Evaluated primarily on the Capacitated Vehicle Routing Problem (CVRP) as a controlled proxy.

## Archivist Review

All candidates were reviewed against vault standards. The candidate concept for graph context aggregation is already captured in the vault under 'learned-graph-context-aggregation-mechanism', and the open question is specific to this paper's submodule combination rather than representing a broad open challenge.

### Rejected Candidates
- [open_question] Unified Multi-Scale Neural Routing (`unified-multiscale-training-pointer-networks`) - paper_local: The question is paper-specific and frames future work around combining particular submodules rather than establishing a broad, reusable benchmark challenge.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

