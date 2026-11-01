---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, a persistent and self-improving autonomous research agent that combines hierarchical memory, branching, and cross-session experimentation to sustain complex scientific investigations. Épi successfully generates 120 record-setting results across numerical bounds and combinatorial constructions, alongside computer-assisted proofs. Furthermore, a lightweight configuration termed Épi-turbo develops executable solvers for operations research tasks, outperforming baseline models at lower computational cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "combinatorial-optimization"
  - "reinforcement-learning"
  - "machine-learning"
timestamp: "2026-11-01T11:37:36Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yue Huang"
  - literal: "Zhangchen Xu"
  - literal: "Xiaonan Luo"
  - literal: "Zheyuan Liu"
  - literal: "Lichi Li"
  - literal: "Yiping Wang"
  - literal: "Peiyang Song"
  - literal: "Eric Gabriel Ramos"
  - literal: "Enze Xie"
  - literal: "Olexandr Isayev"
  - literal: "Paul Liang"
  - literal: "Nouha Dziri"
  - literal: "Huan Sun"
  - literal: "Jianfeng Gao"
  - literal: "Ying Liu"
  - literal: "Misha Sra"
  - literal: "Xiangliang Zhang"
  - literal: "Alex Pentland"
  - literal: "Zichen Chen"
issued:
  date-parts:
    - [2026, 10, 18]

# Domain-specific custom fields
paper_id: "2610.24944"
paper_source: "openalex"
architectures:
  []
concepts:
  - name: "epi"
    description: "An autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience, persistent memory, and independent review."
datasets:
  - name: "FrontierOR"
    description: "A benchmark suite consisting of 30 complex operational research tasks used to evaluate the algorithmic coding and solver development capabilities of Épi-turbo."
open_questions:
  - name: "memory-management-long-horizon-agents"
    description: "Investigate mechanisms for dynamically pruning or abstracting hierarchical research memory and branch histories to prevent context window saturation and computational bloat during exceptionally long-horizon agentic discovery campaigns."
skill: "GeneralMLSkill"
processed_at: "2026-11-01T11:37:36Z"
created_at: "2026-11-01T11:37:36Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, a persistent and self-improving autonomous research agent that combines hierarchical memory, branching, and cross-session experimentation to sustain complex scientific investigations. Épi successfully generates 120 record-setting results across numerical bounds and combinatorial constructions, alongside computer-assisted proofs. Furthermore, a lightweight configuration termed Épi-turbo develops executable solvers for operations research tasks, outperforming baseline models at lower computational cost.

## Key Contributions

- Introduces Épi, an autonomous research agent utilizing persistent research history, hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Produces 120 record-setting results, including record numerical bounds and a computer-assisted proof of Tuza's conjecture for split graphs.
- Introduces Épi-turbo, a lightweight configuration for algorithmic coding that achieves a 5.4% higher score than Codex on FrontierOR tasks at 64% of the model cost.

## Limitations

The abstract highlights reliance on fixed verifiers and underlying model capabilities, but does not detail failure modes in exploratory research.

## Open Questions & Future Work

- [[memory-management-long-horizon-agents]]

## Key Concepts

- [[epi]]: An autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience, persistent memory, and independent review.

## Archivist Review

Approved the core agent architecture Épi and its associated open question on memory management for long-horizon agents. FrontierOR is approved as a key evaluation dataset for operations research solvers. Épi-turbo is rejected as a subcomponent/variant of the overarching Épi agent architecture.

### Approved Concepts
- Épi: Épi is the core autonomous research agent architecture introduced, combining persistent history, hierarchical memory, and branching to sustain long-horizon scientific investigations.

### Approved Open Questions
- Memory Management in Long-Horizon Agents: As autonomous research agents scale to longer campaigns, managing the tradeoff between memory retention, retrieval accuracy, and context window limitations becomes a fundamental architectural bottleneck.

### Rejected Candidates
- [concept] Épi-turbo (`epi-turbo`) - subcomponent_of_broader_mechanism: subcomponent_of_broader_mechanism

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

