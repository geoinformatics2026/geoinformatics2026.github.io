---
title: "Global Settlement Classification from True-Color Satellite Imagery"
authors:
- "Vincent Zhang"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Global Settlement Classification from True-Color Satellite Imagery

**Author Information**  
Vincent Zhang<sup>1</sup>


<sup>1</sup> University of Virginia  



## Abstract

Accurate and scalable identification of human set- tlements from satellite imagery is essential for urban planning, disaster response, and sustainable development monitoring. This study presents a global framework for classifying true-color satellite imagery into urban, rural, and uninhabited categories using physically observed Earth observation data. Imagery is obtained from the Harmonized Landsat-Sentinel (HLS) v2.0 collection, providing 30-meter surface reflectance measurements with consistent global coverage. Ground truth labels are derived from the Global Urban and Rural Settlement (GURS) dataset through spatially aligned raster windowing and resolution-aware class weighting. A globally distributed tile dataset spanning six continents is constructed using reprojection, affine coor- dinate alignment, and systematic filtering of low-information regions. Unsupervised clustering, gradient boosting, and deep convolutional neural networks are evaluated under conditions of extreme spatial class imbalance, reflecting the predominance of uninhabited land. While convolutional networks achieve higher overall accuracy, gradient boosting demonstrates stronger recall for inhabited classes, highlighting trade-offs between model com- plexity and reliable settlement detection in imbalanced geospatial data.



Keywords: remote sensing, global settlement mapping, urban-rural classification, satellite imagery, raster preprocessing, spatial class imbalance, machine learning




```{admonition} Presentation Information
:class: note

**Submission ID:** P9277  
**Session:** [Urban Building Extraction and Remote Sensing](./Session_LEA-4/)  
**Theme:** Land, Ecology, Agriculture \& Sustainable Dev.    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** Town Plaza-02-Seminar Room 5 & 6 (SR-F)  
```