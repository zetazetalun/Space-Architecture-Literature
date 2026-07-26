# Multivariate adaptive regression splines for two-stage design optimization of bio-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Yuxin Yuan, Jiajie Cheng, Lei Wang
**Publication:** Structural and Multidisciplinary Optimization (2025)
**DOI:** 10.1007/s00158-025-04022-x

## Abstract
This paper proposes an adaptively updating two-stage multi-objective optimization design framework based on Multivariate Adaptive Regression Splines (MARS) for the design of the bio-inspired drill into the lunar regolith. In this framework, the geometry parameters and the controlling strategies are optimized in Stage 1 and Stage 2, respectively, aided by discrete element modeling of the bio-inspired drilling process. Minimizing construction cost and total power consumption are the design objectives in Stage 1, whereas maximizing drilling effectiveness and drilling efficiency are the design objectives in Stage 2.

## Key Parameters and Design Space

### Table 2: Input parameters adopted for the numerical simulations
| Parameter | Value |
|---|---|
| Particle density, ́ (kg/m³) | 2720 |
| Porosity, n | 0.45 |
| Particle radius, r_p (m) | 0.004 |
| Gravity, g (m/s²) | 1.625 |
| Particle effective modulus, E* (Pa) | 5 × 10⁷ |

### Table 3: Design space with coarse intervals for MARS model construction
| Category | Design parameter | Design space |
|---|---|---|
| Drill geometry | Anchor height, H (m) | 2r, 2.5r, 3r, 3.5r, 4r, 4.5r, 5r |
| | Anchor shape, b (m) | 3r, 4r, 5r, 6r, 7r, 10r |
| | Cone apex angle, α (°) | 30, 60, 90, 120, 150, 180 |
| Controlling strategies | Downward velocity, V_D (m/s) | 0.01, 0.02, 0.03, 0.04 |
| | Rotation velocity, V_R (rpm) | 0, 100, 200, 300, 400 |
| | Expansion velocity, V_E | 0.01, 0.02, 0.03, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 2r, 3r, 4r, 5r |

## Summary of Findings
The proposed MARS-based framework provides a more accurate optimal design compared to traditional methods by identifying non-dominant designs across a continuous design space. In Stage 1 (Geometry), the cone apex angle was found to be the most critical factor affecting power consumption. In Stage 2 (Control Strategies), downward and rotation velocities were the primary influences on drilling effectiveness and efficiency, while expansion velocity had negligible impact.

## Conclusion
MARS significantly reduces the computational burden of Discrete Element Method (DEM) simulations while yielding superior Pareto fronts. The iterative updating process ensures that the optimal design is not limited to initially selected candidate points, providing a robust solution for designing tools for extreme extraterrestrial environments.