---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
3rd year Biostatistics Ph.D. student specializing in joint models, causal inference, and dynamic prediction for complex clinical data. Experienced in collaborating with multidisciplinary teams, managing clinical datasets, and communicating results for non-statisticians. 1 year experience in consulting across dermatology, oncology, radiology, and adolescent health studies. 1 year experience in deep learning and reinforcement learning using PyTorch.

Education
======
* Ph.D. in Biostatistics, University of Nebraska Medical Center, Omaha, NE (Aug 2023 – Present), GPA: 3.97/4.00; Qualifying Exam Passed.
  * Thesis: Joint analysis for biomarkers with a change point anchored at interval-censored event
  * Courses: Survival Analysis, Correlated Data Analysis, Bayesian Theory and Method, Causal Inference, Theory of Generalized Linear/Mixed Models, High Dimensional Inference and Multiple Testing, Advanced Biostatistics Theory I/II
* B.S. in Mathematics and Applied Mathematics, Shanghai Jiao Tong University, Shanghai, China (Sept 2019 – Jun 2023), GPA: 3.68/4.30.
  * Thesis: Temporal Difference Algorithm's Implicit Bias and Continuous Modeling
  * Courses: Probability Theory, Mathematical Statistics, Stochastic Processes, Statistical Learning, Ordinary Differential Equations

Research Experience
======
* Graduate Research Assistant, University of Nebraska Medical Center (Aug 2023 – Present)
  * Dissertation: Joint analysis for multivariate biomarkers with a change point anchored at interval-censored event time, with applications to Huntington's Disease (HD).
  * Topic 1: Two-phase joint model for change point biomarkers and interval-censored data.
    * Proposed a two-phase joint model with biomarker trajectories that change after an interval-censored event time.
    * Used B-spline to approximate the cumulative hazard; Fisher-scoring algorithm for MLE.
    * Validated via repeated simulations and bootstrap in R; applied to PREDICT-HD data.
    * Extended to Bayesian framework using Rstan and HMC sampling for posterior inference.
  * Topic 2: Causal mediation analysis and dynamic prediction based on the two-phase joint model.
    * Used g-formula to compute natural direct and indirect effects (NDE/NIE) of covariates on biomarkers and survival.
    * Applied to HD data to demonstrate CAP score's causal pathways on onset and biomarker trajectories.
    * Derived joint predictive distribution of biomarkers and event time using Bayesian posterior for individual-level prediction.

* OLR1+ Lipid-Associated TAMs Drive Immune Exclusion in MMRp Colorectal Cancer (Independent Project)
  * Conducted a six-phase single-cell RNA-seq analysis integrating 153,136 cells from five cohorts using scVI/scANVI.
  * Identified OLR1+ TAM differentiation with 75.5× enrichment in CRC; characterized SPP1-ITGAV and LGALS1-CD69 crosstalk with FAP+ myofibroblasts as immune exclusion mechanisms.
  * Built an Attention-MIL patient stratification model (AUC = 0.909); validated findings in GSE188711 and TCGA-COAD cohorts.
  * Tools: Python (scvi-tools, scanpy, PyTorch, palantir), R (NicheNet), LIANA.

* Temporal Difference Algorithm's Implicit Bias and Continuous Modeling, Shanghai Jiao Tong University (Sept 2022 – Jun 2023)
  * Explored implicit regularization and convergence properties of temporal difference (TD) algorithms in reinforcement learning.
  * Developed RL agents and environments using PyTorch, NumPy, and Gymnasium; analyzed convergence across environment settings.

Work Experience
======
* Graduate Research Assistant, ProjectDRIVE randomized trial, University of Nebraska Medical Center (Aug 2025 – Present)
  * Managed and cleaned longitudinal adolescent driving safety data; imputed missing values for improved efficiency.
  * Used T-test and ANOVA to assess group balance at randomization; built R Shiny dashboard to present results.
  * Applied linear mixed effects models (LMM) to study communication score trajectories and group-by-assessment interactions.

* Graduate Research Assistant, Center for Collaboration on Research Design and Analysis (CCORDA), University of Nebraska Medical Center (Aug 2024 – Jun 2025)
  * Provided statistical consulting on clinical trial design, sample size calculation, and test selection across diverse fields.
  * Analyzed clinical and REDCap data (data cleaning, descriptive analysis, regression, survival analysis) in SAS and R; created TLF visualizations.
  * Selected project highlights:
    * Dermatology – Wilcoxon signed-rank and McNemar's tests for patient-reported vs. actual SC/AK/chemoprevention outcomes.
    * Oncology (AML) – K-M curves, log-rank tests, and Cox regression to identify GA impairments affecting overall survival.
    * Radiology – ROC/AUC analysis for FA and MD histogram statistics to differentiate HGG from benign MRI lesions.
    * Oncology (Prostate) – SAS Macro tables and T-test for FRAX scores across Prednisone use and hip fracture groups.

* Graduate Teaching Assistant, University of Nebraska Medical Center (Aug 2023 – May 2024)
  * Teaching assistant in Intro to SAS (Fall 2023) and Biostatistics II (Spring 2024).

Technical Skills
======
* Programming: R (ggplot2, shiny, survival, tidyverse), SAS (Macro, SQL), Python (NumPy, Matplotlib, PyTorch)
* Tools: SQL, SPSS, R Markdown, Microsoft Office Suite, Parallel Computing, Excel VBA, Git, Power BI, AWS
* Certifications: SAS Certified Professional: Base/Advanced Programming Using SAS 9.4; Deep Learning Specialization

Awards
======
* Winner, 2026 LiDS (Lifetime Data Science) Student Paper Competition — *Joint analysis for multivariate longitudinal and event time data with a change point anchored at interval-censored event time*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Service and Leadership
======
* Collaborative statistical consulting across dermatology, oncology, radiology, and adolescent health studies.
