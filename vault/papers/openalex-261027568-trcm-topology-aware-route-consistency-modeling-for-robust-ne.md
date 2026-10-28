---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization solvers for the Capacitated Vehicle Routing Problem (CVRP) typically rely on autoregressive node selection with implicit route structures. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities from node representations and injects them as a guidance signal. TRCM combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle supervision imbalances, reducing optimality gaps on CVRP50 and CVRP100 under matched decoding budgets. Controlled tests further demonstrate improved robustness and objective stability under demand perturbations."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "autoregressive-models"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
timestamp: "2026-10-28T10:58:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Peiheng Jian"
  - literal: "Zhenwei Wang"
  - literal: "Tiehua Zhang"
  - literal: "Lei Zhang"
  - literal: "Zhishu Shen"
  - literal: "Ruibin Bai"
  - literal: "Zhijun Ding"
issued:
  date-parts:
    - [2026, 10, 20]

# Domain-specific custom fields
paper_id: "2610.27568"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "topology-aware-route-consistency-modeling"
    description: "An explicit route-consistency modeling framework that predicts pairwise same-route probabilities from node representations and injects them into node selection for neural vehicle routing."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:45Z"
created_at: "2026-10-28T10:58:45Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization solvers for the Capacitated Vehicle Routing Problem (CVRP) typically rely on autoregressive node selection with implicit route structures. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities from node representations and injects them as a guidance signal. TRCM combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle supervision imbalances, reducing optimality gaps on CVRP50 and CVRP100 under matched decoding budgets. Controlled tests further demonstrate improved robustness and objective stability under demand perturbations.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM), an explicit route-consistency modeling framework for autoregressive neural vehicle routing solvers.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.
- Improves average objective on XML100 by 0.24% under 8-fold augmented inference.

## Limitations

Evaluated primarily on standard CVRP and XML benchmarks; applicability to broader pick-up and delivery or time-window variants remains to be explored.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: An explicit route-consistency modeling framework that predicts pairwise same-route probabilities from node representations and injects them into node selection for neural vehicle routing.

## Archivist Review

Approved the core concept 'Topology-Aware Route-Consistency Modeling' which already exists in the vault under 'topology-aware-route-consistency-modeling'. Rejected the open question as it requests broad scaling and efficiency improvements without capturing a distinct, narrow theoretical bottleneck. Left datasets empty since problem instances like CVRP50/CVRP100/XML100 are standard benchmark categories rather than individual standalone datasets.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces a novel explicit route-consistency modeling principle for autoregressive neural routing solvers to bridge node-level selection and route organization.

### Rejected Candidates
- [open_question] Scaling Topology-Aware Route Consistency (`scaling-topology-aware-route-consistency-neural-routing`) - not_novel: Broad future work request regarding scale and efficiency without specifying a precise mechanistic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

