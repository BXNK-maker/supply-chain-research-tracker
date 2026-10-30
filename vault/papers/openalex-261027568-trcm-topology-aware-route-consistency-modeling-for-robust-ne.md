---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), a method that explicitly models route-level customer co-assignment to guide node-level decision making in autoregressive neural vehicle routing solvers. By predicting pairwise same-route probabilities using representations from standard construction pipelines and incorporating structure-preserving augmentation with Topological Entropy-based reweighting, TRCM addresses structural unevenness and class imbalance. Evaluations on CVRP50, CVRP100, and XML100 demonstrate reduced optimality gaps and improved solution robustness under matched decoding budgets and augmented inference."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "autoregressive-models"
  - "combinatorial-optimization"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
timestamp: "2026-10-30T11:09:04Z"

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
    description: "A method for explicit route-consistency modeling in autoregressive neural vehicle routing solvers."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:09:04Z"
created_at: "2026-10-30T11:09:04Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

This paper introduces Topology-Aware Route-Consistency Modeling (TRCM), a method that explicitly models route-level customer co-assignment to guide node-level decision making in autoregressive neural vehicle routing solvers. By predicting pairwise same-route probabilities using representations from standard construction pipelines and incorporating structure-preserving augmentation with Topological Entropy-based reweighting, TRCM addresses structural unevenness and class imbalance. Evaluations on CVRP50, CVRP100, and XML100 demonstrate reduced optimality gaps and improved solution robustness under matched decoding budgets and augmented inference.

## Key Contributions

- Proposes TRCM to explicitly model route-level customer co-assignment and inject same-route probabilities as a consistency signal into autoregressive neural routing.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to address class imbalance and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets.
- Improves average objective on XML100 by 0.24% under 8-fold augmented inference.

## Limitations

Evaluated primarily on standard CVRP instances and XML100; broader generalization to heterogeneous routing constraints requires further study.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A method for explicit route-consistency modeling in autoregressive neural vehicle routing solvers.

## Archivist Review

Approved the core concept 'Topology-Aware Route-Consistency Modeling' which already exists in the vault under the exact same slug. Rejected the open question candidate as it falls into the category of routine future work requests (efficiency and reliability). No datasets were approved since CVRP benchmarks are standard routing datasets rather than unique standalone artifacts.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Central to the paper's novelty as a method for explicit route-level customer co-assignment guidance in neural vehicle routing.

### Rejected Candidates
- [open_question] Reliability and Efficiency of Route Consistency Signals (`improving-reliability-and-efficiency-of-route-consistency-signals-in-neural-routing`) - not_novel: Generic future work request concerning computational efficiency and signal reliability without a specific unresolved mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

