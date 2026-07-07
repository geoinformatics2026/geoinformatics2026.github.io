---
title: "Upscaling NEON Individual-Tree Biomass to Grid-Level AGB Mapping: A Multi-Scale Assessment with Multisource Remote Sensing and ESF-SVC"
authors:
- "Tiantian Ran"
- "Yumin Chen"
- "Shanshan Wei"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Upscaling NEON Individual-Tree Biomass to Grid-Level AGB Mapping: A Multi-Scale Assessment with Multisource Remote Sensing and ESF-SVC

**Author Information**  
Tiantian Ran<sup>1</sup>, Yumin Chen<sup>1</sup>, Shanshan Wei<sup>2</sup>


<sup>1</sup> 武汉大学  

<sup>2</sup> 新加坡国立大学  



## Abstract

Aboveground biomass (AGB) is a key indicator of forest carbon storage and cycling, yet substantial uncertainty remains when scaling AGB from field plots to remote-sensing grids. Using multi-site NEON vegetation structure data from 2022, individual-tree AGB was estimated from diameter at breast height (DBH), total tree height, and taxonomic information using taxon-specific or generalized allometric equations. For small trees without stem diameter measurements, measurement height and basal stem diameter were incorporated following Annighöfer et al. (2016). These tree-level estimates were subsequently aggregated into gridded AGB labels at three spatial support units (400, 100, and 25 m²) derived from the same plots to explicitly evaluate scale effects on model performance. Spectral, radar, and terrain predictors were derived from NASADEM, Sentinel-2, Sentinel-1 GRD, land-cover, and ancillary environmental datasets. Predictor variables were screened using correlation analysis and multicollinearity diagnostics prior to stepwise regression. To address spatial nonstationarity, an ESF-SVC (Eigenvector Spatial Filtering–Spatially Varying Coefficient) framework was implemented and benchmarked against conventional regression models. Model performance declined with decreasing label size, from 400 m² (R² = 0.79, RMSE = 257 Mg ha⁻¹) to 100 m² (R² = 0.77, RMSE = 389 Mg ha⁻¹) and 25 m² (R² = 0.71, RMSE = 408 Mg ha⁻¹). These results indicate that finer label units are more susceptible to within-plot heterogeneity and sampling noise, which propagates into model uncertainty.  By explicitly addressing spatial nonstationarity, the ESF-SVC framework improves the spatial stability of AGB estimates and disentangles regionally heterogeneous effects of terrain, radar backscatter, and spectral indices on biomass. This spatially explicit modeling strategy provides a rigorous methodological basis for determining optimal plot support and enhancing regional-scale forest AGB mapping.



Keywords: multisource remote sensing,  ESF-SVC,  spatial nonstationarity,  scale effect,  forest biomass mapping




```{admonition} Presentation Information
:class: note

**Submission ID:** R4070  
**Session:** [Vegetation and Forest Monitoring with UAV and LiDAR](./Session_REE-6/)  
**Theme:** Remote Sensing, Earth Obs. \& Env. Monitoring    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 16:30 – 18:00  
**Venue:** Stephen Riady Centre-01-Seminar Room 3 & 4 (SR-B)  
```