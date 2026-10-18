---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes delivery planning into building, floor, and room levels by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that incorporates privacy constraints and structural connectivity. At the execution level, a closed-loop mapping, localization, and navigation system integrates with physical robotic hardware to ensure consistency with planned routes. Real-world validation on a multi-sensor robotic platform demonstrates enhanced delivery efficiency and multi-floor routing rationality."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
timestamp: "2026-10-18T09:18:29Z"

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
  - name: "multi-robot-cooperative-routing-and-uncertainty-aware-planning"
    description: "Extend the routing framework and motion planning architectures to support multi-robot cooperative task allocation, fleet coordination, and uncertainty-aware planning under dynamic demand and access constraints."
skill: "GeneralMLSkill"
processed_at: "2026-10-18T09:18:29Z"
created_at: "2026-10-18T09:18:29Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes delivery planning into building, floor, and room levels by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that incorporates privacy constraints and structural connectivity. At the execution level, a closed-loop mapping, localization, and navigation system integrates with physical robotic hardware to ensure consistency with planned routes. Real-world validation on a multi-sensor robotic platform demonstrates enhanced delivery efficiency and multi-floor routing rationality.

## Key Contributions

- Introduces a hierarchical Building-Floor-Room abstraction that decomposes large-scale indoor delivery to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling multi-level connectivity, room-level access, and privacy constraints.
- Validates the framework on a real multi-sensor robotic platform demonstrating reliable multi-floor privacy-preserving delivery.

## Open Questions & Future Work

- [[multi-robot-cooperative-routing-and-uncertainty-aware-planning]]

## Archivist Review

The paper-local delivery framework concept was rejected as it pertains to a specific robotics system architecture rather than a general ML mechanism. The open question on multi-robot cooperative routing and uncertainty-aware planning was approved as it captures a substantive unresolved challenge in spatial multi-agent coordination.

### Approved Open Questions
- Multi-Robot Cooperative Routing and Uncertainty-Aware Planning: Extending single-robot hierarchical delivery frameworks to multi-robot cooperative fleets is vital for scaling autonomous logistics in large commercial and residential facilities, requiring robust decentralized task allocation and collision avoidance.

### Rejected Candidates
- [concept] Hierarchical Building-Floor-Room Framework (`hierarchical-building-floor-room-framework`) - paper_local: This is a paper-local system architecture rather than a broadly reusable machine learning primitive.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

