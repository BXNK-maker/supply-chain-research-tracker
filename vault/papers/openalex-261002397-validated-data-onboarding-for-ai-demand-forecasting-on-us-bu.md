---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Validated Data Onboarding for AI Demand Forecasting on U.S. Building Meter Data: Design, Controlled Evaluation, and a Corrected Negative Result"
description: "This paper presents a validated data-onboarding pipeline that detects and repairs defects in electric meter data using only past-available information prior to model training. Evaluating on hourly data from twelve U.S. buildings, the author demonstrates that minor data corruptions drastically degrade gradient-boosting, ridge regression, and random forest forecasting performance, and that the proposed pipeline successfully restores accuracy to clean-data baselines. The study also transparently documents and corrects a negative result where an initial pipeline version over-cleaned natural data."
resource: "https://arxiv.org/abs/2610.02397"
tags:
  - "data-cleaning"
  - "demand-forecasting"
  - "machine-learning"
  - "time-series"
timestamp: "2026-10-15T09:33:29Z"

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
  - name: "Building Data Genome 2"
    description: "Hourly electricity data for twelve U.S. buildings (210,528 rows, 2016-2017) used for controlled evaluation of demand forecasting."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:33:29Z"
created_at: "2026-10-15T09:33:29Z"
---

# Validated Data Onboarding for AI Demand Forecasting on U.S. Building Meter Data: Design, Controlled Evaluation, and a Corrected Negative Result

**Authors**: Yixuan Liang
**Date**: 2026-10-01
**Paper ID**: [openalex:2610.02397](https://arxiv.org/abs/2610.02397)

## Summary

This paper presents a validated data-onboarding pipeline that detects and repairs defects in electric meter data using only past-available information prior to model training. Evaluating on hourly data from twelve U.S. buildings, the author demonstrates that minor data corruptions drastically degrade gradient-boosting, ridge regression, and random forest forecasting performance, and that the proposed pipeline successfully restores accuracy to clean-data baselines. The study also transparently documents and corrects a negative result where an initial pipeline version over-cleaned natural data.

## Key Contributions

- Demonstrated that seeded, hash-logged defects affecting 0.10% of training data raise gradient-boosting forecasting error by 86% on U.S. building meter data.
- Showed that a past-only data-onboarding pipeline successfully returns forecasting error to the clean-data baseline (MASE 0.760 clean, 1.415 corrupted, 0.729 repaired) while retaining 93% of training targets.
- Documented a corrected negative result where an initial pipeline version over-cleaned natural data and worsened forecasts by 25%, resolved via per-building calibration.

## Limitations

Evaluated specifically on electricity meter data from twelve U.S. buildings; generalization to broader smart-meter or alternative multi-modal grid telemetry remains to be explored.

## Archivist Review

The paper presents a valuable empirical study on data cleaning and onboarding for building meter demand forecasting, but its concepts (such as the specific onboarding pipeline) are paper-local data-engineering implementations rather than reusable vault-level primitives. The Building Data Genome 2 dataset is approved as a standard benchmark dataset for building energy time-series analysis.

## Datasets

- [[Building Data Genome 2]]

## Links

- [Abstract](https://arxiv.org/abs/2610.02397)
- [PDF](https://arxiv.org/pdf/2610.02397)

