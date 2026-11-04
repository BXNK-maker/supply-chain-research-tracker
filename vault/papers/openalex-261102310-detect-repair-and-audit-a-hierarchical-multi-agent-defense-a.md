---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Detect, Repair and Audit: A Hierarchical Multi-Agent Defense Against Adversarial Attacks in Energy Forecasting"
description: "This paper proposes a hierarchical multi-agent defense framework called Detect, Repair and Audit to protect Time-Series Large Language Models (TS-LLMs) against adversarial attacks in energy forecasting. Guided by a three-layer conceptual model derived from energy standards, the framework integrates a Multi-Agent Reinforcement Learning (MARL) detector and signal repair at local control centers, alongside an evidence-grounded LLM auditing agent for Virtual Power Plants. Experiments demonstrate that the MARL detector achieves an F1 score above 0.91, signal repair reduces Relative Squared Error (RSE) by up to 83%, and the system satisfies stringent local latency budgets."
resource: "https://arxiv.org/abs/2611.02310"
tags:
  - "time-series"
  - "demand-forecasting"
  - "multi-agent-reinforcement-learning"
  - "error-mitigation"
  - "interpretable-machine-learning"
timestamp: "2026-11-04T12:48:48Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zewei Shi"
  - literal: "Ruoxi Sun"
  - literal: "Minhui Xue"
  - literal: "Feng Liu"
  - literal: "Hua Ma"
  - literal: "Xingliang Yuan"
  - literal: "Surya Nepal"
issued:
  date-parts:
    - [2026, 11, 2]

# Domain-specific custom fields
paper_id: "2611.02310"
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
processed_at: "2026-11-04T12:48:48Z"
created_at: "2026-11-04T12:48:48Z"
---

# Detect, Repair and Audit: A Hierarchical Multi-Agent Defense Against Adversarial Attacks in Energy Forecasting

**Authors**: Zewei Shi, Ruoxi Sun, Minhui Xue, Feng Liu, Hua Ma, Xingliang Yuan, Surya Nepal
**Date**: 2026-11-02
**Paper ID**: [openalex:2611.02310](https://arxiv.org/abs/2611.02310)

## Summary

This paper proposes a hierarchical multi-agent defense framework called Detect, Repair and Audit to protect Time-Series Large Language Models (TS-LLMs) against adversarial attacks in energy forecasting. Guided by a three-layer conceptual model derived from energy standards, the framework integrates a Multi-Agent Reinforcement Learning (MARL) detector and signal repair at local control centers, alongside an evidence-grounded LLM auditing agent for Virtual Power Plants. Experiments demonstrate that the MARL detector achieves an F1 score above 0.91, signal repair reduces Relative Squared Error (RSE) by up to 83%, and the system satisfies stringent local latency budgets.

## Key Contributions

- Proposes a three-layer conceptual model extracted from energy standards and regulatory frameworks to address security postures in energy infrastructure.
- Develops a Multi-Agent Reinforcement Learning (MARL) detector and signal repair mechanism achieving an F1 score above 0.91 and reducing input Relative Squared Error (RSE) by up to 83%.
- Deploys an evidence-grounded LLM auditing agent with human-in-the-loop validation that detects 77.78% of attacks on the Sherlock dataset while meeting IEEE 1646 latency constraints (7.95 ms average).

## Archivist Review

Applied strict filtering standards. The concepts and questions proposed in this paper are tightly coupled to energy infrastructure standards, regulatory frameworks, and sector-specific auditing tasks, which limits their broad cross-domain reusability across general machine learning research.

### Rejected Candidates
- [concept] Hierarchical Multi-Agent Defense (`hierarchical-multi-agent-defense`) - not_reusable: The proposed hierarchical multi-agent defense framework is heavily tailored to energy infrastructure, regulation-derived three-layer conceptual models, and specific energy standards, making it too domain-specific and insufficiently reusable as a general machine learning vault note.
- [open_question] Robustness of Hierarchical Energy Defenses (`hierarchical-adversarial-defense-energy-forecasting`) - low_impact: The open question focuses specifically on energy forecasting defense frameworks and local control center latency budgets rather than a broad, foundational research bottleneck in machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2611.02310)
- [PDF](https://arxiv.org/pdf/2611.02310)

