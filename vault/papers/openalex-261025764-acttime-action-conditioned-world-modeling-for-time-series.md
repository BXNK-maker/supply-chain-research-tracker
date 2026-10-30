---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "ActTime is an action-conditioned world model for time series designed to predict how system outcomes change under different candidate actions given an observed history. Trained exclusively on factual trajectories without paired counterfactual supervision, ActTime updates variable-specific latent states via an action-conditioned transition and observation correction mechanism. Evaluated across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms baseline methods across diverse tasks including factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-10-30T11:08:51Z"

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
    description: "An action-conditioned world model for time series that predicts outcomes under different candidate actions from observed history."
datasets:
  []
open_questions:
  - name: "action-regime-extrapolation-uncertainty"
    description: "Future work must investigate how to characterize uncertainty under substantial distribution shifts and adapt action-conditioned dynamics with limited new interaction when operating in regimes unsupported by the training trajectories."
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:08:51Z"
created_at: "2026-10-30T11:08:51Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

ActTime is an action-conditioned world model for time series designed to predict how system outcomes change under different candidate actions given an observed history. Trained exclusively on factual trajectories without paired counterfactual supervision, ActTime updates variable-specific latent states via an action-conditioned transition and observation correction mechanism. Evaluated across a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms baseline methods across diverse tasks including factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.

## Key Contributions

- Introduced ActTime, an action-conditioned world model for time series that updates variable-specific latent states and rolls forward under candidate actions to simulate future trajectories using only factual training data.
- Constructed a simulator-grounded evaluation suite spanning building energy, traffic, greenhouse climate, and inventory management, covering factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Demonstrated through empirical evaluation that ActTime ranks first in 12 of 16 domain-task settings.
- Showed that factual accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these tasks.

## Open Questions & Future Work

- [[action-regime-extrapolation-uncertainty]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different candidate actions from observed history.

## Archivist Review

Approved the core model concept 'acttime' since it represents a distinct architectural approach to action-conditioned time-series world modeling already partially present or complementary in the vault. Approved one significant open question on action-regime extrapolation and uncertainty under distribution shift, while rejecting the secondary future work question on risk-sensitive planning.

### Approved Concepts
- ActTime: It is the core model introduced in the paper for action-conditioned time series world modeling and intervention-effect prediction.

### Approved Open Questions
- Extrapolation and Uncertainty in Action Regimes: Crucial for bridging the gap between purely observational/factual training data and robust out-of-distribution control in real-world deployments.

### Rejected Candidates
- [open_question] Risk-Sensitive Planning via Predictive Uncertainty (`risk-sensitive-planning-uncertainty`) - not_novel: Standard future work direction exploring how to use existing uncertainty estimates for risk-sensitive planning, which is secondary to the primary methodological contribution.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

