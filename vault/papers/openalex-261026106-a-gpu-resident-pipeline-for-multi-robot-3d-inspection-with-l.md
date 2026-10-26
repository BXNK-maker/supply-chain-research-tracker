---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The paper introduces an end-to-end GPU-resident pipeline for multi-robot 3D inspection under limited perception and short-range constraints. The NP-hard joint problem is decomposed into five main stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming, and priority-based multi-agent path finding with continuous-time conflict checking. Key technical components include custom CUDA kernels for batched epsilon-visibility, advanced tour upper bounds with forbidden-pair cuts, and a 4D space-time extension of GPU parallel-frontier A*. Evaluated on 14 complex meshes up to 7.2 million faces, the pipeline demonstrates robust performance, effective ablation of routing cuts, and collision-free waypoint attainment."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
  - "vehicle-routing-problem"
timestamp: "2026-10-26T10:43:28Z"

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
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-26T10:43:28Z"
created_at: "2026-10-26T10:43:28Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The paper introduces an end-to-end GPU-resident pipeline for multi-robot 3D inspection under limited perception and short-range constraints. The NP-hard joint problem is decomposed into five main stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming, and priority-based multi-agent path finding with continuous-time conflict checking. Key technical components include custom CUDA kernels for batched epsilon-visibility, advanced tour upper bounds with forbidden-pair cuts, and a 4D space-time extension of GPU parallel-frontier A*. Evaluated on 14 complex meshes up to 7.2 million faces, the pipeline demonstrates robust performance, effective ablation of routing cuts, and collision-free waypoint attainment.

## Key Contributions

- Presents a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures handling visibility, set cover, min-max vehicle routing, and priority-based multi-agent path finding.
- Develops a GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels.
- Introduces a beta-aware per-vehicle tour upper bound with forbidden-pair cuts for the min-max vehicle routing MIP formulation.
- Extends Zhou and Zeng's GPU parallel-frontier A* search into a 4D space-time variant for multi-agent path finding with continuous-time conflict checking.
- Evaluates the pipeline on 14 meshes with up to 7.2 million faces, demonstrating scalability and measuring gaps against analytical and LP-relaxation lower bounds.

## Archivist Review

The proposed open question is highly domain-specific to multi-robot inspection pipelines rather than representing a general machine learning bottleneck. Therefore, all candidates were rejected to maintain vault standards.

### Rejected Candidates
- [open_question] Location-Routing for Viewpoint Selection (`location-routing-viewpoint-selection`) - paper_local: Too domain-specific to multi-robot 3D inspection pipelines rather than a broad, reusable ML bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

