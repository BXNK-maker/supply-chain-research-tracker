---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The authors introduce ActTime, an action-conditioned world model for time series that predicts how future outcomes change under different candidate actions given an observed history. Trained exclusively on factual trajectories without supervision on alternative actions, ActTime combines variable-specific latent state updates with observation correction. Evaluated across a simulator-grounded suite encompassing building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across multiple decision and forecasting tasks."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "reinforcement-learning"
  - "demand-forecasting"
timestamp: "2026-10-26T10:42:27Z"

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
    description: "An action-conditioned world model for time series that updates variable-specific latent states through action-conditioned transitions and observation correction."
datasets:
  []
open_questions:
  - name: "action-regime-extrapolation-and-adaptation"
    description: "Investigate how to characterize uncertainty under distribution shifts and adapt action-conditioned time-series dynamics when facing substantially different action regimes that are unsupported by the training data."
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:42:27Z"
created_at: "2026-10-26T10:42:27Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The authors introduce ActTime, an action-conditioned world model for time series that predicts how future outcomes change under different candidate actions given an observed history. Trained exclusively on factual trajectories without supervision on alternative actions, ActTime combines variable-specific latent state updates with observation correction. Evaluated across a simulator-grounded suite encompassing building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms existing approaches across multiple decision and forecasting tasks.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states and supports counterfactual plan comparison.
- Trained using only factual trajectories without paired alternative-action outcomes or explicit planning supervision.
- Evaluated across a simulator-grounded suite covering building energy, traffic, greenhouse climate, and inventory management, ranking first in 12 of 16 domain-task settings.
- Demonstrates via empirical analysis that factual accuracy, intervention fidelity, and decision quality are distinct and non-interchangeable objectives.

## Open Questions & Future Work

- [[action-regime-extrapolation-and-adaptation]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that updates variable-specific latent states through action-conditioned transitions and observation correction.

## Archivist Review

Approved the central action-conditioned world model concept (acttime) and the open question on action-regime extrapolation. Rejected the evaluation suite as it is an aggregate collection of domain tasks rather than a standalone named dataset.

### Approved Concepts
- ActTime: It is the central methodological contribution of the paper, representing a novel action-conditioned world model for time series forecasting and decision-making.

### Approved Open Questions
- Action Regime Extrapolation and Adaptation: Addressing distribution shift and action-regime extrapolation is crucial for deploying world models safely in real-world controlled systems where novel actions may be sampled during optimization.

### Rejected Candidates
- [dataset] Simulator-Grounded Evaluation Suite (`simulator-grounded-evaluation-suite`) - generic: Not a specific named public dataset, but a collection of simulation-based domains.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

