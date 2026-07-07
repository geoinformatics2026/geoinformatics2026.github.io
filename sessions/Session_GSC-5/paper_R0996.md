---
title: "On the spatial distance between training and validation data in model evaluation"
authors:
- "Weitao Hou"
- "Yongze Song"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# On the spatial distance between training and validation data in model evaluation

**Author Information**  
Weitao Hou<sup>1</sup>, Yongze Song<sup>1</sup>


<sup>1</sup> Curtin University  



## Abstract

Validation in spatial modelling is essential for assessing how well spatial predictions reflect local contexts and broader spatial patterns. However, common validation relies solely on statistical measures, which overlook the spatial bias introduced by the geographic distribution of training and testing data, leading to underestimation or overestimation of model accuracy and undermining confidence in the predicted spatial patterns. Thus, we propose a validation method that addresses spatial bias in validation for spatial modelling. The method identifies the relationship between prediction error and training-testing distance using a moving distance validation model, determines the optimal distance at peak error, and calculates spatially weighted indicators with Gaussian-based weighting. We demonstrate the validation indicators by evaluating the accuracy of models trained to predict newly installed rooftop solar capacity in Greater Perth, Western Australia, including aspatial and spatial validation models. The results reveal that spatial model performance cannot be reliably assessed without explicitly accounting for spatial distance between training and testing data, since traditional aspatial validation masks spatial heterogeneity and underestimates prediction error. We recommend that researchers consider the influence of spatial distance during model validation and adopt the method introduced in this study to improve the robustness of model assessments in spatial modelling.



Keywords: Spatial validation,  Distance effect,  Spatial heterogeneity,  Spatial interpretability




```{admonition} Presentation Information
:class: note

**Submission ID:** R0996  
**Session:** [Advanced Geospatial Data and Methods for Transforming Healthy Cities Delivery - Part 1](./Session_GSC-5/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 51 (LT-51)  
```