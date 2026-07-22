# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5  
**Published:** 26 November 2023

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for clam-inspired drill design using the discrete element method (DEM). The geometry and controlling strategies are optimized to minimize construction cost and power consumption while maximizing drilling effectiveness and efficiency.

## 1. Introduction
The Artemis mission highlights the necessity for utilizing in situ resources on the Moon. Lunar regolith has great prospects for construction and habituation. However, drilling on the Moon faces challenges like low gravity and high transportation costs. Clam-inspired (bio-inspired) strategies offer potential for high efficiency and low-cost sustainable designs in geotechnical engineering.

## 2. Methodology
### 2.1 Numerical Modeling
- **Software:** 3D DEM-based Particle Flow Code (PFC3D) version 7.0.
- **Simulant:** Lunar Highlands Simulant (LHS-1).
- **Gravity:** 1.625 m/s².
- **Phases:** I. Cone penetration, II. Anchor expansion, III. Self-penetration.

### 2.2 Input Parameters (Table 1)
| Parameter | Value |
| :--- | :--- |
| Particle density | 2720 kg/m³ |
| Porosity | 0.45 |
| Particle radius | 0.004 m |
| Particle effective modulus | 5 x 10⁷ Pa |
| Wall normal/shear stiffness | 1.5 x 10⁷ N/m³ |

## 3. Results
### 3.1 Drill Geometry Optimization (Stage 1)
Objectives: Minimize construction cost ($C$) and total power consumption ($W$).
- **Anchor shape:** Cylinder-shaped anchors are more effective in penetration reduction than arc-shaped anchors.
- **Cone apex angle:** Smaller angles (sharper tips) reduce penetration resistance and local stress peaks.
- **Optimal Geometry Result:** $H=3r, b=5r, \alpha=60^\circ$ (identified as the knee point on the Pareto front).

### 3.2 Controlling Strategy Optimization (Stage 2)
Objectives: Maximize drilling effectiveness ($E_1$) and efficiency ($E_2$).
- **Downward velocity ($V_D$):** Lower velocities allow more time for stress relaxation in regolith particles.
- **Rotation velocity ($V_R$):** Optimal designs suggest low or zero rotation for the clam-inspired mechanism to maintain efficiency.
- **Optimal Control Result:** $V_D=0.01$ m/s, $V_R=0$ rpm, $V_E=0.01$ (normalized), $L=3r$.

## 4. Conclusions
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. Optimal drill geometry achieves a trade-off between mass (cost) and energy use.
3. Lower downward velocity and closer anchor-cone distance significantly enhance drilling performance by facilitating stress redistribution in the regolith.