---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), a method that enhances autoregressive neural vehicle routing solvers by explicitly predicting pairwise same-route probabilities and injecting them as guidance into the node selection process. To handle class imbalance and structural unevenness in same-route supervision, TRCM incorporates structure-preserving augmentation and Topological Entropy-based reweighting. Empirical evaluations on CVRP50, CVRP100, and XML100 benchmarks demonstrate consistent reductions in optimality gaps compared to standard autoregressive baselines."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "autoregressive-models"
  - "combinatorial-optimization"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
timestamp: "2026-10-26T10:42:39Z"

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
    description: "A method for neural vehicle routing that explicitly models pairwise customer co-assignment probabilities to guide node-level constructive decisions."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:42:39Z"
created_at: "2026-10-26T10:42:39Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), a method that enhances autoregressive neural vehicle routing solvers by explicitly predicting pairwise same-route probabilities and injecting them as guidance into the node selection process. To handle class imbalance and structural unevenness in same-route supervision, TRCM incorporates structure-preserving augmentation and Topological Entropy-based reweighting. Empirical evaluations on CVRP50, CVRP100, and XML100 benchmarks demonstrate consistent reductions in optimality gaps compared to standard autoregressive baselines.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly predict pairwise same-route probabilities and guide node selection in autoregressive neural routing.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to address class-imbalanced and structurally uneven same-route supervision.
- Reduces the optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.
- Achieves a reduced CVRP100 optimality gap of 1.49% under 8-fold augmented inference, while improving average objective by 0.24% on XML100.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A method for neural vehicle routing that explicitly models pairwise customer co-assignment probabilities to guide node-level constructive decisions.

## Archivist Review

Approved the central methodological concept 'Topology-Aware Route-Consistency Modeling' (TRCM), which already exists in the vault. Rejected the open question as it represents routine scaling and future work extensions rather than a distinct conceptual bottleneck. No datasets were approved since CVRP50/100 are standard problem instances rather than standalone research datasets.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces an explicit route-level consistency signal into autoregressive neural routing solvers to bridge node-level selection and route organization.

### Rejected Candidates
- [open_question] Improving Route Consistency and Scaling (`improving-route-consistency-signaling-and-scaling`) - low_impact: The question is largely a routine request for scaling and efficiency tuning without a sharply defined foundational bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

