---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research"
description: "We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience using persistent research history, hierarchical memory, and independent review. Épi successfully produces 120 record-setting results across numerical bounds and constructions, including improved bounds for the n-queens constant and a computer-assisted proof of Tuza's conjecture. Additionally, a lightweight configuration termed Épi-turbo achieves superior performance on operations research tasks compared to baseline models at lower computational cost."
resource: "https://arxiv.org/abs/2610.24944"
tags:
  - "reinforcement-learning"
  - "machine-learning"
timestamp: "2026-10-25T09:31:36Z"

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
  []
open_questions:
  - name: "domain-general-autonomous-research"
    description: "Develop general-purpose frameworks that enable autonomous research agents to seamlessly transition between disparate domains (such as pure mathematical theorem proving, geometric packing, and combinatorial operations research optimization) without requiring hand-crafted problem-specific prompts, heuristics, or reward shaping."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:31:36Z"
created_at: "2026-10-25T09:31:36Z"
---

# Epi: Towards a Persistent, Self-Improving Agent for Autonomous Research

**Authors**: Yue Huang, Zhangchen Xu, Xiaonan Luo, Zheyuan Liu, Lichi Li, Yiping Wang, Peiyang Song, Eric Gabriel Ramos, Enze Xie, Olexandr Isayev, Paul Liang, Nouha Dziri, Huan Sun, Jianfeng Gao, Ying Liu, Misha Sra, Xiangliang Zhang, Alex Pentland, Zichen Chen
**Date**: 2026-10-18
**Paper ID**: [openalex:2610.24944](https://arxiv.org/abs/2610.24944)

## Summary

We present Épi, an autonomous research agent designed to sustain investigations across model sessions and evolve its methods through accumulated experience using persistent research history, hierarchical memory, and independent review. Épi successfully produces 120 record-setting results across numerical bounds and constructions, including improved bounds for the n-queens constant and a computer-assisted proof of Tuza's conjecture. Additionally, a lightweight configuration termed Épi-turbo achieves superior performance on operations research tasks compared to baseline models at lower computational cost.

## Key Contributions

- Proposed Épi, a persistent, self-improving autonomous research agent featuring hierarchical memory, branching, and independent review to sustain investigations across model sessions.
- Produced 120 record-setting results, including 20 numerical bound records and 100 construction records, such as an 84-fold narrower interval for the n-queens constant and a computer-assisted proof of Tuza's conjecture for split graphs.
- Introduced Épi-turbo, achieving a 5.4% higher total benchmark score on 30 FrontierOR tasks than Codex at 64% of its model cost.

## Open Questions & Future Work

- [[domain-general-autonomous-research]]

## Key Concepts

- [[epi]]: A persistent, self-improving autonomous research agent that sustains investigations across model sessions and evolves its methods through accumulated experience.

## Archivist Review

Approved the central autonomous research agent framework 'Epi' and the open question concerning domain-general autonomous research capabilities, ensuring strict adherence to vault standards and avoiding routine or low-impact entities.

### Approved Concepts
- Epi: Epi introduces a persistent, self-improving autonomous research agent framework that sustains investigations across sessions and achieves record-setting mathematical and computational results.

### Approved Open Questions
- Domain-General Autonomous Research Agents: Crucial for scaling autonomous agents toward true general scientific discovery rather than domain-restricted solver tuning.

## Links

- [Abstract](https://arxiv.org/abs/2610.24944)
- [PDF](https://arxiv.org/pdf/2610.24944)

