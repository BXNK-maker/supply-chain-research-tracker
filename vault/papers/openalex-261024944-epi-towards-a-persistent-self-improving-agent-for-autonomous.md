---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, an autonomous research agent that sustains investigations across model sessions and evolves its methods through persistent research history, hierarchical memory, and branching. Épi produced 120 record-setting results, including record numerical bounds, construction records, and a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, the authors introduce Épi-turbo, a lightweight configuration for algorithmic coding that outperforms Codex on FrontierOR tasks at a lower model cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "reinforcement-learning"
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-10-30T11:08:14Z"

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
    description: "An autonomous research agent that sustains investigations across model sessions using hierarchical memory, branching, and review."
datasets:
  []
open_questions:
  - name: "long-horizon-autonomous-research-continuity"
    description: "Develop robust frameworks for multi-session autonomous research agents that can seamlessly maintain research continuity, learn generalizable insights from experimental feedback, and automatically balance the exploration of alternative hypotheses with backtracking."
skill: "GeneralMLSkill"
processed_at: "2026-10-30T11:08:14Z"
created_at: "2026-10-30T11:08:14Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, an autonomous research agent that sustains investigations across model sessions and evolves its methods through persistent research history, hierarchical memory, and branching. Épi produced 120 record-setting results, including record numerical bounds, construction records, and a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, the authors introduce Épi-turbo, a lightweight configuration for algorithmic coding that outperforms Codex on FrontierOR tasks at a lower model cost.

## Key Contributions

- Proposed Épi, a persistent autonomous research agent combining hierarchical memory, branching, and independent review across session boundaries.
- Achieved 120 record-setting results, including record numerical bounds and construction records across multiple families, such as narrowing the n-queens constant interval and the quartic Feigenbaum attractor dimension.
- Provided a computer-assisted proof of Tuza's conjecture for split graphs under specific constraints.
- Introduced Épi-turbo, a lightweight configuration for algorithmic coding that achieves a 5.4% higher benchmark score than Codex on FrontierOR tasks at 64% of its model cost.

## Open Questions & Future Work

- [[long-horizon-autonomous-research-continuity]]

## Key Concepts

- [[epi]]: An autonomous research agent that sustains investigations across model sessions using hierarchical memory, branching, and review.

## Archivist Review

Approved the core autonomous research agent concept 'Épi' and the associated open question on long-horizon research continuity, adhering to vault scarcity and novelty guidelines. FrontierOR was rejected as a routine benchmark suite.

### Approved Concepts
- Épi: Central to the paper's contribution as a persistent, self-improving autonomous research agent.

### Approved Open Questions
- Long-Horizon Autonomous Research Continuity: Addressing these three core challenges is fundamental to scaling autonomous agents from short script generation to long-horizon, self-improving scientific discovery.

### Rejected Candidates
- [dataset] FrontierOR (`frontieror`) - not_reusable: Routine benchmark dataset without prior vault status.

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

