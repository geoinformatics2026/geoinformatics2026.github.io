---
title: "Mixed Geographically Weighted XGBoost (M-GWXGB) Model: A New Spatially Explicit Machine Learning Model"
authors:
- "Fan Gao"
- "Sylvia He"
- "Mei-Po Kwan"

---

# Mixed Geographically Weighted XGBoost (M-GWXGB) Model: A New Spatially Explicit Machine Learning Model

**Author Information**  
Fan Gao<sup>1</sup>, Sylvia He<sup>1</sup>, Mei-Po Kwan<sup>2</sup>


<sup>1</sup> Department of Geography and Resource Management, The Chinese University of Hong Kong, China  

<sup>2</sup> Dept of GRM, The Chinese University of Hong Kong, China; ISEIS, The Chinese University of Hong Kong, China  



## Abstract

Analyzing spatially varying relationships constitutes a fundamental pursuit in geography, crucial for comprehending intricate spatial patterns. These relationships canarise fromspatial heterogeneityor from nonlinearity. To distinguish these diverse relationships, researchers have developed spatially varying coefficient (SVC) models and machine learning (ML) techniques. When confronted with nonlinear relationships that also exhibit spatial nonstationarity, though, existing models might produce misleading conditional relationships.To address this research gap, this study introduces a mixed geographically weighted extreme gradient boosting (M-GWXGB) model, which integrates a semiparametric generalized additive model with a multiscale ML approach to estimate variable-specific spatial processes while addressing both spatial heterogeneity and nonlinearity. We calculate the marginal contributions to extract spatially varying and nonlinear relationships. We evaluate the efficiency of our proposed approach on three simulated datasets and a real-world dataset, showing that M-GWXGB can avoid the misinterpretation of spatial variation as nonlinearity and vice versa. Additionally, our new model outperforms mainstream spatially explicit ML models (e.g., XGB, graph convolutional network, GWXGB) and SVCs (e.g., multiscale geographically weighted regression) in terms of predictability, interpretability, and the capability to estimate variable specific spatial processes, particularly when spatial heterogeneity and nonlinearity coexist. Finally, we propose a roadmap to guide the application of the M-GWXGB model. Our empirical analysis yields valuable insights into leveraging M-GWXGB to elucidate complex geographical phenomena, highlighting its potential to understand spatially varying processes in spatial data.



Keywords: nonlinear relationship,  spatial varying relationship,  spatially explicit machine learning models,  XGBoost



```{admonition} Presentation Information
:class: note

**Submission ID:** 4084  
**Session:** [Spatial Weighting Spatially Variable](./Session_B7/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15
**Venue:** room 7
```