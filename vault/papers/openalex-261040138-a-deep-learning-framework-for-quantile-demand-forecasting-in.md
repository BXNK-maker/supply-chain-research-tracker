---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A Deep Learning Framework for Quantile Demand Forecasting in E-commerce with Doubly Censored Data"
description: "This paper introduces a deep learning framework for quantile demand forecasting with doubly censored data, addressing scenarios in e-commerce where actual sales are capped by stock and boosted by promotions. The authors propose a straightforward training approach alongside a tailored evaluation metric backed by theoretical guarantees. Empirical results on inventory simulations and real-world applications demonstrate that the proposed estimator outperforms existing baselines and correlates well with oracle calibration measures."
resource: "https://arxiv.org/abs/2610.40138"
tags:
  - "demand-forecasting"
  - "retail-automation"
timestamp: "2026-11-01T11:38:57Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Z. Ye"
  - literal: "Jiawen Wei"
  - literal: "Teng Song"
  - literal: "Chen Chen"
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
  - name: "doubly-censored-quantile-forecasting"
    description: "A deep learning framework for quantile demand forecasting under doubly censored data conditions in retail."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:38:57Z"
created_at: "2026-11-01T11:38:57Z"
---

# A Deep Learning Framework for Quantile Demand Forecasting in E-commerce with Doubly Censored Data

**Authors**: Z. Ye, Jiawen Wei, Teng Song, Chen Chen, Guangrui Ma
**Date**: 2026-10-29
**Paper ID**: [openalex:2610.40138](https://arxiv.org/abs/2610.40138)

## Summary

This paper introduces a deep learning framework for quantile demand forecasting with doubly censored data, addressing scenarios in e-commerce where actual sales are capped by stock and boosted by promotions. The authors propose a straightforward training approach alongside a tailored evaluation metric backed by theoretical guarantees. Empirical results on inventory simulations and real-world applications demonstrate that the proposed estimator outperforms existing baselines and correlates well with oracle calibration measures.

## Key Contributions

- Introduces a deep learning framework for learning quantiles from doubly-censored observations in e-commerce demand forecasting.
- Proposes a tailored evaluation metric with theoretical guarantees that correlates well with the oracle calibration measure.
- Demonstrates through inventory simulations and real-world applications that the proposed estimator outperforms existing baselines and improves retail operations.

## Limitations

Limitations and future work are not explicitly discussed in the abstract.

## Key Concepts

- [[doubly-censored-quantile-forecasting]]: A deep learning framework for quantile demand forecasting under doubly censored data conditions in retail.

## Archivist Review

Applied strict criteria for vault curation, approving only the core methodology concept of doubly censored quantile forecasting while rejecting standard statistical practices and paper-local helper elements. No open questions or datasets met the threshold for standalone inclusion.

### Approved Concepts
- Doubly Censored Quantile Forecasting: Introduces a deep learning framework and tailored evaluation metric to handle doubly censored demand data in e-commerce.

### Rejected Candidates
- [concept] Quantile Estimation (`quantile-estimation`) - not_novel: Standard statistical and machine learning technique rather than a novel reusable concept specific to this work.

## Links

- [Abstract](https://arxiv.org/abs/2610.40138)
- [PDF](https://arxiv.org/pdf/2610.40138)

