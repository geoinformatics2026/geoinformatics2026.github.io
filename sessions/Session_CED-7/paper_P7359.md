---
title: "STC-Fire: A Topographic-Adaptive Method for Forest Fire Monitoring Using Himawari-8 Data"
authors:
- "Xiaorui She"
- "Qingxiang Meng"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# STC-Fire: A Topographic-Adaptive Method for Forest Fire Monitoring Using Himawari-8 Data

**Author Information**  
Xiaorui She<sup>1</sup>, Qingxiang Meng<sup>1</sup>


<sup>1</sup> School of Remote Sensing and Information Engineering,Wuhan University  



## Abstract

Forest fires represent one of the most significant natural hazards in the mountainous regions of Southwest China. Due to the rugged terrain, traditional geostationary satellite fire detection algorithms often suffer from high false alarm rates, as they struggle to distinguish between instantaneous solar heating on sun-facing slopes and actual fire radiative emissions. To address this challenge, this paper proposes a Spatio-Temporal Contextual fire monitoring method (STC-Fire) that integrates topographic-adaptive correction with dynamic gradient analysis. Leveraging the high temporal resolution of the Himawari-8 satellite, the method first incorporates SRTM DEM data to construct a topographically constrained spatial background sampling field. This approach physically corrects brightness temperature (BT) deviations caused by variations in aspect and elevation. Furthermore, a dynamic BT gradient model based on 10-minute observation intervals is established to extract thermal pulse characteristics during the initial stages of a fire, effectively isolating non-stationary background noise. Validation using a typical wildfire event in Muli, Sichuan, demonstrates that the STC-Fire algorithm achieves a precision of 88.67% and an F1- score of 91.71% in complex terrain. Compared to MODIS polar- orbiting products, the proposed method advances the early warning time by approximately 150 minutes on average. This research significantly suppresses terrain-induced false alarms while maintaining high recall, providing reliable technical support for early and precise forest fire warnings in topographically complex regions.



Keywords: Forest fire, Geostationary satellite, Spatio-temporal context, Topographic adaptation, Early warning




```{admonition} Presentation Information
:class: note

**Submission ID:** P7359  
**Session:** [Multi-Hazard Detection, Simulation, and Disaster Monitoring](./Session_CED-7/)  
**Theme:** Climate, Env. Hazards \& Disaster Risk    
**Date:** Day 3, 22 July (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** Town Plaza-02-Seminar Room 3 & 4 (SR-E)  
```