---
title: "Heterogeneous Spatio-Temporal Graph Learning for Localized Sparse Meteorological Forecasting"
authors:
- "Sheng Li"
- "Qian Li"
- "Wei Li"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R1870.pdf
---

# Heterogeneous Spatio-Temporal Graph Learning for Localized Sparse Meteorological Forecasting

**Author Information**  
Sheng Li<sup>1</sup>, Qian Li<sup>1</sup>, Wei Li<sup>1</sup>


<sup>1</sup> National University of Defense Technology  



## Abstract

Localized meteorological forecasting is essential for human socio-economic activities, but it remains challenging due to the inherent complexity of atmospheric dynamics. Current deep learning-based forecasting methods primarily rely on structured reanalysis data, which can introduce uncertainty errors during the assimilation of multisource observational data, particularly in regions with sparse weather stations. Furthermore, relying exclusively on the sparse and unstructured nature of ground observational data fails to accurately capture localized meso-scale and micro-scale meteorological conditions. To address these limitations, we propose a Heterogeneous Spatio-temporal Graph Neural Network (HSTGNN) designed to integrate sparse ground observational data with large-scale reanalysis data for precise in situ forecasting of localized meteorological variables. The proposed framework consists of three core components: 1) Hybrid Graph Constructor (HGC): Maps sparse observations and gridded reanalysis data into heterogeneous nodes, building a hybrid topological structure through a dual-channel mechanism that combines geographical distance graphs and data-driven adaptive learning graphs. 2) Hierarchical Heterogeneous Message Passing Module (H²MPM): Hierarchically processes relationships among multisource meteorological variables, enabling differentiated feature interactions and fully capturing complex spatial dependencies across heterogeneous data. 3) Temporal Linear Unit (TLU): Leverages a single-layer linear regression model combined with a direct multistep prediction strategy to efficiently extract temporal dependencies and perform sequential forecasting for each station. Extensive experiments conducted on two real-world datasets demonstrate that HSTGNN effectively models the spatio-temporal dependencies inherent in heterogeneous meteorological data. The results show that the proposed framework comprehensively captures localized meteorological patterns and achieves outstanding, state-of-the-art predictive performance under sparse observational conditions.



Keywords: Heterogeneous graph neural network,  Meteorological forecasting,  Spatio-temporal forecasting



Semantic Tags: meteorological forecasting; heterogeneous graph neural network; spatiotemporal forecasting; sparse weather stations; atmospheric dynamics; deep learning; graph structure; localized prediction


```{admonition} Presentation Information
:class: note

**Submission ID:** R1870  
**Session:** [Hydrometeorological Forecasting and Precipitation Modeling ](./Session_CED-4/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** TP-Lv2-SR-D (Room-3/4)  
```