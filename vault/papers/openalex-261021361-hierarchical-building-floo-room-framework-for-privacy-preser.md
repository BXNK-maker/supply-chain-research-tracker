---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. It models multi-level spatial connectivity and room-level privacy constraints as an extension of the capacitated vehicle routing problem (CVRP). At the execution level, the framework incorporates a novel privacy-preserving hardware design and a closed-loop mapping, localization, and navigation system. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery efficiency and path rationality."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
timestamp: "2026-10-24T09:16:43Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Xiaoji"
  - literal: "Luo Rui"
  - literal: "Chen Jinhua"
  - literal: "Xiang Changying"
  - literal: "Zhang Leihan"
  - literal: "Zhongyuan Liao"
  - literal: "domain:"
  - literal: "key_contributions:["
  - literal: ","
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
processed_at: "2026-10-24T09:16:43Z"
created_at: "2026-10-24T09:16:43Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao, domain:, key_contributions:[, ,
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. It models multi-level spatial connectivity and room-level privacy constraints as an extension of the capacitated vehicle routing problem (CVRP). At the execution level, the framework incorporates a novel privacy-preserving hardware design and a closed-loop mapping, localization, and navigation system. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor delivery efficiency and path rationality.

## Key Contributions

- Introduces a hierarchical Building-Floor-Room abstraction framework that decomposes autonomous delivery in large-scale buildings to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling inter-building/inter-floor connectivity, room-level access constraints, and privacy-sensitive areas.
- Combines a novel non-interactive privacy-preserving hardware design with reachability-aware distances and a closed-loop SLAM and navigation system for real-world multi-floor robotic delivery.

## Archivist Review

Applied strict scarcity and novelty filters. The proposed open question is a routine request for theoretical bounds on a heuristic vehicle routing decomposition, so it was rejected to prevent vault bloat. No concepts or datasets met the criteria for permanent vault notes.

### Rejected Candidates
- [open_question] Theoretical Performance Bounds for Hierarchical Routing (`hierarchical-routing-performance-bounds`) - low_impact: Standard request for theoretical bounds on a heuristic routing decomposition, which does not constitute a major standalone unresolved bottleneck for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

