---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization models for the Capacitated Vehicle Routing Problem (CVRP) often construct solutions via sequential node selection with only implicit route organization. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from node representations and injects them as a route-consistency guidance signal. TRCM combines structure-preserving augmentation with Topological Entropy-based reweighting to handle class-imbalanced supervision, reducing optimality gaps on CVRP50 and CVRP100 benchmarks."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "vehicle-routing-problem"
  - "autoregressive-models"
  - "neural-routing-solver"
  - "combinatorial-optimization"
timestamp: "2026-10-29T11:15:34Z"

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
    description: "A modeling approach that predicts pairwise same-route probabilities and injects them as a route-consistency signal into autoregressive customer selection for neural vehicle routing."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-29T11:15:34Z"
created_at: "2026-10-29T11:15:34Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization models for the Capacitated Vehicle Routing Problem (CVRP) often construct solutions via sequential node selection with only implicit route organization. To address this, the authors propose Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from node representations and injects them as a route-consistency guidance signal. TRCM combines structure-preserving augmentation with Topological Entropy-based reweighting to handle class-imbalanced supervision, reducing optimality gaps on CVRP50 and CVRP100 benchmarks.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly model route-level customer co-assignment and guide autoregressive node selection.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets.
- Improves the average objective on XML100 under 8-fold augmented inference by 0.24% with enhanced stability on demand variations.

## Limitations

Evaluated primarily on standard CVRP and XML benchmarks under autoregressive construction settings.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A modeling approach that predicts pairwise same-route probabilities and injects them as a route-consistency signal into autoregressive customer selection for neural vehicle routing.

## Archivist Review

Approved the core concept 'topology-aware-route-consistency-modeling' which already exists in the vault (matching the paper title and method). Rejected the open question as it represents generic future work requesting efficiency improvements and broader evaluations. No critical unique datasets were proposed.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: TRCM introduces explicit route-level customer co-assignment prediction to guide autoregressive node-level decisions, serving as a core architectural principle for robust neural routing.

### Rejected Candidates
- [open_question] Efficiency and Reliability of Route-Consistency Signals (`reliability-and-efficiency-of-route-consistency-signals-in-neural-routing`) - not_novel: Boilerplate future work request extending evaluation and improving computational efficiency without defining a precise mechanistic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

