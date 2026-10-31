---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing"
description: "Neural combinatorial optimization for the Capacitated Vehicle Routing Problem (CVRP) often relies on sequential node selection without explicit route representation. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from standard node representations and injects them as a route-consistency signal into the customer selection process. To handle imbalanced and structurally uneven supervision, TRCM uses structure-preserving augmentation and Topological Entropy-based reweighting. Experimental results demonstrate improved optimality gaps on CVRP50 and CVRP100 benchmarks compared to baseline autoregressive models."
resource: "https://arxiv.org/abs/2610.27568"
tags:
  - "autoregressive-models"
  - "neural-routing-solver"
  - "vehicle-routing-problem"
timestamp: "2026-10-31T10:42:55Z"

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
    description: "A technique that predicts pairwise same-route probabilities from node representations and injects them into autoregressive customer selection as a route-consistency signal."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:42:55Z"
created_at: "2026-10-31T10:42:55Z"
---

# TRCM: Topology-Aware Route-Consistency Modeling for Robust Neural Vehicle Routing

**Authors**: Peiheng Jian, Zhenwei Wang, Tiehua Zhang, Lei Zhang, Zhishu Shen, Ruibin Bai, Zhijun Ding
**Date**: 2026-10-20
**Paper ID**: [openalex:2610.27568](https://arxiv.org/abs/2610.27568)

## Summary

Neural combinatorial optimization for the Capacitated Vehicle Routing Problem (CVRP) often relies on sequential node selection without explicit route representation. This paper proposes Topology-Aware Route-Consistency Modeling (TRCM), which predicts pairwise same-route probabilities from standard node representations and injects them as a route-consistency signal into the customer selection process. To handle imbalanced and structurally uneven supervision, TRCM uses structure-preserving augmentation and Topological Entropy-based reweighting. Experimental results demonstrate improved optimality gaps on CVRP50 and CVRP100 benchmarks compared to baseline autoregressive models.

## Key Contributions

- Proposes Topology-Aware Route-Consistency Modeling (TRCM) to explicitly model customer co-assignment and inject same-route probabilities into autoregressive node selection.
- Combines structure-preserving augmentation and Topological Entropy (TE)-based reweighting to address class imbalance and structurally uneven same-route supervision.
- Reduces the optimality gap on CVRP50 from 3.67% to 3.28% and on CVRP100 from 2.11% to 1.99% under matched decoding budgets.

## Key Concepts

- [[topology-aware-route-consistency-modeling]]: A technique that predicts pairwise same-route probabilities from node representations and injects them into autoregressive customer selection as a route-consistency signal.

## Archivist Review

The concept 'topology-aware-route-consistency-modeling' already exists in the vault and is appropriately matched. No new datasets or open questions meet the rigorous inclusion criteria for standalone vault notes.

### Approved Concepts
- Topology-Aware Route-Consistency Modeling: Introduces an explicit route-level consistency signal for autoregressive neural routing solvers to improve customer selection.

## Links

- [Abstract](https://arxiv.org/abs/2610.27568)
- [PDF](https://arxiv.org/pdf/2610.27568)

