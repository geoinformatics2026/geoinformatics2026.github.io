---
title: "GEO-FedGNN: A Multi-Scenario Federated Graph Neural Network Framework for Privacy-Preserving Geospatial Modelling"
authors:
- "Minwei Zhao"
- "Guangyu Xiang"
- "Yunlei Su"
- "Zhecheng Shi"
- "Filip Biljecki"
- "Cai Wu"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R0003.pdf
---

# GEO-FedGNN: A Multi-Scenario Federated Graph Neural Network Framework for Privacy-Preserving Geospatial Modelling

**Author Information**  
Minwei Zhao<sup>1</sup>, Guangyu Xiang<sup>1</sup>, Yunlei Su<sup>1</sup>, Zhecheng Shi<sup>1</sup>, Filip Biljecki<sup>2</sup>, Cai Wu<sup>1</sup>


<sup>1</sup> The Hong Kong University of Science and Technology (Guangzhou)  

<sup>2</sup> National University of Singapore  



## Abstract

Geoinformatics applications increasingly depend on multi-source spatial data, including environmental monitoring records, remote sensing products, census statistics, and administrative data, that are distributed across institutions.However, centralizing these data for predictive modeling raises substantial privacy, governance, and data-sovereignty concerns under regulations such as the GDPR. We propose Geo-FedGNN: a general Vertical Federated Learning (VFL) framework based on Graph Neural Networks (GNNs) to enable collaborative geospatial prediction without sharing raw features. The framework represents geographic units (e.g., administrative areas) as graph nodes connected by spatial adjacency or proximity relations, while features are vertically partitioned across institutions. Each institution trains local GNNs over the shared or partially overlapping spatial topology using its private feature subset and shares only intermediate node embeddings and model parameters as privacy-preserving outputs. A central server integrates these representations through configurable spatial topological reasoning and fusion mechanisms (e.g., concatenation, gated fusion, or bilinear interaction) to optimize a downstream predictor. By decoupling data governance from predictive integration, the architecture provides a task-agnostic foundation for collaborative geospatial modeling across domains such as health, transport, and land use. We evaluate the framework on London’s Lower Layer Super Output Areas (LSOAs) using institutionally separated environmental (13 variables, including NO₂ and NDVI) and census (55 demographic and socioeconomic variables) datasets. Anxiety medication prescriptions per capita serve as an NHS-relevant prediction task in a simulated multi-institution collaboration scenario. The federated model achieves a folded test-set R² of approximately 0.74, remaining within 2% of a centralized benchmark. Experiments under a simulated homomorphic-encryption setting further indicate that enhanced privacy protection can be incorporated with negligible utility loss. These results demonstrate that Geo-FedGNN offer a practical and generalizable approach for privacy-preserving multi-source spatial analytics in institutionally constrained settings.



Keywords: Federated Learning,  Graph Neural Networks,  Geospatial Modeling,  Privacy-Preserving Analytics



Semantic Tags: federated learning; graph neural network; geospatial modeling; privacy-preserving analytics; vertical federated learning; multi-source spatial data; GDPR compliance


```{admonition} Presentation Information
:class: note

**Submission ID:** R0003  
**Session:** [Spatiotemporal Modeling and Graph Neural Networks](./Session_GSC-8/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** TP-Lv2-SR-E (Room-5/6)  
```