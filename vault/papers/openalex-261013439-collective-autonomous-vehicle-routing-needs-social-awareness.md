---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates how collective autonomous vehicle (AV) route choices impact human-driven vehicles (HDVs) in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning (MARL). The authors introduce a social reward component—marginal cost—computed via counterfactual simulations to account for an AV's externality on other road users. Experiments on the real-world networks of Ingolstadt and Provins demonstrate that social AV routing reduces HDV travel time impacts and improves overall system performance, benefiting both human drivers and AVs alike. Furthermore, a selective evaluation of marginal costs for high-impact AVs achieves similar performance at a significantly lower computational cost."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "choice-modeling"
  - "multi-omics"
  - "vehicle-routing-problem"
  - "mixed-autonomy-traffic"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-17T08:58:02Z"

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
  - name: "socially-aware-autonomous-vehicle-routing"
    description: "A multi-agent reinforcement learning reward formulation that incorporates marginal cost externalities on human drivers into autonomous vehicle routing policies."
datasets:
  []
open_questions:
  - name: "socially-aware-av-routing-mixed-autonomy"
    description: "Investigate scalable multi-agent reinforcement learning reward shaping mechanisms and socially-aware coordination strategies that mitigate negative traffic externalities on human drivers without excessively degrading autonomous vehicle travel times or requiring computationally expensive counterfactual simulations across entire transportation networks."
skill: "GeneralMLSkill"
processed_at: "2026-10-17T08:58:02Z"
created_at: "2026-10-17T08:58:02Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates how collective autonomous vehicle (AV) route choices impact human-driven vehicles (HDVs) in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning (MARL). The authors introduce a social reward component—marginal cost—computed via counterfactual simulations to account for an AV's externality on other road users. Experiments on the real-world networks of Ingolstadt and Provins demonstrate that social AV routing reduces HDV travel time impacts and improves overall system performance, benefiting both human drivers and AVs alike. Furthermore, a selective evaluation of marginal costs for high-impact AVs achieves similar performance at a significantly lower computational cost.

## Key Contributions

- Introduces a socially-aware reward function incorporating marginal cost into Multi-Agent Reinforcement Learning (MARL) for autonomous vehicle routing to mitigate negative externalities on human drivers.
- Demonstrates on the Ingolstadt and Provins networks that social AV routing reduces human-driven vehicle travel time overhead (dropping from 1.7% to 1.1% at 40% penetration) while paradoxically also improving AV travel times.
- Proposes a scalable approximation strategy by computing counterfactual marginal costs only for AVs whose route choices most impact the traffic system.

## Limitations

Excessive weighting of the social component in the reward function causes the system to fail to reach desired performance levels.

## Open Questions & Future Work

- [[socially-aware-av-routing-mixed-autonomy]]

## Key Concepts

- [[socially-aware-autonomous-vehicle-routing]]: A multi-agent reinforcement learning reward formulation that incorporates marginal cost externalities on human drivers into autonomous vehicle routing policies.

## Archivist Review

Approved the overarching concept of socially-aware autonomous vehicle routing and its corresponding open question regarding scalable mixed-autonomy coordination. Rejected the specific marginal cost reward as a subcomponent of the broader mechanism. No specific datasets met the strict criteria for standalone archival notes.

### Approved Concepts
- Socially-Aware Autonomous Vehicle Routing: Provides a novel MARL reward formulation incorporating marginal cost externalities for mixed-autonomy traffic routing.

### Approved Open Questions
- Socially-Aware Autonomous Vehicle Routing: Addressing traffic externalities between autonomous and human-driven vehicles is crucial for the deployment of mixed-autonomy routing algorithms in real-world urban infrastructure.

### Rejected Candidates
- [concept] Marginal Cost Reward (`marginal-cost-reward`) - subcomponent_of_broader_mechanism: Subcomponent of the broader socially-aware autonomous vehicle routing framework.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

