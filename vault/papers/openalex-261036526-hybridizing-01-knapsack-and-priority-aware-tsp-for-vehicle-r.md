---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits"
description: "This paper models distribution logistics with capacity constraints and service priorities as an applied variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose a hybrid approach combining a 0/1 knapsack objective weighted by client priority squared and a priority-biased Nearest Neighbor routing heuristic. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the approach achieves 96.4% capacity utilization and R$ 18,392.60 revenue by prioritizing high-value and high-priority customers."
resource: "https://arxiv.org/abs/2610.36526"
tags:
  - "vehicle-routing-problem"
  - "combinatorial-optimization"
timestamp: "2026-11-02T13:03:11Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:03:11Z"
created_at: "2026-11-02T13:03:11Z"
---

# Hybridizing 0/1 Knapsack and Priority-Aware TSP for Vehicle Routing: an Applied Variant of the TSP with Profits

**Authors**: Aron da Silva Bezerra, Francisco Márcio Barboza, Aron da Silva Bezerra, Francisco Márcio Barboza
**Date**: 2026-10-27
**Paper ID**: [openalex:2610.36526](https://arxiv.org/abs/2610.36526)

## Summary

This paper models distribution logistics with capacity constraints and service priorities as an applied variant of the Traveling Salesperson Problem with Profits (TSPP). The authors propose a hybrid approach combining a 0/1 knapsack objective weighted by client priority squared and a priority-biased Nearest Neighbor routing heuristic. Evaluated on a 14-customer scenario with a 1,100 kg capacity, the approach achieves 96.4% capacity utilization and R$ 18,392.60 revenue by prioritizing high-value and high-priority customers.

## Key Contributions

- Proposes an applied variant of the TSP with Profits featuring a 0/1 knapsack objective weighted by client priority squared ($v_i \cdot p_i^2$).
- Introduces a priority bias in the Nearest Neighbor heuristic for the TSP parameterized by $\alpha$.
- Evaluates the approach on a 14-customer scenario with 1,100 kg capacity, achieving 96.4% capacity utilization and R$ 18,392.60 revenue while successfully excluding low-priority customers.
- Conducts a sensitivity analysis of the priority exponent to justify the quadratic choice and discusses limitations of the hierarchical decomposition.

## Limitations

The limitations of the hierarchical decomposition are explicitly discussed.

## Archivist Review

The concept 'Priority-Aware TSP with Profits' already exists in the vault. The proposed open question is a bundle of routine future work tasks rather than a sharply defined bottleneck. Therefore, no new vault entries are added.

### Rejected Candidates
- [concept] Priority-Aware TSP with Profits (`priority-aware-tsp-with-profits`) - duplicate_existing: Already exists in the vault under the exact same slug.
- [open_question] Systematic Calibration and Extension for Priority-Aware Routing (`systematic-parameter-calibration-and-extension-for-priority-aware-tsp-with-profits`) - not_novel: Contains routine future work requests such as larger benchmarks, multi-vehicle extensions, and parameter tuning.

## Links

- [Abstract](https://arxiv.org/abs/2610.36526)
- [PDF](https://arxiv.org/pdf/2610.36526)

