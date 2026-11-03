---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning"
description: "This paper studies a carbon-aware Electric Vehicle Routing Problem that optimizes routing, charging, and waiting decisions to minimize charging-related emissions driven by time-varying grid carbon intensity. To address the dependency of these decisions on carbon intensity forecasts, the authors propose a decision-focused learning approach that trains a linear predictor using approximate SPO+ directions with a Large Neighborhood Search solver. Experiments on realistic Germany-based instances demonstrate that carbon-aware optimization significantly reduces realized emissions, and decision-focused training outperforms conventional prediction-focused learning in total realized cost despite lower pointwise prediction accuracy."
resource: "https://arxiv.org/abs/2610.39645"
tags:
  - "decarbonization"
  - "vehicle-routing-problem"
  - "stochastic-demands"
timestamp: "2026-11-03T12:37:35Z"

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
  - name: "carbon-aware-electric-vehicle-routing-problem"
    description: "An electric vehicle routing problem formulation that incorporates charging-related emissions and schedule flexibility to minimize grid carbon intensity."
datasets:
  []
open_questions:
  - name: "computational-efficiency-in-dfl-routing"
    description: "Future work should investigate reducing the computational overhead of decision-focused learning loops by exploring lower solver time limits, surrogate models, or alternative training sample strategies to mitigate the high training time associated with large-scale routing solvers."
skill: "GeneralMLSkill"
processed_at: "2026-11-03T12:37:35Z"
created_at: "2026-11-03T12:37:35Z"
---

# Carbon-Aware Electric Vehicle Routing Problem with Decision-Focused Learning

**Authors**: Jaume Reixach, Wanru Chen, Jiaming Wu, Balaźs Kulcsár
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.39645](https://arxiv.org/abs/2610.39645)

## Summary

This paper studies a carbon-aware Electric Vehicle Routing Problem that optimizes routing, charging, and waiting decisions to minimize charging-related emissions driven by time-varying grid carbon intensity. To address the dependency of these decisions on carbon intensity forecasts, the authors propose a decision-focused learning approach that trains a linear predictor using approximate SPO+ directions with a Large Neighborhood Search solver. Experiments on realistic Germany-based instances demonstrate that carbon-aware optimization significantly reduces realized emissions, and decision-focused training outperforms conventional prediction-focused learning in total realized cost despite lower pointwise prediction accuracy.

## Key Contributions

- Proposes a carbon-aware Electric Vehicle Routing Problem formulation that incorporates charging-related emissions and temporal charging/waiting flexibility to shift demand toward lower carbon intensity periods.
- Applies a decision-focused learning approach using approximate SPO+ directions to train a linear carbon intensity predictor that is solver-aware of the underlying Large Neighborhood Search and exact postprocessing.
- Demonstrates on Germany-based instances that explicit consideration of charging-related emissions reduces realized emissions by 28.76% on average compared to carbon-blind optimization.
- Shows that decision-focused training reduces realized total cost by 2.30% relative to conventional prediction-focused learning, outperforming it on 75.5% of test instances despite having lower pointwise predictive accuracy.

## Limitations

Results rely on realistic Germany-based instances and linear predictors with SPO+ approximations; broader generalization to non-linear predictors and other power grids remains to be fully explored.

## Open Questions & Future Work

- [[computational-efficiency-in-dfl-routing]]

## Key Concepts

- [[carbon-aware-electric-vehicle-routing-problem]]: An electric vehicle routing problem formulation that incorporates charging-related emissions and schedule flexibility to minimize grid carbon intensity.

## Archivist Review

Approved the core carbon-aware EVRP problem formulation and the open question concerning computational efficiency in decision-focused routing, while rejecting broad pre-existing methodologies like decision-focused learning and ad-hoc case study datasets.

### Approved Concepts
- Carbon-Aware Electric Vehicle Routing Problem: Establishes a novel vehicle routing formulation that integrates time-varying grid carbon intensity and charging/waiting flexibility to shift charging demand.

### Approved Open Questions
- Improving Decision-Focused Training Efficiency: High computational cost is a primary bottleneck for scaling decision-focused learning to complex combinatorial optimization problems like vehicle routing.

### Rejected Candidates
- [concept] Decision-Focused Learning (`decision-focused-learning`) - not_novel: Decision-focused learning is a well-established existing methodology rather than a novel concept introduced by this paper.
- [dataset] Germany-Based Instances (`germany-based-instances`) - weak_evidence: Ad-hoc synthetic or case-study instances rather than a standardized, widely adopted benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2610.39645)
- [PDF](https://arxiv.org/pdf/2610.39645)

