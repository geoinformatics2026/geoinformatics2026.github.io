---
title: "Interpretable Generative Diffusion Model for Metro Passenger Flow Prediction and Spatio-Temporal Attribution Analysis: A Case Study of the Taipei Metro, Taiwan"
authors:
- "Shih-Chi Wang"
- "Po-Yen Lin"
- "Yi-Chung Chen"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Interpretable Generative Diffusion Model for Metro Passenger Flow Prediction and Spatio-Temporal Attribution Analysis: A Case Study of the Taipei Metro, Taiwan

**Author Information**  
Shih-Chi Wang<sup>1</sup>, Po-Yen Lin<sup>1</sup>, Yi-Chung Chen<sup>2</sup>


<sup>1</sup> Bachelor Program in Intellectual Creativity Engineering, National Chung Hsing University  

<sup>2</sup> Department of Computer Science and Engineering, National Chung Hsing University  



## Abstract

Accurate metro passenger flow prediction is essential for schedule optimization, crowd management, and urban transit safety. However, existing forecasting methods predominantly focus on numerical accuracy while lacking uncertainty quantification and model interpretability. Transit control centers therefore cannot trace the upstream geospatial origins of sudden overcrowding, limiting preemptive intervention capabilities. This study proposes an interpretable generative diffusion model framework for metro passenger flow prediction and spatio-temporal attribution analysis, applied to the Taipei Metro network in Taiwan using real-world origin-destination flow data from 2017 to 2021. The geospatial network topology is constructed using station coordinates and a Gaussian distance-decay kernel to define the weighted adjacency matrix, capturing the geographic proximity constraints governing passenger propagation. The framework first employs a Diffusion Convolutional Recurrent Neural Network (DCRNN) encoder with bidirectional random-walk-based diffusion convolutions on the directed transit graph to extract spatio-temporal conditional features. These features then guide a Spatio-Temporal 1D U-Net denoising diffusion backbone, which iteratively reconstructs future flow distributions from noise and generates confidence intervals for uncertainty quantification. A cross-attention fusion layer further establishes explicit dependency mappings between predicted future states and historical network conditions. The resulting attention weights are decomposed into spatial attribution heatmaps overlaid on the metro network topology and temporal-lag distribution charts, translating black-box predictions into spatiotemporally interpretable decision support. Furthermore, the upper bounds of these confidence intervals are mapped to a three-color early warning mechanism to flag escalating congestion risks. These visualizations and risk indicators enable operators to identify critical upstream source stations and quantify crowd propagation delays before congestion peaks. The framework is validated against ARIMA, LSTM, and STGCN baselines using MAE, RMSE, and CRPS metrics. This research contributes to GeoAI-driven sustainable urban mobility by bridging generative deep learning with geospatial network analysis for transparent and proactive transit management.



Keywords: Metro Passenger Flow Prediction,  Explainable AI (XAI),  Uncertainty Quantification,  Spatio-Temporal Graph Neural Network,  Generative Diffusion Model,  GeoAI




```{admonition} Presentation Information
:class: note

**Submission ID:** R7914  
**Session:** [Geographical Principles in Spatial Analysis and Modeling](./Session_GSC-4/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 51 (LT-51)  
```