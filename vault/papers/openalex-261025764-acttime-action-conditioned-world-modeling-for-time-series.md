---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model for time series designed to predict future outcomes under different intervention actions from observed histories. Trained exclusively on factual trajectories without paired counterfactuals, ActTime maintains variable-specific latent states via action-conditioned transitions and observation corrections. Evaluated across building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across diverse tasks including factual prediction, intervention fidelity, and closed-loop planning. Furthermore, empirical findings demonstrate that factual accuracy, intervention fidelity, and decision quality are distinct metrics that frequently exhibit model-ranking reversals."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-10-29T11:15:24Z"

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
    description: "An action-conditioned world model for time series that predicts how outcomes change under different actions using factual training trajectories."
datasets:
  []
open_questions:
  - name: "distribution-shift-action-extrapolation"
    description: "Characterize uncertainty under substantial distribution shifts in action regimes that are unsupported by the training data, and adapt the learned dynamics with limited new interaction."
skill: "GeneralMLSkill"
processed_at: "2026-10-29T11:15:24Z"
created_at: "2026-10-29T11:15:24Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model for time series designed to predict future outcomes under different intervention actions from observed histories. Trained exclusively on factual trajectories without paired counterfactuals, ActTime maintains variable-specific latent states via action-conditioned transitions and observation corrections. Evaluated across building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across diverse tasks including factual prediction, intervention fidelity, and closed-loop planning. Furthermore, empirical findings demonstrate that factual accuracy, intervention fidelity, and decision quality are distinct metrics that frequently exhibit model-ranking reversals.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states via action-conditioned transitions and observation corrections.
- Demonstrates that ActTime is trained exclusively on factual trajectories without requiring paired alternative-action outcomes or direct planning supervision.
- Evaluates ActTime on a simulator-grounded evaluation suite covering building energy, traffic, greenhouse climate, and inventory management across factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning, ranking first in 12 of 16 domain-task settings.
- Reveals through empirical analysis that factual accuracy, intervention fidelity, and decision quality are non-interchangeable, with substantial model-ranking reversal rates between these tasks.

## Open Questions & Future Work

- [[distribution-shift-action-extrapolation]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts how outcomes change under different actions using factual training trajectories.

## Archivist Review

Approved the core concept ActTime and the open question regarding action distribution shift and extrapolation, as both represent substantial, reusable contributions and challenges in action-conditioned time series modeling. No datasets met the strict novelty or standalone naming standards for vault storage.

### Approved Concepts
- ActTime: ActTime is the primary methodological contribution of the paper, representing an action-conditioned world model that updates variable-specific latent states and supports intervention and planning in time series.

### Approved Open Questions
- Action Distribution Shift and Extrapolation: Crucial for deploying action-conditioned world models in real-world safety-critical environments where policies frequently encounter out-of-distribution control actions.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

