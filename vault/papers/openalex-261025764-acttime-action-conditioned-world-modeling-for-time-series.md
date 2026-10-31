---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model for time series designed to predict how future outcomes change under different actions and to support plan comparison. ActTime updates variable-specific latent states via an action-conditioned transition corrected by observations, and rolls forward under candidate actions using only factual trajectories for training. Evaluated across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime ranks first in 12 of 16 settings. The findings also reveal that factual prediction accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable performance axes."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "dynamic-pricing"
  - "demand-forecasting"
timestamp: "2026-10-31T10:42:37Z"

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
    description: "An action-conditioned world model for time series that predicts outcomes under different actions and supports reliable plan comparison."
datasets:
  []
open_questions:
  - name: "extrapolation-under-action-distribution-shift"
    description: "Future work should address learning action-conditioned dynamics that can robustly extrapolate to substantially different action regimes unsupported by the training data, as well as characterizing and managing predictive uncertainty under such distribution shifts."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:42:37Z"
created_at: "2026-10-31T10:42:37Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model for time series designed to predict how future outcomes change under different actions and to support plan comparison. ActTime updates variable-specific latent states via an action-conditioned transition corrected by observations, and rolls forward under candidate actions using only factual trajectories for training. Evaluated across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime ranks first in 12 of 16 settings. The findings also reveal that factual prediction accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable performance axes.

## Key Contributions

- Introduces ActTime, an action-conditioned world model that updates variable-specific latent states through action-conditioned transitions and observation corrections.
- Demonstrates that ActTime can be trained using only factual trajectories without paired alternative-action outcomes or planning supervision.
- Establishes a simulator-grounded evaluation suite across building energy, traffic, greenhouse climate, and inventory management covering factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Shows that ActTime ranks first in 12 of 16 domain-task settings and highlights that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives.

## Open Questions & Future Work

- [[extrapolation-under-action-distribution-shift]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different actions and supports reliable plan comparison.

## Archivist Review

Approved the core model concept 'acttime' which already exists in the vault under 'acttime' (or aligns with vault naming) and the open question regarding action distribution shift extrapolation, both of which are central and reusable for time-series control and decision-making literature.

### Approved Concepts
- ActTime: It is the core model introduced by the paper for action-conditioned world modeling and intervention-effect prediction in time series.

### Approved Open Questions
- Extrapolation Under Action Distribution Shift: Crucial for deploying world models in real-world physical systems where exploration or intervention ranges may exceed historical training data distribution.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

