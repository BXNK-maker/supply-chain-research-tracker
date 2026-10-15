---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Evolutionary Giant Tour for CVRP using NSE and ML Heuristic"
description: "This paper introduces an evolutionary giant-tour approach for the Capacitated Vehicle Routing Problem (CVRP) that separates the evolutionary search from route construction. The method combines an adapted Node Shift Encoding (NSE) with an unsupervised machine-learning repair heuristic to restore fleet feasibility following an unconstrained linear split. Computational evaluations on standard benchmark instances indicate that NSE outperforms existing encodings, and the proposed ML-driven pipeline delivers lower routing costs and higher feasibility rates than conventional fleet-constrained split methods."
resource: "https://arxiv.org/abs/2610.03816"
tags:
  - "machine-learning"
  - "evolutionary-algorithms"
  - "combinatorial-optimization"
timestamp: "2026-10-15T04:44:07Z"

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
processed_at: "2026-10-15T04:44:07Z"
created_at: "2026-10-15T04:44:07Z"
---

# Evolutionary Giant Tour for CVRP using NSE and ML Heuristic

**Authors**: Souad Abdoune, Menouar Boulif
**Date**: 2026-10-01
**Paper ID**: [openalex:2610.03816](https://arxiv.org/abs/2610.03816)

## Summary

This paper introduces an evolutionary giant-tour approach for the Capacitated Vehicle Routing Problem (CVRP) that separates the evolutionary search from route construction. The method combines an adapted Node Shift Encoding (NSE) with an unsupervised machine-learning repair heuristic to restore fleet feasibility following an unconstrained linear split. Computational evaluations on standard benchmark instances indicate that NSE outperforms existing encodings, and the proposed ML-driven pipeline delivers lower routing costs and higher feasibility rates than conventional fleet-constrained split methods.

## Key Contributions

- Adapted Node Shift Encoding (NSE) to the Capacitated Vehicle Routing Problem (CVRP) giant-tour setting, demonstrating superior solution quality and feasibility over Path Representation and Double Chromosome.
- Proposed an unsupervised machine-learning repair heuristic that restores fleet feasibility after an unconstrained linear split, achieving success in approximately 72% of cases.
- Demonstrated that the Linear-Split-ML-Heuristic pipeline is more robust than traditional fleet-constrained split methods from the literature, delivering lower costs and higher feasibility rates.

## Limitations

Evaluation is limited to standard benchmark instances for CVRP, and the machine-learning repair heuristic successfully restores feasibility in about 72% of cases rather than guaranteeing 100% feasibility.

## Archivist Review

No concepts met the strict bar for permanent vault storage. Node Shift Encoding and Linear-Split-ML-Heuristic are paper-specific adaptations/pipelines within combinatorial optimization rather than broad foundational concepts with independent future reuse.

## Links

- [Abstract](https://arxiv.org/abs/2610.03816)
- [PDF](https://arxiv.org/pdf/2610.03816)

