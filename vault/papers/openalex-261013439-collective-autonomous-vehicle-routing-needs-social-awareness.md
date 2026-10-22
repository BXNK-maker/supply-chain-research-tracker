---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic and demonstrates that selfish routing creates negative externalities for human-driven vehicles. To resolve this, the authors introduce a social reward component via marginal cost—measured through counterfactual simulations—within a multi-agent reinforcement learning framework. Experiments across the real-world networks of Ingolstadt and Provins show that incorporating this social component reduces human-driven vehicle travel time increases while unexpectedly shortening AV travel times as well. Furthermore, a scalable variant that computes marginal costs selectively for high-impact AVs achieves comparable performance with lower computational overhead."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "mixed-autonomy-traffic"
  - "multi-agent-reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-22T09:48:52Z"

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
    description: "A routing approach for autonomous vehicles that incorporates a social marginal-cost component into multi-agent reinforcement learning rewards to mitigate externalities on human drivers."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:48:52Z"
created_at: "2026-10-22T09:48:52Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic and demonstrates that selfish routing creates negative externalities for human-driven vehicles. To resolve this, the authors introduce a social reward component via marginal cost—measured through counterfactual simulations—within a multi-agent reinforcement learning framework. Experiments across the real-world networks of Ingolstadt and Provins show that incorporating this social component reduces human-driven vehicle travel time increases while unexpectedly shortening AV travel times as well. Furthermore, a scalable variant that computes marginal costs selectively for high-impact AVs achieves comparable performance with lower computational overhead.

## Key Contributions

- Introduces a social reward component based on marginal cost for multi-agent reinforcement learning autonomous vehicle routing to capture externalities on human-driven vehicles.
- Demonstrates on Ingolstadt and Provins networks that social AV routing decreases human-driven vehicle travel time penalties while simultaneously improving AV travel times compared to purely selfish routing.
- Proposes a scalable approximation that computes marginal costs only for AVs with the highest impact on the traffic system, reducing counterfactual simulation overhead.

## Limitations

Excessive weighting of the social component in the reward function causes the system to fail to reach desired performance levels.

## Key Concepts

- [[social-av-routing]]: A routing approach for autonomous vehicles that incorporates a social marginal-cost component into multi-agent reinforcement learning rewards to mitigate externalities on human drivers.

## Archivist Review

Approved the concept 'social-av-routing' as it represents a distinct and reusable MARL reward formulation for mixed-autonomy traffic coordination. The open question was rejected because it mirrors the core concept and does not expose a separate technical bottleneck. No datasets were approved since Ingolstadt and Provins are standard traffic network simulation topologies rather than standalone machine learning datasets.

### Approved Concepts
- Social AV Routing: Introduces a social reward component with marginal cost to coordinate autonomous vehicles in mixed-autonomy traffic, avoiding negative externalities on human drivers.

### Rejected Candidates
- [open_question] Socially-Aware Autonomous Vehicle Routing (`scalable-social-av-routing-objectives`) - duplicate_existing: Redundant with the approved concept of social AV routing and lacks a specific technical bottleneck or unresolved formulation beyond the proposed MARL reward approach.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

