---
title: "R Shiny App: Volcano Plot Generator"
excerpt: "Interactive web app for visualizing gene expression differences via volcano plots, supporting pairwise comparisons across 2 or 3+ groups with covariate adjustment using lm() and emmeans()."
collection: portfolio
---

## Overview

An interactive R Shiny application for generating volcano plots from gene expression data. Supports covariate-adjusted pairwise comparisons, making it suitable for clinical omics studies where confounders need to be accounted for.

**[View on GitHub](https://github.com/Emomeow/R-shiny)** | **[Live Demo](https://yuezhan.shinyapps.io/Volcano/)**

## Features

- Upload wide-format gene expression data
- Automatic pairwise comparisons using `lm()` and `emmeans()`
- Supports 2-group and 3+ group comparisons
- Covariate adjustment built in
- Interactive volcano plot with significance thresholds
- Highlights up/downregulated genes

## Tools

**R**: shiny, emmeans, ggplot2, dplyr
