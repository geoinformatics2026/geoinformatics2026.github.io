---
title: "GeoAI for Small Geospatial Data"
authors:
- "Guofeng Cao"
- "Guiye Li"

---

# GeoAI for Small Geospatial Data

**Author Information**  
Guofeng Cao<sup>1</sup>, Guiye Li<sup>1</sup>


<sup>1</sup> University of Colorado Boulder  



## Abstract

Deep learning has transformed geospatial analysis by enabling the representation of complex, nonlinear patterns in high-dimensional data. Deep neural networks have achieved remarkable success in applications such as remote sensing image interpretation, large-scale environmental modeling, and analysis of gridded Earth observation products. However, these models typically rely on massive training datasets to estimate large numbers of parameters and often lack mechanisms for uncertainty quantification. In many scientific and environmental applications, geospatial observations are sparse, irregularly distributed, costly to collect, and highly unbalanced across space and time. Such characteristics fundamentally challenge conventional GeoAI models and limit their reliability in data-scarce settings.   While traditional spatial statistical methods in GIScience have long addressed small-sample inference and uncertainty characterization, their integration with modern deep learning remains limited. As a result, the small-data problem persists as a critical bottleneck for GeoAI. In this paper, we systematically review the methodological challenges that arise when applying GeoAI to small and sparse geospatial datasets, and synthesize recent advances aimed at overcoming these limitations. We then introduce a neural process–based framework, termed Neural Kriging (NK), designed specifically for geospatial estimation under data scarcity. By combining stochastic process, deep neural networks, and meta-learning, the NK framework learns transferable spatial representations across tasks while preserving uncertainty awareness. Through comprehensive synthetic experiments and real-world case studies across multiple domains, we demonstrate that NK framework achieves robust performance and calibrated uncertainty estimates in when observations are sparse. Our results suggest a promising direction toward reliable, uncertainty-aware GeoAI for scientific applications where data are inherently limited. 



Keywords: GeoAI,  Geostatistics,  Small data,  Uncertainty,  Deep learning



```{admonition} Presentation Information
:class: note

**Submission ID:** 7353  
**Session:** [Cyberinfrastructure and GeoAI for Intelligent Spatial Decision Support](./Session_D2/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30
**Venue:** room 2
```