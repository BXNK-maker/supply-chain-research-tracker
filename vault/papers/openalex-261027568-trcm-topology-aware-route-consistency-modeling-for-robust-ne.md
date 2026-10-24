---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization models for the Capacitated Vehicle Routing Problem (CVRP) typically rely on sequential node selection that represents route organization only implicitly. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities from node representations and injects them as a route-consistency signal into the customer selection process. To address class imbalance and structural unevenness in supervision, TRCM integrates structure-preserving augmentation with Topological Entropy-based reweighting. Experimental results demonstrate reduced optimality gaps on CVRP50, CVRP100, and XML100 benchmarks compared to standard autoregressive construction baselines."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "vehicle-routing-problem"
  - "neural-routing-solver"
  - "autoregressive-models"
timestamp: "2026-10-24T09:15:47Z"

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
    description: "An explicit route-consistency modeling framework for neural vehicle routing that predicts pairwise same-route probabilities using topological entropy-based reweighting and structure-preserving augmentation."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:15:47Z"
created_at: "2026-10-24T09:15:47Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization models for the Capacitated Vehicle Routing Problem (CVRP) typically rely on sequential node selection that represents route organization only implicitly. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities from node representations and injects them as a route-consistency signal into the customer selection process. To address class imbalance and structural unevenness in supervision, TRCM integrates structure-preserving augmentation with Topological Entropy-based reweighting. Experimental results demonstrate reduced optimality gaps on CVRP50, CVRP100, and XML100 benchmarks compared to standard autoregressive construction baselines.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly model customer co-assignment and guide node selection in autoregressive neural vehicle routing.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to address class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.
- Improves the CVRP100 optimality gap from 1.61% to 1.49% under 8-fold augmented inference and improves the average objective on XML100 by 0.24%.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: An explicit route-consistency modeling framework for neural vehicle routing that predicts pairwise same-route probabilities using topological entropy-based reweighting and structure-preserving augmentation.

## Archivist Review

Approved the overarching concept 'Topology-Aware Route-Consistency Modeling' (matching the existing vault entry), while rejecting the subcomponent and the open question due to low impact and boilerplate phrasing.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces explicit route-level customer co-assignment and topological entropy-based reweighting to guide node-level autoregressive vehicle routing solvers.

### Rejected Candidates
- [concept] Topological Entropy-Based Reweighting (`topological-entropy-reweighting`) - subcomponent_of_broader_mechanism: Subcomponent of the broader TRCM framework rather than an independently reusable architectural mechanism.
- [open_question] Improving Route-Consistency Signal Efficiency (`route-consistency-efficiency-and-scaling`) - low_impact: Too generic and boilerplate in requesting efficiency improvements without a tightly defined foundational bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

