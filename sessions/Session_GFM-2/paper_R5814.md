---
title: "Fine-scale population spatialization with accumulable features from street view imagery and points of interest"
authors:
- "Yaxian Qing"
- "Huayi Wu"
- "Kunlun Qi"

---

# Fine-scale population spatialization with accumulable features from street view imagery and points of interest

**Author Information**  
Yaxian Qing<sup>1</sup>, Huayi Wu<sup>1</sup>, Kunlun Qi<sup>2</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> China University of Geosciences  



## Abstract

Population spatialization serves as a pivotal technique for delineating the geographical distribution patterns of human populations, which is essential for urban planning and the optimal allocation of public resources. Most existing studies rely on the density of points of interest (POI) but often overlook the attraction heterogeneity among similar POI categories. To address this limitation, this paper proposes a population spatialization method that integrates POI features with accumulable street view imagery (SVI) features. We extract dynamic object counts from SVIs to enhance spatial heterogeneity and introduce a virtual street combination-based data augmentation (VSCDA) strategy to boost model generalization across multi-scale grids. Finally, a random forest model is employed to estimate the grid-scale population distribution. Experimental results indicate that the proposed method achieved an R2 of 0.92 and a Mean Absolute Error (MAE) of 10,059 at a 100 m grid scale, significantly outperforming benchmark products such as WorldPop and GHS-POP. Ablation experiments further confirm that the VSCDA strategy reduces the MAE by over 2% at fine-to-medium scales. This integration of accumulable visual features and data augmentation provides a robust technical paradigm for advancing fine-scale population spatialization research.



Keywords: Street View Imagery,  Population Spatialization,  Data Augmentation,  Random Forest,  Spatialization Modeling



Semantic Tags: population spatialization; street view imagery; point of interest analysis; random forest; data augmentation; urban planning; spatial modeling


```{admonition} Presentation Information
:class: note

**Submission ID:** R5814  
**Session:** [Emerging LLM-based Methods for Geospatial Analysis - Part 2](./Session_GFM-2/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** LT-1  
```