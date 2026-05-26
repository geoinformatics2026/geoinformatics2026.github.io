---
title: "A Multi-Agent Framework for Geographic Computational Question Answering with Large Language Models"
authors:
- "Hao Li"
- "Faming Jing"
- "Haizhen Chen"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R2177.pdf
---

# A Multi-Agent Framework for Geographic Computational Question Answering with Large Language Models

**Author Information**  
Hao Li<sup>1</sup>, Faming Jing<sup>1</sup>, Haizhen Chen<sup>1</sup>


<sup>1</sup> Institute of Surveying, Mapping and Remote Sensing Technology, Ningbo  



## Abstract

Geographic question answering has largely followed a conventional “text-in, text-out” paradigm, which is inadequate for complex geographic computation tasks requiring workflow planning, data retrieval, operator invocation, and result integration. To address this limitation, this study proposes a geographic computational question answering approach based on a multi-agent framework. The framework adopts a divide-and-conquer design, in which different agents specialize in distinct stages of the geographic task pipeline, including query understanding, task decomposition, tool selection, execution coordination, and answer synthesis. To support effective collaboration, a spatiotemporal environment state is introduced to record and maintain the historical outputs and contextual information generated during multi-agent execution. In addition, this study examines the advantages and limitations of different geographic tool granularities and encapsulation strategies, and further designs a unified structured template for tool description and packaging, thereby improving the reliability and scalability of tool invocation in language-driven geographic workflows. Experimental results show that the proposed framework achieves a success rate of 0.81, while reducing execution time by approximately 70% and token consumption by about 25% compared with baseline methods. The proposed approach moves geographic question answering beyond traditional text response generation toward a new paradigm of “text-to-geographic-task computation,” in which natural language queries can be automatically parsed and translated into executable geographic workflows. This significantly extends the capability boundary of geographic question answering and provides a practical technical path for intelligent geospatial analysis.



Keywords: Geographic question answering,  multi-agent framework,  large language models



Semantic Tags: geographic question answering; multi-agent framework; large language model; geospatial computation; task decomposition; tool orchestration; spatial reasoning; divide-and-conquer


```{admonition} Presentation Information
:class: note

**Submission ID:** R2177  
**Session:** [Emerging LLM-based Methods for Geospatial Analysis - Part 1](./Session_GFM-1/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv1-LT-50  
```