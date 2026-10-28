---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception"
description: "This paper presents an end-to-end, GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception constraints. The pipeline decomposes the NP-hard joint problem into five stages—candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing solved via MIP, and priority-based multi-agent path finding with continuous-time conflict checking—supported by custom CUDA kernels and search extensions. Evaluated on 14 meshes with up to 7.2 million faces, the approach demonstrates scalability, collision freedom, and efficient trajectory generation compared to analytical and LP-relaxation lower bounds."
resource: "https://arxiv.org/abs/2610.26106"
tags:
  - "fleet-scheduling"
  - "multi-agent-reinforcement-learning"
  - "time-series"
timestamp: "2026-10-28T11:00:14Z"

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
processed_at: "2026-10-28T11:00:14Z"
created_at: "2026-10-28T11:00:14Z"
---

# A GPU-Resident Pipeline for Multi-Robot 3D Inspection with Limited Perception

**Authors**: Kryštof Pšenička, Stefan Edelkamp
**Date**: 2026-10-19
**Paper ID**: [openalex:2610.26106](https://arxiv.org/abs/2610.26106)

## Summary

This paper presents an end-to-end, GPU-resident pipeline for multi-robot 3D inspection of underwater structures under limited perception constraints. The pipeline decomposes the NP-hard joint problem into five stages—candidate viewpoint generation, visibility computation, set cover, min-max vehicle routing solved via MIP, and priority-based multi-agent path finding with continuous-time conflict checking—supported by custom CUDA kernels and search extensions. Evaluated on 14 meshes with up to 7.2 million faces, the approach demonstrates scalability, collision freedom, and efficient trajectory generation compared to analytical and LP-relaxation lower bounds.

## Key Contributions

- An end-to-end GPU-accelerated pipeline for multi-robot 3D inspection integrating viewpoint generation, visibility computation, set cover, min-max vehicle routing, and priority-based multi-agent path finding.
- A GPU batch adaptation of Lien's epsilon-visibility utilizing four custom CUDA kernels.
- A beta-aware per-vehicle tour upper bound and Desrochers-Laporte coefficient lift with forbidden-pair cuts for the min-max vehicle routing MIP.
- A 4D space-time extension of Zhou and Zeng's GPU parallel-frontier A* algorithm for multi-agent path finding.
- An experimental evaluation on 14 meshes with up to 7.2 million faces, ablating routing cuts and parallel-frontier search while measuring end-to-end performance against lower bounds.

## Archivist Review

Applied strict selection criteria: no concepts or datasets were proposed, and the two proposed open questions were rejected because one represents a standard general research direction in MAPF rather than a paper-specific bottleneck, and the other addresses a pipeline design choice rather than an overarching universal bottleneck.

### Rejected Candidates
- [open_question] Integrated Location-Routing Viewpoint Selection (`location-routing-viewpoint-selection`) - low_impact: The paper treats staged decomposition as a design choice; the question does not identify a fundamental theoretical or algorithmic roadblock that transcends this specific pipeline architecture.
- [open_question] CBS-Based MAPF for Dense Fleets (`cbs-mapf-dense-fleets`) - generic: Conflict-Based Search for dense fleets is a broad, well-known general direction in multi-agent path finding rather than an explicit, paper-derived unresolved question.

## Links

- [Abstract](https://arxiv.org/abs/2610.26106)
- [PDF](https://arxiv.org/pdf/2610.26106)

