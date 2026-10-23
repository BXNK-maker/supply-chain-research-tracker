---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "This paper introduces Topology-Aware Route-Consistency Modeling (TRCM) to improve autoregressive neural vehicle routing solvers by explicitly predicting pairwise same-route customer probabilities and injecting them as guidance into the node selection process. To address class imbalance and structural unevenness in route supervision, TRCM incorporates structure-preserving augmentation alongside Topological Entropy-based reweighting. Experimental evaluations on CVRP50, CVRP100, and XML100 demonstrate reductions in optimality gaps and improved robustness against demand variations under matched and augmented decoding budgets."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "neural-routing-solver"
  - "vehicle-routing-problem"
  - "machine-learning"
  - "combinatorial-optimization"
timestamp: "2026-10-23T09:45:01Z"

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
    description: "A method for neural vehicle routing that explicitly models pairwise same-route customer probabilities to guide node-level constructive decoding."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:45:01Z"
created_at: "2026-10-23T09:45:01Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

This paper introduces Topology-Aware Route-Consistency Modeling (TRCM) to improve autoregressive neural vehicle routing solvers by explicitly predicting pairwise same-route customer probabilities and injecting them as guidance into the node selection process. To address class imbalance and structural unevenness in route supervision, TRCM incorporates structure-preserving augmentation alongside Topological Entropy-based reweighting. Experimental evaluations on CVRP50, CVRP100, and XML100 demonstrate reductions in optimality gaps and improved robustness against demand variations under matched and augmented decoding budgets.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly predict pairwise same-route customer probabilities and guide autoregressive node selection in neural vehicle routing.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets.
- Demonstrates improved robustness under 8-fold augmented inference and controlled demand-reassignment tests on XML100.

## Limitations

Evaluated primarily on standard CVRP benchmark sizes (CVRP50, CVRP100) and XML100.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A method for neural vehicle routing that explicitly models pairwise same-route customer probabilities to guide node-level constructive decoding.

## Archivist Review

Approved the core concept 'Topology-Aware Route-Consistency Modeling' as a reusable architectural principle for neural vehicle routing solvers. Rejected the proposed open question as it fell into general future-work boilerplate rather than defining a precise, non-trivial bottleneck.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Central methodological contribution introducing explicit route-level co-assignment guidance for autoregressive neural vehicle routing solvers.

### Rejected Candidates
- [open_question] Broadening Route Consistency Routing Settings (`broadening-route-consistency-routing-settings`) - not_novel: The open question is broad boilerplate future work requesting more settings and efficiency improvements rather than a specific technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

