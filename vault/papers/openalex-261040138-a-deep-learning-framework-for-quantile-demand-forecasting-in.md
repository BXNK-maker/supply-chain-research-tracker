---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Deep Learning Framework for Quantile Demand Forecasting in E-commerce with Doubly Censored Data"
description: "This paper introduces a deep learning framework and tailored evaluation metric for quantile demand forecasting under doubly censored observations, where actual sales are capped by stock and boosted by promotions. Supported by theoretical guarantees, the approach outperforms existing baselines and proves effective in inventory simulations and real-world e-commerce applications."
resource: "https://arxiv.org/abs/2610.40138"
tags:
  - "demand-forecasting"
  - "time-series"
  - "retail-automation"
timestamp: "2026-11-02T13:00:01Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Z. Ye"
  - literal: "Jiawen Wei"
  - literal: "Teng Song"
  - literal: "Chen Chen"
  - literal: "Guangrui Ma"
  - literal: "Guangrui Ma"
issued:
  date-parts:
    - [2026, 10, 29]

# Domain-specific custom fields
paper_id: "2610.40138"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "doubly-censored-demand-forecasting"
    description: "A deep learning framework and evaluation methodology for quantile demand forecasting under doubly censored retail observations."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:00:01Z"
created_at: "2026-11-02T13:00:01Z"
---

# A Deep Learning Framework for Quantile Demand Forecasting in E-commerce with Doubly Censored Data

**Authors**: Z. Ye, Jiawen Wei, Teng Song, Chen Chen, Guangrui Ma, Guangrui Ma
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.40138](https://arxiv.org/abs/2610.40138)

## Summary

This paper introduces a deep learning framework and tailored evaluation metric for quantile demand forecasting under doubly censored observations, where actual sales are capped by stock and boosted by promotions. Supported by theoretical guarantees, the approach outperforms existing baselines and proves effective in inventory simulations and real-world e-commerce applications.

## Key Contributions

- Introduces a deep learning framework for quantile demand forecasting from doubly censored observations (capped by stock and boosted by promotions).
- Proposes a tailored evaluation metric with theoretical guarantees that correlates well with the oracle calibration measure.
- Demonstrates through inventory simulations and real-world applications that the proposed estimator surpasses existing baselines and provides practical utility in retail operations.

## Key Concepts

- [[doubly-censored-demand-forecasting]]: A deep learning framework and evaluation methodology for quantile demand forecasting under doubly censored retail observations.

## Archivist Review

Approved the central methodological contribution of deep learning for doubly censored demand forecasting while adhering to scarcity guidelines and rejecting standard statistical techniques.

### Approved Concepts
- Doubly Censored Demand Forecasting: Introduces the first deep learning framework and formulation for quantile demand forecasting under doubly censored data (capped by stock and boosted by promotions).

### Rejected Candidates
- [concept] Quantile Estimation (`quantile-estimation`) - not_novel: Too broad and standard across machine learning; not a novel specific concept introduced by this paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.40138)
- [PDF](https://arxiv.org/pdf/2610.40138)

