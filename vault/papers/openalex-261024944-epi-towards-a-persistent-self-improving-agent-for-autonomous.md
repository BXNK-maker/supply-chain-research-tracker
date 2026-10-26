---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "The paper introduces Épi, an autonomous research agent designed to sustain scientific and mathematical investigations across model sessions using persistent history, hierarchical memory, and independent verification. Épi achieves 120 record-setting results in mathematics—including narrower intervals for constants, dual certificates for linear programming bounds, and computer-assisted proofs—and a lightweight variant, Épi-turbo, outperforms Codex on operations research tasks at lower cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "reinforcement-learning"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "fleet-scheduling"
timestamp: "2026-10-26T10:41:51Z"

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
    description: "An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience using persistent history, hierarchical memory, and branching review."
datasets:
  - name: "FrontierOR"
    description: "A benchmark suite of 30 operations research tasks used to evaluate Épi-turbo against Codex."
open_questions:
  - name: "long-horizon-autonomous-research-continuity"
    description: "Develop robust mechanisms for automated hypothesis generation, multi-session experience retention, and principled backtracking that can sustain open-ended scientific investigations across extended operational campaigns without human intervention."
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:41:51Z"
created_at: "2026-10-26T10:41:51Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

The paper introduces Épi, an autonomous research agent designed to sustain scientific and mathematical investigations across model sessions using persistent history, hierarchical memory, and independent verification. Épi achieves 120 record-setting results in mathematics—including narrower intervals for constants, dual certificates for linear programming bounds, and computer-assisted proofs—and a lightweight variant, Épi-turbo, outperforms Codex on operations research tasks at lower cost.

## Key Contributions

- Presents Épi, an autonomous research agent featuring persistent research history, hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Épi produces 120 record-setting results, including an 84-fold narrower interval for the n-queens constant and a 3.6-million-fold narrower rigorous interval for the quartic Feigenbaum attractor dimension.
- Establishes exact dual certificates showing that the Cohn-Elkies linear-programming bound cannot be sharp in dimensions 10 and 11, and provides a computer-assisted proof of Tuza's conjecture for specific graph classes.
- Introduces Épi-turbo, a lightweight configuration for algorithmic coding that achieves a 5.4% higher total benchmark score than Codex on 30 FrontierOR tasks at 64% of its model cost.

## Open Questions & Future Work

- [[long-horizon-autonomous-research-continuity]]

## Key Concepts

- [[epi]]: An autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience using persistent history, hierarchical memory, and branching review.

## Archivist Review

Approved the core persistent research agent concept 'epi', the operations research benchmark 'FrontierOR', and the open question regarding long-horizon autonomous research continuity. Applied strict selectivity to ensure that only central architectural contributions and transferable questions enter the vault.

### Approved Concepts
- Épi: It is the core persistent, self-improving agent proposed in the paper, central to all autonomous research and optimization results.

### Approved Open Questions
- Long-Horizon Autonomous Research Continuity: Essential for scaling autonomous agents from short script-generation tasks to months-long, self-directed scientific discovery processes.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

