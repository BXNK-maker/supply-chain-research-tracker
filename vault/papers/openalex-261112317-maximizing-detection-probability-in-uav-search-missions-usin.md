---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Maximizing Detection Probability in UAV Search Missions using Random-Key Optimizers"
description: "This paper addresses stochastic and real-time path planning for Unmanned Aerial Vehicles (UAVs) in Search and Rescue (SAR) operations by combining closed-loop probability updates with Random-Key Optimizers (RKO). The problem is formulated as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP), enabling adaptive balancing between probability maximization and resource minimization. Computational results demonstrate scalability and effectiveness, while highlighting that systematic prior biases degrade performance more severely than complete lack of prior information."
resource: "https://arxiv.org/abs/2611.12317"
tags:
  - "robotics"
  - "vehicle-routing-problem"
  - "stochastic-demands"
  - "reinforcement-learning"
timestamp: "2026-11-20T13:48:47Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Antonio Dantas"
  - literal: "Elcio Shiguemori"
  - literal: "Antonio Chaves"
issued:
  date-parts:
    - [2026, 11, 9]

# Domain-specific custom fields
paper_id: "2611.12317"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "random-key-optimizers"
    description: "An optimization framework used here for routing Unmanned Aerial Vehicles under stochastic constraints."
datasets:
  []
open_questions:
  - name: "bayesian-belief-updates-and-kinematic-constraints-in-uav-sar"
    description: "Extend the current route-planning framework by incorporating Bayesian belief updates of target probabilities after each empty observation, relaxing the assumption of certain detection in visited cells, and replacing simplified two-dimensional obstacle-free corridors with more realistic kinematic and environmental constraints for practical field deployment."
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:48:47Z"
created_at: "2026-11-20T13:48:47Z"
---

# Maximizing Detection Probability in UAV Search Missions using Random-Key Optimizers

**Authors**: Antonio Dantas, Elcio Shiguemori, Antonio Chaves
**Date**: 2026-11-09
**Paper ID**: [openalex:2611.12317](https://arxiv.org/abs/2611.12317)

## Summary

This paper addresses stochastic and real-time path planning for Unmanned Aerial Vehicles (UAVs) in Search and Rescue (SAR) operations by combining closed-loop probability updates with Random-Key Optimizers (RKO). The problem is formulated as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP), enabling adaptive balancing between probability maximization and resource minimization. Computational results demonstrate scalability and effectiveness, while highlighting that systematic prior biases degrade performance more severely than complete lack of prior information.

## Key Contributions

- Introduces a configurable data-driven routing architecture combining closed-loop probability updates with Random-Key Optimizers (RKO) for UAV search and rescue missions.
- Formulates the problem as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP) balancing probability maximization and resource minimization.
- Demonstrates that systematic map biases degrade performance twice as severely as having no prior information at all.

## Limitations

The framework degrades under systematically biased priors, performing worse than having no prior information.

## Open Questions & Future Work

- [[bayesian-belief-updates-and-kinematic-constraints-in-uav-sar]]

## Key Concepts

- [[random-key-optimizers]]: An optimization framework used here for routing Unmanned Aerial Vehicles under stochastic constraints.

## Archivist Review

Approved the random-key optimizers concept as a reusable stochastic routing framework and the open question regarding Bayesian belief updates and kinematic constraints for UAV SAR. No standalone datasets were provided in the paper text.

### Approved Concepts
- Random-Key Optimizers: Central architectural optimizer for UAV routing under stochastic constraints.

### Approved Open Questions
- Bayesian Updates and Kinematic Constraints: Crucial for bridging the gap between simplified heuristic simulations and real-world UAV deployment where sensor uncertainty, false negatives, and dynamic environment states heavily influence search effectiveness.

## Links

- [Abstract](https://arxiv.org/abs/2611.12317)
- [PDF](https://arxiv.org/pdf/2611.12317)

