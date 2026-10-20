---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic and demonstrates that purely selfish routing creates negative travel-time externalities for human-driven vehicles (HDVs). To mitigate this, the authors propose a socially-aware reward function that incorporates a marginal cost computed via counterfactual simulations. Evaluated using multi-agent reinforcement learning (MARL) on the real-world networks of Ingolstadt and Provins, the proposed method reduces HDV travel time increases, improves overall system performance, and paradoxically benefits the AVs themselves. Furthermore, a targeted selection heuristic reduces computational complexity by computing marginal costs only for high-impact AVs."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "multi-agent-reinforcement-learning"
  - "mixed-autonomy-traffic"
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:47:05Z"

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
    description: "A routing framework for collective autonomous vehicles that integrates a social marginal cost reward via counterfactual simulations to optimize mixed-autonomy traffic systems."
datasets:
  - name: "Ingolstadt"
    description: "Real-world traffic network of Ingolstadt used to evaluate mixed-autonomy vehicle routing and social rewards."
  - name: "Provins"
    description: "Real-world traffic network of Provins used for evaluating scalable social AV routing."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-20T09:47:05Z"
created_at: "2026-10-20T09:47:05Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic and demonstrates that purely selfish routing creates negative travel-time externalities for human-driven vehicles (HDVs). To mitigate this, the authors propose a socially-aware reward function that incorporates a marginal cost computed via counterfactual simulations. Evaluated using multi-agent reinforcement learning (MARL) on the real-world networks of Ingolstadt and Provins, the proposed method reduces HDV travel time increases, improves overall system performance, and paradoxically benefits the AVs themselves. Furthermore, a targeted selection heuristic reduces computational complexity by computing marginal costs only for high-impact AVs.

## Key Contributions

- Introduces a social marginal cost component to AV rewards computed via counterfactual simulation to account for externalities on human-driven vehicles (HDVs).
- Demonstrates using multi-agent reinforcement learning (MARL) on real-world networks (Ingolstadt and Provins) that social AV routing reduces HDV travel time increases and surprisingly shortens AV travel times compared to purely selfish routing.
- Proposes a scalable approximation that computes marginal costs only for AVs whose route choices most affect the traffic system, significantly reducing computational overhead.

## Limitations

The system performance fails to reach desired levels when the weight of the social component in the reward is set too high.

## Key Concepts

- [[social-av-routing]]: A routing framework for collective autonomous vehicles that integrates a social marginal cost reward via counterfactual simulations to optimize mixed-autonomy traffic systems.

## Archivist Review

Approved the core concept 'social-av-routing' by reusing the existing vault slug to avoid duplication, and approved Ingolstadt and Provins datasets as specific named traffic networks central to the paper's evaluation. The open question candidate was rejected because it duplicates the existing vault entry 'socially-aware-av-routing'.

### Approved Concepts
- Socially-Aware Autonomous Vehicle Routing: Introduces a novel social reward component (marginal cost via counterfactual simulation) to collective AV routing in mixed-autonomy traffic to prevent negative externalities on human drivers.

### Rejected Candidates
- [open_question] Socially-Aware Autonomous Vehicle Routing (`social-av-routing-objectives`) - duplicate_existing: Duplicates the existing vault question 'socially-aware-av-routing' which covers the exact same research direction on balancing AV rewards and human travel externalities.

## Datasets

- [[Ingolstadt]]
- [[Provins]]

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

