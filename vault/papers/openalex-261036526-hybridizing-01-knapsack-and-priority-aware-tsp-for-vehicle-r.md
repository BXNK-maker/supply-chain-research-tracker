---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper proposes an applied variant of the Traveling Salesperson Problem with Profits for distribution logistics with capacity constraints and service priorities. The methodology introduces a 0/1 knapsack objective weighted by client priority squared and a priority-biased Nearest Neighbor heuristic parameterized by alpha. Evaluated on a 14-customer scenario, the approach achieves high capacity utilization and prioritizes high-value customers effectively compared against classical greedy heuristics and integer programming solvers."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-31T10:41:42Z"

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
processed_at: "2026-10-31T10:41:42Z"
created_at: "2026-10-31T10:41:42Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper proposes an applied variant of the Traveling Salesperson Problem with Profits for distribution logistics with capacity constraints and service priorities. The methodology introduces a 0/1 knapsack objective weighted by client priority squared and a priority-biased Nearest Neighbor heuristic parameterized by alpha. Evaluated on a 14-customer scenario, the approach achieves high capacity utilization and prioritizes high-value customers effectively compared against classical greedy heuristics and integer programming solvers.

## Key Contributions

- Proposes an applied variant of the TSP with Profits integrating a 0/1 knapsack objective weighted by client priority squared ($v_i \cdot p_i^2$) and a priority-biased Nearest Neighbor heuristic for vehicle routing under capacity constraints.
- Demonstrates on a 14-customer scenario that the approach achieves 96.4% capacity utilization and R$ 18,392.60 revenue while exclusively excluding low-priority customers.
- Provides a sensitivity analysis justifying the quadratic priority exponent choice and explicitly discusses the limitations of the hierarchical decomposition.

## Limitations

The limitations of the hierarchical decomposition are explicitly discussed.

## Archivist Review

The single open question candidate is a narrow, paper-local future work item regarding parameter tuning in a heuristic, which does not meet the high bar for permanent vault storage. No concepts or datasets were proposed or approved.

### Rejected Candidates
- [open_question] Systematic Analysis of Priority Bias Parameter (`systematic-analysis-of-priority-bias-parameter`) - low_impact: This is a narrow future-work suggestion specific to tuning a priority bias parameter in a specific heuristic, lacking broad foundational significance across machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

