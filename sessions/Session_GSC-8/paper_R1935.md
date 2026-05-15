---
title: "Modeling dynamic higher-order spatio-temporal relationships: hypergraph-enhanced load forecasting for power grids"
authors:
- "Ying Luo"
- "Qingfeng Guan"

---

# Modeling dynamic higher-order spatio-temporal relationships: hypergraph-enhanced load forecasting for power grids

**Author Information**  
Ying Luo<sup>1</sup>, Qingfeng Guan<sup>1</sup>


<sup>1</sup> China University of Geosciences  



## Abstract

Modeling complex spatio-temporal dependencies is a fundamental challenge in geospatial analytics and Earth Observation (EO) applications. Short-term load forecasting (STLF), characterized by intricate cross-regional interactions and dynamic temporal patterns, serves as a representative benchmark for such tasks. Existing methods primarily capture temporal or pairwise spatial dependencies and rely on static predefined structures, struggling to model higher-order and time-varying inter-regional relationships in geospatial data. To address this, we propose a novel Hypergraph-Enhanced Adaptive Spatio-Temporal Convolutional Recurrent Network (ASTHCRN). ASTHCRN integrates hypergraph convolution to model higher-order spatial relationships among multiple entities and incorporates a data-driven adaptive mechanism. This mechanism jointly learns node and hyperedge embeddings to dynamically construct hypergraphs, eliminating the dependence on predefined topologies, a capability crucial for handling EO data where physical connections are often implicit. By seamlessly integrating hypergraph convolution with Gated Recurrent Unit (GRU), ASTHCRN achieves intrinsic coupling and co-evolution of spatio-temporal features, rather than relying on the conventional stacked or sequential spatial–temporal modules. This unified design allows ASTHCRN to capture mutually reinforcing spatio-temporal dynamics more effectively. Experiments on four heterogeneous load datasets demonstrated that ASTHCRN significantly outperformed six state-of-the-art baselines across key metrics (up to 8.71% in MAE and 19.71% in MAPE). While validated on STLF in this study, ASTHCRN’s hypergraph-based spatio-temporal architecture is task-agnostic, holding potential for multimodal EO tasks and as a core component for future GeoAI foundation models. Code and data are available at https://github.com/HPSCIL/ASTHCRN.



Keywords: Spatio-temporal Forecasting,  Short-term Load Forecasting,  Hypergraph Neural Networks,  High-order relationships,  Adaptive structure learning



Semantic Tags: spatio-temporal forecasting; short-term load forecasting; hypergraph neural network; high-order spatial dependencies; adaptive structure learning; power grid; geospatial analytics; inter-regional interaction


```{admonition} Presentation Information
:class: note

**Submission ID:** R1935  
**Session:** [Spatiotemporal Modeling and Graph Neural Networks](./Session_GSC-8/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SR-D  
```