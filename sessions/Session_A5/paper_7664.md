---
title: "A Geometry-Aware, Voxel-Based Framework for Facade-Resolved Urban Road-Traffic Noise Assessment"
authors:
- "Tzu-Cheng Chang"
- "Sisi Zlatanova"
- "Ben Gorte"
- "Ta-Chien Chan"

---

# A Geometry-Aware, Voxel-Based Framework for Facade-Resolved Urban Road-Traffic Noise Assessment

**Author Information**  
Tzu-Cheng Chang<sup>1</sup>, Sisi Zlatanova<sup>2</sup>, Ben Gorte<sup>2</sup>, Ta-Chien Chan<sup>3</sup>


<sup>1</sup> National Taiwan University  

<sup>2</sup> University of New South Wales  

<sup>3</sup> Research Center for Humanities and Social Sciences, Academia Sinica  



## Abstract

Accurately characterizing urban road-traffic noise in three dimensions (3D), with explicit representation of facade orientation and vertical variation, remains challenging. Many workflows collapse exposure onto two-dimensional surfaces or represent blockage as a fixed loss that does not reflect local geometry, thereby distorting facade-level exposure contrasts and potentially misprioritizing mitigation actions. This study develops a voxel-based urban noise framework that integrates CityGML building geometry, DEM-derived building base elevations, and traffic observations to estimate road-traffic noise at surface receivers in Nangang District, Taipei. The framework is evaluated under three nested configurations: (i) a baseline voxel noise surface derived from merged building and road attributes; (ii) a traffic-driven CRTN line-source formulation that derives an 18-hour LA10 baseline from traffic flow and speed and applies finite-segment distance, uphill-slope, and angle-of-view corrections with energy superposition across nearby segments; and (iii) a facade-aware CRTN formulation that assigns each voxel to a facade plane or roof, replaces fixed blocked-path attenuation with geometry-dependent screening based on path difference, and incorporates site-layout proxy terms for near-facade and opposite-facade street-canyon effects. Across 53,097 building aggregates, all pairwise contrasts are significant under Holm-corrected Wilcoxon tests. At the voxel level, median exposure increases by +6.857 dB from the baseline to the traffic-driven formulation, but by only +1.909 dB from the baseline to the facade-aware formulation. The facade-aware formulation is 5.011 dB lower than the traffic-driven formulation. Building-level medians show the same ordering. Introducing facade assignment and geometry-dependent screening removes 72.2% of the voxel-level median uplift observed in the traffic-driven formulation, indicating that much of the apparent increase reflects omitted shielding and facade-context effects rather than elevated source loading. These results support interpreting the traffic-driven formulation as a corridor-scale screening envelope, whereas the facade-aware formulation provides a more defensible basis for facade-level intervention design and resource allocation in dense urban environments. 



Keywords: 3D noise mapping,  Traffic noise,  Voxel modeling,  Facade exposure



```{admonition} Presentation Information
:class: note

**Submission ID:** 7664  
**Session:** [Traffic Facade Voxel Crowd](./Session_A5/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30
**Venue:** room 5
```