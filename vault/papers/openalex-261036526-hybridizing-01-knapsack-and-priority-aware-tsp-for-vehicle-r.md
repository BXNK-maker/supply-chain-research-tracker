---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper models distribution logistics with capacity constraints and service priorities as a variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose a hybrid approach combining a 0/1 Knapsack objective weighted by the square of client priorities with a priority-biased Nearest Neighbor heuristic. Evaluated on a 14-customer scenario with a 1,100 kg capacity limit, the proposed method achieves 96.4% capacity utilization and significant revenue while effectively prioritizing high-value clients."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-03T12:36:21Z"

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
processed_at: "2026-11-03T12:36:21Z"
created_at: "2026-11-03T12:36:21Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper models distribution logistics with capacity constraints and service priorities as a variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose a hybrid approach combining a 0/1 Knapsack objective weighted by the square of client priorities with a priority-biased Nearest Neighbor heuristic. Evaluated on a 14-customer scenario with a 1,100 kg capacity limit, the proposed method achieves 96.4% capacity utilization and significant revenue while effectively prioritizing high-value clients.

## Key Contributions

- Proposes an applied variant of the TSP with Profits integrating a 0/1 Knapsack objective weighted by client priority squared (v_i \cdot p_i^2) and a priority-biased Nearest Neighbor heuristic parameterized by \alpha.
- Achieves 96.4\% capacity utilization and R$ 18,392.60 revenue while serving 9 out of 14 customers, correctly excluding all low-priority customers on the base scenario.
- Performs sensitivity analysis on the priority exponent, providing formal justification for the quadratic choice in priority-aware distribution logistics.

## Limitations

The limitations of the hierarchical decomposition approach are explicitly discussed in the evaluation.

## Archivist Review

The proposed candidate open question is too paper-local and specific to a heuristic routing parameter tuning detail. Therefore, no concepts or open questions were approved.

### Rejected Candidates
- [open_question] Systematic Calibration of Priority Bias (`systematic-calibration-of-priority-bias-parameter`) - low_impact: The open question relates to a very local heuristic parameter in a small-scale applied routing variant and does not represent a broad unresolved bottleneck for machine learning or operations research as a whole.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

