# Multivariate adaptive regression splines for two-stage design optimization of bio-inspired drilling into the lunar regolith

**Liang Zhang, Yuxin Yuan, Jiajie Cheng, Lei Wang**

*Structural and Multidisciplinary Optimization (2025) 68:92*
*https://doi.org/10.1007/s00158-025-04022-x*

## Abstract
This paper proposes an adaptively updating two-stage multi-objective optimization design framework based on Multivariate Adaptive Regression Splines (MARS) for the design of the bio-inspired drill into the lunar regolith. Minimizing construction cost and total power consumption are the design objectives in Stage 1, whereas maximizing drilling effectiveness and drilling efficiency are the design objectives in Stage 2. The proposed framework provides an efficient solution and valuable insights for the optimal design of a bio-inspired drill into the lunar regolith.

## Methodology: Bio-Inspired Drilling
The bio-inspired drilling process (clam-inspired) involves three phases:
1. **Cone penetration** (Phase I)
2. **Anchor expansion** (Phase II)
3. **Self-penetration** (Phase III)

### Numerical Modeling
- **Software:** Particle Flow Code (PFC3D) version 7.0.
- **Simulant:** Lunar Highlands Simulant (LHS-1).
- **Geometry Parameters:** Anchor height (H), anchor shape (b), and cone apex angle (α).
- **Control Parameters:** Downward velocity (Vd), rotation velocity (Vr), expansion velocity (Ve), and anchor-cone distance (L).

## Design Optimization Results

### Stage 1: Geometry Optimization
- **Objective:** Minimize construction cost (C) and total power consumption (W).
- **Optimal Design:** H = 2r, b = 3r, α = 63°.
- **MARS Performance:** R² ≈ 0.988, RMSE ≈ 0.40.

### Stage 2: Controlling Strategy Optimization
- **Objective:** Maximize drilling effectiveness (E1) and drilling efficiency (E2).
- **Optimal Design:** Vd = 0.01 m/s, Vr = 0, Ve = 0.01, L = 1r.

## Key Findings
- **Critical Factor:** The cone apex angle (α) is the most critical factor for total power consumption in geometry design.
- **Drilling Parameters:** Downward velocity and rotation velocity primarily influence drilling effectiveness and efficiency.
- **Optimization Efficiency:** MARS-based surrogate models allow for global design space exploration with significantly reduced computational burden compared to exhaustive Discrete Element Method (DEM) simulations.
- **Bio-inspired Advantage:** The dual-anchor clam-inspired strategy provides an energy-efficient alternative suitable for low-gravity environments without requiring large external forces.

## Conclusion
The adaptively updating MARS framework identifies superior optimal designs compared to traditional methods by filling gaps in the discrete design space. The findings provide a roadmap for developing automated, bio-inspired excavators and site characterization tools for lunar and extraterrestrial bases.