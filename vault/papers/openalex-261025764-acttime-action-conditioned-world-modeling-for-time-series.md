---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model designed to predict how time-series outcomes change under different control actions from the same observed history. Trained exclusively on factual trajectories without requiring counterfactual supervision, ActTime updates latent states via action-conditioned transitions and observation corrections. Evaluated on a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms competing methods, demonstrating that factual accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable properties."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "reinforcement-learning"
  - "demand-forecasting"
timestamp: "2026-10-24T09:14:54Z"

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
    description: "An action-conditioned world model for time series that predicts how outcomes change under different actions from the same observed history."
datasets:
  []
open_questions:
  - name: "out-of-distribution-action-extrapolation-and-uncertainty"
    description: "Investigate how to characterize uncertainty under distribution shifts and adapt action-conditioned dynamics with limited new interaction when evaluating policies or actions substantially different from those supported by the training data."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:14:54Z"
created_at: "2026-10-24T09:14:54Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model designed to predict how time-series outcomes change under different control actions from the same observed history. Trained exclusively on factual trajectories without requiring counterfactual supervision, ActTime updates latent states via action-conditioned transitions and observation corrections. Evaluated on a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms competing methods, demonstrating that factual accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable properties.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states through an action-conditioned transition and observation correction.
- Enables future trajectory rollout under candidate actions using only factual trajectories during training, avoiding the need for paired counterfactual action outcomes or planning supervision.
- Demonstrates through a simulator-grounded evaluation suite across building energy, traffic, greenhouse climate, and inventory management that ActTime ranks first in 12 of 16 domain-task settings.
- Shows that factual prediction accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these capabilities.

## Open Questions & Future Work

- [[out-of-distribution-action-extrapolation-and-uncertainty]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts how outcomes change under different actions from the same observed history.

## Archivist Review

Approved 'ActTime' as it represents a novel and reusable action-conditioned world modeling framework for time-series control tasks. Also approved the open question regarding out-of-distribution action extrapolation and uncertainty under distribution shift, which identifies a genuine architectural and deployment limitation.

### Approved Concepts
- ActTime: It is the central methodological contribution of the paper, representing a novel action-conditioned world modeling approach for time-series forecasting and planning.

### Approved Open Questions
- Out-Of-Distribution Action Extrapolation: Crucial for extending action-conditioned world models from constrained simulator environments to real-world deployment settings where unobserved or extreme actions can occur.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

