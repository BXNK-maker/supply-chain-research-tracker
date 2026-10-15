---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction"
description: "Short-term bike-sharing demand forecasting is challenged by spatial-temporal non-stationarity and the integration of unstructured external text. This paper proposes a framework where a Large Language Model drives a semantic shockwave mechanism, converting free-form urban texts into quantified spatial-temporal perturbation fields defined by intensity, spatial reach, and temporal lag. These Gaussian decay fields are injected into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) that handles grid-level sparsity using a dual-branch output head and multi-task zero-inflated loss. Experiments on the operational Barcelona Bicing dataset demonstrate superior performance over established baselines, particularly during high-demand periods."
resource: "https://arxiv.org/abs/2610.03834"
tags:
  - "machine-learning"
  - "time-series"
timestamp: "2026-10-15T04:44:43Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xuxilu Zhang"
  - literal: "Francesc Soriguera"
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
    description: "A mechanism driven by a Large Language Model that converts unstructured urban text into quantified spatial-temporal perturbation fields."
datasets:
  - name: "Barcelona Bicing"
    description: "An operational bike-sharing dataset from Barcelona used to evaluate grid-level demand prediction performance."
open_questions:
  - name: "real-time-llm-spatiotemporal-forecasting"
    description: "Future research needs to explore online, real-time LLM parameter extraction pipelines to support live operational deployment, integrate multi-modal data streams such as live video feeds and social media signals for improved detection of unscheduled disruptions, and validate the generalizability of the semantic shockwave representation across diverse urban forms and transit networks."
skill: "GeneralMLSkill"
processed_at: "2026-10-15T04:44:43Z"
created_at: "2026-10-15T04:44:43Z"
---

# LLM-enhanced spatio-temporal learning for grid-level docked bike sharing demand prediction

**Authors**: Xuxilu Zhang, Francesc Soriguera, Xuxilu Zhang, Francesc Soriguera
**Date**: 2026-10-02
**Paper ID**: [openalex:2610.03834](https://arxiv.org/abs/2610.03834)

## Summary

Short-term bike-sharing demand forecasting is challenged by spatial-temporal non-stationarity and the integration of unstructured external text. This paper proposes a framework where a Large Language Model drives a semantic shockwave mechanism, converting free-form urban texts into quantified spatial-temporal perturbation fields defined by intensity, spatial reach, and temporal lag. These Gaussian decay fields are injected into a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) that handles grid-level sparsity using a dual-branch output head and multi-task zero-inflated loss. Experiments on the operational Barcelona Bicing dataset demonstrate superior performance over established baselines, particularly during high-demand periods.

## Key Contributions

- Proposes a forecasting framework where an LLM drives a semantic shockwave mechanism to convert free-form urban text into quantified spatial-temporal perturbation fields.
- Extracts three physically interpretable parameters per event (intensity, spatial reach, and temporal lag) to construct Gaussian decay fields injected into the forecasting model.
- Introduces a Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (ZI-ASTGCN) featuring a dual-branch output head and multi-task zero-inflated loss to handle grid-level measurement sparsity.
- Outperforms established neural baselines on the operational Barcelona Bicing dataset, especially during high-demand periods.

## Limitations

Performance relies on the accuracy and availability of unstructured external text sources and their extraction via LLMs, though specific limitations on compute overhead or failure modes under noisy data are not explicitly detailed in the abstract.

## Open Questions & Future Work

- [[real-time-llm-spatiotemporal-forecasting]]

## Key Concepts

- [[semantic-shockwave-mechanism]]: A mechanism driven by a Large Language Model that converts unstructured urban text into quantified spatial-temporal perturbation fields.

## Archivist Review

Approved the overarching 'Semantic Shockwave Mechanism' concept as a reusable paradigm for integrating unstructured text into spatio-temporal models, while rejecting the architecture-specific variant ZI-ASTGCN as too paper-local. Kept the primary evaluation dataset (Barcelona Bicing) and the open question concerning real-time online LLM semantic extraction.

### Approved Concepts
- Semantic Shockwave Mechanism: Provides a novel foundational link for injecting unstructured textual information into numerical spatio-temporal pipelines via physically interpretable parameters.

### Approved Open Questions
- Real-Time LLM Spatio-Temporal Forecasting: This is technically important because moving from offline to online semantic extraction and ensuring cross-city generalizability are key bottlenecks for deploying LLM-enhanced spatio-temporal models in real-world intelligent transportation systems.

### Rejected Candidates
- [concept] Zero-Inflated Adaptive Spatio-Temporal Graph Convolutional Network (`zi-astgcn`) - paper_local: Domain-specific graph neural network architecture variant that is too narrow and paper-local for permanent vault notes.

## Datasets

- [[Barcelona Bicing]]

## Links

- [Abstract](https://arxiv.org/abs/2610.03834)
- [PDF](https://arxiv.org/pdf/2610.03834)

