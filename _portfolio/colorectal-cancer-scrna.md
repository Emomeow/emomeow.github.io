---
title: "OLR1+ Lipid-Associated TAMs Drive Immune Exclusion in MMRp Colorectal Cancer"
excerpt: "Single-cell RNA-seq analysis of immune resistance mechanisms in microsatellite-stable colorectal cancer, integrating 153,136 cells across five cohorts to characterize tumor microenvironment and identify suppressive immune populations."
collection: portfolio
---

## Overview

A comprehensive six-phase single-cell RNA-seq analysis investigating immune resistance mechanisms in microsatellite-stable (MMRp) colorectal cancer. Integrates 153,136 cells from five cohorts to characterize tumor microenvironment composition and identify suppressive immune populations.

**[View on GitHub](https://github.com/Emomeow/colorectal-cancer)**

## Key Finding

OLR1+ lipid-associated tumor-associated macrophages (TAMs) form positive-feedback crosstalk loops with FAP+ myofibroblasts via SPP1-ITGAV and LGALS1-CD69 signaling, creating immune exclusion barriers that drive resistance to immunotherapy in MMRp CRC.

## Analysis Pipeline

1. **Multi-cohort integration** — scVI/scANVI integration of 153,136 cells across 10 lineages from five independent cohorts
2. **Trajectory analysis** — Identified OLR1+ TAM differentiation with 75.5× enrichment in colorectal cancer vs. normal tissue
3. **Patient stratification** — Attention-MIL model for patient stratification (AUC = 0.909)
4. **Cell communication** — LIANA/NicheNet analysis of intercellular signaling and metabolic mechanisms
5. **Independent validation** — Validated findings in GSE188711 and TCGA-COAD cohorts

## Technologies

- **Python**: scvi-tools, scanpy, palantir, PyTorch (Attention-MIL)
- **R**: Metabolic pathway analysis, NicheNet
- **Tools**: LIANA, scANVI, single-cell trajectory inference
