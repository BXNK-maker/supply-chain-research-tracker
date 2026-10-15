---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Evolutionary Giant Tour for CVRP using NSE and ML Heuristic"
description: "This paper investigates an evolutionary giant-tour approach for the Capacitated Vehicle Routing Problem (CVRP) by decoupling the evolutionary search from route construction. The authors adapt Node Shift Encoding (NSE) to the CVRP giant-tour representation and introduce an unsupervised machine-learning repair heuristic to restore fleet feasibility after unconstrained linear splitting. Computational results on standard benchmarks demonstrate that NSE combined with the ML-based repair pipeline consistently surpasses traditional encodings and constrained split methods in both solution cost and feasibility."
resource: "https://arxiv.org/abs/2610.03816"
tags:
  - "combinatorial-optimization"
  - "evolutionary-algorithms"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-15T09:34:37Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Souad Abdoune"
  - literal: "Menouar Boulif"
issued:
  date-parts:
    - [2026, 10, 1]

# Domain-specific custom fields
paper_id: "2610.03816"
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
processed_at: "2026-10-15T09:34:37Z"
created_at: "2026-10-15T09:34:37Z"
---

# Evolutionary Giant Tour for CVRP using NSE and ML Heuristic

**Authors**: Souad Abdoune, Menouar Boulif
**Date**: 2026-10-01
**Paper ID**: [openalex:2610.03816](https://arxiv.org/abs/2610.03816)

## Summary

This paper investigates an evolutionary giant-tour approach for the Capacitated Vehicle Routing Problem (CVRP) by decoupling the evolutionary search from route construction. The authors adapt Node Shift Encoding (NSE) to the CVRP giant-tour representation and introduce an unsupervised machine-learning repair heuristic to restore fleet feasibility after unconstrained linear splitting. Computational results on standard benchmarks demonstrate that NSE combined with the ML-based repair pipeline consistently surpasses traditional encodings and constrained split methods in both solution cost and feasibility.

## Key Contributions

- Adapted Node Shift Encoding (NSE) to the Capacitated Vehicle Routing Problem giant-tour setting, outperforming Path Representation and Double Chromosome in solution quality and feasibility.
- Proposed an unsupervised machine-learning repair heuristic that restores fleet feasibility after an unconstrained linear split in approximately 72% of cases.
- Demonstrated that the Linear-Split-ML-Heuristic pipeline is more robust than traditional constrained split methods, delivering lower costs and higher feasibility rates on standard benchmark instances.

## Limitations

The abstract does not specify runtime overheads or scalability limits on extremely large-scale CVRP instances beyond standard benchmark tests.

## Archivist Review

Applied strict selection criteria: no standalone concepts or open questions met the bar for long-term vault inclusion, as the techniques are specific to CVRP evolutionary algorithms.

### Rejected Candidates
- [open_question] Smarter Repair and Route Equity (`smarter-dismantling-and-route-equity-extensions`) - paper_local: Paper-specific future work directions regarding repair heuristics and route equity in CVRP.

## Links

- [Abstract](https://arxiv.org/abs/2610.03816)
- [PDF](https://arxiv.org/pdf/2610.03816)

