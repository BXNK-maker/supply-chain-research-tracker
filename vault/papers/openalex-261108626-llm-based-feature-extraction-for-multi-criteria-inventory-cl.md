---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "LLM-Based Feature Extraction for Multi-Criteria Inventory Classification"
description: "This paper proposes an LLM-based feature extraction pipeline that converts unstructured customer feedback and operational data into quantitative vector embeddings and evaluation criteria for multi-criteria inventory classification (MCIC). By incorporating these text-derived features into the Hadi-Vencheh model, the approach effectively captures customer sentiment signals to enhance inventory prioritization. Experimental results show measurable reclassification effects, demonstrating the value of integrating unstructured data into traditional supply chain inventory management."
resource: "https://arxiv.org/abs/2611.08626"
tags:
  - "machine-learning"
  - "time-series"
  - "demand-forecasting"
timestamp: "2026-11-18T13:42:17Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Humza Akhtar"
  - literal: "Rami Pinto"
issued:
  date-parts:
    - [2026, 11, 5]

# Domain-specific custom fields
paper_id: "2611.08626"
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
processed_at: "2026-11-18T13:42:17Z"
created_at: "2026-11-18T13:42:17Z"
---

# LLM-Based Feature Extraction for Multi-Criteria Inventory Classification

**Authors**: Humza Akhtar, Rami Pinto
**Date**: 2026-11-05
**Paper ID**: [openalex:2611.08626](https://arxiv.org/abs/2611.08626)

## Summary

This paper proposes an LLM-based feature extraction pipeline that converts unstructured customer feedback and operational data into quantitative vector embeddings and evaluation criteria for multi-criteria inventory classification (MCIC). By incorporating these text-derived features into the Hadi-Vencheh model, the approach effectively captures customer sentiment signals to enhance inventory prioritization. Experimental results show measurable reclassification effects, demonstrating the value of integrating unstructured data into traditional supply chain inventory management.

## Key Contributions

- Proposes an LLM-based feature extraction approach to transform unstructured customer feedback and operational data into quantitative features using vector embeddings and LLM-generated evaluation criteria.
- Integrates enriched text-derived features into a multi-criteria inventory classification (MCIC) framework based on the Hadi-Vencheh model.
- Demonstrates measurable reclassification effects and enhanced inventory prioritization on e-commerce datasets when customer sentiment signals are included.

## Archivist Review

All candidates were rejected. The inventory classification concept is standard operations research rather than a novel ML primitive, and the open questions are either too domain-local or too general (bias/robustness) to qualify as permanent vault items.

### Rejected Candidates
- [concept] Multi-Criteria Inventory Classification (MCIC) (`multi-criteria-inventory-classification`) - not_novel: Multi-criteria inventory classification is a well-established operations research domain rather than a novel ML machine architecture or foundational pattern.
- [open_question] Operational Validation of LLM Inventory Classification (`operational-validation-llm-inventory-classification`) - paper_local: This is a paper-local empirical evaluation question about downstream supply chain performance for a specific model application.
- [open_question] Robustness and Bias Detection in LLM Scores (`robustness-and-bias-detection-for-llm-scores`) - generic: Too broad and standard as a general LLM deployment concern rather than a specific structural research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.08626)
- [PDF](https://arxiv.org/pdf/2611.08626)

