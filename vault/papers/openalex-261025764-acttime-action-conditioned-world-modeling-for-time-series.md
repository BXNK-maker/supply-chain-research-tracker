---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model designed to predict how time-series outcomes change under different candidate actions from the same observed history. Trained exclusively on factual trajectories without paired counterfactuals, ActTime updates variable-specific latent states via action-conditioned transitions and observation corrections before rolling forward for planning. Through a simulator-grounded evaluation across building energy, traffic, greenhouse climate, and inventory management, the authors demonstrate that ActTime ranks first in 12 of 16 settings and establish that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "dynamic-pricing"
  - "fleet-scheduling"
timestamp: "2026-10-22T09:49:25Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xinxing Zhou"
  - literal: "Xiaojie Yuan"
  - literal: "Yanlong Wen"
  - literal: "Ming Jin"
issued:
  date-parts:
    - [2026, 10, 19]

# Domain-specific custom fields
paper_id: "2610.25764"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "acttime"
    description: "An action-conditioned world model for time series that predicts outcomes under different candidate actions from the same observed history."
datasets:
  []
open_questions:
  - name: "out-of-distribution-action-extrapolation-and-adaptation"
    description: "Investigate the extrapolation capabilities of action-conditioned world models under out-of-distribution action regimes and develop techniques to adapt system dynamics using limited new interaction data while robustly handling distribution shifts and unobserved confounding."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:25Z"
created_at: "2026-10-22T09:49:25Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model designed to predict how time-series outcomes change under different candidate actions from the same observed history. Trained exclusively on factual trajectories without paired counterfactuals, ActTime updates variable-specific latent states via action-conditioned transitions and observation corrections before rolling forward for planning. Through a simulator-grounded evaluation across building energy, traffic, greenhouse climate, and inventory management, the authors demonstrate that ActTime ranks first in 12 of 16 settings and establish that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates latent states through action-conditioned transitions and observation corrections.
- Proposes a training framework using solely factual trajectories without requiring paired alternative-action outcomes or planning supervision.
- Establishes a simulator-grounded evaluation suite covering building energy, traffic, greenhouse climate, and inventory management across factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Demonstrates that ActTime ranks first in 12 of 16 domain-task settings and proves that factual accuracy, intervention fidelity, and decision quality are distinct capabilities with high ranking reversal rates.

## Limitations

The paper evaluates on simulated environments and four specific domains; scaling to complex unconstrained real-world systems remains an open challenge.

## Open Questions & Future Work

- [[out-of-distribution-action-extrapolation-and-adaptation]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different candidate actions from the same observed history.

## Archivist Review

Approved the core concept ActTime representing the proposed action-conditioned time-series world model, along with a significant open question on out-of-distribution action extrapolation. Rejected redundant general terms in accordance with vault standards.

### Approved Concepts
- ActTime: ActTime is the primary methodological contribution of the paper, serving as a novel action-conditioned world model for time series forecasting and planning.

### Approved Open Questions
- Out-of-Distribution Action Extrapolation: Crucial for deploying world models safely in real-world controlled environments where unexpected or extreme actions might be evaluated or requested.

### Rejected Candidates
- [concept] Action-Conditioned World Model (`action-conditioned-world-model`) - subcomponent_of_broader_mechanism: Subsumed by the ActTime concept which is more specific to the paper's primary contribution.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

