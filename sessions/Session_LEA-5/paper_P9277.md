---
title: "Global Settlement Classification from True-Color Satellite Imagery"
authors:
- "Vincent Zhang"

---

# Global Settlement Classification from True-Color Satellite Imagery

**Author Information**  
Vincent Zhang<sup>1</sup>


<sup>1</sup> University of Virginia  



## Abstract

Accurate and scalable identification of human set- tlements from satellite imagery is essential for urban planning, disaster response, and sustainable development monitoring. This study presents a global framework for classifying true-color satellite imagery into urban, rural, and uninhabited categories using physically observed Earth observation data. Imagery is obtained from the Harmonized Landsat-Sentinel (HLS) v2.0 collection, providing 30-meter surface reflectance measurements with consistent global coverage. Ground truth labels are derived from the Global Urban and Rural Settlement (GURS) dataset through spatially aligned raster windowing and resolution-aware class weighting. A globally distributed tile dataset spanning six continents is constructed using reprojection, affine coor- dinate alignment, and systematic filtering of low-information regions. Unsupervised clustering, gradient boosting, and deep convolutional neural networks are evaluated under conditions of extreme spatial class imbalance, reflecting the predominance of uninhabited land. While convolutional networks achieve higher overall accuracy, gradient boosting demonstrates stronger recall for inhabited classes, highlighting trade-offs between model com- plexity and reliable settlement detection in imbalanced geospatial data.



Keywords: remote sensing, global settlement mapping, urban-rural classification, satellite imagery, raster preprocessing, spatial class imbalance, machine learning



Semantic Tags: global settlement classification; urban-rural mapping; satellite imagery; Harmonized Landsat-Sentinel; machine learning; spatial class imbalance; Earth observation


```{admonition} Presentation Information
:class: note

**Submission ID:** P9277  
**Session:** [Urban Building Extraction and Remote Sensing ](./Session_LEA-5/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** SR-D  
```