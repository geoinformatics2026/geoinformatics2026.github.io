---
title: "Deep learning driven spatiotemporal prediction of global carbon emissions from container shipping"
authors:
- "Hongchu Yu"
- "Chenxi Jiang"
- "Qinglong Fang"
- "Tianming Wei"
- "Lei Xu"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R1696.pdf
---

# Deep learning driven spatiotemporal prediction of global carbon emissions from container shipping

**Author Information**  
Hongchu Yu<sup>1</sup>, Chenxi Jiang<sup>1</sup>, Qinglong Fang<sup>1</sup>, Tianming Wei<sup>1</sup>, Lei Xu<sup>2</sup>


<sup>1</sup> School of Navigation, Wuhan University of Technology  

<sup>2</sup> National Engineering Research Center for Geographic Information System, China University of Geosciences (Wuhan)  



## Abstract

Container shipping is a major contributor to global CO₂ emissions, and fine-grained forecasting of emission hotspots is essential for proactive maritime environmental management. This study develops a deep learning framework for global, grid-based spatiotemporal prediction of container-ship carbon emissions derived from AIS-based bottom-up inventories. Daily emissions are mapped to global raster images and normalized to stabilize learning, then organized with a sliding-window strategy to model temporal dependence. We propose ConvLSTM-CBAMNet, which integrates a Convolutional Long Short-Term Memory (ConvLSTM) encoder with a lightweight Convolutional Block Attention Module (CBAM) to enhance both channel-wise feature selection and spatial localization of salient emission regions. The model is evaluated on a 360×180 global grid using RMSE, MAE, and SSIM to jointly assess numerical accuracy and spatial-structure fidelity. Compared with four representative baselines (Transformer, ConvGRU, CNN-LSTM, and standard ConvLSTM), ConvLSTM-CBAMNet achieves the best overall performance (RMSE 0.0914, MAE 0.0432, SSIM 0.9035), delivering substantial gains over the strongest baseline ConvLSTM (RMSE reduction 19.4%, MAE reduction 16.8%, SSIM increase 5.8%). Robustness experiments with multiple random seeds show consistently lower variance and statistically significant improvements (paired t-tests, p < 0.01). Visual comparisons further indicate that the proposed method better preserves the boundaries and textures of high-emission corridors along major shipping lanes and around ports, and mitigates error accumulation in multi-step recursive forecasting. The resulting predictions can support dynamic identification of future emission hotspots, inform the adjustment of Emission Control Areas, and enable pollution-peak mitigation through operational planning, contributing to data-driven decarbonization strategies for the shipping sector.



Keywords: Spatiotemporal prediction,  Deep learning,  Container ships,  Carbon emissions,  AIS data



Semantic Tags: container shipping; carbon emissions; deep learning; spatiotemporal prediction; AIS data; ConvLSTM; global maritime emissions; emission hotspot; ocean monitoring


```{admonition} Presentation Information
:class: note

**Submission ID:** R1696  
**Session:** [Transport Emissions and Low-Carbon Urban Mobility Systems ](./Session_TMU-2/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** TP-Lv2-SR-F (Room-5/6)  
```