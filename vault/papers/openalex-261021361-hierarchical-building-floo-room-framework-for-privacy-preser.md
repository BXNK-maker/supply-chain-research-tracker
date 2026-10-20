---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "Autonomous delivery in large-scale buildings requires coordinated planning across multiple spatial scales while respecting privacy constraints and physical limitations. This paper introduces a hierarchical Building-Floor-Room framework that decomposes the routing problem to reduce optimization complexity and formulate a building-aware capacitated vehicle routing problem (CVRP). At the execution level, the system combines a novel non-interactive privacy-preserving hardware design with a closed-loop mapping, localization, and navigation pipeline. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery with improved path efficiency."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-20T09:47:31Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Xiaoji"
  - literal: "Luo Rui"
  - literal: "Chen Jinhua"
  - literal: "Xiang Changying"
  - literal: "Zhang Leihan"
  - literal: "Zhongyuan Liao"
  - literal: "Dianrong Yu"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21361"
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
processed_at: "2026-10-20T09:47:31Z"
created_at: "2026-10-20T09:47:31Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao, Dianrong Yu
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

Autonomous delivery in large-scale buildings requires coordinated planning across multiple spatial scales while respecting privacy constraints and physical limitations. This paper introduces a hierarchical Building-Floor-Room framework that decomposes the routing problem to reduce optimization complexity and formulate a building-aware capacitated vehicle routing problem (CVRP). At the execution level, the system combines a novel non-interactive privacy-preserving hardware design with a closed-loop mapping, localization, and navigation pipeline. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery with improved path efficiency.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room framework that decomposes multi-scale delivery problems to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) incorporating inter-building connectivity, floor connectivity, and privacy constraints.
- Validates a real multi-sensor robotic platform demonstrating reliable multi-floor delivery, reachability-aware distances, and closed-loop mapping and navigation.

## Archivist Review

Applied strict filtering standards for the vault. The proposed concept and open question are highly specific to indoor robotic delivery systems and multi-floor vehicle routing rather than reusable foundational machine learning mechanisms or general open scientific bottlenecks. Therefore, all candidates were rejected to maintain vault purity.

### Rejected Candidates
- [concept] Building-Floor-Room Framework (`building-floor-room-framework`) - paper_local: This is a domain-specific system design for indoor robotic delivery rather than a broadly reusable machine learning or foundational algorithmic primitive.
- [open_question] Hierarchical Routing Bounds and Multi-Robot Coordination (`hierarchical-routing-bounds-multi-robot-coordination`) - paper_local: The question is specific to the paper's hierarchical indoor routing system and multi-robot extensions rather than a major foundational machine learning bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

