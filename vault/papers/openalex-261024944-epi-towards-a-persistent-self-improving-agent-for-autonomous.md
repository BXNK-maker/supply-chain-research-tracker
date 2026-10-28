---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "The paper introduces Épi, an autonomous research agent designed to sustain scientific investigations across model sessions and self-improve through accumulated experience and hierarchical memory. Épi integrates persistent research history, branching, and independent review to execute long-running experiments evaluated by a fixed verifier. The agent established 120 record-setting mathematical results—including dramatic interval refinements for the n-queens constant and quartic Feigenbaum attractor dimension, along with a computer-assisted proof of Tuza's conjecture. Furthermore, a lightweight configuration termed Épi-turbo developed executable solvers for operational research tasks, outperforming Codex on FrontierOR at lower model costs."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "demand-forecasting"
  - "vehicle-routing-problem"
timestamp: "2026-10-28T10:58:26Z"

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
    description: "A benchmark of 30 operational research tasks used to evaluate the lightweight configuration Épi-turbo."
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:58:26Z"
created_at: "2026-10-28T10:58:26Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

The paper introduces Épi, an autonomous research agent designed to sustain scientific investigations across model sessions and self-improve through accumulated experience and hierarchical memory. Épi integrates persistent research history, branching, and independent review to execute long-running experiments evaluated by a fixed verifier. The agent established 120 record-setting mathematical results—including dramatic interval refinements for the n-queens constant and quartic Feigenbaum attractor dimension, along with a computer-assisted proof of Tuza's conjecture. Furthermore, a lightweight configuration termed Épi-turbo developed executable solvers for operational research tasks, outperforming Codex on FrontierOR at lower model costs.

## Key Contributions

- Épi introduces a persistent autonomous research agent combining hierarchical memory, independent review, and cross-session execution to sustain investigations and evolve methods.
- Épi achieved 120 record-setting results, including an 84-fold narrower interval for the n-queens constant and a 3.6-million-fold narrower interval for the quartic Feigenbaum attractor dimension.
- Épi delivered a computer-assisted proof of Tuza's conjecture for split graphs under specific constraints.
- Épi-turbo achieved a 5.4% higher total benchmark score than Codex on 30 FrontierOR tasks at 64% of its model cost.

## Archivist Review

Approved the benchmark dataset FrontierOR which is already tracked in the vault, and rejected any redundant or paper-local concepts to maintain strict quality standards.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

