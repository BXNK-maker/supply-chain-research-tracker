---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction"
description: "This paper introduces an LLM-enhanced spatio-temporal forecasting framework for grid-level docked bike-sharing demand. The method converts unstructured urban text into quantified spatial-temporal perturbation fields using a semantic shockwave mechanism, which extracts intensity, spatial reach, and temporal lag parameters. These fields are subsequently fed into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) designed to handle extreme sparsity. Experiments on the Barcelona Bicing dataset demonstrate that the proposed approach outperforms conventional neural baselines, particularly during anomalous high-demand periods."
resource: "https://arxiv.org/abs/2610.03834"
tags:
  - "demand-forecasting"
  - "time-series"
timestamp: "2026-10-15T09:34:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xuxilu Zhang"
  - literal: "Francesc Soriguera"
issued:
  date-parts:
    - [2026, 10, 2]

# Domain-specific custom fields
paper_id: "2610.03834"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "semantic-shockwave-mechanism"
    description: "A mechanism converting free-form urban text into quantified spatial-temporal perturbation fields via an LLM."
  - name: "zero-inflated-adaptive-spatio-temporal-graph-convolutional-network"
    description: "A graph convolutional network designed to handle sparse grid-level measurements using a dual-branch output head and a multi-task zero-inflated loss."
datasets:
  []
open_questions:
  - name: "real-time-llm-spatio-temporal-forecasting-generalizability"
    description: "Future work needs to address three primary limitations: transitioning offline LLM-based parameter extraction into real-time streaming architectures, incorporating broader multi-modal data sources (such as video streams and social media signals) to better capture unscheduled urban events, and validating the generalizability of the semantic shockwave framework across cities with diverse urban forms and transport systems."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T09:34:45Z"
created_at: "2026-10-15T09:34:45Z"
---

# LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction

**Authors**: Xuxilu Zhang, Francesc Soriguera
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03834](https://arxiv.org/abs/2610.03834)

## Summary

This paper introduces an LLM-enhanced spatio-temporal forecasting framework for grid-level docked bike-sharing demand. The method converts unstructured urban text into quantified spatial-temporal perturbation fields using a semantic shockwave mechanism, which extracts intensity, spatial reach, and temporal lag parameters. These fields are subsequently fed into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) designed to handle extreme sparsity. Experiments on the Barcelona Bicing dataset demonstrate that the proposed approach outperforms conventional neural baselines, particularly during anomalous high-demand periods.

## Key Contributions

- Proposes a forecasting framework where an LLM drives a semantic shockwave mechanism to convert free-form urban text into quantified spatial-temporal perturbation fields.
- Introduces the Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) featuring a dual-branch output head and a multi-task zero-inflated loss to handle extreme grid-level measurement sparsity.
- Demonstrates superior performance over established neural baselines on the operational Barcelona Bicing dataset, particularly during high-demand periods.

## Limitations

The abstract does not explicitly detail computational overhead or scalability limits associated with LLM-based text conversion in real-time operational pipelines.

## Open Questions & Future Work

- [[real-time-llm-spatio-temporal-forecasting-generalizability]]

## Key Concepts

- [[semantic-shockwave-mechanism]]: A mechanism converting free-form urban text into quantified spatial-temporal perturbation fields via an LLM.
- [[zero-inflated-adaptive-spatio-temporal-graph-convolutional-network]]: A graph convolutional network designed to handle sparse grid-level measurements using a dual-branch output head and a multi-task zero-inflated loss.

## Archivist Review

Approved the core methodological concepts (Semantic Shockwave Mechanism and ZI-ASTGCN) as they provide reusable architectural patterns for LLM-enhanced spatio-temporal forecasting. Approved the open question addressing real-time streaming, multi-modal integration, and cross-city generalizability as a substantive research bottleneck. Rejected the dataset since it already exists or represents a standard operational benchmark.

### Approved Concepts
- Semantic Shockwave Mechanism: It provides a novel bridge for transforming unstructured external text into structured spatial-temporal perturbation fields using LLMs.
- Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network: It effectively handles pronounced sparsity in grid-level demand measurements by coupling a dual-branch output head with a multi-task zero-inflated loss.

### Approved Open Questions
- Real-time LLM Spatio-Temporal Forecasting: Identifying these bottlenecks is critical for scaling LLM-enhanced spatio-temporal forecasting models from static historical benchmarks to robust, real-time urban deployment across diverse metropolitan areas.

### Rejected Candidates
- [dataset] Barcelona Bicing Dataset (`barcelona-bicing-dataset`) - not_novel: Routine operational dataset used for evaluation without introducing a methodological breakthrough.

## Links

- [Abstract](https://arxiv.org/abs/2610.03834)
- [PDF](https://arxiv.org/pdf/2610.03834)

