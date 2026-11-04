---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper investigates an applied variant of the Traveling Salesperson Problem with Profits (TSPP) for distribution logistics involving capacity constraints and customer priorities. The authors introduce a hybrid model combining a 0/1 Knapsack objective weighted by the square of client priorities with a priority-biased Nearest Neighbor heuristic. Evaluated on a 14-customer benchmark scenario, the method achieves 96.4% capacity utilization and successfully prioritizes high-value deliveries, outperforming classical greedy baselines."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-11-04T12:45:27Z"

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
processed_at: "2026-11-04T12:45:27Z"
created_at: "2026-11-04T12:45:27Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper investigates an applied variant of the Traveling Salesperson Problem with Profits (TSPP) for distribution logistics involving capacity constraints and customer priorities. The authors introduce a hybrid model combining a 0/1 Knapsack objective weighted by the square of client priorities with a priority-biased Nearest Neighbor heuristic. Evaluated on a 14-customer benchmark scenario, the method achieves 96.4% capacity utilization and successfully prioritizes high-value deliveries, outperforming classical greedy baselines.

## Key Contributions

- Proposes an applied variant of the Traveling Salesperson Problem with Profits (TSPP) integrating a 0/1 Knapsack objective weighted by client priority squared and a priority-biased Nearest Neighbor heuristic.
- Demonstrates on a 14-customer scenario with a 1,100 kg capacity that the approach serves 9 high-priority customers, achieves 96.4% capacity utilization, and yields R$ 18,392.60 in revenue.
- Performs a sensitivity analysis validating the quadratic priority exponent choice over alternative formulations.

## Limitations

The limitations of the hierarchical decomposition approach are explicitly discussed.

## Archivist Review

Applied stringent review criteria: no concepts or datasets were proposed, and the single proposed open question was rejected as a standard request for larger-scale experiments and multi-vehicle extensions rather than a distinct structural bottleneck.

### Rejected Candidates
- [open_question] Priority-Aware TSP with Profits Extensions (`priority-aware-tsp-profits-future-work`) - low_impact: The open question primarily lists standard extensions and future experimental variations such as scaling to multiple vehicles and larger instances, lacking a deep structural methodological bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

