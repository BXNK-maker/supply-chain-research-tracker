---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Validated Data Onboarding for AI Demand Forecasting on U.S. Building Meter Data: Design, Controlled Evaluation, and a Corrected Negative Result"
description: "This paper introduces a validated data-onboarding pipeline designed to detect and repair defects in electric meter data prior to AI demand forecasting, using exclusively past-available information to prevent data leakage. Evaluated on 12 U.S. buildings from the Building Data Genome 2 dataset, the pipeline successfully restores forecasting accuracy degraded by seeded defects across gradient boosting, ridge regression, and random forest models. Additionally, the report details a corrected negative result where an initial pipeline iteration over-cleaned natural data, highlighting the necessity of careful per-building calibration."
resource: "https://arxiv.org/abs/2610.02397"
tags:
  - "machine-learning"
  - "time-series"
  - "demand-forecasting"
  - "data-cleaning"
timestamp: "2026-10-15T04:43:39Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yixuan Liang"
issued:
  date-parts:
    - [2026, 10, 1]

# Domain-specific custom fields
paper_id: "2610.02397"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:43:39Z"
created_at: "2026-10-15T04:43:39Z"
---

# Validated Data Onboarding for AI Demand Forecasting on U.S. Building Meter Data: Design, Controlled Evaluation, and a Corrected Negative Result

**Authors**: Yixuan Liang
**Date**: 2026-10-01
**Paper ID**: [openalex:2610.02397](https://arxiv.org/abs/2610.02397)

## Summary

This paper introduces a validated data-onboarding pipeline designed to detect and repair defects in electric meter data prior to AI demand forecasting, using exclusively past-available information to prevent data leakage. Evaluated on 12 U.S. buildings from the Building Data Genome 2 dataset, the pipeline successfully restores forecasting accuracy degraded by seeded defects across gradient boosting, ridge regression, and random forest models. Additionally, the report details a corrected negative result where an initial pipeline iteration over-cleaned natural data, highlighting the necessity of careful per-building calibration.

## Key Contributions

- Proposed a validated data-onboarding pipeline that detects and repairs defects in meter data using only past-available information prior to model training.
- Demonstrated on Building Data Genome 2 that seeded defects touching 0.10% of training data raise gradient-boosting forecasting error by 86%, which is fully mitigated by the pipeline while retaining 93% of training targets.
- Documented a corrected negative result showing that an early version of the pipeline over-cleaned natural data and degraded forecasts by 25%, resolved via per-building calibration.
- Achieved robust reproducibility with SHA-256 verified pinned inputs, automated testing, and continuous integration.

## Limitations

Initial versions of the pipeline over-cleaned natural data, requiring careful per-building calibration to prevent forecast degradation.

## Archivist Review

The proposed concept of a validated data-onboarding pipeline for building meter data is too application-specific and lacks generalizability across distinct machine learning domains. Therefore, no concepts or datasets are approved for permanent vault inclusion in this review.

### Rejected Candidates
- [concept] Validated Data Onboarding Pipeline (`validated-data-onboarding-pipeline`) - not_reusable: A specific data-cleaning pipeline applied to building meter data is domain-specific and insufficiently reusable across diverse machine learning subfields to merit a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2610.02397)
- [PDF](https://arxiv.org/pdf/2610.02397)

