---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic using multi-agent reinforcement learning, addressing the negative externalities that selfish AV routing imposes on human-driven vehicles. By incorporating a social marginal cost component—computed via counterfactual simulations—into the AV reward function, the authors demonstrate on real-world networks in Ingolstadt and Provins that social routing reduces human travel times, improves overall system performance, and surprisingly benefits the AVs themselves. Furthermore, a selective computation approach reduces the computational cost of counterfactual simulations by targeting only the most influential AVs."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "choice-modeling"
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-15T09:33:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Anastasia Psarou"
  - literal: "Mikołaj Rams"
  - literal: "Blazej Torbus"
  - literal: "Rafał Kucharski"
issued:
  date-parts:
    - [2026, 10, 9]

# Domain-specific custom fields
paper_id: "2610.13439"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "social-av-routing"
    description: "A routing reward mechanism for autonomous vehicles that incorporates the marginal travel time impact on human drivers using counterfactual simulations."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:33:52Z"
created_at: "2026-10-15T09:33:52Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic using multi-agent reinforcement learning, addressing the negative externalities that selfish AV routing imposes on human-driven vehicles. By incorporating a social marginal cost component—computed via counterfactual simulations—into the AV reward function, the authors demonstrate on real-world networks in Ingolstadt and Provins that social routing reduces human travel times, improves overall system performance, and surprisingly benefits the AVs themselves. Furthermore, a selective computation approach reduces the computational cost of counterfactual simulations by targeting only the most influential AVs.

## Key Contributions

- Introduces a social marginal cost component into multi-agent reinforcement learning for autonomous vehicle routing to account for externalities on human-driven vehicles.
- Demonstrates on real-world networks (Ingolstadt and Provins) that social AV routing reduces human-driven vehicle travel time penalties and paradoxically improves AV travel times relative to purely selfish routing.
- Develops a selective counterfactual simulation approach that computes marginal costs only for impactful AVs, significantly lowering computational overhead while preserving performance.

## Limitations

Excessively high weights on the social reward component can prevent the system from reaching desired performance levels.

## Key Concepts

- [[social-av-routing]]: A routing reward mechanism for autonomous vehicles that incorporates the marginal travel time impact on human drivers using counterfactual simulations.

## Archivist Review

Approved the core concept 'Social AV Routing' because it represents a clear, reusable methodology for mixed-autonomy traffic routing using multi-agent reinforcement learning. No datasets met the strict threshold for standalone vault notes.

### Approved Concepts
- Social AV Routing: Introduces a novel social component (marginal cost) into multi-agent reinforcement learning reward functions for autonomous vehicle routing to internalize externalities on human drivers.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

