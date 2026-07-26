# Multivariate adaptive regression splines for two-stage design optimization of bio-inspired drilling into the lunar regolith

**Liang Zhang, Yuxin Yuan, Jiajie Cheng, Lei Wang**

**Published:** 2025 in *Structural and Multidisciplinary Optimization*

## Abstract
This paper proposes an adaptively updating two-stage multi-objective optimization design framework based on Multivariate Adaptive Regression Splines (MARS) for the design of the bio-inspired drill into the lunar regolith. In this framework, the geometry parameters and the controlling strategies are optimized in Stage 1 and Stage 2, respectively, aided by discrete element modeling of the bio-inspired drilling process. The proposed framework provides an efficient solution and valuable insights for the optimal design of a bio-inspired drill into the lunar regolith.

## Technical Parameters and Design Space

| Category | Design parameter | Design space (Coarse Intervals) |
| :--- | :--- | :--- |
| Drill geometry | Anchor height, H (m) | 2r, 2.5r, 3r, 3.5r, 4r, 4.5r, 5r |
| | Anchor shape, b (m) | 3r, 4r, 5r, 6r, 7r, 10r |
| | Cone apex angle, alpha (deg) | 30, 60, 90, 120, 150, 180 |
| Controlling strategies | Downward velocity, VD (m/s) | 0.01, 0.02, 0.03, 0.04 |
| | Rotation velocity, VR (rpm) | 0, 100, 200, 300, 400 |
| | Expansion velocity, VE | 0.01, 0.02, 0.03, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 2r, 3r, 4r, 5r |

## Key Findings
1. **Surrogate Modeling Efficiency:** MARS accurately predicts drilling performance metrics (Construction Cost, Power Consumption, Effectiveness, Efficiency) with R-squared values exceeding 0.988.
2. **Optimization Superiority:** The adaptively updating MARS framework identifies a more accurate Pareto front and knee point compared to traditional discrete grid search methods.
3. **Sensitivity Analysis:** Cone apex angle is the most critical factor for power consumption in geometry design, while downward and rotation velocities dominate drilling effectiveness and efficiency.

## Conclusion
The MARS-based framework significantly reduces the computational burden of Discrete Element Method (DEM) simulations. The study identifies an optimal lunar drill design: H=2r, b=3r, alpha=63 degrees, with a specific low-velocity control strategy (VD=0.01 m/s, VR=0).