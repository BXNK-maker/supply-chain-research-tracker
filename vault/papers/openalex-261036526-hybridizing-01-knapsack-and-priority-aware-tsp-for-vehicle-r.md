---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper proposes an applied variant of the Traveling Salesperson Problem with Profits (TSPP) tailored for distribution logistics with capacity constraints and service priorities. The method combines a 0/1 Knapsack objective weighted by the squared client priority and a priority-biased Nearest Neighbor heuristic for routing. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the approach effectively prioritizes high-value customers, achieving high capacity utilization and superior revenue compared to classical greedy heuristics and integer programming solvers."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-10-30T11:09:14Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Aron da Silva Bezerra"
  - literal: "Francisco Márcio Barboza"
issued:
  date-parts:
    - [2026, 10, 27]

# Domain-specific custom fields
paper_id: "2610.36526"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:09:14Z"
created_at: "2026-10-30T11:09:14Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper proposes an applied variant of the Traveling Salesperson Problem with Profits (TSPP) tailored for distribution logistics with capacity constraints and service priorities. The method combines a 0/1 Knapsack objective weighted by the squared client priority and a priority-biased Nearest Neighbor heuristic for routing. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the approach effectively prioritizes high-value customers, achieving high capacity utilization and superior revenue compared to classical greedy heuristics and integer programming solvers.

## Key Contributions

- Proposes a variant of the Traveling Salesperson Problem with Profits (TSPP) combining a 0/1 Knapsack objective weighted by client priority squared ($v_i \cdot p_i^2$) and a priority-biased Nearest Neighbor heuristic parameterized by $\alpha$.
- Achieves 96.4% vehicle capacity utilization, serving 9 out of 14 customers while excluding all 5 low-priority customers on the evaluated scenario, generating R$ 18,392.60 in revenue.
- Demonstrates through sensitivity analysis that squaring the client priority factor yields superior prioritization outcomes compared to linear alternatives.

## Limitations

The limitations of the hierarchical decomposition approach are explicitly highlighted.

## Archivist Review

Applied vehicle routing variant with a priority-weighted knapsack objective and nearest-neighbor heuristic. No standalone concepts or open questions met the rigorous standard for vault inclusion, as the techniques and questions are narrow and paper-local.

### Rejected Candidates
- [open_question] Systematic Sensitivity and Scalability Analysis (`systematic-sensitivity-analysis-hierarchical-decomposition`) - paper_local: The open question requests routine sensitivity tuning and large-scale scaling experiments for a specific heuristic variant, which is paper-local and incremental rather than a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

