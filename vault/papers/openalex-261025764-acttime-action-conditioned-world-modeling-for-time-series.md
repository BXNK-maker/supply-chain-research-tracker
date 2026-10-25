---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "ActTime is an action-conditioned world model for time series designed to predict how outcomes change under different actions given an observed history, enabling reliable comparison of candidate plans. Trained solely on factual trajectories without paired alternative-action outcomes, ActTime maintains variable-specific latent states through action-conditioned transitions and observation correction. Evaluation across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management demonstrates that ActTime outperforms baseline methods, while empirical analysis confirms that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-10-25T09:31:41Z"

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
    description: "An action-conditioned world model for time series that predicts outcomes under different candidate actions from observed histories."
datasets:
  []
open_questions:
  - name: "action-regime-extrapolation-and-uncertainty"
    description: "Characterizing the uncertainty under distribution shifts and adapting the dynamics with limited new interaction when rolling out alternative action regimes substantially different from training data remain open challenges for action-conditioned time-series world models."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:31:41Z"
created_at: "2026-10-25T09:31:41Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

ActTime is an action-conditioned world model for time series designed to predict how outcomes change under different actions given an observed history, enabling reliable comparison of candidate plans. Trained solely on factual trajectories without paired alternative-action outcomes, ActTime maintains variable-specific latent states through action-conditioned transitions and observation correction. Evaluation across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management demonstrates that ActTime outperforms baseline methods, while empirical analysis confirms that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states and supports counterfactual planning under candidate actions using only factual training data.
- Constructs a simulator-grounded evaluation suite covering building energy, traffic, greenhouse climate, and inventory management across factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Demonstrates through empirical evaluation that ActTime ranks first in 12 of 16 domain-task settings.
- Shows that factual prediction accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these tasks.

## Open Questions & Future Work

- [[action-regime-extrapolation-and-uncertainty]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different candidate actions from observed histories.

## Archivist Review

Approved the core concept 'ActTime' and the open question regarding action-regime extrapolation and uncertainty, as they represent reusable methodology and a substantive unresolved research challenge in action-conditioned time-series modeling.

### Approved Concepts
- ActTime: Introduces a novel action-conditioned world modeling approach for time-series that explicitly supports intervention-effect prediction and closed-loop planning.

### Approved Open Questions
- Extrapolation and Uncertainty in Action-Conditioned Models: Crucial for extending action-conditioned models from controlled simulation benchmarks to safe, robust real-world decision-making settings subject to distribution shifts and unobserved interventions.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

