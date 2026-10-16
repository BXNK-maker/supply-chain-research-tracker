---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning (MARL), demonstrating that purely selfish routing creates negative externalities for human drivers. To address this, the authors introduce a social reward component based on marginal cost—computed via counterfactual simulations where an AV is removed—to capture and mitigate an AV's impact on other road users. Experiments on the real-world networks of Ingolstadt and Provins show that social routing reduces AV travel times, limits human-driven vehicle delays, and improves overall system performance, with selective marginal cost computation offering a scalable computational shortcut."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "machine-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-16T09:28:42Z"

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
    description: "A routing framework for autonomous vehicles that incorporates the marginal cost of externalities on human drivers into reinforcement learning rewards."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:28:42Z"
created_at: "2026-10-16T09:28:42Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning (MARL), demonstrating that purely selfish routing creates negative externalities for human drivers. To address this, the authors introduce a social reward component based on marginal cost—computed via counterfactual simulations where an AV is removed—to capture and mitigate an AV's impact on other road users. Experiments on the real-world networks of Ingolstadt and Provins show that social routing reduces AV travel times, limits human-driven vehicle delays, and improves overall system performance, with selective marginal cost computation offering a scalable computational shortcut.

## Key Contributions

- Introduces a social routing reward incorporating marginal cost to account for autonomous vehicle externalities on human drivers in mixed-autonomy traffic.
- Demonstrates via multi-agent reinforcement learning on Ingolstadt and Provins networks that social routing shortens AV travel times while mitigating travel time increases for human drivers.
- Proposes a scalable approximation by computing marginal costs only for high-impact AVs to reduce counterfactual simulation overhead.

## Limitations

High social weight in the reward can cause the system to fail to reach desired performance, and full marginal cost computation requires expensive counterfactual simulations.

## Key Concepts

- [[social-av-routing]]: A routing framework for autonomous vehicles that incorporates the marginal cost of externalities on human drivers into reinforcement learning rewards.

## Archivist Review

We approved the core concept of social autonomous vehicle routing, reusing the existing vault slug 'social-av-routing' since it aligns with the existing entry. The subcomponent candidate 'marginal-cost-reward' was correctly rejected as a subcomponent of this broader routing framework. No datasets or open questions met the strict standalone criteria.

### Approved Concepts
- Social Autonomous Vehicle Routing: Introduces a paradigm shift from purely selfish routing optimization in AVs to socially aware routing that accounts for externalities on human-driven vehicles.

### Rejected Candidates
- [concept] Marginal Cost Reward (`marginal-cost-reward`) - subcomponent_of_broader_mechanism: Subcomponent of broader social autonomous vehicle routing mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

