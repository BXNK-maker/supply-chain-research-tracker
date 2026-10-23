---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "The paper presents Épi, a persistent and self-improving autonomous research agent that maintains continuity across model sessions via hierarchical memory, branching, and independent review. Épi demonstrates strong capabilities by producing 120 record-setting mathematical and computational results, alongside a computer-assisted proof of Tuza's conjecture. Furthermore, the authors introduce Épi-turbo, a lightweight variant that outperforms Codex on FrontierOR combinatorial optimization tasks at a fraction of the model cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-23T09:42:25Z"

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
    description: "An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:42:25Z"
created_at: "2026-10-23T09:42:25Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

The paper presents Épi, a persistent and self-improving autonomous research agent that maintains continuity across model sessions via hierarchical memory, branching, and independent review. Épi demonstrates strong capabilities by producing 120 record-setting mathematical and computational results, alongside a computer-assisted proof of Tuza's conjecture. Furthermore, the authors introduce Épi-turbo, a lightweight variant that outperforms Codex on FrontierOR combinatorial optimization tasks at a fraction of the model cost.

## Key Contributions

- Proposed Épi, an autonomous research agent utilizing persistent research history, hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Achieved 120 record-setting mathematical and computational results, including narrow intervals for the n-queens constant and quartic Feigenbaum attractor dimension, and a computer-assisted proof of Tuza's conjecture for split graphs.
- Introduced Épi-turbo, a lightweight configuration that develops executable solvers for operations research tasks, achieving a 5.4% higher score than Codex on 30 FrontierOR tasks at 64% of its model cost.

## Limitations

Not explicitly discussed in the abstract, but scope is focused on mathematical discovery and algorithmic coding tasks.

## Key Concepts

- [[epi]]: An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience.

## Archivist Review

Approved the overarching concept 'Épi' as a novel persistent autonomous research agent framework. Rejected 'Épi-turbo' as a subcomponent variant of the main framework per vault policy prioritizing broader mechanisms. FrontierOR is already present in the vault under datasets, so no new dataset notes were created.

### Approved Concepts
- Épi: Core agent framework introduced to sustain investigations across sessions and evolve methods via accumulated experience.

### Rejected Candidates
- [concept] Épi-turbo (`epi-turbo`) - subcomponent_of_broader_mechanism: Épi-turbo is a lightweight domain-specific variant/subcomponent of the overarching Épi agent framework rather than a distinct foundational concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

