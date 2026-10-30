---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The authors present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view sensors. The NP-hard joint problem is decomposed into five core stages—candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed-integer programming with lifted subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking. Through custom CUDA kernels, a batch adaptation of epsilon-visibility, and a 4D space-time extension of parallel-frontier A*, the pipeline achieves end-to-end GPU acceleration evaluated on 14 meshes with up to 7.2 million faces."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "robotics"
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-30T11:10:08Z"

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
processed_at: "2026-10-30T11:10:08Z"
created_at: "2026-10-30T11:10:08Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The authors present a complete, GPU-resident pipeline for multi-robot 3D inspection of underwater structures using fleets of robots with limited field-of-view sensors. The NP-hard joint problem is decomposed into five core stages—candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed-integer programming with lifted subtour elimination, and priority-based multi-agent path finding with continuous-time conflict checking. Through custom CUDA kernels, a batch adaptation of epsilon-visibility, and a 4D space-time extension of parallel-frontier A*, the pipeline achieves end-to-end GPU acceleration evaluated on 14 meshes with up to 7.2 million faces.

## Key Contributions

- Presented an end-to-end GPU-accelerated pipeline for multi-robot 3D inspection of underwater structures integrating five core stages from viewpoint generation to collision-checked path finding.
- Developed a GPU batch adaptation of Lien's epsilon-visibility with four custom CUDA kernels.
- Introduced a beta-aware per-vehicle tour upper bound derived from the interpolated objective with lifted Miller-Tucker-Zemlin subtour elimination and forbidden-pair cuts.
- Proposed a 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm for multi-agent path finding.

## Archivist Review

No concepts, open questions, or datasets met the strict criteria for permanent standalone vault notes. The proposed concepts and open questions are either paper-internal implementation details or standard robotics extensions without broad cross-domain reusability.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

