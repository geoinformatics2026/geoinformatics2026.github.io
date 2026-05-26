---
title: "A WRF-ML hybrid modeling framework for characterizing near-surface meteorological fields and LCZ-based microclimate spatiotemporal patterns."
authors:
- "Wen Liu"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R1822.pdf
---

# A WRF-ML hybrid modeling framework for characterizing near-surface meteorological fields and LCZ-based microclimate spatiotemporal patterns.

**Author Information**  
Wen Liu<sup>1</sup>


<sup>1</sup> Shenzhen University  



## Abstract

Understanding microclimatic variations across Local Climate Zones (LCZs) is crucial for optimizing urban morphology to enhance human thermal comfort and promote sustainable urban environments. While numerous studies have examined the spatio-temporal patterns and underlying mechanisms of thermal environments in different LCZ types, temperature variability within identical LCZs remain insufficiently explored. Moreover, research on other microclimate factors—such as relative humidity (RH) and wind speed (WS)—at both inter- and intra-LCZ scales is limited. In this study, a hybrid modeling framework based on the Weather Research and Forecast (WRF) model was proposed to accurately predict near-surface meteorological fields. lt was achieved by refining the Urban Canopy Model (UCM) during the preprocessing stage of the WRF model and then integrating ML algorithms during its postprocessing stage. The predictive performance of four WRF-based datasets was evaluated and compared under relatively stable weather conditions across four seasons. The best-performing ML(XGBoost)-enhanced model dataset was applied to identify multivariate microclimate variations both inter- and intra-LCZs. The analysis was conducted in Shenzhen, southern China. The results revealed that: (1) the WRF-ML hybrid models performed significantly better than the Standard and UCM-refined WRF models, with the optimal XGBoost-enhanced model achieving hourly average RMSE values of 0.613 K for AT, 1.131% for RH, and 0.207 m/s for WS; (2) unique local geographic conditions, such as coastal surroundings and continuous natural landscapes, significantly influence microclimate variations within urban built-up areas; (3) inter-LCZ microclimate differences were generally within 1.5 K for AT, 9% for RH, and 0.7 m/s for WS, exceeding intra-LCZ differences; and (4) built-up LCZs could be further divided into 2~4 subcategories with distinct microclimate conditions, some of which showed relatively favorable microclimate environments during the high temperature period. Our findings contribute to the fine-grained assessment of urban microclimate environments and deepen the understanding of LCZs' microclimate variations.



Keywords: Urban Climate,  Thermal Environment,  Weather Research and Forecast (WRF),  Urban Canopy Model (UCM),  Local Climate Zone (LCZ),  Machine Learning (ML),  Shenzhen



Semantic Tags: local climate zone; urban microclimate; WRF model; urban canopy model; machine learning; thermal environment; spatiotemporal patterns; Shenzhen


```{admonition} Presentation Information
:class: note

**Submission ID:** R1822  
**Session:** [Urban Heat and Thermal Environment - Part 1 ](./Session_CED-2/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```