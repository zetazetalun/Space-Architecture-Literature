# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024)  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5  
**Published:** 26 November 2023 (Volume 19, 2024)

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill into the lunar regolith. The drilling process is analyzed using the discrete element method (DEM) based on parameters calibrated for the lunar highlands simulant (LHS-1). The study optimizes both drill geometry (anchor height, shape, cone apex angle) and controlling strategies (downward, rotation, and expansion velocities) with respect to construction cost, power consumption, and drilling efficiency.

## 1. Introduction
The Artemis mission highlights the necessity for utilizing in situ resources on the Moon for long-term strategies. Lunar regolith has great prospects in construction and habitation. However, lunar drilling faces challenges including high costs, low gravity, and extreme temperatures. Bio-inspired strategies, such as clam-inspired drilling, offer potential for high-efficiency, low-cost designs.

## 2. Methodology
### 2.1 Numerical Modeling
The 3D DEM-based program Particle Flow Code (PFC3D) version 7.0 was used. The simulation utilized lunar highlands simulant (LHS-1) properties under a low gravity of 1.625 m/s².

| Parameter | Value |
| :--- | :--- |
| Particle density, ρ (kg/m³) | 2720 |
| Porosity, n | 0.45 |
| Particle radius, rp (m) | 0.004 |
| Ball-wall friction coefficient, fpw | 0.3 |
| Particle effective modulus, E* (Pa) | 5 x 10⁷ |
| Normal-to-shear stiffness ratio, K* | 1.0 |
| Wall normal stiffness, kn (N/m³) | 1.5 x 10⁷ |

### 2.2 Optimization Framework
*   **Stage 1: Geometry Optimization.** Objectives: Minimize construction cost (C) and total power consumption (W).
*   **Stage 2: Controlling Strategy Optimization.** Objectives: Maximize drilling effectiveness (E1) and drilling efficiency (E2).

## 3. Results and Key Findings
*   **Geometry:** Cylinder-shaped anchors and sharp tips are more effective in reducing penetration resistance. A shorter anchor height contributes to better stress relaxation near the cone tip.
*   **Optimal Geometry Design:** Anchor height $H=3r$, anchor shape $b=5r$, and cone apex angle $\alpha=60^\circ$.
*   **Optimal Controlling Strategies:** Downward velocity $V_D = 0.01$ m/s, rotation velocity $V_R = 0$ rpm, expansion velocity $V_E = 0.01$, and anchor-cone distance $L = 3r$.

## 4. Conclusion
The proposed framework provides an efficient solution for designing bio-inspired drills for the lunar surface. Low downward and rotation velocities contribute to better penetration effectiveness, while specific geometric configurations minimize the energy footprint required for ISRU site characterization.