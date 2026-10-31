---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "We present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures, computing 6-DOF trajectories that jointly cover a target surface fraction while minimizing makespan and total cost. The approach decomposes the NP-hard joint problem into five GPU-accelerated stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed-integer programming with lifted constraints, and priority-based multi-agent path finding with continuous-time conflict checking. Evaluated across 14 meshes with up to 7.2 million faces, the system demonstrates efficient end-to-end performance and collision-free waypoint attainment."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "robotics"
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-31T10:43:45Z"

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
processed_at: "2026-10-31T10:43:45Z"
created_at: "2026-10-31T10:43:45Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

We present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures, computing 6-DOF trajectories that jointly cover a target surface fraction while minimizing makespan and total cost. The approach decomposes the NP-hard joint problem into five GPU-accelerated stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed-integer programming with lifted constraints, and priority-based multi-agent path finding with continuous-time conflict checking. Evaluated across 14 meshes with up to 7.2 million faces, the system demonstrates efficient end-to-end performance and collision-free waypoint attainment.

## Key Contributions

- An end-to-end GPU-accelerated pipeline for multi-robot 3D inspection integrating five core stages (candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing via MIP, and priority-based multi-agent path finding)
- A GPU batch adaptation of Lien's epsilon-visibility utilizing four custom CUDA kernels
- A beta-aware per-vehicle tour upper bound incorporating Desrochers-Laporte coefficient lift with forbidden-pair cuts for the routing MIP
- A 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* for multi-agent path finding

## Archivist Review

No concepts, datasets, or open questions from this paper met the rigorous long-term standards of the vault. The proposed open question on coupled location-routing is too specific to multi-robot 3D inspection pipelines rather than representing a broad, reusable foundational bottleneck.

### Rejected Candidates
- [open_question] Coupled Location-Routing Viewpoint Selection (`location-routing-viewpoint-selection`) - paper_local: paper_local

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

