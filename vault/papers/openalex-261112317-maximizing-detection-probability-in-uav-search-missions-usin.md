---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Maximizing Detection Probability in UAV Search Missions using Random-Key Optimizers"
description: "This paper addresses stochastic and real-time UAV path planning for Search and Rescue (SAR) missions by modeling the problem as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP). The authors propose a configurable architecture that pairs a closed-loop probability update mechanism with Random-Key Optimizers to balance probability maximization and resource minimization. Computational evaluations demonstrate that the approach is scalable and competitive for multi-objective routing in unstable environments, though it remains vulnerable to systematically biased prior maps."
resource: "https://arxiv.org/abs/2611.12317"
tags:
  - "vehicle-routing-problem"
  - "robotics"
  - "stochastic-demands"
  - "reinforcement-learning"
timestamp: "2026-11-19T14:11:58Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:11:58Z"
created_at: "2026-11-19T14:11:58Z"
---

# Maximizing Detection Probability in UAV Search Missions using Random-Key Optimizers

**Authors**: Antonio Dantas, Elcio Shiguemori, Antonio Chaves
**Date**: 2026-11-09
**Paper ID**: [openalex:2611.12317](https://arxiv.org/abs/2611.12317)

## Summary

This paper addresses stochastic and real-time UAV path planning for Search and Rescue (SAR) missions by modeling the problem as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP). The authors propose a configurable architecture that pairs a closed-loop probability update mechanism with Random-Key Optimizers to balance probability maximization and resource minimization. Computational evaluations demonstrate that the approach is scalable and competitive for multi-objective routing in unstable environments, though it remains vulnerable to systematically biased prior maps.

## Key Contributions

- Introduces a data-driven routing architecture combining closed-loop probability updates with Random-Key Optimizers (RKO) for UAV Search and Rescue (SAR) missions.
- Formulates the path planning task as a dynamic probabilistic variant of the Open Vehicle Routing Problem (OVRP) with adaptive multi-objective switching.
- Demonstrates that the proposed scheme is scalable and competitive with single-path scenarios while revealing failure modes under systematically biased prior maps.

## Limitations

The framework degrades severely under systematically biased prior maps, performing about half as well as flying with no prior at all.

## Archivist Review

The paper discusses Random-Key Optimizers for UAV path planning, but random-key encoding is a standard established metaheuristic technique rather than a novel vault-worthy primitive. No other candidates were provided, so no items are approved.

### Rejected Candidates
- [concept] Random-Key Optimizers (`random-key-optimizers`) - not_novel: Random-key genetic algorithms are a long-standing established metaheuristic technique rather than a novel machine learning primitive introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2611.12317)
- [PDF](https://arxiv.org/pdf/2611.12317)

