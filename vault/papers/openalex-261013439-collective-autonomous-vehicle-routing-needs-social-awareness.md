---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic using Multi-Agent Reinforcement Learning and demonstrates that purely selfish AV routing creates negative externalities for human-driven vehicles (HDVs). To resolve this, the authors propose incorporating a social component—marginal cost measured via counterfactual simulation—into the AV reward function. Experiments on the Ingolstadt and Provins road networks show that this social reward limits HDV travel time increases, improves overall system performance, and surprisingly benefits the AVs themselves. Furthermore, a selective computation scheme for marginal costs significantly reduces the computational overhead of counterfactual simulations while maintaining competitive performance."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "mixed-autonomy-traffic"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-18T09:17:27Z"

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
  - name: "social-autonomous-vehicle-routing"
    description: "A multi-agent reinforcement learning approach for autonomous vehicle routing that incorporates a social marginal-cost reward component to mitigate negative externalities on human drivers."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:17:27Z"
created_at: "2026-10-18T09:17:27Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic using Multi-Agent Reinforcement Learning and demonstrates that purely selfish AV routing creates negative externalities for human-driven vehicles (HDVs). To resolve this, the authors propose incorporating a social component—marginal cost measured via counterfactual simulation—into the AV reward function. Experiments on the Ingolstadt and Provins road networks show that this social reward limits HDV travel time increases, improves overall system performance, and surprisingly benefits the AVs themselves. Furthermore, a selective computation scheme for marginal costs significantly reduces the computational overhead of counterfactual simulations while maintaining competitive performance.

## Key Contributions

- Introduces a social reward component based on marginal cost—computed via counterfactual simulation—to internalize the externalities autonomous vehicles (AVs) impose on human-driven vehicles (HDVs).
- Demonstrates via Multi-Agent Reinforcement Learning (MARL) on Ingolstadt and Provins networks that social AV routing reduces HDV travel time increases (e.g., dropping from 1.7% to 1.1% at 40% penetration) while paradoxically improving AV travel times.
- Proposes a scalable approximation strategy by computing marginal costs selectively for AVs whose route choices most impact the traffic system, significantly reducing counterfactual simulation overhead.

## Limitations

The system performance is sensitive to the weight assigned to the social component in the reward function, failing to reach desired performance if the weight is set too high.

## Key Concepts

- [[social-autonomous-vehicle-routing]]: A multi-agent reinforcement learning approach for autonomous vehicle routing that incorporates a social marginal-cost reward component to mitigate negative externalities on human drivers.

## Archivist Review

Approved the core reusable concept of social autonomous vehicle routing and its marginal-cost reward formulation. The open question was rejected because an existing vault entry already covers socially-aware autonomous vehicle routing.

### Approved Concepts
- Social Autonomous Vehicle Routing: Introduces a novel social reward formulation using marginal cost computed via counterfactual simulation to mitigate negative externalities of autonomous vehicles on human-driven vehicles.

### Rejected Candidates
- [open_question] Socially-Aware Autonomous Vehicle Routing (`social-awareness-av-routing-mar-objectives`) - duplicate_existing: This open question is near-duplicate or closely overlaps with existing vault entries on socially-aware autonomous vehicle routing.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

