---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization for the Capacitated Vehicle Routing Problem typically constructs solutions via sequential node selection without explicit route-level representation. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities and injects them as consistency signals into the customer selection process. Using structure-preserving augmentation and Topological Entropy-based reweighting to handle supervision imbalances, TRCM improves solution optimality across standard CVRP benchmarks and augmented inference settings."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "vehicle-routing-problem"
  - "autoregressive-models"
  - "combinatorial-optimization"
  - "neural-routing-solver"
timestamp: "2026-11-01T11:39:02Z"

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
    description: "A technique that predicts pairwise same-route probabilities from autoregressive node representations and injects them as a route-consistency signal during customer selection."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:39:02Z"
created_at: "2026-11-01T11:39:02Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization for the Capacitated Vehicle Routing Problem typically constructs solutions via sequential node selection without explicit route-level representation. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities and injects them as consistency signals into the customer selection process. Using structure-preserving augmentation and Topological Entropy-based reweighting to handle supervision imbalances, TRCM improves solution optimality across standard CVRP benchmarks and augmented inference settings.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly model pairwise same-route probabilities and guide node-level customer selection in autoregressive neural solvers for the CVRP.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to address class-imbalance and structural unevenness in same-route supervision.
- Reduces the optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.
- Demonstrates robustness via 8-fold augmented inference on CVRP100 (reducing the gap from 1.61% to 1.49%) and improved performance on XML100.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A technique that predicts pairwise same-route probabilities from autoregressive node representations and injects them as a route-consistency signal during customer selection.

## Archivist Review

Approved the central concept of topology-aware route-consistency modeling as it matches an existing entry in the vault and represents a clear methodological contribution. Rejected the open question because it touches broadly on efficiency and scaling without isolating a precise architectural or theoretical bottleneck.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces explicit route-level co-assignment modeling to guide node-level constructive decisions in neural vehicle routing solvers.

### Rejected Candidates
- [open_question] Efficiency and Scaling of Route Consistency (`computational-efficiency-route-consistency-routing`) - other: The open question combines standard scaling challenges with vague future work extensions rather than isolating a specific unresolved mechanism or theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

