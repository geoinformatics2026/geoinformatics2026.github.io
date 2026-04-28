---
title: "Knowledge Graph-Enhanced Multimodal Large Language Models for Automated Geospatial Code Generation in Google Earth Engine"
authors:
- "Haoyue Jiao"
- "Shuyang Hou"
- "Ziqi Liu"
- "Lutong Xie"
- "Guanyu Chen"
- "Shaowen Wu"
- "Xuefeng Guan"
- "Huayi Wu"

---

# Knowledge Graph-Enhanced Multimodal Large Language Models for Automated Geospatial Code Generation in Google Earth Engine

**Author Information**  
Haoyue Jiao<sup>1</sup>, Shuyang Hou<sup>1</sup>, Ziqi Liu<sup>1</sup>, Lutong Xie<sup>1</sup>, Guanyu Chen<sup>1</sup>, Shaowen Wu<sup>1</sup>, Xuefeng Guan<sup>1</sup>, Huayi Wu<sup>1</sup>


<sup>1</sup> Wuhan University  



## Abstract

Google Earth Engine (GEE), a cloud-based geospatial analysis platform integrating massive remote sensing data and high-performance computing capabilities, has become a fundamental infrastructure for large-scale environmental monitoring and spatial modeling. However, its script-based analytical paradigm requires substantial programming skills and systematic knowledge of spatial analysis, which constrains the efficient implementation of complex tasks. Although large language models have demonstrated strong potential in code generation, they still face challenges in professional GEE scenarios, including intent misunderstanding, insufficient domain knowledge support, and limited workflow orchestration capability. To address these issues, this paper proposes an automated GEE code generation approach that integrates multimodal large language models with a geospatial knowledge graph. A multimodal code–map dataset is first constructed to support the development of a domain-specific modeling knowledge graph, which structurally represents datasets, operator semantics, analytical steps, and visualization elements. Building upon this foundation, a graph-structured retrieval-augmented generation framework is designed to map user natural language queries and map visual inputs into structured workflow knowledge. Subgraph matching and workflow constraint mechanisms are further introduced to guide staged code generation, thereby enhancing logical consistency and controllability. Experimental results demonstrate that the proposed method significantly outperforms baseline models in terms of code accuracy, executability, and visualization-result consistency, providing a new technical pathway for intelligent modeling and automated implementation of complex GIS spatial analysis tasks.



Keywords: Google Earth Engine,  Multimodal Large Language Model,  Geospatial Knowledge Graph,  Automated Code Generation



```{admonition} Presentation Information
:class: note

**Submission ID:** 9755  
**Session:** [Code Knowledge Generation Language](./Session_E3/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15
**Venue:** room 3
```