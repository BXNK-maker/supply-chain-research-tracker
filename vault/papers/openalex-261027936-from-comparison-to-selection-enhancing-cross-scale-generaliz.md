---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem"
description: "This paper investigates the cross-scale generalization limitations of attention-based Pointer Networks trained via reinforcement learning on the Capacitated Vehicle Routing Problem (CVRP). The authors identify three core causes of performance degradation across different scale shifts: node density shifts, attention dispersion, and graph context dilution. To mitigate these issues, they evaluate various modifications and propose a learned, permutation-invariant graph-context aggregation mechanism. By leveraging the complementarity of these approaches, an approach selector is introduced that consistently reduces routing costs by up to 3.2% across both seen and unseen problem sizes."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "reinforcement-learning"
  - "vehicle-routing-problem"
  - "neural-routing-solver"
timestamp: "2026-10-28T10:56:03Z"

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
processed_at: "2026-10-28T10:56:03Z"
created_at: "2026-10-28T10:56:03Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for for Capacitated Vehicle Routing Problem

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates the cross-scale generalization limitations of attention-based Pointer Networks trained via reinforcement learning on the Capacitated Vehicle Routing Problem (CVRP). The authors identify three core causes of performance degradation across different scale shifts: node density shifts, attention dispersion, and graph context dilution. To mitigate these issues, they evaluate various modifications and propose a learned, permutation-invariant graph-context aggregation mechanism. By leveraging the complementarity of these approaches, an approach selector is introduced that consistently reduces routing costs by up to 3.2% across both seen and unseen problem sizes.

## Key Contributions

- Identified three key factors degrading cross-scale generalization in Pointer Networks for CVRP: node density shifts, attention dispersion, and graph context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) addressing context dilution.
- Introduced an approach selector combining complementary cross-scale modifications that reduces routing cost by up to 3.2% across seen and unseen training-target size pairs.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

