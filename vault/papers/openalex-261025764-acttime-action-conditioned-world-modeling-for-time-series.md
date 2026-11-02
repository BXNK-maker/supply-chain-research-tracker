---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "This paper introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states through an action-conditioned transition and predicts future trajectories under different candidate actions. Trained exclusively on factual trajectories without paired alternative outcomes, ActTime evaluates counterfactual interventions across building energy, traffic, greenhouse climate, and inventory management domains. Extensive evaluations reveal that factual accuracy, intervention fidelity, and decision quality are not interchangeable, with ActTime achieving top performance across the majority of evaluated domain-task settings."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-11-02T13:05:25Z"

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
    description: "An action-conditioned world model for time series that updates latent states and supports reliable comparison of candidate plans from factual trajectories alone."
datasets:
  []
open_questions:
  - name: "out-of-distribution-action-extrapolation"
    description: "Future work needs to investigate how action-conditioned world models for time series can reliably extrapolate to substantially different action regimes that are unsupported by the training data, particularly regarding characterization of uncertainty under distribution shifts and adaptation with limited new interactions."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:05:25Z"
created_at: "2026-11-02T13:05:25Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

This paper introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states through an action-conditioned transition and predicts future trajectories under different candidate actions. Trained exclusively on factual trajectories without paired alternative outcomes, ActTime evaluates counterfactual interventions across building energy, traffic, greenhouse climate, and inventory management domains. Extensive evaluations reveal that factual accuracy, intervention fidelity, and decision quality are not interchangeable, with ActTime achieving top performance across the majority of evaluated domain-task settings.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that simulates outcomes under different candidate actions using only factual trajectories during training.
- Evaluates across a diverse simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, covering factual prediction, intervention-effect prediction, offline decision making, and closed-loop planning.
- Demonstrates that ActTime ranks first in 12 of 16 domain-task settings.
- Shows that factual accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these evaluation dimensions.

## Open Questions & Future Work

- [[out-of-distribution-action-extrapolation]]

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that updates latent states and supports reliable comparison of candidate plans from factual trajectories alone.

## Archivist Review

Approved the central 'acttime' concept as a reusable action-conditioned time-series world modeling framework, and approved the open question on out-of-distribution action extrapolation because it addresses a fundamental generalization bottleneck in control-oriented forecasting. No datasets were provided or required.

### Approved Concepts
- ActTime: Introduces the core action-conditioned world modeling framework for time series that handles counterfactual evaluation and planning.

### Approved Open Questions
- Out-of-Distribution Action Extrapolation: Crucial for deploying world models safely in real-world controlled environments where policies may encounter novel or extreme out-of-distribution control inputs.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

