---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates how collective autonomous vehicle (AV) routing in mixed-autonomy traffic impacts human-driven vehicles (HDVs) and proposes incorporating a marginal-cost social reward into multi-agent reinforcement learning (MARL) policies. By evaluating AV impact through counterfactual simulations where specific AVs are removed, the proposed social routing approach reduces negative externalities on HDVs while unexpectedly improving AV travel times. Furthermore, a scalable selective computation strategy limits counterfactual simulations to influential AVs, maintaining high performance at a lower computational cost across the Ingolstadt and Provins road networks."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "mixed-autonomy-traffic"
  - "multi-agent-reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-23T09:44:55Z"

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
    description: "An autonomous vehicle routing framework using a marginal-cost social reward computed via counterfactual simulation to balance selfish travel time minimization with impact on human drivers."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:44:55Z"
created_at: "2026-10-23T09:44:55Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates how collective autonomous vehicle (AV) routing in mixed-autonomy traffic impacts human-driven vehicles (HDVs) and proposes incorporating a marginal-cost social reward into multi-agent reinforcement learning (MARL) policies. By evaluating AV impact through counterfactual simulations where specific AVs are removed, the proposed social routing approach reduces negative externalities on HDVs while unexpectedly improving AV travel times. Furthermore, a scalable selective computation strategy limits counterfactual simulations to influential AVs, maintaining high performance at a lower computational cost across the Ingolstadt and Provins road networks.

## Key Contributions

- Introduces a social component (marginal cost) to AV reward functions in MARL routing to capture and mitigate negative externalities on human-driven vehicles (HDVs).
- Demonstrates on Ingolstadt and Provins networks that social AV routing decreases HDV travel time increases (e.g., dropping from 1.7% to 1.1% at 40% AV penetration) while simultaneously shortening AV travel times.
- Proposes a scalable approximation that computes marginal costs only for AVs whose route choices most impact the traffic system, significantly reducing counterfactual simulation overhead without sacrificing performance.

## Limitations

Excessive weighting of the social component in the reward function causes the system to fail to reach desired performance levels.

## Key Concepts

- [[social-av-routing]]: An autonomous vehicle routing framework using a marginal-cost social reward computed via counterfactual simulation to balance selfish travel time minimization with impact on human drivers.

## Archivist Review

Approved the core concept 'Social AV Routing' since it already exists in the vault and captures the paper's principal methodological contribution. The open question was rejected as redundant with the existing concept and vault scope.

### Approved Concepts
- Social AV Routing: Introduces a novel social reward formulation using marginal cost computed via counterfactual simulation to mitigate negative externalities of autonomous vehicles on human-driven vehicles.

### Rejected Candidates
- [open_question] Socially Aware AV Routing Objectives (`socially-aware-av-routing-objectives`) - duplicate_existing: Overlaps heavily with the core themes of the approved concept and is largely addressed by the paper's selective marginal cost mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

