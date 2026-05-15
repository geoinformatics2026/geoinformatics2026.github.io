---
title: "An Automatic Code Generation Framework for Geospatial Computing Platforms"
authors:
- "Wenjie Chen"
- "Longgang Xiang"

---

# An Automatic Code Generation Framework for Geospatial Computing Platforms

**Author Information**  
Wenjie Chen<sup>1</sup>, Longgang Xiang<sup>1</sup>


<sup>1</sup> Wuhan University  



## Abstract

Recent advances in large language models (LLMs) have created new opportunities for the automated generation of scientific computing programs. However, automatically generating reliable and executable geospatial analysis code remains challenging, as geospatial tasks typically require substantial domain knowledge and involve complex analytical workflows and logical constraints. This paper proposes an automatic code generation framework for geospatial computing platforms. The proposed framework integrates LLMs with structured geospatial knowledge to guide the generation of analytical code. By introducing external knowledge resources and task-oriented code patterns, it provides domain-specific constraints and prior support for the generation process, thereby improving the reliability and executability of the generated programs. Furthermore, to explicitly represent the workflow logic of geospatial computing, the generated programs are modeled as directed acyclic graphs (DAGs), enabling structured representation and analysis of computational steps, logical dependencies, and overall analytical workflows. Experimental results on a set of representative remote sensing analysis tasks demonstrate that the framework can automatically generate executable programs covering common geospatial operations, including spectral index calculation, data preprocessing, and result visualization. Compared with direct generation based on general-purpose LLMs, the incorporation of structured geospatial knowledge effectively improves both the structural consistency of the generated workflows and the executability of the resulting code. This study provides an interpretable and practical approach to the automatic generation of geospatial analysis programs.



Keywords: Geospatial computing,  Code generation,  Large language models,  Geospatial workflows



Semantic Tags: geospatial code generation; large language model; geospatial computing; workflow automation; domain knowledge; geospatial knowledge graph; natural language interface; analytical code


```{admonition} Presentation Information
:class: note

**Submission ID:** R5173  
**Session:** [Emerging LLM-based Methods for Geospatial Analysis - Part 1](./Session_GFM-1/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** LT-1  
```