---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The paper presents a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures, computing 6-DOF trajectories for a fleet of robots with limited perception to cover a target mesh surface. The joint NP-hard problem is decomposed into five core stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming with lifted Miller-Tucker-Zemlin subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking. The authors introduce GPU batch adaptations for visibility and pathfinding, novel routing cuts and tour upper bounds, and evaluate the approach across 14 large-scale meshes."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
  - "neural-routing-solver"
timestamp: "2026-10-22T09:49:30Z"

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
processed_at: "2026-10-22T09:49:30Z"
created_at: "2026-10-22T09:49:30Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The paper presents a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures, computing 6-DOF trajectories for a fleet of robots with limited perception to cover a target mesh surface. The joint NP-hard problem is decomposed into five core stages—viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming with lifted Miller-Tucker-Zemlin subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking. The authors introduce GPU batch adaptations for visibility and pathfinding, novel routing cuts and tour upper bounds, and evaluate the approach across 14 large-scale meshes.

## Key Contributions

- An end-to-end GPU-accelerated pipeline for multi-robot 3D inspection integrating five core stages with documented kernel design
- A GPU batch adaptation of Lien's epsilon-visibility utilizing four custom CUDA kernels
- A beta-aware per-vehicle tour upper bound derived from the interpolated objective, supplementing the Desrochers-Laporte coefficient lift with forbidden-pair cuts
- A 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm
- Experimental evaluation on 14 meshes containing up to 7.2M faces measuring end-to-end performance and gap against lower bounds

## Archivist Review

Applied strict filtering standards to ensure only highly reusable concepts and substantial bottlenecks enter the vault. The candidate open question represents a standard pipeline modularity trade-off rather than an overarching foundational research question.

### Rejected Candidates
- [open_question] Coupled Viewpoint Selection and Routing (`location-routing-viewpoint-selection`) - not_novel: Routine problem separation in robotics routing pipelines that does not constitute a standalone foundational vault bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

