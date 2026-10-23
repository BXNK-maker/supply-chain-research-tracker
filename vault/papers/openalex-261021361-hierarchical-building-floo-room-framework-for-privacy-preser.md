---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings"
description: "This paper introduces a hierarchical Building-Floor-Room framework for autonomous delivery in large-scale buildings that decomposes optimization complexity across multiple spatial levels. By formulating a building-aware capacitated vehicle routing problem (CVRP) model that incorporates privacy constraints and structural connectivity, the approach enables globally feasible task assignment. Coupled with a physical hardware design for non-interactive delivery and closed-loop navigation, the system achieves reliable multi-floor indoor delivery performance on real robotic platforms."
resource: "https://arxiv.org/abs/2610.21361"
tags:
  - "vehicle-routing-problem"
  - "time-series"
timestamp: "2026-10-23T09:45:23Z"

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
    description: "A hierarchical delivery framework based on a Building-Floor-Room abstraction that decomposes delivery routing problems across multiple spatial levels."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-23T09:45:23Z"
created_at: "2026-10-23T09:45:23Z"
---

# Hierarchical Building-Floo-Room Framework for Privacy-Preserving Autonomous Delivery in Large-Scale Buildings

**Authors**: Xu Xiaoji, Luo Rui, Chen Jinhua, Xiang Changying, Zhang Leihan, Zhongyuan Liao
**Date**: 2026-10-15
**Paper ID**: [openalex:2610.21361](https://arxiv.org/abs/2610.21361)

## Summary

This paper introduces a hierarchical Building-Floor-Room framework for autonomous delivery in large-scale buildings that decomposes optimization complexity across multiple spatial levels. By formulating a building-aware capacitated vehicle routing problem (CVRP) model that incorporates privacy constraints and structural connectivity, the approach enables globally feasible task assignment. Coupled with a physical hardware design for non-interactive delivery and closed-loop navigation, the system achieves reliable multi-floor indoor delivery performance on real robotic platforms.

## Key Contributions

- Proposes a hierarchical Building-Floor-Room framework that decomposes large-scale indoor delivery optimization into multiple spatial levels.
- Formulates a building-aware extension of the capacitated vehicle routing problem (CVRP) incorporating inter-building connectivity, room-level access constraints, and privacy-sensitive areas.
- Introduces a hardware and software execution-level design featuring non-interactive privacy-preserving delivery, reachability-aware distances, and closed-loop SLAM.
- Validates the framework on a real multi-sensor robotic platform in real-world multi-floor delivery scenarios.

## Limitations

Performance is demonstrated on specific physical robotic platforms; scalability under extreme congestion or highly dynamic architectural changes requires further investigation.

## Key Concepts

- [[hierarchical-building-floor-room-framework]]: A hierarchical delivery framework based on a Building-Floor-Room abstraction that decomposes delivery routing problems across multiple spatial levels.

## Archivist Review

Approved the hierarchical building-floor-room framework concept as it corresponds directly to an existing vault concept (hierarchical-building-floor-room-framework). Rejected all open questions due to being paper-local, overly generic, or overlapping with existing vault entries. No datasets met the strict criteria for standalone archival.

### Approved Concepts
- Building-Floor-Room Framework: It is the core architectural novelty enabling multi-level decomposition for large-scale indoor delivery.

### Rejected Candidates
- [concept] Building-Aware CVRP Extension (`capacitated-vehicle-routing-problem-extension`) - subcomponent_of_broader_mechanism: A standard variant formulation of CVRP rather than a newly invented standalone machine learning architecture or concept.
- [open_question] Theoretical Performance Bounds for Hierarchical Routing (`theoretical-performance-bounds-hierarchical-routing`) - paper_local: Too specific to this paper's particular formulation rather than representing a broad, recurring vault-level bottleneck.
- [open_question] Multi-Robot Cooperative Optimization for Delivery (`multi-robot-cooperative-optimization-indoor-delivery`) - duplicate_existing: Substantially overlaps with existing multi-robot coordination questions in the vault.
- [open_question] Uncertainty-Aware Planning Under Dynamic Constraints (`uncertainty-aware-planning-dynamic-demand`) - generic: Too broad and standard for dynamic robotics planning without a distinct methodological angle.

## Links

- [Abstract](https://arxiv.org/abs/2610.21361)
- [PDF](https://arxiv.org/pdf/2610.21361)

