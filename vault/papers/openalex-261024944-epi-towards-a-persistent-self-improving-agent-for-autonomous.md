---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience, persistent history, hierarchical memory, branching, and independent review. Operating across session boundaries with a fixed verifier, Épi achieves numerous record-setting mathematical results, including narrower intervals for mathematical constants and proofs for graph theory conjectures. Furthermore, a lightweight configuration termed Épi-turbo develops executable solvers for operations research tasks, outperforming Codex in efficiency and benchmark score."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "reinforcement-learning"
timestamp: "2026-10-29T11:15:17Z"

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
  []
datasets:
  - name: "FrontierOR"
    description: "A benchmark for operations research tasks used to evaluate Épi-turbo."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-29T11:15:17Z"
created_at: "2026-10-29T11:15:17Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience, persistent history, hierarchical memory, branching, and independent review. Operating across session boundaries with a fixed verifier, Épi achieves numerous record-setting mathematical results, including narrower intervals for mathematical constants and proofs for graph theory conjectures. Furthermore, a lightweight configuration termed Épi-turbo develops executable solvers for operations research tasks, outperforming Codex in efficiency and benchmark score.

## Key Contributions

- Épi produced 120 record-setting results, including 20 numerical bound records and 100 construction records across multiple families, such as an 84-fold narrower interval for the n-queens constant.
- Épi established via exact dual certificates that the Cohn-Elkies linear-programming bound cannot be sharp in dimensions 10 and 11, and provided a computer-assisted proof of Tuza's conjecture for split graphs.
- Épi-turbo achieved a 5.4% higher total score on 30 FrontierOR tasks than Codex at 64% of the model cost, using the same underlying model and reasoning effort.

## Archivist Review

The FrontierOR dataset is approved as it is a specific named benchmark used for evaluating operations research agents in the paper, matching existing vault conventions. The open question is rejected because it is too broad and aspirational rather than a precise structural bottleneck.

### Rejected Candidates
- [open_question] Autonomous Research Continuity and Memory (`autonomous-research-continuity-and-memory`) - low_impact: Too broad as an open-ended research question for long-horizon agents rather than a specific technical bottleneck.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

