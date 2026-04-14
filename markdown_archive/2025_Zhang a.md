# Multivariate adaptive regression splines for two-stage design optimization of bio-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Yuxin Yuan, Jiajie Cheng, Lei Wang  
**Published:** 19 May 2025 (Online)  
**Journal:** Structural and Multidisciplinary Optimization (2025) 68:92  
**DOI:** https://doi.org/10.1007/s00158-025-04022-x

## Abstract
This paper proposes an adaptively updating two-stage multi-objective optimization design framework based on Multivariate Adaptive Regression Splines (MARS) for the design of the bio-inspired drill into the lunar regolith. In this framework, the geometry parameters and the controlling strategies are optimized in Stage 1 and Stage 2, respectively, aided by discrete element modeling of the bio-inspired drilling process. Minimizing construction cost and total power consumption are the design objectives in Stage 1, whereas maximizing drilling effectiveness and drilling efficiency are the design objectives in Stage 2. The Pareto front-based design optimization method is utilized to identify the optimal design in each stage. The proposed framework provides an efficient solution and valuable insights for the optimal design of a bio-inspired drill into the lunar regolith.

## 1. Introduction
Lunar regolith presents significant potential for construction and habitation on the Moon. In situ drilling is one of the most effective and straightforward approaches to understanding its properties. Direct adaptation of terrestrial technology remains challenging due to limited knowledge, lack of human involvement, and high costs. Bio-inspired designs (e.g., clam-inspired) offer energy-efficient, small-scale solutions suitable for low-gravity environments.

## 2. Numerical Modeling
The discrete element method (DEM) program, Particle Flow Code (PFC3D), was used to simulate lunar highlands simulant (LHS-1). The bio-inspired drilling process involves three phases: 
1. **Phase I:** Cone penetration
2. **Phase II:** Anchor expansion
3. **Phase III:** Self-penetration

### Table 2: Input parameters for numerical simulations
| Parameter | Value |
|---|---|
| Particle density, ρ (kg/m³) | 2720 |
| Porosity, n | 0.45 |
| Particle effective modulus, E* (Pa) | 5 × 10⁷ |
| Normal-to-shear stiffness ratio, K* | 1.0 |
| Gravity, g (m/s²) | 1.625 |

## 3. Optimization Framework

### Table 3: Design Space Parameters
| Category | Design Parameter | Design Space |
|---|---|---|
| **Drill Geometry** | Anchor height, H (m) | 2r to 5r |
| | Anchor shape, b (m) | 3r to 10r |
| | Cone apex angle, α (°) | 30 to 180 |
| **Strategies** | Downward velocity, VD (m/s) | 0.01 to 0.04 |
| | Rotation velocity, VR (rpm) | 0 to 400 |
| | Expansion velocity, VE | 0.01 to 0.04 |
| | Anchor-cone distance, L (m) | 1r to 5r |

## 4. Key Results
The final MARS model for drill geometry in Stage 1 is formulated as:
`W = 0.55818 + 0.5515*BF1 + 0.87449*BF2 - 1.0501*BF3` (where W is power consumption).

The final optimal design for the bio-inspired drill into lunar regolith is:
- **H = 2r**
- **b = 3r**
- **α = 63°**
- **VD = 0.01 m/s**
- **VR = 0 rpm**
- **VE = 0.01**
- **L = 1r**

## 5. Conclusion
The study concludes that MARS-based optimization yields more accurate optimal designs than traditional methods by exploring a continuous design space and identifying non-dominant designs closer to the "Utopia Design." Feature relative importance analysis identified the cone apex angle (α) as the most critical factor for Stage 1 power consumption.