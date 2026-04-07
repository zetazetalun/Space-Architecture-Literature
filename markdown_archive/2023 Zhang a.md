# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen
**Published:** Acta Geotechnica (2024)
**DOI:** 10.1007/s11440-023-02119-5

## Abstract
In recent years, many nations have launched lunar exploration missions. Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill into the lunar regolith using the discrete element method (DEM) based on lunar highlands simulant (LHS-1) parameters. The framework optimizes both geometry (anchor height, shape, cone apex angle) and controlling strategies (velocities and anchor-cone distance) to minimize construction cost and power consumption while maximizing drilling effectiveness and efficiency.

## 1. Introduction
Artemis missions highlight the necessity for utilizing in situ resources on the Moon. Drilling is essential for site investigation and resource characterization. Bio-inspired strategies, such as clam-inspired designs, offer potential for high-efficiency, low-cost drilling tools suitable for extreme lunar environments characterized by low gravity and high transport costs.

## 2. Methodology
### 2.1 Numerical Modeling
- **Software:** 3D DEM-based program Particle Flow Code (PFC3D) v7.0.
- **Simulant:** Lunar Highlands Simulant (LHS-1).
- **Gravity:** 1.625 m/s².
- **Drilling Phases:** 
  1. Phase I: Cone penetration.
  2. Phase II: Anchor expansion.
  3. Phase III: Self-penetration.

### 2.2 Optimization Framework
- **Stage 1 (Geometry):** Objectives include minimizing construction cost (surface area) and total power consumption. Parameters: Anchor height (H), Anchor shape (b), Cone apex angle (α).
- **Stage 2 (Control Strategies):** Objectives include maximizing drilling effectiveness (E1) and efficiency (E2). Parameters: Downward velocity (VD), Rotation velocity (VR), Expansion velocity (VE), Anchor-cone distance (L).

## 3. Results
- **Optimal Geometry:** Identified at the knee point of the Pareto front: H = 3r, b = 5r, α = 60°.
- **Optimal Strategies:** VD = 0.01 m/s, VR = 0 (no rotation preferred for efficiency in the specific optimized model), VE = 0.01 m/s, and L = 3r.
- **Effect of Geometry:** Cylinder-shaped anchors and sharp tips are more effective at reducing penetration resistance.
- **Effect of Control:** Low downward and expansion velocities allow more time for regolith particles to transfer load, improving performance.

## 4. Conclusion
The two-stage optimization framework provide an efficient solution for bio-inspired drill design on the Moon. The optimal design balances the trade-off between power consumption and drilling performance, serving as a guide for future extraterrestrial sub-surface exploration tools.