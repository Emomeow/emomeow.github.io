---
title: "PhD Thesis: Joint Analysis for Multivariate Biomarkers with a Change Point Anchored at Interval-Censored Event Time"
excerpt: "R implementation of a two-phase joint modeling framework for longitudinal biomarkers and interval-censored event times, with applications to Huntington's Disease progression data from the PREDICT-HD study."
collection: portfolio
---

## Overview

This repository contains the R code for my PhD dissertation, implementing a joint statistical modeling framework that simultaneously analyzes longitudinal biomarker trajectories and interval-censored event times. The methodology captures how biological markers change before and after an unobserved disease onset event.

**[View on GitHub](https://github.com/Emomeow/PhD-Thesis)**

## Methods

- **Two-phase longitudinal sub-model**: Mixed-effects regression capturing biomarker trajectories with an abrupt change point anchored at the interval-censored event time
- **Survival sub-model**: Proportional hazards model for interval-censored diagnosis times; baseline hazard specified as constant, piecewise constant, or B-spline
- **Estimation**: MLE via Gauss-Hermite quadrature and Fisher-scoring algorithm
- **Bootstrap resampling**: Standard error computation and model validation
- **Causal mediation analysis**: G-formula approach for natural direct and indirect effects
- **Dynamic prediction**: Bayesian posterior predictive distribution for individualized event-time prediction

## Application

Applied to the PREDICT-HD study to examine cognitive biomarkers (Symbol Digit Modalities Test, Stroop Word Reading) and understand progression patterns before and after Huntington's Disease onset.

## Tools

**R**: MASS, dplyr, splines2, statmod, survival, ggplot2, JMbayes2
