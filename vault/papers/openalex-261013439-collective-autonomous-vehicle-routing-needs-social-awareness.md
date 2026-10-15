---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers"
description: "This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning, highlighting how selfish routing negatively impacts human-driven vehicles (HDVs). The authors introduce a social marginal cost component to the AV reward function—computed via counterfactual simulations—to account for an AV's impact on other road users. Experiments on the Ingolstadt and Provins networks demonstrate that incorporating this social reward reduces HDV travel time increases, improves overall system efficiency, and paradoxically yields better travel times for the AVs themselves. Furthermore, a scalable selective computation approach is introduced to compute marginal costs only for high-impact AVs, reducing computational complexity."
resource: "https://arxiv.org/abs/2610.13439"
tags:
  - "machine-learning"
timestamp: "2026-10-15T04:43:59Z"

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
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:43:59Z"
created_at: "2026-10-15T04:43:59Z"
---

# Collective Autonomous Vehicle Routing Needs Social Awareness for Coexistence with Human Drivers

**Authors**: Anastasia Psarou, Mikołaj Rams, Blazej Torbus, Rafał Kucharski
**Date**: 2026-10-09
**Paper ID**: [openalex:2610.13439](https://arxiv.org/abs/2610.13439)

## Summary

This paper investigates collective autonomous vehicle (AV) routing in mixed-autonomy traffic networks using Multi-Agent Reinforcement Learning, highlighting how selfish routing negatively impacts human-driven vehicles (HDVs). The authors introduce a social marginal cost component to the AV reward function—computed via counterfactual simulations—to account for an AV's impact on other road users. Experiments on the Ingolstadt and Provins networks demonstrate that incorporating this social reward reduces HDV travel time increases, improves overall system efficiency, and paradoxically yields better travel times for the AVs themselves. Furthermore, a scalable selective computation approach is introduced to compute marginal costs only for high-impact AVs, reducing computational complexity.

## Key Contributions

- Introduces a social component (marginal cost) to AV reward functions in MARL mixed-autonomy routing, capturing an AV's impact on human-driven vehicles via counterfactual simulations.
- Demonstrates on real-world networks (Ingolstadt and Provins) that social reward incorporation reduces HDV travel time externalities, improves overall system performance, and unexpectedly benefits AV travel times relative to selfish routing.
- Proposes a scalable selective computation strategy that calculates marginal costs only for AVs whose route choices most impact the system, reducing computational overhead while maintaining performance.

## Limitations

Excessive weight assigned to the social component in the reward function causes the system to fail to reach desired performance levels.

## Archivist Review

Reviewed the candidates from the paper analysis. The open question regarding socially aware autonomous vehicle routing is specific to a specialized application domain (traffic routing) rather than a foundational ML bottleneck. Therefore, no concepts, datasets, or open questions were approved for the permanent vault.

### Rejected Candidates
- [open_question] Socially Aware Autonomous Vehicle Routing (`socially-aware-av-routing-objectives`) - low_impact: The proposed question is overly narrow and specific to mixed-autonomy vehicle routing rather than representing a broad, foundational bottleneck in machine learning generalization or optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.13439)
- [PDF](https://arxiv.org/pdf/2610.13439)

