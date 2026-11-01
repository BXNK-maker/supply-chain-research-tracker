---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper models distribution logistics with capacity constraints and service priorities as a variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose two adaptations: a 0/1 knapsack objective weighted by client priority squared, and a priority-biased Nearest Neighbor heuristic parameterized by alpha. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the method achieves 96.4% capacity utilization and R$ 18,392.60 revenue while successfully filtering low-priority customers."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "demand-forecasting"
timestamp: "2026-11-01T11:36:44Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Aron da Silva Bezerra"
  - literal: "Francisco Márcio Barboza"
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
  - name: "priority-aware-tsp-with-profits"
    description: "A variant of the Traveling Salesperson Problem with Profits incorporating quadratic priority weighting and priority-biased nearest neighbor heuristics."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:36:44Z"
created_at: "2026-11-01T11:36:44Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza, Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper models distribution logistics with capacity constraints and service priorities as a variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose two adaptations: a 0/1 knapsack objective weighted by client priority squared, and a priority-biased Nearest Neighbor heuristic parameterized by alpha. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the method achieves 96.4% capacity utilization and R$ 18,392.60 revenue while successfully filtering low-priority customers.

## Key Contributions

- Proposes a hybrid variant of the TSP with Profits combining a 0/1 Knapsack objective weighted by client priority squared with a priority-biased Nearest Neighbor heuristic.
- Demonstrates on a 14-customer, 1,100 kg capacity scenario that the approach achieves 96.4% capacity utilization and R$ 18,392.60 revenue while correctly excluding low-priority customers.
- Provides a sensitivity analysis justifying the quadratic choice for the priority exponent.

## Limitations

The limitations of the hierarchical decomposition are explicitly discussed.

## Key Concepts

- [[priority-aware-tsp-with-profits]]: A variant of the Traveling Salesperson Problem with Profits incorporating quadratic priority weighting and priority-biased nearest neighbor heuristics.

## Archivist Review

Approved the central concept of the priority-aware TSP with profits variant as it represents a reusable modeling framework for vehicle routing with profits and priorities. Rejected the quadratic priority weighting concept as a subcomponent of the broader mechanism. Rejected the open question on parameter calibration as too paper-local and minor. No standalone datasets were included since the evaluation used a custom 14-customer scenario.

### Approved Concepts
- Priority-Aware TSP with Profits: Introduces an applied variant of the TSP with Profits combining a 0/1 knapsack objective with priority-squared weighting and a priority-biased nearest neighbor heuristic.

### Rejected Candidates
- [concept] Quadratic Priority Weighting (`quadratic-priority-weighting`) - subcomponent_of_broader_mechanism: Subcomponent of the broader priority-aware TSPP mechanism.
- [open_question] Systematic Calibration of Priority Bias (`systematic-calibration-priority-bias-parameter`) - low_impact: Too narrow to a specific parameter tuning question for a single heuristic variant rather than a foundational open bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

