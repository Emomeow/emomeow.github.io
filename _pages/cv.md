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
Biostatistics Ph.D. candidate specializing in joint models, causal inference, and dynamic prediction for complex clinical data. Experienced in collaborating with multidisciplinary teams, managing clinical datasets, and communicating results for non-statisticians.

Education
======
* Ph.D. in Biostatistics, University of Nebraska Medical Center, Omaha, NE (Aug 2023 – Present), GPA: 3.97/4.00; Qualifying Exam Passed. Thesis: Joint analysis for biomarkers with a change point anchored at interval-censored event.
* B.S. in Mathematics and Applied Mathematics, Shanghai Jiao Tong University, Shanghai, China (Sept 2019 – Jun 2023), GPA: 3.68/4.30. Thesis: Temporal Difference Algorithm’s Implicit Bias and Continuous Modeling.

Research experience
======
* Graduate Research Assistant, University of Nebraska Medical Center (Aug 2023 – Present)
  * Developed two-phase joint models for multivariate biomarkers with change points around interval-censored events; applied to Huntington’s Disease data and validated via simulation and bootstrap.
  * Built causal mediation and dynamic prediction frameworks on top of joint models to quantify natural effects of covariates and deliver individualized event-time predictions.
* Temporal Difference Algorithm’s Implicit Bias and Continuous Modeling, Shanghai Jiao Tong University (Sept 2022 – Jun 2023)
  * Explored implicit regularization and convergence properties of temporal difference algorithms through PyTorch simulations and visualization.

Work experience
======
* Graduate Research Assistant, ProjectDRIVE randomized trial, University of Nebraska Medical Center (Aug 2025 – Present)
  * Managed and cleaned longitudinal adolescent driving safety data, assessed group balance, and visualized results with R.
  * Applied linear mixed effects models to study communication score trajectories and group-by-assessment interactions.
* Graduate Research Assistant, Center for Collaboration on Research Design and Analysis (CCORDA), University of Nebraska Medical Center (Aug 2024 – Jun 2025)
  * Consulted on clinical trial design, sample size estimation, and statistical testing across dermatology, oncology, and radiology studies.
  * Led data cleaning, descriptive analysis, regression, and survival modeling in SAS and R, delivering TLF visualizations for investigators.
  * Selected project highlights: patient-reported vs. actual dermatology outcomes; geriatric assessment prognostic factors in AML; MRI histogram analyses for lesion differentiation; FRAX risk profiling in prostate cancer.

Teaching experience
======
* Graduate Teaching Assistant, University of Nebraska Medical Center (Aug 2023 – May 2024)
  * Intro to SAS (Fall 2023) and Biostatistics II (Spring 2024).

Technical skills
======
* Programming: R (ggplot2, shiny, survival, tidyverse), SAS (Macro, SQL), Python (NumPy, Matplotlib, PyTorch)
* Tools: SQL, SPSS, R Markdown, Microsoft Office Suite, Parallel Computing, Excel VBA, Git, Power BI
* Certification: SAS Certified Professional: Base/Advanced Programming Using SAS 9.4

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

Service and leadership
======
* Collaborative statistical consulting across dermatology, oncology, radiology, and adolescent health studies.
