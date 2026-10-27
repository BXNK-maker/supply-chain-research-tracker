---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "ActTime is an action-conditioned world model for time series designed to predict how system outcomes change under different candidate actions from the same observed history. Trained solely on factual trajectories without paired counterfactual outcomes, it updates variable-specific latent states through action-conditioned transitions and observation corrections before rolling forward for planning. Evaluated across simulator-grounded domains including building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across diverse decision-making tasks, highlighting the divergence between factual accuracy and intervention fidelity."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-10-27T10:10:22Z"

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
  - name: "real-world-transfer-and-action-distribution-shift"
    description: "Investigating the transferability of action-conditioned time-series world models to real-world controlled-intervention datasets and live deployment settings, specifically in scenarios involving out-of-distribution action regimes and uncertainty-aware risk-sensitive planning."
skill: "GeneralMLSkill"
processed_at: "2026-10-27T10:10:22Z"
created_at: "2026-10-27T10:10:22Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

ActTime is an action-conditioned world model for time series designed to predict how system outcomes change under different candidate actions from the same observed history. Trained solely on factual trajectories without paired counterfactual outcomes, it updates variable-specific latent states through action-conditioned transitions and observation corrections before rolling forward for planning. Evaluated across simulator-grounded domains including building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across diverse decision-making tasks, highlighting the divergence between factual accuracy and intervention fidelity.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states through action-conditioned transitions and observation corrections.
- Trains exclusively on factual trajectories without requiring paired alternative-action outcomes or direct planning supervision.
- Evaluated across a simulator-grounded evaluation suite spanning building energy, traffic, greenhouse climate, and inventory management, ranking first in 12 of 16 domain-task settings.
- Demonstrates that factual prediction accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these tasks.

## Open Questions & Future Work

- [[real-world-transfer-and-action-distribution-shift]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different candidate actions from the same observed history.

## Archivist Review

Approved the core concept 'acttime' (reusing the existing vault slug 'acttime') and the open question regarding real-world transfer and action distribution shift under strict scarcity constraints.

### Approved Concepts
- ActTime: Central to the paper's novelty as an action-conditioned world model for time series forecasting, intervention-effect prediction, and decision-making.

### Approved Open Questions
- Real-World Transfer and Action Distribution Shift: Bridging the gap between simulation-grounded evaluation and real-world deployment under distribution shift is a critical bottleneck for deploying world models in high-stakes physical domains.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

