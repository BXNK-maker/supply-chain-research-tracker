---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tailoring Optimization Approaches with Domain Knowledge in Industry Process for Meta-heuristic Development"
description: "The paper introduces the Industry Process for Meta-heuristic Development (IPMD) schema, a systematic methodology for designing meta- and hyper-heuristic applications for industrial optimization. Within this framework, the authors present Balancing Non-dominated Tournament Genetic Programming (BNTGP), a hyper-heuristic utilizing genetic programming to explore heuristic search spaces. BNTGP is evaluated on two challenging NP-hard multi-objective optimization problems: routing (Capacitated Vehicle Routing Problem with Time Windows) and scheduling (Multi-Skill Resource Constrained Project Scheduling Problem)."
resource: "https://arxiv.org/abs/2611.13940"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
  - "evolutionary-algorithms"
  - "machine-learning"
timestamp: "2026-11-19T14:08:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jakub Cebula"
  - literal: "Konrad Gmyrek"
  - literal: "Paweł B. Myszkowski"
  - literal: "Marko Ðurasević"
  - literal: "Łukasz P. Olech"
  - literal: "Adam Paliszek-Saładyga"
issued:
  date-parts:
    - [2026, 11, 10]

# Domain-specific custom fields
paper_id: "2611.13940"
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
processed_at: "2026-11-19T14:08:52Z"
created_at: "2026-11-19T14:08:52Z"
---

# Tailoring Optimization Approaches with Domain Knowledge in Industry Process for Meta-heuristic Development

**Authors**: Jakub Cebula, Konrad Gmyrek, Paweł B. Myszkowski, Marko Ðurasević, Łukasz P. Olech, Adam Paliszek-Saładyga
**Date**: 2026-11-10
**Paper ID**: [openalex:2611.13940](https://arxiv.org/abs/2611.13940)

## Summary

The paper introduces the Industry Process for Meta-heuristic Development (IPMD) schema, a systematic methodology for designing meta- and hyper-heuristic applications for industrial optimization. Within this framework, the authors present Balancing Non-dominated Tournament Genetic Programming (BNTGP), a hyper-heuristic utilizing genetic programming to explore heuristic search spaces. BNTGP is evaluated on two challenging NP-hard multi-objective optimization problems: routing (Capacitated Vehicle Routing Problem with Time Windows) and scheduling (Multi-Skill Resource Constrained Project Scheduling Problem).

## Key Contributions

- Proposed the Industry Process for Meta-heuristic Development (IPMD) schema as a systematic methodology for designing meta- and hyper-heuristics in industrial settings.
- Introduced Balancing Non-dominated Tournament Genetic Programming (BNTGP) as a genetic programming-based hyper-heuristic framework.
- Demonstrated the application of BNTGP to two complex NP-hard multi-objective optimization problems: the Capacitated Vehicle Routing Problem with Time Windows and the Multi-Skill Resource Constrained Project Scheduling Problem.

## Archivist Review

The proposed concepts and open questions are specific to evolutionary algorithms and combinatorial optimization heuristics (meta- and hyper-heuristics), falling outside the core scope of general machine learning methodology and architectural primitives. Therefore, all candidates have been rejected in accordance with our high-selectivity standard.

### Rejected Candidates
- [concept] Industry Process for Meta-heuristic Development (`industry-process-for-meta-heuristic-development`) - low_impact: A specific engineering methodology/schema for industrial deployment rather than a general ML modeling concept or architectural pattern.
- [concept] Balancing Non-dominated Tournament Genetic Programming (`bntgp`) - not_reusable: A specialized genetic programming variant specific to combinatorial optimization heuristics, lacking widespread cross-domain reusability across general machine learning.
- [open_question] Automatic Feature Design and Selection (`automatic-feature-design-and-selection-in-hyper-heuristics-bn-tgp`) - low_impact: A fairly standard and incremental future work direction regarding feature engineering in genetic programming.
- [open_question] Transferability and Interpretability of Heuristics (`transferability-and-interpretability-of-evolved-heuristics`) - low_impact: A routine question about generalizability of evolved heuristics in evolutionary algorithms without a specific architectural bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2611.13940)
- [PDF](https://arxiv.org/pdf/2611.13940)

