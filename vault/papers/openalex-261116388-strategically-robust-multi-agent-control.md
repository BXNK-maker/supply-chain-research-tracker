---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Strategically Robust Multi-Agent Control"
description: "This paper introduces strategically robust multi-agent control, a novel framework that bridges standard game-theoretic control and fully adversarial robust control by accounting for misspecified control policies of other agents. The authors formulate a new equilibrium concept, strategically robust dynamic equilibrium, which interpolates between these two paradigms across open- and closed-loop settings. Alongside theoretical guarantees and computational advantages, numerical experiments in vehicle platooning, inventory management, and network control demonstrate increased resilience and a 'free-lunch' phenomenon where robustness improves performance and social welfare."
resource: "https://arxiv.org/abs/2611.16388"
tags:
  - "control-theory"
  - "multi-agent-reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-11-20T13:48:03Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Boris Velasevic"
  - literal: "Nicolas Lanzetti"
  - literal: "Eric Mazumdar"
issued:
  date-parts:
    - [2026, 11, 12]

# Domain-specific custom fields
paper_id: "2611.16388"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-11-20T13:48:03Z"
created_at: "2026-11-20T13:48:03Z"
---

# Strategically Robust Multi-Agent Control

**Authors**: Boris Velasevic, Nicolas Lanzetti, Eric Mazumdar
**Date**: 2026-11-12
**Paper ID**: [openalex:2611.16388](https://arxiv.org/abs/2611.16388)

## Summary

This paper introduces strategically robust multi-agent control, a novel framework that bridges standard game-theoretic control and fully adversarial robust control by accounting for misspecified control policies of other agents. The authors formulate a new equilibrium concept, strategically robust dynamic equilibrium, which interpolates between these two paradigms across open- and closed-loop settings. Alongside theoretical guarantees and computational advantages, numerical experiments in vehicle platooning, inventory management, and network control demonstrate increased resilience and a 'free-lunch' phenomenon where robustness improves performance and social welfare.

## Key Contributions

- Introduces strategically robust multi-agent control as a bridge between game-theoretic control and fully adversarial robust control.
- Formulates the strategically robust dynamic equilibrium concept for dynamic games that accommodates misspecified control policies of other players.
- Demonstrates computational benefits of accounting for strategic robustness over classic game-theoretic control approaches.
- Illustrates via numerical experiments on vehicle platooning, inventory management, and network control that strategic robustness yields resilience to misspecification and can improve social welfare (the 'free-lunch' phenomenon).

## Archivist Review

The core concepts proposed by the paper (strategically-robust-multi-agent-control and strategically-robust-dynamic-equilibrium) already exist in the knowledge vault. The candidate open question was rejected as a paper-local extension rather than a broad foundational bottleneck.

### Rejected Candidates
- [concept] Strategically Robust Multi-Agent Control (`strategically-robust-multi-agent-control`) - duplicate_existing: Already exists in the vault.
- [concept] Strategically Robust Dynamic Equilibrium (`strategically-robust-dynamic-equilibrium`) - duplicate_existing: Already exists in the vault.
- [open_question] Global Infinite-Horizon Equilibrium Computation (`infinite-horizon-equilibria-computation`) - paper_local: Paper-local specific extension of infinite-horizon game solving rather than a broadly reusable open bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.16388)
- [PDF](https://arxiv.org/pdf/2611.16388)

