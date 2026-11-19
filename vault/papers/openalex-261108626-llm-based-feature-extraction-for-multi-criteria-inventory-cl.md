---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "LLM-Based Feature Extraction for Multi-Criteria Inventory Classification"
description: "This paper introduces an LLM-based feature extraction approach that transforms unstructured customer feedback into quantitative features using vector embeddings and LLM-generated evaluation criteria for multi-criteria inventory classification (MCIC). By integrating these enriched features into the Hadi-Vencheh model, the method captures customer sentiment signals that remain underutilized in traditional inventory management. Experimental results demonstrate measurable reclassification effects and improved inventory prioritization when incorporating unstructured data."
resource: "https://arxiv.org/abs/2611.08626"
tags:
  - "demand-forecasting"
  - "machine-learning"
timestamp: "2026-11-19T14:04:29Z"

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
  - name: "operational-validation-inventory-reclassification"
    description: "Further research is needed to validate whether inventory item reclassifications resulting from LLM-derived qualitative features translate into measurable operational improvements, such as enhanced service levels, reduced stockout rates, and lower holding costs, by testing against datasets with observable ground-truth outcomes."
skill: "GeneralMLSkill"
processed_at: "2026-11-19T14:04:29Z"
created_at: "2026-11-19T14:04:29Z"
---

# LLM-Based Feature Extraction for Multi-Criteria Inventory Classification

**Authors**: Humza Akhtar, Rami Pinto
**Date**: 2026-11-05
**Paper ID**: [openalex:2611.08626](https://arxiv.org/abs/2611.08626)

## Summary

This paper introduces an LLM-based feature extraction approach that transforms unstructured customer feedback into quantitative features using vector embeddings and LLM-generated evaluation criteria for multi-criteria inventory classification (MCIC). By integrating these enriched features into the Hadi-Vencheh model, the method captures customer sentiment signals that remain underutilized in traditional inventory management. Experimental results demonstrate measurable reclassification effects and improved inventory prioritization when incorporating unstructured data.

## Key Contributions

- Proposes an LLM-based feature extraction approach to transform unstructured customer feedback and operational text into quantitative features for multi-criteria inventory classification.
- Integrates LLM-generated evaluation criteria and vector embeddings with the Hadi-Vencheh model to enrich MCIC frameworks.
- Demonstrates measurable reclassification effects and enhanced inventory prioritization by incorporating customer sentiment signals into inventory management.

## Open Questions & Future Work

- [[operational-validation-inventory-reclassification]]

## Archivist Review

The paper applies LLM feature extraction to multi-criteria inventory classification. No reusable core ML architectural concept was proposed, but the open question regarding operational validation of inventory reclassification is worth tracking.

### Approved Open Questions
- Operational Validation of Inventory Reclassification: Crucial for establishing the practical business value of AI-augmented multi-criteria inventory classification systems over traditional operational metrics.

## Links

- [Abstract](https://arxiv.org/abs/2611.08626)
- [PDF](https://arxiv.org/pdf/2611.08626)

