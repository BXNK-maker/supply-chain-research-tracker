---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "Autonomous delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while maintaining privacy and scheduling efficiency. This paper introduces a hierarchical Building-Floor-Room framework that decomposes optimization complexity via a building-aware extension of the capacitated vehicle routing problem (CVRP). At the execution level, it couples reachability-aware distances with a closed-loop mapping, localization, and navigation system on a multi-sensor robotic platform. Real-world validations demonstrate reliable multi-floor delivery with improved path rationality and privacy compliance."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "autonomous-delivery"
  - "robotics"
  - "privacy-preserving"
  - "hierarchical-planning"
timestamp: "2026-10-29T11:16:08Z"

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
  - name: "balancing-hierarchical-environment-models"
    description: "Design effective hierarchical models that balance geometric fidelity, semantic richness, and computational tractability across large-scale indoor environments."
skill: "GeneralMLSkill"
processed_at: "2026-10-29T11:16:08Z"
created_at: "2026-10-29T11:16:08Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

Autonomous delivery in large-scale buildings requires coordinated planning across building, floor, and room levels while maintaining privacy and scheduling efficiency. This paper introduces a hierarchical Building-Floor-Room framework that decomposes optimization complexity via a building-aware extension of the capacitated vehicle routing problem (CVRP). At the execution level, it couples reachability-aware distances with a closed-loop mapping, localization, and navigation system on a multi-sensor robotic platform. Real-world validations demonstrate reliable multi-floor delivery with improved path rationality and privacy compliance.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room framework that decomposes autonomous delivery planning across multiple spatial levels to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling inter-building/floor connectivity and room-level privacy constraints.
- Introduces a hardware design for non-interactive, privacy-preserving delivery backed by reachability-aware distances and a closed-loop SLAM/navigation system.

## Open Questions & Future Work

- [[balancing-hierarchical-environment-models]]

## Archivist Review

Applied strict screening to avoid duplicates with existing vault entries. The first open question overlaps conceptually with balancing-hierarchical-environment-models, but we can reuse or reject based on distinct focus. The second open question duplicates existing routing approximation and multi-agent coordination questions. No new concepts met the high bar for standalone notes.

### Approved Open Questions
- Hierarchical Environmental Modeling Complexity: Essential for scaling multi-robot delivery frameworks to larger, more complex real-world facilities without exploding computational overhead.

### Rejected Candidates
- [open_question] Multi-Robot Hierarchical Routing Optimization (`multi-robot-hierarchical-routing-optimization`) - duplicate_existing: Nearly identical to existing open questions on routing approximation and environment modeling in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

