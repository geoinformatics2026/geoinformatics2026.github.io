---
title: "High-Resolution Population Mapping in the Yangtze River Economic Belt Using PopNet with Multi-Source Spatial Data"
authors:
- "Mei Yang"
- "Yan Jin"
- "Hailong Zhang"
- "Yan Jia"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# High-Resolution Population Mapping in the Yangtze River Economic Belt Using PopNet with Multi-Source Spatial Data

**Author Information**  
Mei Yang<sup>1</sup>, Yan Jin<sup>1</sup>, Hailong Zhang<sup>1</sup>, Yan Jia<sup>1</sup>


<sup>1</sup> Nanjing University of Posts and Telecommunications  



## Abstract

High-resolution population distribution data provide a fundamental basis for analyzing regional population agglomeration patterns. However, existing open-access gridded population datasets often have limitations in spatial resolution and regional adaptability, which may constrain fine-scale population studies in the Yangtze River Economic Belt (YREB). To address the challenges of high dimensionality, complex spatial dependence in multi-source spatial data, and the limited computational efficiency of traditional models, this study proposes a high resolution population mapping method based on the PopNet model, with the YREB as the study area. Multi-source spatial variables, including remote sensing imagery, land use, nighttime light data, road networks, and points of interest (POIs), are integrated to construct a pixel-scale feature set, which is then modeled using the PopNet framework. The model uses convolutional neural networks (CNNs) to characterize the continuous variation of spatial features, while adopting autoencoders and residual connections to to enhance modeling capacity for large-scale, high-resolution data while maintaining computational feasibility. The predicted results are constrained and calibrated based on county level statistical population data to generate a 100 m resolution population raster product. The results show that the PopNet model outperforms comparative models such as Random Forest and ResAutoNet in population prediction accuracy, and demonstrates stable performance across multiple spatial scales, with an R² value of 0.902. The population mapping results indicate that high-value areas are primarily concentrated in urban built-up areas and major human activity sites, expanding zonally along transportation corridors. This study demonstrates that the proposed PopNet-based approach effectively improves the accuracy and spatial detail of high-resolution population mapping in the YREB.



Keywords: high-resolution population mapping, deep learning, Yangtze River Economic Belt, multi-source spatial data, population spatialization




```{admonition} Presentation Information
:class: note

**Submission ID:** P0714  
**Session:** [Population, Migration, and Rural Settlement Dynamics](./Session_UPS-2/)  
**Theme:** Urban Analytics, Planning \& Socioeconomics    
**Date:** Day 1, 20 July (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** Stephen Riady Centre-01-Seminar Room 1 & 2 (SR-A)  
```