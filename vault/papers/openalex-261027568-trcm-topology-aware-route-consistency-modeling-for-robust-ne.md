---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization models typically construct vehicle routing solutions through sequential node selection without explicitly representing route organization. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities using node representations and injects them as a route-consistency signal into customer selection. To address class imbalance and uneven supervision, TRCM employs structure-preserving augmentation and Topological Entropy-based reweighting. Experimental results demonstrate improved optimality gaps across CVRP50 and CVRP100 benchmarks under matched decoding budgets."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "neural-routing-solver"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-02T13:06:43Z"

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
    description: "A method for robust neural vehicle routing that explicitly models pairwise same-route probabilities to guide node selection in autoregressive models."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:06:43Z"
created_at: "2026-11-02T13:06:43Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization models typically construct vehicle routing solutions through sequential node selection without explicitly representing route organization. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities using node representations and injects them as a route-consistency signal into customer selection. To address class imbalance and uneven supervision, TRCM employs structure-preserving augmentation and Topological Entropy-based reweighting. Experimental results demonstrate improved optimality gaps across CVRP50 and CVRP100 benchmarks under matched decoding budgets.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly predict pairwise same-route probabilities and guide autoregressive node selection in vehicle routing solvers.
- Combines structure-preserving augmentation with Topological Entropy-based reweighting to handle class-imbalanced and structurally uneven same-route supervision.
- Reduces optimality gap from 3.67% to 3.28% on CVRP50 and from 2.11% to 1.99% on CVRP100 under matched decoding budgets.

## Limitations

Tested primarily on CVRP instances up to size 100; scalability to large-scale vehicle routing remains to be fully explored.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A method for robust neural vehicle routing that explicitly models pairwise same-route probabilities to guide node selection in autoregressive models.

## Archivist Review

The central concept 'Topology-Aware Route-Consistency Modeling' is approved as it already exists in the vault under the exact same slug ('topology-aware-route-consistency-modeling'). The open question is rejected because it amounts to routine future scaling and efficiency explorations rather than a standalone structural bottleneck. No datasets are approved as they are standard CVRP problem sizes rather than novel distinct datasets.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces a novel structural principle for autoregressive neural routing by explicitly modeling pairwise same-route probabilities to guide node selection.

### Rejected Candidates
- [open_question] Improving Route-Consistency Efficiency and Generalization (`improving-route-consistency-efficiency`) - low_impact: The question is a standard forward-looking extension regarding scalability and computational overhead rather than a sharp, technically distinct unresolved bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

