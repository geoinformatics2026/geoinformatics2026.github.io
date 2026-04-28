---
title: "Integrating DISPATCH and In-Situ Constraints into a 1D-ResUNet for SMAP Soil Moisture Downscaling"
authors:
- "Hailong Zhang"
- "Mei Yang"
- "Yan Jin"

---

# Integrating DISPATCH and In-Situ Constraints into a 1D-ResUNet for SMAP Soil Moisture Downscaling

**Author Information**  
Hailong Zhang<sup>1</sup>, Mei Yang<sup>1</sup>, Yan Jin<sup>1</sup>


<sup>1</sup> Nanjing University of Posts and Telecommunications  



## Abstract

Soil Moisture Active Passive (SMAP) products provide global soil moisture observations but their coarse spatial resolution limits local-scale applications. This study proposes an observation-constrained 1D Residual U-Net (1D-ResUNet) framework for spatially seamless downscaling of SMAP soil moisture to 1 km resolution. The DISPATCH product is incorporated as a physically based prior input, and thirteen 1-km auxiliary variables are used to characterize land surface conditions. To enhance prediction reliability, a hybrid loss function is designed to jointly constrain pixel-level predictions and in-situ observations during model optimization. A 32-km block-based partitioning combined with NDVI-stratified sampling is implemented to ensure objective evaluation. Validation against ground measurements shows that the proposed framework achieves an RMSE of 0.0160, bias of -0.0050, outperforming conventional machine learning methods. The results demonstrate improved spatial consistency and robustness across heterogeneous surface conditions.



Keywords: Soil moisture,  DISPATCH,  1D-ResUNet,  Hybrid loss



```{admonition} Presentation Information
:class: note

**Submission ID:** 9169  
**Session:** [Locust Drought Moisture Propagation](./Session_C6/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45
**Venue:** room 6
```