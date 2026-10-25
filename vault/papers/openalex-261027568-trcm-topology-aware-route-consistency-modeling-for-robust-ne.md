---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "This paper introduces Topology-Aware Route-Consistency Modeling (TRCM) to improve autoregressive neural solvers for the Capacitated Vehicle Routing Problem (CVRP). TRCM explicitly models route-level customer co-assignment by predicting pairwise same-route probabilities from node representations and injecting them as guidance into the node selection process. To address class imbalance and structural unevenness, the method combines structure-preserving data augmentation with Topological Entropy-based reweighting. Experimental results demonstrate consistent reductions in optimality gaps on CVRP50 and CVRP100 benchmarks under matched decoding budgets and augmented inference."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "neural-routing-solver"
  - "autoregressive-models"
  - "combinatorial-optimization"
timestamp: "2026-10-25T09:32:28Z"

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
    description: "A framework that predicts pairwise same-route probabilities using node representations and injects them as a route-consistency signal into autoregressive neural routing."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:32:28Z"
created_at: "2026-10-25T09:32:28Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

This paper introduces Topology-Aware Route-Consistency Modeling (TRCM) to improve autoregressive neural solvers for the Capacitated Vehicle Routing Problem (CVRP). TRCM explicitly models route-level customer co-assignment by predicting pairwise same-route probabilities from node representations and injecting them as guidance into the node selection process. To address class imbalance and structural unevenness, the method combines structure-preserving data augmentation with Topological Entropy-based reweighting. Experimental results demonstrate consistent reductions in optimality gaps on CVRP50 and CVRP100 benchmarks under matched decoding budgets and augmented inference.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly model route-level customer co-assignment and guide node-level autoregressive decisions.
- Combines structure-preserving augmentation with Topological Entropy-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets.
- Improves the CVRP100 optimality gap to 1.49% under 8-fold augmented inference and improves the average objective on XML100 by 0.24%.

## Limitations

Evaluated primarily on standard CVRP and XML100 benchmarks; generalization to other complex variants of routing remains to be fully explored.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A framework that predicts pairwise same-route probabilities using node representations and injects them as a route-consistency signal into autoregressive neural routing.

## Archivist Review

Approved the overarching topology-aware route-consistency modeling concept, which is already present in the vault. Rejected the subcomponent and open question as they duplicate or subserve existing vault entries.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces explicit route-level customer co-assignment and pairwise same-route probabilities to guide autoregressive node selection in vehicle routing.

### Rejected Candidates
- [concept] Topological Entropy-Based Reweighting (`topological-entropy-reweighting`) - subcomponent_of_broader_mechanism: Subcomponent of TRCM rather than a standalone overarching paradigm.
- [open_question] Route Consistency and Scalability (`route-consistency-efficiency-broad-routing`) - duplicate_existing: Overlaps with existing routing generalization and scaling challenges in the vault without introducing a sufficiently distinct bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

