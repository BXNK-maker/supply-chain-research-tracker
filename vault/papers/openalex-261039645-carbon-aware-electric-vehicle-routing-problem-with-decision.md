---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning"
description: "The paper studies a Carbon-Aware Electric Vehicle Routing Problem that minimizes charging-related emissions by shifting demand to periods of low grid carbon intensity. To address the dependence on carbon forecasts, the authors propose a decision-focused learning approach using approximate SPO+ directions to train a linear predictor solver-aware. Experiments on Germany-based instances show that decision-focused training reduces realized total cost by 2.30% compared to conventional prediction-focused learning, even with lower pointwise predictive accuracy."
resource: "https://arxiv.org/abs/2610.39645"
tags:
  - "vehicle-routing-problem"
  - "decarbonization"
  - "combinatorial-optimization"
  - "demand-forecasting"
timestamp: "2026-11-01T11:38:51Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jaume Reixach"
  - literal: "Wanru Chen"
  - literal: "Jiaming Wu"
  - literal: "Balázs Kulcsár"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.39645"
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
processed_at: "2026-11-01T11:38:51Z"
created_at: "2026-11-01T11:38:51Z"
---

# Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning

**Authors**: Jaume Reixach, Wanru Chen, Jiaming Wu, Balázs Kulcsár
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39645](https://arxiv.org/abs/2610.39645)

## Summary

The paper studies a Carbon-Aware Electric Vehicle Routing Problem that minimizes charging-related emissions by shifting demand to periods of low grid carbon intensity. To address the dependence on carbon forecasts, the authors propose a decision-focused learning approach using approximate SPO+ directions to train a linear predictor solver-aware. Experiments on Germany-based instances show that decision-focused training reduces realized total cost by 2.30% compared to conventional prediction-focused learning, even with lower pointwise predictive accuracy.

## Key Contributions

- Formulated the Carbon-Aware Electric Vehicle Routing Problem (EVRP) integrating routing, charging, and waiting decisions to minimize charging-related emissions driven by time-varying grid carbon intensity.
- Proposed a decision-focused learning approach using approximate SPO+ directions to train a linear carbon intensity predictor in a solver-aware manner.
- Employed a time-limited Large Neighborhood Search followed by exact postprocessing as the underlying combinatorial optimization solver.
- Demonstrated on realistic Germany-based instances that decision-focused training reduces realized total cost by 2.30% compared to conventional prediction-focused learning, despite lower pointwise predictive accuracy.

## Limitations

Optimization yields higher non-carbon operating costs when prioritizing carbon reduction.

## Archivist Review

Applied strict scarcity and novelty filters. The paper applies established decision-focused learning and SPO+ techniques to a carbon-aware electric vehicle routing problem, which does not yield broadly reusable architectural primitives or foundational open questions deserving permanent standalone notes.

### Rejected Candidates
- [open_question] Computational Efficiency in Decision-Focused Routing (`computational-efficiency-in-dfl-routing`) - low_impact: This is primarily a routine computational training-time bottleneck and hardware/speed optimization concern rather than a deep foundational research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.39645)
- [PDF](https://arxiv.org/pdf/2610.39645)

