---
title: "Shapley-based local indicator for spatial validation"
authors:
- "Pengcheng Zhang"
- "Wen Yi"
- "Yongze Song"
- "Haiyang Liu"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Shapley-based local indicator for spatial validation

**Author Information**  
Pengcheng Zhang<sup>1</sup>, Wen Yi<sup>1</sup>, Yongze Song<sup>2</sup>, Haiyang Liu<sup>3</sup>


<sup>1</sup> The Hong Kong Polytechnic University, Hong Kong  

<sup>2</sup> Curtin University, Perth, Australia  

<sup>3</sup> Hokkaido University, Nayoro, Japan  



## Abstract

Model validation plays a crucial role in geographical sciences by revealing biases in prediction models and ensuring the reliability of spatial predictions. Current validation systems rely on accuracy metrics, including fitness and error-based global validation metrics. However, these metrics typically evaluate model performance with a single value, failing to account for spatial effects and not providing validation for each variable. This study introduces a shapley-based local validation (SLV) indicator that integrates localized residual decomposition using spatial buffers and SHAP values to quantify variable-level contributions to prediction errors. The developed SLV indicator is applied for spatial validation of prediction performance across multiple machine learning models used to forecast road deterioration. The models employ vehicle-based laser scanning data collected from the metropolitan road network in Western Australia. The results indicate that the SLV indicator, compared to fitness and error-based global validation metrics, provides two key benefits: first, effective mapping of localized model performance and validation of differences across regions; second, assessment of individual variables’ contributions to model accuracy, capturing subtle differences that traditional metrics miss. The SLV indicator can be integrated with various modeling approaches, allowing for a more comprehensive validation framework that enhances our overall model evaluation process and supports more informed decision-making in geospatial applications.



Keywords: Geospatial analysis,  spatial prediction,  model validation,  local determinants




```{admonition} Presentation Information
:class: note

**Submission ID:** R6275  
**Session:** [Advanced Geospatial Data and Methods for Transforming Healthy Cities Delivery - Part 1](./Session_GSC-5/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 51 (LT-51)  
```