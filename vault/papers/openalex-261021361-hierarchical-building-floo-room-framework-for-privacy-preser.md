---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper presents a hierarchical Building-Floor-Room delivery framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes multi-level spatial planning by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that models room-level constraints and privacy-sensitive areas. At the execution level, it integrates non-interactive privacy hardware with closed-loop mapping, localization, and navigation. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery performance."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-21T09:47:59Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Xiaoji"
  - literal: "Luo Rui"
  - literal: "Chen Jinhua"
  - literal: "Xiang Changying"
  - literal: "Zhang Leihan"
  - literal: "Zhongyuan Liao"
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
processed_at: "2026-10-21T09:47:59Z"
created_at: "2026-10-21T09:47:59Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper presents a hierarchical Building-Floor-Room delivery framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes multi-level spatial planning by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that models room-level constraints and privacy-sensitive areas. At the execution level, it integrates non-interactive privacy hardware with closed-loop mapping, localization, and navigation. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery performance.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room abstraction framework that decomposes large-scale indoor delivery optimization to reduce complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling multi-level connectivity, room-level access constraints, and privacy-sensitive areas.
- Introduces a hardware design for non-interactive, privacy-preserving delivery integrated with reachability-aware distances and a closed-loop mapping, localization, and navigation system.
- Validates the framework on a real multi-sensor robotic platform, demonstrating reliable multi-floor delivery with improved path rationality and efficiency.

## Archivist Review

Strictly applied the selectivity filter to reject domain-specific robotics frameworks and vehicle routing questions that lack broad reuse across general machine learning and AI research.

### Rejected Candidates
- [concept] Hierarchical Building-Floor-Room Framework (`hierarchical-building-floor-room-framework`) - paper_local: The proposed hierarchical building-floor-room abstraction is specific to indoor robotic delivery logistics and lacks broader generalizability across diverse ML domains.
- [open_question] Theoretical Performance Bounds for Hierarchical Routing (`theoretical-performance-bounds-hierarchical-routing`) - low_impact: This open question about approximation bounds in vehicle routing is domain-specific to operations research and robotics routing rather than general machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

