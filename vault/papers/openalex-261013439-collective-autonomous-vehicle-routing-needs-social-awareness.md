---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning, showing that purely selfish routing creates negative externalities for human-driven vehicles (HDVs). To resolve this, the authors introduce a social reward component termed 'marginal cost', which captures an AV's impact on other road users via counterfactual simulation. Experiments on the Ingolstadt and Provins networks demonstrate that social AV routing decreases HDV travel time delays, shortens AV travel times, and improves overall system performance. Furthermore, computing marginal costs selectively for high-impact AVs achieves near-identical performance at significantly reduced computational cost."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "multi-agent-reinforcement-learning"
  - "mixed-autonomy-traffic"
timestamp: "2026-10-21T09:47:41Z"

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
    description: "A multi-agent reinforcement learning approach for autonomous vehicle routing that incorporates social marginal cost rewards to mitigate externalities on human drivers."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-21T09:47:41Z"
created_at: "2026-10-21T09:47:41Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning, showing that purely selfish routing creates negative externalities for human-driven vehicles (HDVs). To resolve this, the authors introduce a social reward component termed 'marginal cost', which captures an AV's impact on other road users via counterfactual simulation. Experiments on the Ingolstadt and Provins networks demonstrate that social AV routing decreases HDV travel time delays, shortens AV travel times, and improves overall system performance. Furthermore, computing marginal costs selectively for high-impact AVs achieves near-identical performance at significantly reduced computational cost.

## Key Contributions

- Introduces a social reward component based on marginal cost to capture an autonomous vehicle's impact on human-driven vehicles in mixed-autonomy traffic networks.
- Demonstrates via Multi-Agent Reinforcement Learning (MARL) on Ingolstadt and Provins networks that social AV routing reduces HDV travel time penalties while surprisingly also benefiting AV travel times.
- Proposes a scalable approximation strategy that computes marginal costs only for AVs whose route choices most affect the traffic system, significantly lowering computational overhead.

## Limitations

Extremely high weights on the social component in the AV reward function lead to failure in reaching desired system performance.

## Key Concepts

- [[social-av-routing]]: A multi-agent reinforcement learning approach for autonomous vehicle routing that incorporates social marginal cost rewards to mitigate externalities on human drivers.

## Archivist Review

Approved 'social-av-routing' as an existing vault concept, but rejected the proposed open question as it is tied specifically to the paper's counterfactual computational efficiency rather than a general open bottleneck.

### Approved Concepts
- Social AV Routing: Introduces a social reward component with marginal cost to balance AV and human-driven vehicle travel times in mixed-autonomy traffic.

### Rejected Candidates
- [open_question] Scalable Social AV Routing (`scalable-social-av-routing`) - paper_local: This is a paper-local performance and computational scaling question specific to counterfactual simulations in mixed-autonomy traffic rather than a broad foundational research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

