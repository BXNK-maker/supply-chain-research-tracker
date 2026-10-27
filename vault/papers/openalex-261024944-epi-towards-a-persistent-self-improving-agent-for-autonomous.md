---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "The authors present Épi, a persistent and self-improving autonomous research agent designed to sustain scientific and mathematical investigations across model sessions using hierarchical memory, branching, and independent review. Épi successfully generated 120 record-setting numerical and construction results, including tighter bounds for the n-queens constant and a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, a lightweight variant called Épi-turbo outperformed Codex on operational research tasks at a fraction of the cost, demonstrating the framework's broad utility for automated scientific discovery and algorithmic coding."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "reinforcement-learning"
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-10-27T10:09:46Z"

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
    description: "A persistent, self-improving autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience."
datasets:
  - name: "FrontierOR"
    description: "A benchmark consisting of 30 operational research tasks used to evaluate algorithmic coding solvers."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-27T10:09:46Z"
created_at: "2026-10-27T10:09:46Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

The authors present Épi, a persistent and self-improving autonomous research agent designed to sustain scientific and mathematical investigations across model sessions using hierarchical memory, branching, and independent review. Épi successfully generated 120 record-setting numerical and construction results, including tighter bounds for the n-queens constant and a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, a lightweight variant called Épi-turbo outperformed Codex on operational research tasks at a fraction of the cost, demonstrating the framework's broad utility for automated scientific discovery and algorithmic coding.

## Key Contributions

- Introduced Épi, a persistent autonomous research agent combining hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Achieved 120 record-setting results, including an 84-fold narrower interval for the n-queens constant and a 3.6-million-fold narrower rigorous interval for the quartic Feigenbaum attractor dimension.
- Provided a computer-assisted proof of Tuza's conjecture for split graphs with specific structural constraints.
- Developed Épi-turbo, achieving a 5.4% higher total benchmark score than Codex on 30 FrontierOR tasks at 64% of the model cost.

## Key Concepts

- [[epi]]: A persistent, self-improving autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience.

## Archivist Review

Approved 'epi' (reusing the existing canonical slug 'epi' already present in the vault) as a core concept representing the persistent research agent framework. Also approved 'FrontierOR' as a specific named dataset used in the paper's evaluation. No open questions were proposed or warranted.

### Approved Concepts
- Épi: Épi is the core persistent, self-improving autonomous research agent framework introduced in the paper, serving as the primary methodological contribution for cross-session scientific discovery.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

