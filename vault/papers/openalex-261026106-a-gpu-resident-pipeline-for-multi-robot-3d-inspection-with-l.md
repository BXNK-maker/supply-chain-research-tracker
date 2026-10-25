---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "This paper presents a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The system decomposes the NP-hard joint problem into five stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via MIP, and priority-based multi-agent path finding—all accelerated via custom CUDA kernels. Evaluated across 14 large meshes up to 7.2 million faces, the pipeline efficiently computes collision-free trajectories while minimizing a balanced makespan and total-cost objective."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "vehicle-routing-problem"
timestamp: "2026-10-25T09:33:22Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Kryštof Pšenička"
  - literal: "Stefan Edelkamp"
issued:
  date-parts:
    - [2026, 10, 19]

# Domain-specific custom fields
paper_id: "2610.26106"
paper_source: "openalex"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "coupled-viewpoint-routing-optimization"
    description: "Investigate joint optimization frameworks that couple viewpoint selection directly with travel cost and vehicle routing, moving beyond decoupled pipeline stages."
skill: "GeneralMLSkill"
processed_at: "2026-10-25T09:33:22Z"
created_at: "2026-10-25T09:33:22Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

This paper presents a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view cameras. The system decomposes the NP-hard joint problem into five stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via MIP, and priority-based multi-agent path finding—all accelerated via custom CUDA kernels. Evaluated across 14 large meshes up to 7.2 million faces, the pipeline efficiently computes collision-free trajectories while minimizing a balanced makespan and total-cost objective.

## Key Contributions

- Developed an end-to-end GPU-resident pipeline for multi-robot 3D inspection under limited perception and short-range fields of view, integrating viewpoint generation, visibility computation, set cover, routing, and pathfinding on the GPU.
- Introduced a GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels.
- Derived a beta-aware per-vehicle tour upper bound supplemented with Desrochers-Laporte coefficient lifts and forbidden-pair cuts for the min-max vehicle routing MIP.
- Proposed a 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm for multi-agent path finding.
- Evaluated the pipeline on 14 meshes with up to 7.2 million faces, demonstrating scalability and measuring end-to-end gaps against analytical and LP-relaxation lower bounds.

## Open Questions & Future Work

- [[coupled-viewpoint-routing-optimization]]

## Archivist Review

The paper presents a specialized GPU-resident pipeline for multi-robot 3D inspection. The proposed pipeline architecture and its specific components are domain-specific applications of search and routing rather than widely reusable ML concepts. Therefore, all concept candidates are rejected, but the open question addressing coupled viewpoint and routing optimization is approved as a valuable, reusable research direction.

### Approved Open Questions
- Coupled Viewpoint and Routing Optimization: Coupling viewpoint generation and routing can prevent suboptimal coverage distributions and improve overall mission efficiency by avoiding the limitations of sequential pipeline decomposition.

### Rejected Candidates
- [concept] GPU-Resident Multi-Robot Inspection Pipeline (`gpu-resident-multi-robot-inspection-pipeline`) - paper_local: Paper-local application pipeline combining existing robotics and search techniques rather than a reusable standalone machine learning primitive.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

