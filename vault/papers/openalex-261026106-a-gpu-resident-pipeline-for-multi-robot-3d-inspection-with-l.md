---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "The paper introduces a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception. The pipeline decomposes the NP-hard joint problem into five stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming, and priority-based multi-agent path finding with continuous-time conflict checking. By accelerating these stages with custom CUDA kernels and parallelized algorithms, the pipeline efficiently computes 6-DOF trajectories for robot fleets across large meshes containing up to 7.2 million faces."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
timestamp: "2026-10-24T09:16:49Z"

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
processed_at: "2026-10-24T09:16:49Z"
created_at: "2026-10-24T09:16:49Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

The paper introduces a complete GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception. The pipeline decomposes the NP-hard joint problem into five stages: viewpoint generation, visibility computation, set cover, min-max vehicle routing via mixed integer programming, and priority-based multi-agent path finding with continuous-time conflict checking. By accelerating these stages with custom CUDA kernels and parallelized algorithms, the pipeline efficiently computes 6-DOF trajectories for robot fleets across large meshes containing up to 7.2 million faces.

## Key Contributions

- An end-to-end GPU-accelerated pipeline for multi-robot 3D inspection under limited perception and visibility constraints, integrating candidate viewpoint generation, visibility computation, set cover, routing, and path finding.
- A GPU batch adaptation of Lien's epsilon-visibility using four custom CUDA kernels to compute surface visibility efficiently.
- A beta-aware per-vehicle tour upper bound combined with Desrochers-Laporte coefficient lifts and forbidden-pair cuts for min-max vehicle routing.
- A 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm for priority-based multi-agent path finding.

## Archivist Review

Applied strict filtering to reject paper-local robotics implementation details and routine modularity improvements. No candidates qualified for permanent vault notes.

### Rejected Candidates
- [open_question] Coupled Viewpoint Selection and Routing (`location-routing-viewpoint-selection`) - not_novel: Routine future work suggesting an integrated formulation for a modularly decomposed robotics pipeline, lacking specific architectural or mathematical formulation detail.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

