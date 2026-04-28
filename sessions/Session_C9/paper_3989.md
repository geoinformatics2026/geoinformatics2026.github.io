---
title: "A View-Dependent Level-of-Detail Rendering Method for Continuous Geographic Features"
authors:
- "Yuchuan Zhou"
- "Xiang Zhang"

---

# A View-Dependent Level-of-Detail Rendering Method for Continuous Geographic Features

**Author Information**  
Yuchuan Zhou<sup>1</sup>, Xiang Zhang<sup>1</sup>


<sup>1</sup> SUN YAT-SEN UNIVERSITY  



## Abstract

Efficient visualization of large-scale geospatial data is a core component of modern web and mobile GIS applications. While Level-of-Detail (LOD) techniques successfully balance visualization quality with computational efficiency, rendering continuous geographic features—such as roads, rivers, and trajectories—remains a significant challenge. Because these extended features span vast distances across a map, they demand variable resolution: high detail near the user's viewpoint and progressive simplification further away. However, existing LOD structures struggle to support variable resolution within a single continuous spatial object. Furthermore, conventional methods decouple the LOD transitions of vector features from the underlying terrain. This separation frequently causes topological inconsistencies and visual artifacts, such as features floating above or penetrating the terrain surface. To address these limitations, we propose a novel view-dependent LOD methodology based on hierarchical spatial tessellation. Our approach approximates continuous geographic features by tessellating their spatial footprint into a hierarchical cell structure. The algorithm dynamically splits or merges these cells in real-time to generate multi-level details adapted to the user's perspective. The primary contributions of this work are threefold: (1) generating adaptive, intra-object LOD with seamless transitions; (2) synchronizing the LOD of discrete spatial features with the underlying digital elevation model (DEM) or terrain surface; and (3) preserving topological consistency to prevent intersection anomalies between adjacent features during transitions. Applicable to both 2D and 3D geospatial environments, experimental results demonstrate that our method facilitates fluid, interactive exploration of large-scale scenes. By strictly maintaining topological connectivity and structural coherence, this approach provides a robust geo-innovation for efficient spatial data visualization.



Keywords: geospatial visualization,  computer graphics,  cartography,  level-of-detail



```{admonition} Presentation Information
:class: note

**Submission ID:** 3989  
**Session:** [Spectral Extraction Features Branch](./Session_C9/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45
**Venue:** room 9
```