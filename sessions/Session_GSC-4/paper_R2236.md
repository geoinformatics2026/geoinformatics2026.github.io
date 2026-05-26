---
title: "AI-PriSM: Voxel-Ready Cellular Grids for Explainable, Policy-Oriented Population Migration Forecasting"
authors:
- "Yohan Chang"
- "Jae Soen Son"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R2236.pdf
---

# AI-PriSM: Voxel-Ready Cellular Grids for Explainable, Policy-Oriented Population Migration Forecasting

**Author Information**  
Yohan Chang<sup>1</sup>, Jae Soen Son<sup>1</sup>


<sup>1</sup> Korea Research Institute for Human Settlements  



## Abstract

Population migration statistics compiled by administrative districts are ill-suited to represent functional urban dynamics because boundaries change and rarely align with living spheres and transport networks. We develop AI-PriSM (AI-based Policy-oriented Spatio-temporal Prediction for Population Migration), a GeoAI decision-support framework that forecasts migration on a 1 km cellular grid and is conceptually voxel-ready for future 3D grid (volumetric) extensions. AI-PriSM is organized into (1) a Migration Volume Prediction module and (2) a Previous-Address (origin) prediction module. The volume module integrates settlement-condition indicators with high expected relevance to migration, including commercial activity, business and employment density, and rail/subway accessibility, and redistributes these variables onto the grid under a Cellular Geography workflow. We benchmark XGBoost, multilayer perceptrons, and reinforcement learning, and apply heuristic hyperparameter optimization (tabu search and genetic algorithms) to improve robustness. To model origin-destination structure, the origin module employs a spatio-temporal graph attention architecture (ST-GRAT) to learn inter-regional movement patterns across multiple origins and destinations. Explainability is built in via SHAP-based attribution to reduce black-box risk and improve policy traceability. Results highlight population size (total population and households) as the dominant driver of migration, followed by rail/subway accessibility and business density, offering quantitative evidence for the continued concentration of population in the Seoul metropolitan area. While ST-GRAT effectively captures movement structure, it shows limitations in predicting absolute migration volumes, indicating the need for further calibration and model advancement. The framework supports ex-ante policy simulations for interventions such as transport infrastructure expansion, housing development, and industrial park siting, enabling more efficient budget allocation and proactive responses to regional decline. A voxel-ready grid design provides a clear pathway to incorporate vertical urban form and multi-level transport systems in subsequent work.



Keywords: GeoAI,  population migration,  cellular geography,  grid/voxel framework,  explainable AI (SHAP),  spatio-temporal graph attention,  policy simulation,  transportation accessibility



Semantic Tags: GeoAI; population migration forecasting; cellular geography; explainable AI; spatio-temporal graph attention; policy simulation; transportation accessibility; China


```{admonition} Presentation Information
:class: note

**Submission ID:** R2236  
**Session:** [Geographical Principles in Spatial Analysis and Modeling](./Session_GSC-4/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv2-LT-52  
```