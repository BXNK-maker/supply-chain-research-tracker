---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The paper proposes a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using short-range, limited field-of-view cameras. The system decomposes the NP-hard joint coverage and routing problem into five core stages—candidate viewpoint generation, visibility computation, set cover, MIP-based min-max vehicle routing, and priority-based multi-agent path finding—all accelerated on the GPU. Through custom CUDA kernels, advanced MIP bounding cuts, and a 4D space-time parallel-frontier A* search, the pipeline efficiently computes 6-DOF collision-free trajectories for robot fleets across complex meshes with up to 7.2 million faces."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "robotics"
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-11-02T13:06:57Z"

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
  - name: "coupled-viewpoint-selection-and-routing"
    description: "Investigate tightly coupled formulations that integrate viewpoint selection with travel cost and vehicle routing, rather than solving them sequentially, to avoid suboptimality caused by pipeline decomposition."
skill: "GeneralMLSkill"
processed_at: "2026-11-02T13:06:57Z"
created_at: "2026-11-02T13:06:57Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The paper proposes a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using short-range, limited field-of-view cameras. The system decomposes the NP-hard joint coverage and routing problem into five core stages—candidate viewpoint generation, visibility computation, set cover, MIP-based min-max vehicle routing, and priority-based multi-agent path finding—all accelerated on the GPU. Through custom CUDA kernels, advanced MIP bounding cuts, and a 4D space-time parallel-frontier A* search, the pipeline efficiently computes 6-DOF collision-free trajectories for robot fleets across complex meshes with up to 7.2 million faces.

## Key Contributions

- Developed an end-to-end GPU-resident pipeline for multi-robot 3D inspection of underwater structures integrating viewpoint generation, visibility computation, set cover, MIP vehicle routing, and multi-agent path finding.
- Introduced a GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels and a 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A*.
- Derived a beta-aware per-vehicle tour upper bound supplemented with Desrochers-Laporte coefficient lifts and forbidden-pair cuts for the min-max vehicle routing MIP.
- Demonstrated scalability on 14 meshes with up to 7.2 million faces, auditing collision freedom and waypoint attainment after trajectory smoothing and measuring gaps against analytical and LP-relaxation lower bounds.

## Open Questions & Future Work

- [[coupled-viewpoint-selection-and-routing]]

## Archivist Review

Approved one open question regarding coupled viewpoint selection and routing, which addresses a fundamental limitation of decoupled inspection pipelines. No concepts or datasets met the strict novelty and reusability standard.

### Approved Open Questions
- Coupled Viewpoint Selection and Routing: Sequential decomposition between viewpoint selection and routing ignores travel cost during viewpoint generation, leading to suboptimal global solutions that tighter integration could resolve.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

