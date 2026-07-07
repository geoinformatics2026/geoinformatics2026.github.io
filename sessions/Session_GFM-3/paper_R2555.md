---
title: "Geospatial Code Diagnosis and Repair Model for Assisting GEE Code Generation Agents"
authors:
- "Ziqi Liu"
- "Shuyang Hou"
- "Haoyue Jiao"
- "Lutong Xie"
- "Guanyu Chen"
- "Shaowen Wu"
- "Xuefeng Guan"
- "Huayi Wu"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Geospatial Code Diagnosis and Repair Model for Assisting GEE Code Generation Agents

**Author Information**  
Ziqi Liu<sup>1</sup>, Shuyang Hou<sup>1</sup>, Haoyue Jiao<sup>1</sup>, Lutong Xie<sup>2</sup>, Guanyu Chen<sup>2</sup>, Shaowen Wu<sup>2</sup>, Xuefeng Guan<sup>1</sup>, Huayi Wu<sup>1</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> Wuhan University	  



## Abstract

Google Earth Engine (GEE) has become a fundamental platform for large-scale geospatial data analysis, yet its complex API structures, chained functional calls, and strict server-side computation logic make automatically generated scripts highly prone to syntactic, semantic, and runtime errors. In GEE code generation agents driven by large language models, error correction is not a peripheral component but a necessary mechanism to ensure executability and analytical validity. Existing general-purpose code models show limited ability in diagnosing GEE-specific errors, particularly when dealing with dataset mismatches, improper band selection, server–client misuse, reducer misconfiguration, and spatial logic inconsistencies. This study proposes a dedicated geospatial code error correction model designed to assist GEE code generation agents by providing line-level error localization, explicit error cause analysis, correction reasoning, and fully revised executable scripts. To enable this capability, a structured supervision dataset is constructed in the form of erroneous code, annotated error line, detailed explanation of the underlying issue, and corresponding corrected code, allowing the model to learn fine-grained debugging patterns and domain-specific repair strategies. The model jointly learns to align error spans with semantic diagnostics and code revision, reducing cascading failures during iterative generation. Experimental evaluation on a curated GEE error benchmark demonstrates that the proposed model substantially improves correction accuracy and final code executability compared with baseline large language models, particularly in scenarios involving multi-step spatial workflows and chained Earth Engine operations. The results indicate that domain-specific correction modeling is essential for reliable geospatial programming agents and provides a practical solution for enhancing robustness in AI-assisted spatial analysis.



Keywords: Google Earth Engine,  Automated Code Repair,  Large Language Models,  Code Generation Agents




```{admonition} Presentation Information
:class: note

**Submission ID:** R2555  
**Session:** [Large Language Models and Agentic GIS](./Session_GFM-3/)  
**Theme:** GeoAI, Foundation Models \& Spatial ML    
**Date:** Day 1, 20 July (Monday)  
**Time:** 16:30 – 18:00  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 50 (LT-50)  
```