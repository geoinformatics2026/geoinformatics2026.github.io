---
title: "A Container-Based Actor–Critic Reinforcement Learning Approach for Optimized Scheduling in Geospatial Computing Clouds"
authors:
- "Wang Xingjuan"
- "Xiang Longgang"

---

# A Container-Based Actor–Critic Reinforcement Learning Approach for Optimized Scheduling in Geospatial Computing Clouds

**Author Information**  
Wang Xingjuan<sup>1</sup>, Xiang Longgang<sup>1</sup>


<sup>1</sup> wuhan University  



## Abstract

As geospatial computing tasks are increasingly executed at scale in cloud environments, the resulting workloads are characterized by data-intensive processing, diverse operator compositions, and heterogeneous resource demands.Under such dynamic conditions, traditional rule-based or static scheduling strategies struggle to jointly optimize makespan and resource utilization. To address this challenge, this paper proposes a container-based optimization scheduling method for geospatial computing clouds, which integrates a scalable containerized parallel computing framework with an Actor–Critic reinforcement learning policy to enable adaptive and coordinated allocation of computing nodes and geospatial tasks.First, we designed and implemented an scalable containerized parallel computing framework for geospatial oprations.Through standardized operator interfaces and adaptation mechanisms, third-party open-source geospatial analysis operators can be integrated with low overhead and plug-and-play functionality, enabling operator-level orchestration and elastic scaling. Second, to address the diverse resource requirements of geospatial operators across heterogeneous resources (e.g., CPU and memory), we construct an operator resource-preference network that explicitly models operator–resource compatibility. This design enhances the scheduler’s awareness of heterogeneous resource characteristics and improves overall resource utilization efficiency.Finally, we combine the Actor–Critic reinforcement learning with spatio-temporal resource preference representations to develop an online scheduling strategy for dynamic environments. The proposed performs joint decision-making over container instances, compute nodes, and task queues in multi-load scenarios, aiming to reduce makespan and improving resource utilization.Experimental results on representative geocomputing workloads and varying task scales (100–600) demonstrate that the proposed method achieves significant improvements in completion time and resource utilization compared to classical scheduling strategies and multi-objective meta-heuristic baselines: average makespan reduction of 13%–22%, CPU utilization increase of 3%–12%, and memory utilization increase of 6%–13%. These results validate the effectiveness and scalability of the proposed method in containerized geographic computing cloud environments.



Keywords: Geospatial computing,  Containerized geospatial cloud,  Unified spatiotemporal framework,  Actor–Critic RL,  Heterogeneous resource coordination



```{admonition} Presentation Information
:class: note

**Submission ID:** 0902  
**Session:** [Emerging LLM-based Methods for Geospatial Analysis: Part 1](./Session_A1/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30
**Venue:** room 1
```