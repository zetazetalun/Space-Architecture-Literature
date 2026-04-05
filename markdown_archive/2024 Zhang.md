# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5  

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill into the lunar regolith using the discrete element method (DEM) based on lunar highlands simulant (LHS-1) parameters. The study optimizes both geometry (anchor height, shape, cone apex angle) and controlling strategies (velocities, anchor-cone distance) to minimize construction cost and power consumption while maximizing drilling effectiveness and efficiency.

## 1. Introduction
Lunar exploration requires the utilization of in situ resources for long-term strategies (e.g., Artemis mission). Drilling is essential for site investigation and resource extraction. Bio-inspired strategies, such as clam-inspired drilling, offer potential for high-efficiency, low-cost, and sustainable designs. This study addresses the lack of optimization reports for such tools in a lunar environment.

## 2. Numerical Modeling
- **Software:** 3D DEM-based program Particle Flow Code (PFC3D) version 7.0.
- **Simulant:** Lunar Highlands Simulant (LHS-1).
- **Environment:** Low gravity (1.625 m/s²).
- **Process Phases:** 
    1. Phase I: Cone penetration.
    2. Phase II: Anchor expansion.
    3. Phase III: Self-penetration.

## 3. Design Parameters & Optimization

### Table 1: Input parameters for numerical simulations
| Parameter | Value |
| :--- | :--- |
| Particle density, ρ | 2720 kg/m³ |
| Porosity, n | 0.45 |
| Particle radius, rp | 0.004 m |
| Particle effective modulus, E* | 5 × 10⁷ Pa |
| Normal-to-shear stiffness ratio, K* | 1.0 |

### Table 2: Design space for optimization
| Category | Design parameter | Design space |
| :--- | :--- | :--- |
| **Drill geometry** | Anchor height, H | 3r, 4r, 5r |
| | Anchor shape, b | 3r, 5r, ∞ |
| | Cone apex angle, α | 30°, 60°, 90° |
| **Controlling strategies** | Downward velocity, VD | 0.01, 0.02, 0.04 m/s |
| | Rotation velocity, VR | 0, 100, 400 rpm |
| | Expansion velocity, VE | 0.01, 0.02, 0.04 |
| | Anchor-cone distance, L | 1r, 3r, 5r |

## 4. Results
- **Optimal Geometry:** Shortest anchor height (H=3r), arc-shaped anchor (b=5r), and moderate cone apex angle (α=60°) were identified as the best trade-off between cost and power.
- **Optimal Controlling Strategies:** The most preferred strategies were downward velocity VD = 0.01 m/s, rotation velocity VR = 0, expansion velocity VE = 0.01, and anchor-cone distance L = 3r.
- **Efficiency:** Bio-inspired drilling significantly reduces penetration resistance by exploiting stress relaxation around the anchor.

## 5. Conclusions
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. Anchor height has a minor effect on penetration resistance but impacts construction cost.
3. Low downward/rotation velocities allow better regolith particle adjustment, enhancing drilling effectiveness.
4. Closer anchor-cone distances improve the stress reduction effect at the cone tip.