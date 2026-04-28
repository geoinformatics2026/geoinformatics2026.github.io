---
title: "Planning for cooler cities: A multimodal AI framework for hyperlocal spatio-temporal urban heat stress prediction and mitigation"
authors:
- "Shengao Yi"
- "Xiaojiang Li"
- "Wei Tu"
- "Tianhong Zhao"

---

# Planning for cooler cities: A multimodal AI framework for hyperlocal spatio-temporal urban heat stress prediction and mitigation

**Author Information**  
Shengao Yi<sup>1</sup>, Xiaojiang Li<sup>1</sup>, Wei Tu<sup>2</sup>, Tianhong Zhao<sup>3</sup>


<sup>1</sup> University of Pennsylvania  

<sup>2</sup> Shenzhen University  

<sup>3</sup> Shenzhen Technology University  



## Abstract

As extreme heat events intensify due to climate change and urbanization, cities face increasing challenges in mitigating outdoor heat stress. While traditional physical models such as SOLWEIG and ENVI-met provide detailed assessments of human-perceived heat exposure, their computational demands limit scalability for city-wide planning. In this study, we propose GSM-UTCI, a multimodal deep learning framework designed to predict both average and hourly Universal Thermal Climate Index (UTCI) at 1-meter hyperlocal resolution across daytime hours. The model fuses surface morphology (nDSM), high-resolution land cover data, and hourly meteorological conditions using a feature-wise linear modulation (FiLM) architecture that dynamically conditions spatial features on atmospheric context. Trained on SOLWEIG-derived UTCI maps, GSM-UTCI effectively emulates the physical model, achieving an R2 of 0.9151 and a mean absolute error (MAE) of 0.41 °C for daytime average UTCI prediction. Across 11 daytime hours (8 a.m.–6 p.m.), it maintains robust hourly performance with an average R2 of 0.8044 and an average MAE of 0.64 °C. Additionally, GSM-UTCI reduces inference time from days to under five minutes for an entire city, enabling rapid city-wide simulations. To demonstrate its planning relevance, we apply GSM-UTCI to simulate systematic landscape transformation scenarios in Philadelphia. Results demonstrate clear and spatially heterogeneous cooling effects. Notably, converting impervious surfaces to tree canopy leads to the largest reduction in heat exposure, lowering the number of residents experiencing strong heat stress (UTCI > 32 °C) by over 374,000, with an average UTCI decrease of 4.18 °C in affected areas. Tract-level analysis further reveals strong alignment between thermal reduction potential and land cover proportions. These findings highlight the value of the GSM-UTCI framework as a scalable decision-support tool for climate adaptation in Philadelphia, while its extension to other cities remains a key direction for future validation.



Keywords: Heat stress,  Multimodal deep learning,  UTCI,  SOLWEIG,  Landscape transformation



```{admonition} Presentation Information
:class: note

**Submission ID:** 2990  
**Session:** [Thermal Heat Tod Surface](./Session_F3/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 16:30 – 17:45
**Venue:** room 3
```