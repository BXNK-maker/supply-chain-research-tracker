---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates how collective autonomous vehicle (AV) routing in mixed-autonomy traffic impacts human-driven vehicles (HDVs) and proposes incorporating a social marginal cost component into AV rewards via multi-agent reinforcement learning. By using counterfactual simulations to capture an AV's externality on other road users, the proposed method reduces HDV travel time increases and paradoxically improves AV travel times compared to purely selfish routing. Furthermore, a selective computation scheme focusing only on high-impact AVs scales the approach efficiently across real-world road networks like Ingolstadt and Provins."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "multi-agent-reinforcement-learning"
  - "mixed-autonomy-traffic"
  - "fleet-scheduling"
timestamp: "2026-10-19T10:27:40Z"

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
    description: "A routing reward mechanism for autonomous vehicles that incorporates marginal costs via counterfactual simulations to account for externalities imposed on human drivers."
datasets:
  []
open_questions:
  - name: "socially-aware-av-routing"
    description: "Investigate how autonomous vehicle routing Multi-Agent Reinforcement Learning (MARL) algorithms can be systematically designed to reduce individual travel times while strictly limiting additional travel time costs or externalities imposed on human drivers and other road users sharing public infrastructure."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T10:27:40Z"
created_at: "2026-10-19T10:27:40Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates how collective autonomous vehicle (AV) routing in mixed-autonomy traffic impacts human-driven vehicles (HDVs) and proposes incorporating a social marginal cost component into AV rewards via multi-agent reinforcement learning. By using counterfactual simulations to capture an AV's externality on other road users, the proposed method reduces HDV travel time increases and paradoxically improves AV travel times compared to purely selfish routing. Furthermore, a selective computation scheme focusing only on high-impact AVs scales the approach efficiently across real-world road networks like Ingolstadt and Provins.

## Key Contributions

- Introduces a social routing reward for autonomous vehicles that incorporates a marginal cost computed via counterfactual simulations to capture externalities on human-driven vehicles.
- Demonstrates via multi-agent reinforcement learning experiments on Ingolstadt and Provins networks that social AV routing reduces human-driven vehicle travel times while simultaneously benefiting autonomous vehicles.
- Proposes a scalable approximation that computes marginal costs only for AVs with the highest impact on traffic, significantly reducing computational overhead without sacrificing performance.

## Limitations

Excessive weighting of the social component in the reward function causes the system to fail to reach desired performance levels.

## Open Questions & Future Work

- [[socially-aware-av-routing]]

## Key Concepts

- [[social-av-routing]]: A routing reward mechanism for autonomous vehicles that incorporates marginal costs via counterfactual simulations to account for externalities imposed on human drivers.

## Archivist Review

Approved the concept of social AV routing and its corresponding open question, as they represent a clear contribution and unresolved research direction in mixed-autonomy traffic management. Datasets representing specific city road networks were rejected as they are local simulation scenarios.

### Approved Concepts
- Social AV Routing: Introduces a novel social reward formulation using marginal cost computed via counterfactual simulations to internalize external costs imposed by autonomous vehicles on human-driven vehicles.

### Approved Open Questions
- Socially Aware AV Routing: Crucial for ensuring equitable and socially responsible coexistence between autonomous and human-driven vehicles in urban public infrastructure without degrading human commuting efficiency.

### Rejected Candidates
- [dataset] Ingolstadt Network (`ingolstadt-network`) - paper_local: Specific real-world city road network graphs used locally for simulation and evaluation rather than standard global benchmarks.
- [dataset] Provins Network (`provins-network`) - paper_local: Specific real-world city road network graphs used locally for simulation and evaluation rather than standard global benchmarks.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

