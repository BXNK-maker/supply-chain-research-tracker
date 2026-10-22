---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods via persistent research history, hierarchical memory, branching, and independent review. Épi achieves 120 record-setting results across numerical bounds and constructions, provides a computer-assisted proof for a case of Tuza's conjecture, and introduces Épi-turbo for efficient algorithmic coding on operational research tasks."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "combinatorial-optimization"
  - "machine-learning"
timestamp: "2026-10-22T09:49:43Z"

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
    description: "Benchmark suite consisting of 30 operational research tasks used to evaluate algorithmic coding and solvers."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:43Z"
created_at: "2026-10-22T09:49:43Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods via persistent research history, hierarchical memory, branching, and independent review. Épi achieves 120 record-setting results across numerical bounds and constructions, provides a computer-assisted proof for a case of Tuza's conjecture, and introduces Épi-turbo for efficient algorithmic coding on operational research tasks.

## Key Contributions

- Épi introduces a persistent, self-improving autonomous research agent that maintains continuity across model sessions using hierarchical memory, branching, and independent review.
- Épi produced 120 record-setting results, including record numerical bounds, construction records, an 84-fold narrower interval for the n-queens constant, and a computer-assisted proof of Tuza's conjecture for split graphs.
- Épi-turbo, a lightweight configuration for algorithmic coding, achieves a 5.4% higher total benchmark score than Codex on 30 FrontierOR tasks at 64% of its model cost.

## Archivist Review

Applied strict scarcity and novelty filters to the candidates. The dataset FrontierOR is approved as a specific named evaluation suite. The open question is rejected as too broad/generic. No standalone methodological concepts qualified for vault note creation.

### Rejected Candidates
- [open_question] General Autonomous Hypothesis Generation (`general-autonomous-hypothesis-generation`) - not_reusable: The open question is too broad and resembles boilerplate future work on general agent capabilities rather than a specific, technical bottleneck.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

