---
title: "Generalized spatial error for validation"
authors:
- "Haiyang Liu"
- "Yongze Song"
- "Pengcheng Zhang"

---

# Generalized spatial error for validation

**Author Information**  
Haiyang Liu<sup>1</sup>, Yongze Song<sup>2</sup>, Pengcheng Zhang<sup>3</sup>


<sup>1</sup> Hokkaido University  

<sup>2</sup> Curtin University  

<sup>3</sup> The Hong Kong Polytechnic University  



## Abstract

The validation of spatial prediction models commonly relies on global, non-spatial metrics, whose inherent error-averaging mechanism ignores the influence of spatial heterogeneity, thus often leading to an overly optimistic assessment of model performance. To address this limitation, we propose the Generalized Spatial Error (GSE), which quantifies and penalizes the spatial structure and heterogeneity present in model residuals through the weighting of local error variance. We systematically evaluated nine machine learning models used for predicting vascular plant species richness in Australia's Murray-Darling Basin (MDB) to validate the utility of GSE. The results show that GSE values are systematically 18-21% higher than the Root Mean Square Error (RMSE) values, and the model's predictive uncertainty is primarily concentrated in areas of high plant diversity eastern region of the basin. Moreover, a sensitivity analysis across different data stratification confirms the robustness of GSE as a diagnostic tool under varying environmental conditions. This significant discrepancy quantifies the spatial structural error smoothed away by RMSE, exposing the severe deficiencies of traditional metrics in assessing a model's true predictive uncertainty in practical applications. By identifying and penalizing the spatial heterogeneity of errors, GSE establishes a more robust performance metric, thereby providing a critical basis for decision-making in practical applications such as environmental management, risk assessment, and resource optimization.



Keywords: Model validation,  Spatial heterogeneity,  RMSE,  Murray-Darling Basin (MDB),  Local statistics



```{admonition} Presentation Information
:class: note

**Submission ID:** 1468  
**Session:** [Advanced Geospatial Data and Methods for Transforming Healthy Cities Delivery: Part 1](./Session_A2/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30
**Venue:** room 2
```