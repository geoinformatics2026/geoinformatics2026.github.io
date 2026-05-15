---
title: "Deep learning-based spatiotemporal fusion of satellite observations and dynamic background fields for improved short-term precipitation forecasting"
authors:
- "Na Zhao"
- "Mingxiao Xu Xu"

---

# Deep learning-based spatiotemporal fusion of satellite observations and dynamic background fields for improved short-term precipitation forecasting

**Author Information**  
Na Zhao<sup>1</sup>, Mingxiao Xu Xu<sup>1</sup>


<sup>1</sup> Institute of Geographic Science and Natural Resources Research  



## Abstract

Short-term precipitation nowcasting is of crucial significance to hydrological disaster early warning, water resource management and ecological environment regulation. However, traditional nowcasting models rely on pure data extrapolation, which is inherently deficient in physical constraints and prone to severe cumulative errors in long-time-scale forecasts, thus severely limiting their practical application in extreme precipitation events. To address this critical issue, this study proposes a novel multimodal deep learning forecasting scheme that integrates high-frequency Integrated Multi-satellite Retrievals for GPM (IMERG) satellite observation data with the dynamic background field of the FuXi meteorological large model to achieve accurate 0–6 hours short-term precipitation prediction. In data construction, ERA5 reanalysis data simulates the 6-hourly output of the FuXi model (70 variables in total), which is matched with 30-minute interval IMERG precipitation observations. A "spatiotemporal packaging" strategy is designed to resolve spatiotemporal resolution inconsistency. The model takes SwinLSTM as the backbone to capture nonlinear precipitation cluster displacement, and incorporates a Gate mechanism for channel feature selection, transposed convolution for spatial downscaling (0.25° to 0.1°) and cross-modal cross-attention for pixel-level feature interaction at T=0 and T=6. Adopting an "anchor fusion and intermediate extrapolation" strategy, it initializes physical background with dynamic constraints, conducts autonomous extrapolation via SwinLSTM and implements residual correction at the 6th hour. Experiments in the Beijing-Tianjin-Hebei region show SwinLSTM achieves the lowest MSE (0.87) among five models, outperforming Optical Flow, ConvLSTM and PredRNN series. Its modeling capacity for light, moderate and heavy precipitation is improved by 8%–55% compared with traditional algorithms, with CSI, HSS and POD metrics all showing steady improvement. The scheme effectively integrates satellite observation details with large model dynamic consistency, enhancing the accuracy and physical rationality of extreme precipitation forecasting, and providing a new technical approach for nowcasting and hydrological disaster mitigation.



Keywords: Deep learning,  Precipitation,  Data fusion



Semantic Tags: precipitation nowcasting; deep learning; spatiotemporal data fusion; satellite observations; background fields; hydrological forecasting; multi-source fusion; extreme precipitation


```{admonition} Presentation Information
:class: note

**Submission ID:** R9629  
**Session:** [Hydrometeorological Forecasting and Precipitation Modeling ](./Session_CED-4/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-C  
```