---
title: "PMDNet: Polarimetric Multivariable Decoupling Network for Enhancing Nowcasting"
authors:
- "Wei Li"
- "Qian Li"
- "Liang Zhang"
- "Sheng Li"
- "Tinger Hu"
- "Na Li"
- "Qi Lv"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R7935.pdf
---

# PMDNet: Polarimetric Multivariable Decoupling Network for Enhancing Nowcasting

**Author Information**  
Wei Li<sup>1</sup>, Qian Li<sup>1</sup>, Liang Zhang<sup>1</sup>, Sheng Li<sup>1</sup>, Tinger Hu<sup>1</sup>, Na Li<sup>1</sup>, Qi Lv<sup>1</sup>


<sup>1</sup> National University of Defense Technology  



## Abstract

Nowcasting plays a critical role in public production and life safety, with radar echo extrapolation (REE) serving as a core technique. Existing deep learning-based REE methods often rely primarily on radar reflectivity, which cannot fully characterize the microphysical properties of precipitation particles. In contrast, dual-polarization radar variables, such as differential reflectivity and specific differential phase shift, provide additional information on particle phase, shape, and liquid water content. However, current methods insufficiently exploit the physical correlations and complementary characteristics among these variables. To address this limitation, we propose PMDNet, a Polarimetric Multivariable Decoupling Network designed to explicitly model the correlation and complementarity between dual polarization variables to enhance precipitation nowcasting. PMDNet introduces a Features Decoupling Network that decouples multivariable inputs into cross-variable correlated common representations and variable-specific unique representations, enabling the model to capture both shared physical associations and distinctive microphysical characteristics. A PredNet is designed to perform spatially adaptive fusion and enables multiscale spatiotemporal prediction, which includes a fusion module based on a cross-attention mechanism and a hybrid spatiotemporal prediction module combining Swin Transformer and GRU. In addition, the proposed PMDNet adopts a decoupling–prediction joint training paradigm to reduce feature redundancy and improve representation efficiency. Extensive experiments conducted on the NJU-CPOL and SC-SPOL dual-polarization radar datasets demonstrate that PMDNet consistently outperforms state-of-the-art spatiotemporal prediction and multivariable REE models at both 1-hour and 3-hour lead times. The proposed method achieves competitive performance in CSI, HSS, SSIM, MAE, and RMSE metrics, particularly under high-intensity precipitation thresholds. These results confirm that explicitly modeling the correlation and complementarity of polarimetric variables significantly enhances nowcasting accuracy and generalization across different climatic regions.



Keywords: precipitation nowcasting,  spatiotemporal sequence forecasting,  weather radar



Semantic Tags: precipitation nowcasting; dual-polarization radar; spatiotemporal sequence forecasting; deep learning; radar echo extrapolation; microphysical properties; differential reflectivity; nowcasting accuracy


```{admonition} Presentation Information
:class: note

**Submission ID:** R7935  
**Session:** [Hydrometeorological Forecasting and Precipitation Modeling ](./Session_CED-4/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```