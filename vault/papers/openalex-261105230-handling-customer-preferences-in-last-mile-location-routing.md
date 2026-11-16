---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Handling Customer Preferences in Last-Mile Location-Routing: A Bilevel Optimization Approach"
description: "This paper studies the Location-Routing Problem with Delivery Preferences in last-mile delivery, where companies make facility activation and routing decisions while anticipating customer choices over home delivery and collection points. The problem is modeled as a mixed-integer bilevel program featuring compensation mechanisms for service inconvenience, and two single-level reformulations are developed to solve it. A two-phase heuristic provides warm starts for the formulations, scaling effectively on larger instances. Computational results demonstrate that incorporating customer preferences significantly improves customer satisfaction and alters facility configurations at a negligible cost increase."
resource: "https://arxiv.org/abs/2611.05230"
tags:
  - "vehicle-routing-problem"
  - "choice-modeling"
  - "combinatorial-optimization"
  - "last-mile-delivery"
timestamp: "2026-11-16T13:16:53Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "José Emmanuel Gómez‐Rocha"
  - literal: "José-Fernando Camacho-Vallejo"
  - literal: "Elena Fernández"
issued:
  date-parts:
    - [2026, 11, 3]

# Domain-specific custom fields
paper_id: "2611.05230"
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
processed_at: "2026-11-16T13:16:53Z"
created_at: "2026-11-16T13:16:53Z"
---

# Handling Customer Preferences in Last-Mile Location-Routing: A Bilevel Optimization Approach

**Authors**: José Emmanuel Gómez‐Rocha, José-Fernando Camacho-Vallejo, Elena Fernández
**Date**: 2026-11-03
**Paper ID**: [openalex:2611.05230](https://arxiv.org/abs/2611.05230)

## Summary

This paper studies the Location-Routing Problem with Delivery Preferences in last-mile delivery, where companies make facility activation and routing decisions while anticipating customer choices over home delivery and collection points. The problem is modeled as a mixed-integer bilevel program featuring compensation mechanisms for service inconvenience, and two single-level reformulations are developed to solve it. A two-phase heuristic provides warm starts for the formulations, scaling effectively on larger instances. Computational results demonstrate that incorporating customer preferences significantly improves customer satisfaction and alters facility configurations at a negligible cost increase.

## Key Contributions

- Introduced the Location-Routing Problem with Delivery Preferences, integrating collection-point activation, home-delivery assignment, and routing decisions while accounting for customer choice over time intervals and collection points.
- Formulated the hierarchical interaction as a mixed-integer bilevel program incorporating compensation mechanisms for service inconvenience, along with two equivalent single-level reformulations.
- Proposed a two-phase heuristic to generate feasible solutions acting as warm starts for the mathematical formulations, demonstrating increased effectiveness as instance size grows.
- Showed through computational experiments that explicitly accounting for customer preferences alters location-routing configurations and improves preference satisfaction with a minor increase in company cost compared to benchmark models ignoring customer choice.

## Archivist Review

Applied strict selectivity standards, ensuring only genuinely reusable concepts and cross-cutting open questions are admitted to the knowledge vault. Since the provided open question was overly specific to last-mile location-routing variants, it was rejected.

### Rejected Candidates
- [open_question] Scalable Algorithms and Stochastic Preferences (`scalable-algorithms-stochastic-preferences-lrp-dp`) - paper_local: Too paper-specific to last-mile location-routing with delivery preferences, lacking the broad cross-cutting value required for permanent vault inclusion.

## Links

- [Abstract](https://arxiv.org/abs/2611.05230)
- [PDF](https://arxiv.org/pdf/2611.05230)

