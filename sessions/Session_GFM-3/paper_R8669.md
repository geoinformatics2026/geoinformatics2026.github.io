---
title: "Integrating GIS and Generative AI for Urban Planning: A Multi-Agent, RAG-Driven Approach for Health-Centric Neighborhood Design"
authors:
- "Xun Shi"
- "Lan Wang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R8669.pdf
---

# Integrating GIS and Generative AI for Urban Planning: A Multi-Agent, RAG-Driven Approach for Health-Centric Neighborhood Design

**Author Information**  
Xun Shi<sup>1</sup>, Lan Wang<sup>2</sup>


<sup>1</sup> Dartmouth College  

<sup>2</sup> College of Architecture and Urban Planning, Tongji University, Shanghai, China  



## Abstract

In this study, we explore the possibility of semantically and meaningfully integrate the functionalities of GIS and Generative AI to support urban planning. We target a specific application: modifying the original urban design of a neighborhood with the goal of improving residents' health. Within this context, we intend to construct a tool that can: 1) understanding the current urban design based on provided GIS data and related documents; 2) grasping the goal of health improvement; 3) ensuring the compliance to the parent design and related laws, regulations, and policies; 4) recommending solutions and simulating scenarios; and 5) implementing these solutions to generate the final modified design. The tool involves Retrieval-Augmented Generation (RAG), autonomous agents, and tool-calling skills. Specifically, RAG will be used to construct a high-quality, domain-specific knowledgebase containing 1) governmental laws, regulations, and policies, 2) theoretical guidelines, and 3) empirical application cases. Such a knowledgebase is fundamental to the intelligent recommendation of solutions. The complex workflow is orchestrated through a multi-agent framework. Specialized AI agents may include: a "Context Agent" digesting text and spatial metadata, a "Compliance Agent" cross-referencing the RAG-enabled knowledgebase for policy adherence, a "Health Simulation Agent" evaluating proposed changes against health metrics, and a "Design Agent" formulating the final recommendations. To bridge the gap between text generation and spatial manipulation, the AI agents are equipped with programmatic "skills" (e.g., Python execution, API integration). These skills allow the AI to directly interact with spatial databases and GIS software, executing spatial queries, running scenario simulations, and procedurally generating the new spatial design files based on the synthesized recommendations. By integrating these Generative AI technologies with traditional GIS workflows, this research presents a scalable, intelligent framework that empowers urban planners to create healthier, more compliant, and highly optimized urban spaces.



Keywords: Generative AI,  GeoAI,  Healthy Cities,  Urban Planning,  Knowledgebase,  RAG,  Agent



Semantic Tags: GIS; generative AI; urban planning; health-centric neighborhood design; retrieval-augmented generation; multi-agent system; knowledge base


```{admonition} Presentation Information
:class: note

**Submission ID:** R8669  
**Session:** [Large Language Models and Agentic GIS](./Session_GFM-3/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** SRC-Lv1-LT-50  
```