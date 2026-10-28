---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ActTime: Action-Conditioned World Modeling for Time Series"
description: "ActTime is an action-conditioned world model for time series that predicts how future outcomes change under different actions, trained exclusively on factual trajectories. It updates latent states through action-conditioned transitions and observation corrections, supporting offline decision making and closed-loop planning. Evaluated across building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms baseline methods, demonstrating that factual accuracy and decision quality are distinct objectives."
resource: "https://arxiv.org/abs/2610.25764"
tags:
  - "time-series"
  - "demand-forecasting"
  - "reinforcement-learning"
timestamp: "2026-10-28T10:58:32Z"

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
    description: "An action-conditioned world model for time series that predicts outcomes under different actions and supports reliable planning without paired counterfactual training data."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:32Z"
created_at: "2026-10-28T10:58:32Z"
---

# ActTime: Action-Conditioned World Modeling for Time Series

**Authors**: Xinxing Zhou, Xiaojie Yuan, Yanlong Wen, Ming Jin
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.25764](https://arxiv.org/abs/2610.25764)

## Summary

ActTime is an action-conditioned world model for time series that predicts how future outcomes change under different actions, trained exclusively on factual trajectories. It updates latent states through action-conditioned transitions and observation corrections, supporting offline decision making and closed-loop planning. Evaluated across building energy, traffic, greenhouse climate, and inventory management, ActTime outperforms baseline methods, demonstrating that factual accuracy and decision quality are distinct objectives.

## Key Contributions

- Introduced ActTime, an action-conditioned world model for time series that updates variable-specific latent states via action-conditioned transitions and observation corrections.
- Trained exclusively on factual trajectories without requiring paired alternative-action outcomes or explicit planning supervision.
- Evaluated on a simulator-grounded evaluation suite spanning building energy, traffic, greenhouse climate, and inventory management, ranking first in 12 of 16 domain-task settings.
- Demonstrated that factual accuracy, intervention fidelity, and decision quality are distinct, with high model-ranking reversal rates between them.

## Key Concepts

- [[acttime]]: An action-conditioned world model for time series that predicts outcomes under different actions and supports reliable planning without paired counterfactual training data.

## Archivist Review

Approved ActTime as a core concept representing action-conditioned world modeling for time series forecasting and planning. The proposed open question was rejected because sim-to-real transfer and distribution shift are general challenges across machine learning rather than specific technical gaps unique to this paper's setting. No datasets were approved since none met the strict criteria.

### Approved Concepts
- ActTime: ActTime is the central methodological contribution of the paper, serving as a novel action-conditioned world model for time series forecasting and planning.

### Rejected Candidates
- [open_question] Real-World Transfer and Distribution Shift (`real-world-transfer-and-distribution-shift`) - generic: This open question covers standard sim-to-real transfer and distribution shift challenges that are generic to machine learning and control models rather than a specific unresolved structural bottleneck unique to this problem class.

## Links

- [Abstract](https://arxiv.org/abs/2610.25764)
- [PDF](https://arxiv.org/pdf/2610.25764)

