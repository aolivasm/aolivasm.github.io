---
title: "Research"
permalink: /research/
layout: single
author_profile: true
---

My methodological research lies at the intersection of causal inference and semiparametric theory. I am particularly interested in addressing unmeasured confounding using instrumental variables, proxy variables, and sensitivity analysis, while allowing for flexible statistical modeling. My work also investigates estimation and regularization in ill-posed inverse problems.

## Methodological work

- **Sharp Instrumental Variable Bounds under The Marginal Sensitivity Model** — with Eric Tchetgen Tchetgen, *arXiv preprint* (2026).<br>
  Develops a framework that combines instrumental variable assumptions with marginal sensitivity models to obtain sharp bounds on causal effects under unmeasured confounding. The paper characterizes the identified sets and develops cross-fitted estimators and confidence sets for valid statistical inference.<br>
  [Preprint](https://arxiv.org/abs/2610.22513) · [R implementation](https://github.com/aolivasm/iv-msm-sa)

- **Proximal Causal Inference for Modified Treatment Policies** — with Peter B. Gilbert and Andrea Rotnitzky, *arXiv preprint* (2025).<br>
  Extends proximal causal inference to continuous exposures and realistic treatment modifications in settings with unmeasured confounding, using negative controls and debiased machine learning. Motivated by vaccine immunobridging studies.<br>
  [Preprint](https://arxiv.org/abs/2512.12038) · [R implementation](https://github.com/aolivasm/proxi-mtp)

- **Source-Condition Analysis of Kernel Adversarial Estimators** — with Andrea Rotnitzky, *arXiv preprint* (2025).<br>
  Finite-sample analysis of RKHS-regularized adversarial estimators for ill-posed regression, comparing their stability and assumptions with existing methods.<br>
  [Preprint](https://arxiv.org/abs/2508.17181)

- **A General Framework for Designing and Evaluating Active-Controlled Trials with Non-Inferiority Objectives** — with Fei Gao and Holly Janes, *Statistics in Medicine* (2026).<br>
  Unifies analytical methods and success criteria for active-controlled trials, enabling systematic comparison of type I error, power, robustness, and design trade-offs.<br>
  [Article](https://doi.org/10.1002/sim.70618) · [R implementation](https://github.com/aolivasm/ni-design)

## Research software

- **[iv-msm-sa](https://github.com/aolivasm/iv-msm-sa)** — R package implementing estimation and inference for sharp causal effect bounds under marginal sensitivity models with instrumental variables.
- **[proxi-mtp](https://github.com/aolivasm/proxi-mtp)** — R code and a simulated dataset demonstrating a doubly robust, cross-fitted estimator for proximal modified treatment policy effects.
- **[ni-design](https://github.com/aolivasm/ni-design)** — R package for designing and evaluating active-controlled non-inferiority trials, supporting preservation-of-effect and inferred-efficacy criteria, fixed-margin and synthesis methods, conditional and unconditional power, sample-size calculations, and sensitivity analyses.

## Selected collaborative projects
- **Immune Correlates and Vaccine Immunobridging: Statistical Innovations, Challenges, and Opportunities** — Co-author, *The Journal of Infectious Diseases* (2025).
  *Overview of recent statistical developments relevant to immunobridging, including variable importance prediction for correlates of risk, controlled risk causal analysis for correlates of protection, and vaccine efficacy transportability methods.*
  [DOI](https://doi.org/10.1093/infdis/jiaf451)
- **Test Sensitivity in a Prospective Cancer Screening Program: A Critique of a Common Proxy Measure** — Co-author, *Statistical Methods in Medical Research* (2023).  
  *Analyzed the relationship between empirical and true sensitivity in cancer screening programs, clarifying conditions under which proxy measures can misrepresent diagnostic performance.* 
  [DOI](https://doi.org/10.1177/09622802221142529)
- **Sensitivity Measures in Studies of Cancer Early Detection Biomarkers** — Co-author, *Cancer Epidemiology, Biomarkers & Prevention* (2025).  
  *Investigated how sensitivity estimates from different phases of biomarker development relate to true preclinical sensitivity, highlighting biases that can arise across study designs and screening intervals.*  
  [DOI](https://doi.org/10.1158/1055-9965.EPI-24-1849)

For a broader publication list, see [Google Scholar](https://scholar.google.com/citations?user=ItjU968AAAAJ&hl=en), [ORCID](https://orcid.org/0000-0003-2779-0068), or my [applied work](/applied-research/).
