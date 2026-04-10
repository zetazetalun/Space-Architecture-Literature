# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Published:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill design using the discrete element method (DEM). The study optimizes both geometry (anchor height, shape, cone angle) and controlling strategies (velocities, distance) to minimize cost and power while maximizing efficiency.

## 1. Introduction
The Artemis mission highlights the necessity of utilizing in situ resources (ISRU). Lunar regolith has great prospects for construction and habituation. However, drilling faces challenges like low gravity and extreme temperatures. Bio-inspired strategies (e.g., razor clam mechanisms) offer potential for low-cost, sustainable designs in geotechnical engineering.

## 2. Methodology
### 2.1 Numerical Modeling
- **Tool:** 3D DEM-based program Particle Flow Code (PFC3D) version 7.0.
- **Simulant:** Lunar Highlands Simulant (LHS-1).
- **Phases:** 
  1. Phase I: Cone penetration.
  2. Phase II: Anchor expansion.
  3. Phase III: Self-penetration.

### 2.2 Optimization Framework
- **Stage 1:** Geometry optimization (Anchor height $H$, Shape $b$, Cone apex angle $\alpha$).
- **Stage 2:** Controlling strategy optimization (Downward velocity $V_D$, Rotation velocity $V_R$, Expansion velocity $V_E$, Anchor-cone distance $L$).

## 3. Results and Discussion
### 3.1 Geometry Optimization
- Blunter tips (large cone angles) induce higher local peaks in penetration resistance.
- Shorter anchor heights are more advantageous for reducing penetration resistance ($Q_c$) due to stress relaxation effects.
- **Optimal Geometry identified:** $H = 3r$, $b = 5r$ (arc-shaped), and $\alpha = 60^\circ$.

### 3.2 Strategy Optimization
- **Downward Velocity ($V_D$):** Higher $V_D$ leads to higher stress levels; lower $V_D$ allows regolith particles time to transfer loads.
- **Rotation Velocity ($V_R$):** Rotation decreases particle attachment to the cone.
- **Optimal Strategy identified:** $V_D = 0.01$ m/s, $V_R = 0$, $V_E = 0.01$ m/s, $L = 3r$.

## 4. Conclusion
The proposed two-stage optimization provides an efficient solution for bio-inspired lunar drilling. Optimal designs balance the trade-off between power consumption and drilling effectiveness.

### Table 1: Input parameters for numerical simulations
| Parameter | Value |
| :--- | :--- |
| Particle density, $\rho$ ($kg/m^3$) | 2720 |
| Porosity, $n$ | 0.45 |
| Particle radius, $r_p$ (m) | 0.004 |
| Particle effective modulus, $E^*$ (Pa) | $5 \times 10^7$ |
| Normal-to-shear stiffness ratio, $K^*$ | 1.0 |