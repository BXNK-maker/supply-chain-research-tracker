---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning"
description: "This paper studies the Carbon-Aware Electric Vehicle Routing Problem, which minimizes charging-related emissions and routing costs by shifting charging demand to low carbon intensity periods. To handle future uncertainty, the authors propose a decision-focused learning approach using approximate SPO+ directions to train a solver-aware carbon intensity predictor. Experiments on Germany-based instances show that decision-focused training reduces realized total cost by 2.30% compared to prediction-focused learning, despite having lower pointwise predictive accuracy."
resource: "https://arxiv.org/abs/2610.39645"
tags:
  - "vehicle-routing-problem"
  - "decarbonization"
  - "demand-forecasting"
  - "combinatorial-optimization"
  - "interpretable-machine-learning"
timestamp: "2026-11-02T13:06:20Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jaume Reixach"
  - literal: "Wanru Chen"
  - literal: "Jiaming Wu"
  - literal: "Balaźs Kulcsár"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.39645"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "decision-focused-learning"
    description: "A machine learning training framework where prediction models are optimized directly with respect to downstream solver performance rather than standard predictive accuracy."
datasets:
  []
open_questions:
  - name: "computational-cost-scaling-dfl-routing"
    description: "Future work should investigate reducing the time limit assigned to the large neighborhood search (LNS) during training, exploring the trade-off between the training time limit and downstream decision performance, and constructing surrogate models to reduce the number of LNS and postprocessing executions required in the training loop."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:06:20Z"
created_at: "2026-11-02T13:06:20Z"
---

# Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning

**Authors**: Jaume Reixach, Wanru Chen, Jiaming Wu, Balaźs Kulcsár
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39645](https://arxiv.org/abs/2610.39645)

## Summary

This paper studies the Carbon-Aware Electric Vehicle Routing Problem, which minimizes charging-related emissions and routing costs by shifting charging demand to low carbon intensity periods. To handle future uncertainty, the authors propose a decision-focused learning approach using approximate SPO+ directions to train a solver-aware carbon intensity predictor. Experiments on Germany-based instances show that decision-focused training reduces realized total cost by 2.30% compared to prediction-focused learning, despite having lower pointwise predictive accuracy.

## Key Contributions

- Introduced a carbon-aware Electric Vehicle Routing Problem that co-optimizes routing, charging, and waiting decisions to minimize charging-related grid emissions alongside conventional routing costs.
- Proposed a decision-focused learning approach using approximate SPO+ directions to train a linear carbon intensity predictor in a solver-aware manner.
- Demonstrated on Germany-based instances that carbon-aware optimization reduces realized carbon emissions by 28.76% compared to carbon-blind optimization.
- Showed that decision-focused training reduces realized total cost by 2.30% relative to conventional prediction-focused learning, achieving superior performance on 75.5% of test instances despite lower pointwise predictive accuracy.

## Limitations

Achieves lower carbon-aware emissions at the expense of higher non-carbon operating costs.

## Open Questions & Future Work

- [[computational-cost-scaling-dfl-routing]]

## Key Concepts

- [[decision-focused-learning]]: A machine learning training framework where prediction models are optimized directly with respect to downstream solver performance rather than standard predictive accuracy.

## Archivist Review

Approved Decision-Focused Learning as a central conceptual framework for solver-aware prediction, and approved the open question on computational scaling in decision-focused routing due to its clear bottleneck definition. No standalone named datasets were present.

### Approved Concepts
- Decision-Focused Learning: Central framework for training carbon intensity predictors that are solver-aware using approximate SPO+ directions for the electric vehicle routing problem.

### Approved Open Questions
- Computational Efficiency in Decision-Focused Routing: The high computational complexity of integrating combinatorial optimization solvers into decision-focused training loops remains a core bottleneck for scaling these methods to larger routing applications.

## Links

- [Abstract](https://arxiv.org/abs/2610.39645)
- [PDF](https://arxiv.org/pdf/2610.39645)

