---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "The paper introduces Épi, a persistent autonomous research agent that maintains continuity across model sessions using hierarchical memory, branching, and independent review. Épi achieves 120 record-setting mathematical and computational results, including tighter bounds for the n-queens constant and the quartic Feigenbaum attractor dimension, alongside a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, the authors present Épi-turbo, a lightweight variant that outperforms Codex on operations research tasks at a fraction of the cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "combinatorial-optimization"
  - "reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-31T10:42:31Z"

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
    description: "A persistent, self-improving autonomous research agent that sustains investigations across model sessions and evolves through accumulated experience."
datasets:
  - name: "FrontierOR"
    description: "A benchmark suite comprising 30 operations research tasks used to evaluate Épi-turbo on algorithmic coding, vehicle routing, scheduling, and production planning."
open_questions:
  - name: "autonomous-agent-branching-memory"
    description: "Investigate and develop advanced mechanisms for autonomous research agents to dynamically prune, merge, or generate search branches and adapt hierarchical memory structures without human intervention."
skill: "GeneralMLSkill"
processed_at: "2026-10-31T10:42:31Z"
created_at: "2026-10-31T10:42:31Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

The paper introduces Épi, a persistent autonomous research agent that maintains continuity across model sessions using hierarchical memory, branching, and independent review. Épi achieves 120 record-setting mathematical and computational results, including tighter bounds for the n-queens constant and the quartic Feigenbaum attractor dimension, alongside a computer-assisted proof of Tuza's conjecture for split graphs. Furthermore, the authors present Épi-turbo, a lightweight variant that outperforms Codex on operations research tasks at a fraction of the cost.

## Key Contributions

- Introduces Épi, a persistent autonomous research agent combining research history, hierarchical memory, branching, and independent review across session boundaries.
- Achieves 120 record-setting results, including 20 numerical bound records and 100 construction records, such as an 84-fold narrower interval for the n-queens constant and a 3.6-million-fold narrower interval for the quartic Feigenbaum attractor dimension.
- Provides a computer-assisted proof of Tuza's conjecture for split graphs with specific structural constraints.
- Introduces Épi-turbo, a lightweight configuration achieving a 5.4% higher total score on 30 FrontierOR tasks than Codex at 64% of its model cost.

## Open Questions & Future Work

- [[autonomous-agent-branching-memory]]

## Key Concepts

- [[epi]]: A persistent, self-improving autonomous research agent that sustains investigations across model sessions and evolves through accumulated experience.

## Archivist Review

Approved the core agent concept 'Épi' and its associated open research question on automated branching and memory management, along with the 'FrontierOR' operations research dataset. Rejected 'Épi-turbo' as a subcomponent/variant of the broader agent architecture.

### Approved Concepts
- Épi: Épi represents a novel persistent, self-improving autonomous research agent architecture that spans model sessions.

### Approved Open Questions
- Automated Branching and Memory Management: Branching strategies and automated memory curation are critical for scaling autonomous agents to handle exponentially growing combinatorial search spaces in scientific discovery.

### Rejected Candidates
- [concept] Épi-turbo (`epi-turbo`) - subcomponent_of_broader_mechanism: epi-turbo is a lightweight task-specific configuration of the overarching agent system (Épi) rather than a distinct standalone mechanism.

## Datasets

- [[FrontierOR]]

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

