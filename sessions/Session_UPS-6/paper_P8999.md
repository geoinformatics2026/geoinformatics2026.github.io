---
title: "Identity Over Intensity: Device-Agnostic Urban WiFi Positioning via Stable Anchor Clustering"
authors:
- "Yuval Margolin"
- "Sagi Dalyot"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Identity Over Intensity: Device-Agnostic Urban WiFi Positioning via Stable Anchor Clustering

**Author Information**  
Yuval Margolin<sup>1</sup>, Sagi Dalyot<sup>1</sup>


<sup>1</sup> The Technion  



## Abstract

Reliable positioning in urban canyons and GNSS- denied environments is a critical challenge for autonomous navigation and location-based services. While WiFi fingerprinting offers a promising alternative, existing methods suffer from device heterogeneity: models trained on one device degrade when applied to another due to hardware-dependent signal variations. This study proposes a device-agnostic WiFi localization framework based on Identity Matching, prioritizing stable infrastructure access points (anchors) over raw signal intensity. Operating on a "train-on-one, test-on-another" paradigm, a radio map is generated using a standard smartphone and utilized to localize an independent robotic rover without prior calibration. The core innovation is a multi-stage spatial-protocol filtering pipeline that isolates fixed infrastructure from dynamic noise. A Layer-2 filter removes Locally Administered Addresses to eliminate randomized mobile hotspots, while density-based spatial clustering rejects access points exhibiting scattered patterns typical of moving vehicles. This pipeline discards over 60% of raw signals as noise. Localization is then performed using a Weighted K-Nearest Neighbors regressor via Manhattan distance. Experimental results from multi-day urban trajectories yield a median positioning error of 2.37 m and a mean error of 3.71 m (at the $99^{th}$ percentile), representing a substantial improvement over a GNSS-shadow- matching baseline. By substantially reducing large localization outliers and narrowing the gap between mean and median accuracy, this identity-driven approach establishes a scalable, hardware-robust methodology for resilient urban positioning. Leveraging existing WiFi infrastructure without device-specific calibration, it supports resource-efficient localization suitable for autonomous robotics and vulnerable pedestrians navigating GNSS-degraded urban environments.



Keywords: WiFi fingerprinting, Positioning, RSSI, Resilient Navigation, Identity Matching




```{admonition} Presentation Information
:class: note

**Submission ID:** P8999  
**Session:** [Urban Spatial Structure, Positioning, and Spatial Development](./Session_UPS-6/)  
**Theme:** Urban Analytics, Planning \& Socioeconomics    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 16:30 – 18:00  
**Venue:** Stephen Riady Centre-01-Seminar Room 1 & 2 (SR-A)  
```