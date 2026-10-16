---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction"
description: "This paper introduces an LLM-enhanced spatial-temporal learning framework for short-term bike-sharing demand prediction that effectively incorporates unstructured urban text. The model utilizes a semantic shockwave mechanism to convert free-form text into quantified spatial-temporal perturbation fields defined by intensity, spatial reach, and temporal lag. These fields are integrated into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) featuring a dual-branch output head and a multi-task zero-inflated loss to handle extreme grid-level measurement sparsity. Experiments on the Barcelona Bicing dataset demonstrate that the proposed approach outperforms conventional baselines, especially during high-demand and anomalous periods."
resource: "https://arxiv.org/abs/2610.03834"
tags:
  - "demand-forecasting"
  - "time-series"
timestamp: "2026-10-16T09:33:18Z"

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
    description: "A framework component that converts free-form urban text into quantified spatial-temporal perturbation fields via an LLM."
  - name: "zero-inflated-adaptive-spatio-temporal-graph-convolutional-network"
    description: "A graph convolutional network designed to handle sparse grid-level measurements in bike-sharing demand prediction using a zero-inflated loss function."
datasets:
  []
open_questions:
  - name: "cross-city-shockwave-generalizability"
    description: "Assess and improve the cross-city generalizability of physics-informed semantic shockwave representations across diverse urban forms and varying public transport networks."
skill: "GeneralMLSkill"
processed_at: "2026-10-16T09:33:18Z"
created_at: "2026-10-16T09:33:18Z"
---

# LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction

**Authors**: Xuxilu Zhang, Francesc Soriguera
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03834](https://arxiv.org/abs/2610.03834)

## Summary

This paper introduces an LLM-enhanced spatial-temporal learning framework for short-term bike-sharing demand prediction that effectively incorporates unstructured urban text. The model utilizes a semantic shockwave mechanism to convert free-form text into quantified spatial-temporal perturbation fields defined by intensity, spatial reach, and temporal lag. These fields are integrated into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) featuring a dual-branch output head and a multi-task zero-inflated loss to handle extreme grid-level measurement sparsity. Experiments on the Barcelona Bicing dataset demonstrate that the proposed approach outperforms conventional baselines, especially during high-demand and anomalous periods.

## Key Contributions

- Proposes a forecasting framework where an LLM drives a semantic shockwave mechanism to convert free-form urban text into quantified spatial-temporal perturbation fields.
- Constructs Gaussian decay fields from three physically interpretable parameters (intensity, spatial reach, and temporal lag) extracted by the LLM and injects them into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN).
- Couples a dual-branch output head with a multi-task zero-inflated loss to jointly train gating probability and conditional flow intensity, addressing severe grid-level measurement sparsity.
- Demonstrates superior performance over established neural baselines on the Barcelona Bicing dataset, particularly during high-demand periods.

## Limitations

The framework's effectiveness depends on the accuracy and temporal-spatial resolution of extracted event parameters from unstructured text sources.

## Open Questions & Future Work

- [[cross-city-shockwave-generalizability]]

## Key Concepts

- [[semantic-shockwave-mechanism]]: A framework component that converts free-form urban text into quantified spatial-temporal perturbation fields via an LLM.
- [[zero-inflated-adaptive-spatio-temporal-graph-convolutional-network]]: A graph convolutional network designed to handle sparse grid-level measurements in bike-sharing demand prediction using a zero-inflated loss function.

## Archivist Review

Approved the two primary methodological concepts that define the paper's core contributions: the semantic shockwave mechanism and the specialized zero-inflated graph network architecture. Approved cross-city generalizability as an open question while rejecting the real-time extraction question as a standard systems engineering concern. Rejected the operational dataset note since it is a routine empirical dataset.

### Approved Concepts
- Semantic Shockwave Mechanism: It provides a novel bridge between unstructured external text and numerical spatial-temporal pipelines by extracting interpretable physical parameters.
- Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network: It addresses the pronounced sparsity of grid-level measurements in urban mobility by combining a dual-branch output head with a multi-task zero-inflated loss.

### Approved Open Questions
- Cross-City Shockwave Generalizability: Ensures that semantic shockwave models are robust and scalable across different metropolitan topographies and transportation configurations.

### Rejected Candidates
- [dataset] Barcelona Bicing Dataset (`barcelona-bicing-dataset`) - not_novel: Routine operational dataset used for empirical evaluation rather than a novel benchmark or core algorithmic contribution.
- [open_question] Real-Time LLM Parameter Extraction (`real-time-llm-parameter-extraction`) - low_impact: Engineering challenge regarding inference latency rather than a fundamental theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.03834)
- [PDF](https://arxiv.org/pdf/2610.03834)

