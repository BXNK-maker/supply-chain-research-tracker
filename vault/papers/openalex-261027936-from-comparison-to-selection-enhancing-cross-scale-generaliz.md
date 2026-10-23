---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Drone Delivery Routing"
description: "This paper investigates cross-scale generalization degradation in attention-based Pointer Networks trained via reinforcement learning for capacitated drone delivery routing (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as key contributing factors, and propose targeted architectural modifications alongside a learned permutation-invariant graph-context aggregation mechanism. By exploiting the complementarity of these models, they introduce an approach selector that chooses the best model per size pair, achieving up to 3.2 percent cost reduction across seen and unseen problem scales."
resource: "https://arxiv.org/abs/2610.27936"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
  - "time-series"
timestamp: "2026-10-23T09:45:42Z"

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
processed_at: "2026-10-23T09:45:42Z"
created_at: "2026-10-23T09:45:42Z"
---

# From Comparison to Selection: Enhancing Cross-Scale Generalization of Pointer Networks Trained with Reinforcement Learning for Capacitated Drone Delivery Routing

**Authors**: Sofiene Lassoued, Devara Tertia, Stefan Lier, Andreas Schwung
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27936](https://arxiv.org/abs/2610.27936)

## Summary

This paper investigates cross-scale generalization degradation in attention-based Pointer Networks trained via reinforcement learning for capacitated drone delivery routing (CVRP). The authors identify node density shifts, attention dispersion, and graph context dilution as key contributing factors, and propose targeted architectural modifications alongside a learned permutation-invariant graph-context aggregation mechanism. By exploiting the complementarity of these models, they introduce an approach selector that chooses the best model per size pair, achieving up to 3.2 percent cost reduction across seen and unseen problem scales.

## Key Contributions

- Identified three key factors limiting cross-scale generalization in pointer networks trained with reinforcement learning for CVRP: node density shifts, attention dispersion, and mean-pooled graph context dilution.
- Proposed a learned, permutation-invariant graph-context aggregation mechanism (weighted average and Set2Set) improving CVRP100-to-CVRP20 transfer by approximately 0.9 percentage points.
- Introduced an approach selector that chooses the best routing model for each training-target size pair, achieving cost improvements of up to 3.2 percent across seen and unseen scales.

## Limitations

Evaluated primarily on the CVRP proxy with specific payload constraints, and future work is needed to extend the approach selector and scaling mechanisms to more complex multi-drone delivery routing variants.

## Archivist Review

Applied strict filtering to keep the vault scarce and high-quality. The sole proposed candidate (approach-selector-cross-scale-routing) was rejected as a paper-local routing heuristic rather than a reusable core ML architectural concept.

### Rejected Candidates
- [concept] Approach Selector for Cross-Scale Routing (`approach-selector-cross-scale-routing`) - paper_local: This is a paper-local heuristic routing selection mechanism tailored to specific training-target scale pairs, lacking broad standalone reusability across unrelated ML domains.

## Links

- [Abstract](https://arxiv.org/abs/2610.27936)
- [PDF](https://arxiv.org/pdf/2610.27936)

