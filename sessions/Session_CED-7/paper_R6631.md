---
title: "Multi-Scale Spatio-Temporal Graph Convolutional Networks for Dynamic Sub-district-Level Urban Fire Risk Prediction"
authors:
- "Dong Xie"
- "Jingnan Huang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R6631.pdf
---

# Multi-Scale Spatio-Temporal Graph Convolutional Networks for Dynamic Sub-district-Level Urban Fire Risk Prediction

**Author Information**  
Dong Xie<sup>1</sup>, Jingnan Huang<sup>1</sup>


<sup>1</sup> Wuhan University  



## Abstract

Precise sub-district-level fire risk prediction is critical for developing resilient cities. Traditional models often fail to adequately capture the complex, non-linear spatiotemporal dependencies inherent in urban environments. This study aims to accurately forecast dynamic fire risks and optimize rescue resource allocation by comprehensively modeling the urban spatial structure. We propose a multi-scale Spatio-Temporal Graph Convolutional Network (ST-GCN) framework, using Wuhan as a case study. To rigorously capture temporal dynamics, the ST-GCN architecture processes daily graph sequences, further enriched by 7-day and 30-day historical fire lags as explicit node features. Simultaneously, spatial graph convolutions aggregate spillover effects across the spatial adjacency of sub-districts. For dual interpretability, we decode spatial determinants via GNNExplainer and evaluate temporal performance stability using a weighted 7-step lag-window similarity matrix. The ST-GCN significantly outperforms traditional baselines, achieving AUCs of 0.75, 0.76, and 0.84 for short-, medium-, and long-term predictions. Explainability analysis reveals that anthropogenic activities and built environments—specifically building year, population density, and floor area ratio—dominate fire risks. Crucially, risk drivers exhibit pronounced spatial heterogeneity: residential and educational risks are population-driven; commercial blocks depend on facility density; whereas industrial zones are distinctly sensitive to wind speed. Interaction subgraph analysis shifts urban management from isolated hotspot identification to dynamic topological intervention, unveiling critical “risk transmission corridors” requiring joint prevention, and natural “safety buffers” (firebreaks) that necessitate preservation. Furthermore, spatial analysis exposes a severe rescue resource mismatch, with only 41.41% of sub-districts meeting the 5-minute response standard. Scenario simulations prove that expanding fire station service radii is far more efficient than in-situ hardware upgrades, potentially increasing coverage to 62.12%. This study provides quantitative, actionable pathways for optimizing spatial rescue allocation and enhancing urban resilience.



Keywords: Spatio-Temporal Graph Convolutional Network,  Sub-district-Level Fire Risk,  Explainable GeoAI,  Urban Safety Resilience,  Fire Rescue Resource Allocation



Semantic Tags: fire risk prediction; spatio-temporal graph convolutional network; GeoAI; urban safety resilience; explainable AI; rescue resource allocation; Wuhan


```{admonition} Presentation Information
:class: note

**Submission ID:** R6631  
**Session:** [Wildfire Detection, Simulation, and Disaster Monitoring](./Session_CED-7/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```