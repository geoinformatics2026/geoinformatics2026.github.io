---
title: "FlowAnchorNetwork (FAN): A Theory-Guided Graph Neural Network for Urban Parcel-Level Land Surface Temperature Prediction"
authors:
- "Dailuo Zhang"
- "Cai Wu"
- "Stephen Law"
- "Minwei Zhao"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R5975.pdf
---

# FlowAnchorNetwork (FAN): A Theory-Guided Graph Neural Network for Urban Parcel-Level Land Surface Temperature Prediction

**Author Information**  
Dailuo Zhang<sup>1</sup>, Cai Wu<sup>1</sup>, Stephen Law<sup>2</sup>, Minwei Zhao<sup>1</sup>


<sup>1</sup> Urban Governance and Design Thrust, Society Hub, The Hong Kong University of Science and Technology (Guangzhou)  

<sup>2</sup> Department of Geography, University College London  



## Abstract

Accurate parcel-level prediction of land surface temperature (LST) is fundamental to understanding the urban heat island (UHI) effect and the design of effective thermal management strategies. Yet, existing machine learning approaches typically ignore spatial dependence by treating parcels as independent, while conventional Graph Neural Networks (GNNs) entangle intrinsic heat generation from local surface properties with lateral heat exchange across neighborhood boundaries. This study proposes the Flow-Anchor Network (FAN), a theory-guided, physically motivated GNN explicitly decomposing urban thermal processes into these two components within a unified modelling framework. FAN operationalizes this decomposition through an anchor-based update rule that consistently preserves each parcel’s intrinsic thermal representation as a stable baseline, with neighborhood influence as a modulating factor. Building on this foundation, two modules are introduced: the Spatial Flow Aggregation (SFA) computes geometry-aware edge weights derived from inter-parcel distance, shared boundary length, and relative area ratios; the Adaptive Coupling Gate (ACG) learns node-specific coupling coefficients that quantify how strongly each parcel responds to its surrounding thermal context, capturing spatially varying coupling behavior across heterogeneous urban surfaces. Validated on nearly 10,000 parcels across Shenzhen, China, FAN achieves a test R2 of 0.888, outperforming tree-based ensemble methods, geographically weighted approaches, and standard GNN architectures including GCN, GAT, GATv2 and GraphSAGE by up to 0.184 in R2. Ablation analysis shows independent contributions from both modules, with the anchor structure alone surpassing geographically weighted random forest and GCN. The coupling coefficients, learned without direct supervision on these relationships, correlate with physical surface properties: vegetated parcels exhibit lower coupling strength while high-density impervious surfaces and enclosed urban canyons show stronger neighborhood dependence. These results demonstrate that encoding domain knowledge into the design of message-passing GNN architecture advances both predictive performance and interpretability, offering a novel geospatial modeling approach capable of structurally decoupling intrinsic attributes from neighborhood interactions.



Keywords: Land Surface Temperature,  Graph Neural Networks,  Knowledge-Guided Machine Learning,  Spatial Heterogeneity,  Urban Morphology,  Physics-inspired Machine Learning



Semantic Tags: land surface temperature; graph neural network; knowledge-guided machine learning; urban heat island; spatial heterogeneity; urban morphology; physics-inspired machine learning


```{admonition} Presentation Information
:class: note

**Submission ID:** R5975  
**Session:** [Urban Heat and Thermal Environment - Part 1 ](./Session_CED-2/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** TP-Lv2-SR-D (Room-3/4)  
```