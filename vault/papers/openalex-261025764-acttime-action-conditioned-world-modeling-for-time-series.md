---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model for time series designed to predict outcomes under alternative candidate actions and support robust plan comparisons. ActTime maintains and updates variable-specific latent states via action-conditioned transitions and observation corrections, enabling future trajectory forecasting under interventions. Trained exclusively on observational factual trajectories without counterfactual supervision, ActTime achieves top performance across diverse simulator-grounded evaluation tasks in building energy, traffic, greenhouse climate, and inventory management. Furthermore, the empirical analysis demonstrates that factual accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable metrics."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "reinforcement-learning"
  - "demand-forecasting"
timestamp: "2026-11-01T11:37:43Z"

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
    description: "An action-conditioned world model for time series that predicts counterfactual outcomes under alternative candidate plans."
datasets:
  []
open_questions:
  - name: "extrapolation-under-action-distribution-shift"
    description: "Investigate and develop methods that explicitly address or resolve distribution shifts and extrapolation challenges when action-conditioned time-series world models are deployed in action regimes substantially unsupported by factual training data, including uncertainty characterization and online adaptation under distribution shift."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:37:43Z"
created_at: "2026-11-01T11:37:43Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model for time series designed to predict outcomes under alternative candidate actions and support robust plan comparisons. ActTime maintains and updates variable-specific latent states via action-conditioned transitions and observation corrections, enabling future trajectory forecasting under interventions. Trained exclusively on observational factual trajectories without counterfactual supervision, ActTime achieves top performance across diverse simulator-grounded evaluation tasks in building energy, traffic, greenhouse climate, and inventory management. Furthermore, the empirical analysis demonstrates that factual accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable metrics.

## Key Contributions

- Introduced ActTime, an action-conditioned world model for time series that updates variable-specific latent states through action-conditioned transitions and observation corrections.
- Demonstrated that ActTime can be trained solely on factual trajectories without requiring paired alternative-action outcomes or planning supervision.
- Constructed a simulator-grounded evaluation suite covering building energy, traffic, greenhouse climate, and inventory management across factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Showed that ActTime ranks first in 12 of 16 domain-task settings and highlighted that factual accuracy, intervention fidelity, and decision quality are non-interchangeable objectives.

## Open Questions & Future Work

- [[extrapolation-under-action-distribution-shift]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts counterfactual outcomes under alternative candidate plans.

## Archivist Review

Approved ActTime as a core concept representing action-conditioned world modeling for time series (reusing the existing vault slug 'acttime'). Approved one open question on action distribution shift extrapolation, while rejecting the risk-sensitive planning question as a routine model extension. No standalone datasets were approved due to lack of distinct named identifiers.

### Approved Concepts
- ActTime: It is the core model proposed in the paper for action-conditioned time series world modeling and intervention planning.

### Approved Open Questions
- Extrapolation Under Action Distribution Shift: Crucial for deploying action-conditioned world models safely in real-world environments where agents frequently encounter out-of-distribution control actions.

### Rejected Candidates
- [open_question] Risk-Sensitive Planning with Uncertainty (`risk-sensitive-planning-with-uncertainty`) - low_impact: Routine extension of utilizing predictive uncertainty in planning algorithms rather than a distinct foundational bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

