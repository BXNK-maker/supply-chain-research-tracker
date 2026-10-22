---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings, decomposing complex routing into manageable spatial levels. The authors formulate a building-aware capacitated vehicle routing problem (CVRP) that models multi-floor connectivity and room-level privacy constraints. At the execution level, a closed-loop mapping, localization, and navigation system paired with specialized hardware bridges abstract task assignment with physical multi-floor robotic execution. Real-world validation on a multi-sensor robotic platform demonstrates enhanced delivery efficiency and path rationality."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "time-series"
timestamp: "2026-10-22T09:49:18Z"

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
  - name: "hierarchical-building-floor-room-framework"
    description: "A multi-level spatial abstraction and routing framework for privacy-preserving autonomous delivery across buildings, floors, and rooms."
datasets:
  []
open_questions:
  - name: "multi-robot-cooperative-optimization-hierarchical-delivery"
    description: "Future work will explore theoretical performance bounds for the hierarchical routing formulation, extension to multi-robot cooperative optimization, and uncertainty-aware planning under dynamic demand and access constraints, further strengthening both the theoretical foundations and practical scalability of hierarchical autonomous delivery."
skill: "GeneralMLSkill"
processed_at: "2026-10-22T09:49:18Z"
created_at: "2026-10-22T09:49:18Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings, decomposing complex routing into manageable spatial levels. The authors formulate a building-aware capacitated vehicle routing problem (CVRP) that models multi-floor connectivity and room-level privacy constraints. At the execution level, a closed-loop mapping, localization, and navigation system paired with specialized hardware bridges abstract task assignment with physical multi-floor robotic execution. Real-world validation on a multi-sensor robotic platform demonstrates enhanced delivery efficiency and path rationality.

## Key Contributions

- Proposed a hierarchical delivery framework based on Building-Floor-Room abstractions to reduce optimization complexity in large-scale indoor environments.
- Formulated a building-aware extension of the capacitated vehicle routing problem (CVRP) incorporating inter-building connectivity, floor transitions, and room-level privacy constraints.
- Developed a hardware design and closed-loop SLAM/navigation system ensuring consistency between high-level routing and physical multi-floor execution.
- Validated the framework on a multi-sensor robotic platform in real-world scenarios, demonstrating reliable multi-floor delivery.

## Limitations

Validation is demonstrated on specific robotic hardware platforms; generalization to highly dynamic or unstructured environments requires further study.

## Open Questions & Future Work

- [[multi-robot-cooperative-optimization-hierarchical-delivery]]

## Key Concepts

- [[hierarchical-building-floor-room-framework]]: A multi-level spatial abstraction and routing framework for privacy-preserving autonomous delivery across buildings, floors, and rooms.

## Archivist Review

Applied strict selection standards, approving the overarching hierarchical building-floor-room framework concept and the multi-robot delivery open question while rejecting domain-specific variants that represent standard routing problem extensions.

### Approved Concepts
- Hierarchical Building-Floor-Room Framework: Introduces a novel multi-level spatial abstraction and CVRP extension for privacy-preserving indoor delivery.

### Approved Open Questions
- Multi-Robot Cooperative Optimization for Delivery: Extending single-agent hierarchical vehicle routing frameworks to multi-robot cooperative settings with uncertainty-aware planning is critical for scaling autonomous logistics in real-world multi-building facilities.

### Rejected Candidates
- [concept] Building-Aware Capacitated Vehicle Routing Problem (`building-aware-cvrp`) - subcomponent_of_broader_mechanism: A standard extension of CVRP applied to a specific domain rather than a foundational new algorithmic paradigm.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

