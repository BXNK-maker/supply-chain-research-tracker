---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "Autonomous delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while respecting privacy and physical constraints. This paper presents a hierarchical Building-Floor-Room framework that decomposes the problem to reduce optimization complexity and formulates a building-aware extension of the capacitated vehicle routing problem. At the execution level, a novel hardware design and a closed-loop mapping, localization, and navigation system ensure consistency between planned routes and physical robot motion. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery with improved path rationality and efficiency."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-26T10:42:53Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Xiaoji"
  - literal: "Luo Rui"
  - literal: "Chen Jinhua"
  - literal: "Xiang Changying"
  - literal: "Zhang Leihan"
  - literal: "Zhongyuan Liao"
  - literal: "Diao Zhongyuan"
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
  - name: "theoretical-performance-bounds-hierarchical-routing"
    description: "Deriving formal theoretical performance bounds, approximation guarantees, and computational complexity characterizations for hierarchical vehicle routing formulations across multi-building, multi-floor, and room-level spatial abstractions remains an open problem."
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:42:53Z"
created_at: "2026-10-26T10:42:53Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao, Diao Zhongyuan
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

Autonomous delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while respecting privacy and physical constraints. This paper presents a hierarchical Building-Floor-Room framework that decomposes the problem to reduce optimization complexity and formulates a building-aware extension of the capacitated vehicle routing problem. At the execution level, a novel hardware design and a closed-loop mapping, localization, and navigation system ensure consistency between planned routes and physical robot motion. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery with improved path rationality and efficiency.

## Key Contributions

- Proposes a hierarchical delivery framework based on Building-Floor-Room abstraction that decomposes spatial planning to reduce optimization complexity.
- Formulates a building-aware capacitated vehicle routing problem (CVRP) incorporating inter-building/floor connectivity, room-level access constraints, and privacy-sensitive areas.
- Introduces a hardware design for non-interactive, privacy-preserving delivery paired with a closed-loop mapping, localization, and navigation system on a multi-sensor robotic platform.

## Open Questions & Future Work

- [[theoretical-performance-bounds-hierarchical-routing]]

## Archivist Review

Applied strict scarcity and novelty filters. The proposed open question on theoretical performance bounds for hierarchical routing represents a genuine algorithmic bottleneck across multi-level routing, while no concept candidates met the high threshold for standalone permanent notes.

### Approved Open Questions
- Theoretical Performance Bounds for Hierarchical Routing: Establishing theoretical performance bounds is crucial to understanding the approximation quality and scalability limits of decoupled hierarchical routing models compared to monolithic formulations.

### Rejected Candidates
- [open_question] Theoretical Performance Bounds for Hierarchical Routing (`theoretical-performance-bounds-hierarchical-routing`) - other: Approved as a distinct, reusable question about hierarchical routing performance bounds.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

