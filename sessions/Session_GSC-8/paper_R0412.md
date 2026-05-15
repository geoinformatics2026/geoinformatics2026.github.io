---
title: "Three-Dimensional Geological Modeling based on Dual-Task Stratigraphy-Aware Attention Networks"
authors:
- "Zhenxi Fang"
- "Syed Yasir Ali Shah"
- "Baoyi Zhang"

---

# Three-Dimensional Geological Modeling based on Dual-Task Stratigraphy-Aware Attention Networks

**Author Information**  
Zhenxi Fang<sup>1</sup>, Syed Yasir Ali Shah<sup>1</sup>, Baoyi Zhang<sup>1</sup>


<sup>1</sup> Central South University  



## Abstract

The current three-dimensional (3D) geological implicit modelling methods are mainly based on interpolation methods, such as Kriging and radial basis functions (RBFs), which struggle to capture the nonlinear characteristics of complex geological structures and are limited in their capacity to integrate multi-source modeling data. To overcome these limitations, we proposed a 3D geological modelling framework, Geo-SAN, which consists of a dual-task stratigraphy-aware attention network. The framework starts with graph neural networks (GNNs) with a multi-scale neighborhood aggregation mechanism which is aimed to identify critical sampled points adjacent to fault planes and aggregate the lithological features. Subsequently, a stratigraphy-aware attention mechanism is introduced to explicitly incorporate similarities in stratigraphic sequence into the framework. A unidirectional stratigraphic scalar field penalty to lithological classification is developed and incorporated into loss functions, thereby denoising lithological classification. Finally, a dual-task prediction head is designed to simultaneously complete lithological classification and scalar field interpolation. Ablation experiment further validates the contributions of the three core components, that is, graph neighborhood aggregation, stratigraphy-aware attention, and dual-task learning. A case study at the Lingnian-Ningping region of Guangxi Zhuang Autonomous Region (GZAR), China, demonstrates that the proposed Geo-SAN framework, with an accuracy of 92.1% in lithological classification and a coefficient of determination (R²) of 0.96 in predicting the scalar field, outperforms the Hermite RBFs (HRBFs). In summary, the proposed framework is an important innovation of intelligent modelling of intricate geological formations, which is promising in the application of concealed mineral exploration.



Keywords: three-dimensional geological modelling,  graph neighborhood aggregation,  stratigraphic sequence,  dual-task learning,  stratigraphy-aware attention network



Semantic Tags: 3D geological modeling; graph neural network; stratigraphic sequence; dual-task learning; attention mechanism; implicit modeling; Kriging; subsurface modeling


```{admonition} Presentation Information
:class: note

**Submission ID:** R0412  
**Session:** [Spatiotemporal Modeling and Graph Neural Networks](./Session_GSC-8/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SR-D  
```