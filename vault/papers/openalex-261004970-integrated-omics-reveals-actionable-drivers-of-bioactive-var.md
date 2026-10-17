---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Integrated omics reveals actionable drivers of bioactive variation in US milk"
description: "This paper presents an integrated seven-layer omics characterization of 60 US retail milk samples, identifying 6,714 compounds and establishing absolute concentrations for 5,288 of them. The authors organized these findings into the web-accessible Dairy Molecule Database (DMD) to link milk compound variations with genetic, transcriptomic, and product-level factors. Furthermore, computational prediction and in vitro testing identified novel antimicrobial peptides active against drug-resistant pathogens, highlighting actionable drivers for milk quality optimization."
resource: "https://arxiv.org/abs/2610.04970"
tags:
  - "multi-omics"
timestamp: "2026-10-17T08:58:50Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Cheng-En Tan"
  - literal: "Mariana Barboza"
  - literal: "Pagkratios Tagkopoulos"
  - literal: "Shanghyeon Kim"
  - literal: "Lukas Maximilian Masopust"
  - literal: "Ivor Prado"
  - literal: "Muhammad Adil Salim"
  - literal: "Fangzhou Li"
  - literal: "George Berdovskiy"
  - literal: "Ilias Apostolakos"
  - literal: "Brandon Invergo"
  - literal: "Karen M. Kalanetra"
  - literal: "Danielle G. Lemay"
  - literal: "David Andrew Mills"
  - literal: "Armin Oloumi"
  - literal: "Cheng-Yu Weng"
  - literal: "Carlito B. Lebrilla"
  - literal: "Xuan He"
  - literal: "Slupsky Carolyn"
  - literal: "Oliver Fiehn"
  - literal: "Ibuki Kusumoto"
  - literal: "Ameer Y. Taha"
  - literal: "Yu Wang"
  - literal: "Daniela Barile"
  - literal: "Alexis Davis"
  - literal: "David E. Olson"
  - literal: "Justin B. Siegel"
  - literal: "Ilias Tagkopoulos"
issued:
  date-parts:
    - [2026, 10, 4]

# Domain-specific custom fields
paper_id: "2610.04970"
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
processed_at: "2026-10-17T08:58:50Z"
created_at: "2026-10-17T08:58:50Z"
---

# Integrated omics reveals actionable drivers of bioactive variation in US milk

**Authors**: Cheng-En Tan, Mariana Barboza, Pagkratios Tagkopoulos, Shanghyeon Kim, Lukas Maximilian Masopust, Ivor Prado, Muhammad Adil Salim, Fangzhou Li, George Berdovskiy, Ilias Apostolakos, Brandon Invergo, Karen M. Kalanetra, Danielle G. Lemay, David Andrew Mills, Armin Oloumi, Cheng-Yu Weng, Carlito B. Lebrilla, Xuan He, Slupsky Carolyn, Oliver Fiehn, Ibuki Kusumoto, Ameer Y. Taha, Yu Wang, Daniela Barile, Alexis Davis, David E. Olson, Justin B. Siegel, Ilias Tagkopoulos
**Date**: 2026-10-04
**Paper ID**: [openalex:2610.04970](https://arxiv.org/abs/2610.04970)

## Summary

This paper presents an integrated seven-layer omics characterization of 60 US retail milk samples, identifying 6,714 compounds and establishing absolute concentrations for 5,288 of them. The authors organized these findings into the web-accessible Dairy Molecule Database (DMD) to link milk compound variations with genetic, transcriptomic, and product-level factors. Furthermore, computational prediction and in vitro testing identified novel antimicrobial peptides active against drug-resistant pathogens, highlighting actionable drivers for milk quality optimization.

## Key Contributions

- Performed an integrated seven-layer omics characterization (genomics, transcriptomics, peptidomics, proteomics, lipidomics, metabolomics, and glycomics) on 60 US retail milk samples across ten geographic regions.
- Identified 6,714 compounds and quantified 5,288 with absolute concentrations, adding 5,220 compounds previously unavailable in existing databases.
- Established the Dairy Molecule Database (DMD), a web-accessible resource linking milk compound concentrations with SNPs, miRNAs, and product-level factors.
- Validated 35 out of 54 computationally predicted antimicrobial candidate peptides, with 6 demonstrating IC50 values below 256 μg/mL against A. baumannii.

## Limitations

The study evaluates 60 US retail samples, and further validation across broader geographic and seasonal scales is necessary to fully establish causal links for supply-chain and breeding interventions.

## Archivist Review

The paper presents an extensive biological multi-omics study on commercial milk, introducing a domain-specific database (Dairy Molecule Database). While valuable for agricultural and nutritional science, it does not introduce a reusable machine learning algorithm, architecture, or general computational method suited for an ML knowledge vault. Therefore, all candidate concepts are rejected.

### Rejected Candidates
- [concept] Dairy Molecule Database (`dairy-molecule-database`) - not_reusable: Domain-specific biological database rather than a reusable machine learning or computational method.

## Links

- [Abstract](https://arxiv.org/abs/2610.04970)
- [PDF](https://arxiv.org/pdf/2610.04970)

