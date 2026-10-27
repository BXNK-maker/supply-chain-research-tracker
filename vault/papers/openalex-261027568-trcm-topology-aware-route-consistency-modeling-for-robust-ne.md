---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), a framework that explicitly models pairwise customer co-assignment probabilities to guide autoregressive node selection in neural vehicle routing solvers. By combining structure-preserving data augmentation with topological entropy-based reweighting, TRCM effectively addresses class imbalance in same-route supervision. Extensive experiments on CVRP50, CVRP100, and XML100 demonstrate consistent optimality gap reductions and more robust routing behavior under demand variations."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "vehicle-routing-problem"
  - "autoregressive-models"
  - "neural-routing-solver"
timestamp: "2026-10-27T10:10:32Z"

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
    description: "A neural routing framework that explicitly models pairwise customer co-assignment probabilities to guide autoregressive node selection."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-27T10:10:32Z"
created_at: "2026-10-27T10:10:32Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), a framework that explicitly models pairwise customer co-assignment probabilities to guide autoregressive node selection in neural vehicle routing solvers. By combining structure-preserving data augmentation with topological entropy-based reweighting, TRCM effectively addresses class imbalance in same-route supervision. Extensive experiments on CVRP50, CVRP100, and XML100 demonstrate consistent optimality gap reductions and more robust routing behavior under demand variations.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM), which explicitly predicts pairwise same-route probabilities to guide autoregressive node selection.
- Combines structure-preserving augmentation with Topological Entropy (TE)-based reweighting to address class imbalance and structurally uneven same-route supervision.
- Reduces the optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.
- Improves the average objective on XML100 by 0.24% under 8-fold augmented inference.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A neural routing framework that explicitly models pairwise customer co-assignment probabilities to guide autoregressive node selection.

## Archivist Review

Approved the overarching TRCM concept which is already present in the vault and maps directly to the paper's core contribution. Rejected the supporting subcomponent and the boilerplate future work open question. No new datasets warranted approval.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling (TRCM): TRCM introduces a novel explicit route-consistency modeling mechanism that predicts pairwise same-route probabilities to guide autoregressive node selection in neural vehicle routing.

### Rejected Candidates
- [open_question] Extending Route-Consistency to Broader Routing Settings (`scaling-route-consistency-routing-settings`) - generic: Generic future work proposal asking for broader evaluation and efficiency improvements without a sharp technical bottleneck.
- [concept] Topological Entropy-Based Reweighting (`topological-entropy-reweighting`) - subcomponent_of_broader_mechanism: Subcomponent of TRCM framework and insufficiently distinct as a standalone mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

