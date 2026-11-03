---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural autoregressive solvers for the Capacitated Vehicle Routing Problem (CVRP) typically construct solutions sequentially without explicitly modeling route organization. This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from intermediate node representations and injects them as a guidance signal during customer selection. To handle class-imbalanced and structurally uneven supervision, TRCM employs structure-preserving augmentation alongside topological entropy-based reweighting. Experimental results on CVRP and XML100 benchmarks demonstrate significant reductions in optimality gaps and enhanced robustness against demand variations."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "time-series"
timestamp: "2026-11-03T12:37:57Z"

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
    description: "A method for neural vehicle routing that predicts pairwise same-route probabilities using structure-preserving augmentation and topological entropy-based reweighting to guide node-level customer selection."
datasets:
  []
open_questions:
  - name: "route-consistency-efficiency-and-reliability"
    description: "Future research can examine how to improve the reliability and computational efficiency of the route-consistency signal while extending its evaluation to broader routing settings, particularly addressing reference partition dependence and the high computational overhead of dense pair prediction."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:37:57Z"
created_at: "2026-11-03T12:37:57Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural autoregressive solvers for the Capacitated Vehicle Routing Problem (CVRP) typically construct solutions sequentially without explicitly modeling route organization. This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from intermediate node representations and injects them as a guidance signal during customer selection. To handle class-imbalanced and structurally uneven supervision, TRCM employs structure-preserving augmentation alongside topological entropy-based reweighting. Experimental results on CVRP and XML100 benchmarks demonstrate significant reductions in optimality gaps and enhanced robustness against demand variations.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities from node representations and injects them into customer selection as a route-consistency signal.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets, with further gains under augmented inference.
- Demonstrates improved objective stability on XML100 and through a controlled demand-reassignment test over 500 variants.

## Open Questions & Future Work

- [[route-consistency-efficiency-and-reliability]]

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A method for neural vehicle routing that predicts pairwise same-route probabilities using structure-preserving augmentation and topological entropy-based reweighting to guide node-level customer selection.

## Archivist Review

Approved the core overarching framework (TRCM) and its primary open question while filtering out paper-local subcomponents and standard benchmark datasets.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces explicit route-level customer co-assignment and topological entropy-based reweighting to guide autoregressive neural vehicle routing solvers.

### Approved Open Questions
- Improving Route-Consistency Efficiency and Reliability: Addressing the computational bottleneck of dense pair prediction and improving the reliability of route-consistency signals are critical for scaling neural routing solvers to larger problem instances.

### Rejected Candidates
- [concept] Topological Entropy Reweighting (`topological-entropy-reweighting`) - subcomponent_of_broader_mechanism: Subcomponent of the broader TRCM framework rather than a standalone overarching mechanism.
- [dataset] XML100 (`xml100`) - not_reusable: Standard benchmark dataset; unnecessary to create a vault note for routine instance sets.
- [dataset] CVRP50 (`cvrp50`) - not_reusable: Standard benchmark dataset instance size.
- [dataset] CVRP100 (`cvrp100`) - not_reusable: Standard benchmark dataset instance size.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

