---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Tailoring Optimization Approaches with Domain Knowledge in Industry Process for Meta-heuristic Development"
description: "This paper introduces the Industry Process for Meta-heuristic Development (IPMD), a systematic methodology for applying meta- and hyper-heuristic applications to complex optimization problems. The authors demonstrate the schema through a case study using Balancing Non-dominated Tournament Genetic Programming (BNTGP) to solve two NP-hard multi-objective problems: the Capacitated Vehicle Routing Problem with Time Windows and the Multi-Skill Resource Constrained Project Scheduling Problem. By leveraging genetic programming, BNTGP acts as a hyper-heuristic capable of exploring a search space of heuristics to solve problem instances generally."
resource: "https://arxiv.org/abs/2611.13940"
tags:
  - "combinatorial-optimization"
  - "vehicle-routing-problem"
timestamp: "2026-11-20T13:48:22Z"

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
processed_at: "2026-11-20T13:48:22Z"
created_at: "2026-11-20T13:48:22Z"
---

# Tailoring Optimization Approaches with Domain Knowledge in Industry Process for Meta-heuristic Development

**Authors**: Jakub Cebula, Konrad Gmyrek, Paweł B. Myszkowski, Marko Ðurasević, Łukasz P. Olech, Adam Paliszek-Saładyga
**Date**: 2026-11-10
**Paper ID**: [openalex:2611.13940](https://arxiv.org/abs/2611.13940)

## Summary

This paper introduces the Industry Process for Meta-heuristic Development (IPMD), a systematic methodology for applying meta- and hyper-heuristic applications to complex optimization problems. The authors demonstrate the schema through a case study using Balancing Non-dominated Tournament Genetic Programming (BNTGP) to solve two NP-hard multi-objective problems: the Capacitated Vehicle Routing Problem with Time Windows and the Multi-Skill Resource Constrained Project Scheduling Problem. By leveraging genetic programming, BNTGP acts as a hyper-heuristic capable of exploring a search space of heuristics to solve problem instances generally.

## Key Contributions

- Introduces the Industry Process for Meta-heuristic Development (IPMD) schema as a systematic methodology for applying meta- and hyper-heuristics to optimization problems.
- Presents a case study using Balancing Non-dominated Tournament Genetic Programming (BNTGP) for solving two NP-hard multi-objective optimization problems: the Capacitated Vehicle Routing Problem with Time Windows and the Multi-Skill Resource Constrained Project Scheduling Problem.
- Demonstrates how genetic programming-based representations enable hyper-heuristics to explore search spaces of heuristics and generalize across problem instances.

## Limitations

The abstract does not report specific quantitative evaluation results, computational overhead, or scalability bounds across larger problem instances.

## Archivist Review

The paper focuses on an industrial process schema and evolutionary computation heuristics (genetic programming for routing and scheduling) within operations research. While well-executed, these concepts and open questions are specific to evolutionary algorithms and combinatorial optimization rather than core, cross-cutting machine learning primitives or general vault-level questions. Therefore, all candidates were rejected to maintain high selectivity.

### Rejected Candidates
- [concept] Industry Process for Meta-heuristic Development (`industry-process-for-meta-heuristic-development`) - not_reusable: Represents a domain-specific software engineering process/schema for meta-heuristic development rather than a fundamental algorithmic primitive or reusable machine learning architecture.
- [concept] Balancing Non-dominated Tournament Genetic Programming (`balancing-non-dominated-tournament-genetic-programming`) - low_impact: A specialized genetic programming variant and application case study within traditional operations research and evolutionary computation rather than a core machine learning vault concept.
- [open_question] Automatic Feature Design in Hyper-Heuristics (`automatic-feature-design-hyper-heuristics`) - low_impact: A standard evolutionary computation and hyper-heuristic research direction rather than an urgent, cross-cutting machine learning bottleneck.
- [open_question] Transferability and Interpretability of Evolved Heuristics (`transferability-and-interpretability-of-heuristics`) - low_impact: Standard future work discussing heuristic generalization within evolutionary algorithms, lacking broader cross-domain machine learning framing.

## Links

- [Abstract](https://arxiv.org/abs/2611.13940)
- [PDF](https://arxiv.org/pdf/2611.13940)

