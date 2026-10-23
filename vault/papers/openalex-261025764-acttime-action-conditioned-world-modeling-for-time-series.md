---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "The paper introduces ActTime, an action-conditioned world model for time series designed to predict outcomes under different candidate actions from the same observed history. Trained exclusively on factual trajectories without paired alternative-action outcomes, ActTime updates variable-specific latent states through an action-conditioned transition and observation correction. Evaluated on a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime ranks first in 12 of 16 settings. Furthermore, the authors show that factual accuracy, intervention fidelity, and decision quality are not interchangeable, highlighting the necessity of task-specific evaluation for decision-making models."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
timestamp: "2026-10-23T09:44:36Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:44:36Z"
created_at: "2026-10-23T09:44:36Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

The paper introduces ActTime, an action-conditioned world model for time series designed to predict outcomes under different candidate actions from the same observed history. Trained exclusively on factual trajectories without paired alternative-action outcomes, ActTime updates variable-specific latent states through an action-conditioned transition and observation correction. Evaluated on a simulator-grounded suite spanning building energy, traffic, greenhouse climate, and inventory management, ActTime ranks first in 12 of 16 settings. Furthermore, the authors show that factual accuracy, intervention fidelity, and decision quality are not interchangeable, highlighting the necessity of task-specific evaluation for decision-making models.

## Key Contributions

- Introduces ActTime, an action-conditioned world model for time series that updates variable-specific latent states and rolls forward under candidate actions.
- Trains exclusively on factual trajectories without requiring paired alternative-action outcomes or planning supervision.
- Evaluated on a simulator-grounded suite across building energy, traffic, greenhouse climate, and inventory management, ranking first in 12 of 16 domain-task settings.
- Demonstrates that factual accuracy, intervention fidelity, and decision quality are distinct, as evidenced by high model-ranking reversal rates between these metrics.

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different candidate actions from the same observed history.

## Archivist Review

Approved ActTime as a standalone vault concept because it establishes a novel and reusable framework for action-conditioned time series world modeling. Rejected the open question candidate as it falls under routine generalization and distribution shift future work.

### Approved Concepts
- ActTime: ActTime introduces a novel action-conditioned world modeling framework for time series that predicts outcomes under different actions from the same observed history.

### Rejected Candidates
- [open_question] Out-of-Distribution Action Extrapolation (`out-of-distribution-action-extrapolation-and-adaptation`) - not_novel: The open question regarding out-of-distribution action extrapolation is a standard form of future work regarding distribution shift and uncertainty estimation rather than a distinct structural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

