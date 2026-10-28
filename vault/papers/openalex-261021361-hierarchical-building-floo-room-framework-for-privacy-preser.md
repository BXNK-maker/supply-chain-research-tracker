---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes delivery planning into building, floor, and room levels by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that incorporates connectivity and privacy constraints. At the execution level, the authors integrate a hardware design for non-interactive delivery with a closed-loop mapping, localization, and navigation system. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor task assignment and routing efficiency."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "reinforcement-learning"
timestamp: "2026-10-28T10:59:33Z"

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
  - name: "building-floor-room-framework"
    description: "A hierarchical delivery framework using a Building-Floor-Room abstraction to decompose routing optimization and enforce privacy constraints in large-scale indoor environments."
datasets:
  []
open_questions:
  - name: "balancing-hierarchical-environment-models"
    description: "Investigate advanced methods for constructing and optimizing hierarchical environment models that balance geometric fidelity, semantic richness, and computational tractability in large-scale indoor spaces."
skill: "GeneralMLSkill"
processed_at: "2026-10-28T10:59:33Z"
created_at: "2026-10-28T10:59:33Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper presents a hierarchical Building-Floor-Room framework for privacy-preserving autonomous delivery in large-scale buildings. The method decomposes delivery planning into building, floor, and room levels by formulating a building-aware extension of the capacitated vehicle routing problem (CVRP) that incorporates connectivity and privacy constraints. At the execution level, the authors integrate a hardware design for non-interactive delivery with a closed-loop mapping, localization, and navigation system. Real-world validation on a multi-sensor robotic platform demonstrates reliable multi-floor task assignment and routing efficiency.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room abstraction framework that decomposes large-scale indoor delivery to reduce optimization complexity.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) modeling inter-building/floor connectivity and room-level privacy constraints.
- Introduces a novel hardware design for non-interactive, privacy-preserving delivery paired with a closed-loop SLAM and navigation system ensuring execution consistency.
- Validates the complete framework on a real multi-sensor robotic platform for multi-floor autonomous delivery.

## Open Questions & Future Work

- [[balancing-hierarchical-environment-models]]

## Key Concepts

- [[building-floor-room-framework]]: A hierarchical delivery framework using a Building-Floor-Room abstraction to decompose routing optimization and enforce privacy constraints in large-scale indoor environments.

## Archivist Review

Approved the core hierarchical Building-Floor-Room framework as a reusable concept and retained the open question on balancing hierarchical environment models. Rejected the building-aware CVRP variant as a subcomponent and the multi-agent expansion question as standard boilerplate future work.

### Approved Concepts
- Building-Floor-Room Framework: Central methodological contribution decomposing autonomous delivery across building, floor, and room levels to reduce optimization complexity.

### Approved Open Questions
- Balancing Hierarchical Environment Models: Crucial for scaling autonomous navigation and task scheduling frameworks to massive, complex multi-building and multi-floor environments without hitting combinatorial bottlenecks.

### Rejected Candidates
- [concept] Building-Aware CVRP (`building-aware-cvrp`) - subcomponent_of_broader_mechanism: Subcomponent of the broader Building-Floor-Room Framework and a standard vehicle routing problem variant extension.
- [open_question] Multi-Robot Uncertainty-Aware Delivery Planning (`multi-robot-uncertainty-aware-delivery`) - not_novel: Standard future work request for multi-agent extension and uncertainty modeling rather than a standalone fundamental bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

