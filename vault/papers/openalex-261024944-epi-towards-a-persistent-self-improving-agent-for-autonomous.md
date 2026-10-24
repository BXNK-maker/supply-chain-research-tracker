---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, a persistent and self-improving autonomous research agent that sustains investigations across model sessions via hierarchical memory, branching, and independent review. Épi achieves substantial breakthroughs in mathematics and computer science, generating 120 record-setting results—including tighter bounds for the n-queens constant and Feigenbaum attractor dimension—as well as a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, its lightweight variant, Épi-turbo, outperforms Codex on operations research tasks at a fraction of the cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "reinforcement-learning"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-24T09:14:48Z"

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
    description: "An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience, hierarchical memory, and branching."
datasets:
  []
open_questions:
  - name: "hierarchical-memory-cross-task-generalization"
    description: "Investigate mechanisms for autonomous research agents to dynamically generalize lessons from past failed branches and dead ends across disparate problem domains, and determine how hierarchical memory stores can be structured to optimize cross-task reasoning without context window explosion or catastrophic forgetting."
skill: "GeneralMLSkill"
processed_at: "2026-10-24T09:14:48Z"
created_at: "2026-10-24T09:14:48Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, a persistent and self-improving autonomous research agent that sustains investigations across model sessions via hierarchical memory, branching, and independent review. Épi achieves substantial breakthroughs in mathematics and computer science, generating 120 record-setting results—including tighter bounds for the n-queens constant and Feigenbaum attractor dimension—as well as a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, its lightweight variant, Épi-turbo, outperforms Codex on operations research tasks at a fraction of the cost.

## Key Contributions

- Introduced Épi, a persistent autonomous research agent combining research history, hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Produced 120 record-setting results, including an 84-fold narrower interval for the n-queens constant and a 3.6-million-fold narrower rigorous interval for the quartic Feigenbaum attractor dimension.
- Established exact dual certificates showing the Cohn-Elkies linear-programming bound cannot be sharp in dimensions 10 and 11, and provided a computer-assisted proof of Tuza's conjecture for specific split graphs.
- Developed Épi-turbo, achieving a 5.4% higher total benchmark score than Codex on 30 FrontierOR tasks at 64% of its model cost.

## Open Questions & Future Work

- [[hierarchical-memory-cross-task-generalization]]

## Key Concepts

- [[epi]]: An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience, hierarchical memory, and branching.

## Archivist Review

Approved the core persistent autonomous research agent architecture concept 'epi' matching the existing vault entry 'epi' and the open question on cross-task generalization in hierarchical memory. Rejected the 'FrontierOR' benchmark suite as a routine evaluation dataset.

### Approved Concepts
- Épi: Introduces a persistent, self-improving autonomous research agent that maintains history, hierarchical memory, and branching across sessions.

### Approved Open Questions
- Cross-Task Lesson Generalization in Hierarchical Memory: Crucial for enabling true persistent self-improvement in autonomous scientific agents, as current systems struggle to effectively distill and transfer failure semantics and tactical insights across independent research campaigns.

### Rejected Candidates
- [dataset] FrontierOR (`frontieror`) - low_impact: Benchmark suite of 30 operations research tasks specific to evaluating operations research coding rather than a broadly adopted standalone ML training dataset.

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

