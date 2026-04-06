# Multivariate adaptive regression splines for two-stage design optimization of bio-inspired drilling into the lunar regolith

**Journal:** Structural and Multidisciplinary Optimization (2025) 68:92
**DOI:** https://doi.org/10.1007/s00158-025-04022-x

## Abstract
This paper proposes an adaptively updating two-stage multi-objective optimization design framework based on Multivariate Adaptive Regression Splines (MARS) for the design of the bio-inspired drill into the lunar regolith. In this framework, the geometry parameters and the controlling strategies are optimized in Stage 1 and Stage 2, respectively, aided by discrete element modeling of the bio-inspired drilling process. Minimizing construction cost and total power consumption are the design objectives in Stage 1, whereas maximizing drilling effectiveness and drilling efficiency are the design objectives in Stage 2. The Pareto front-based design optimization method is utilized to identify the optimal design in each stage. The proposed framework provides an efficient solution and valuable insights for the optimal design of a bio-inspired drill into the lunar regolith, which will set the stage for the design of bio-inspired tools and technologies applicable to other extraterrestrial environments.

## 1 Introduction
In recent years, there has been a growing global interest in lunar exploration. As an almost unlimited resource on the Moon, the lunar regolith presents significant potential for construction and habitation on the Moon. In situ drilling is one of the most effective and straightforward approaches to understanding the properties of the lunar regolith. Bio-inspired designs (e.g., clam-inspired designs) have recently gained significant attention and provide energy-efficient solutions for advancing drilling technology for advanced geotechnical in situ characterization. 

## 3 Adaptively updating multi-objective design optimization framework

### 3.1 Numerical modeling of bio-inspired drilling process
The bio-inspired drilling process can be divided into three phases: cone penetration (Phase I), anchor expansion (Phase II), and self-penetration (Phase III). The discrete element method (DEM)-based program, Particle Flow Code (PFC3D) version 7.0, is utilized to analyze the behavior of lunar regolith (LHS-1 simulant).

### Table 2: Input parameters adopted for the numerical simulations
| Parameter | Value |
| :--- | :--- |
| Particle density, ρ (kg/m³) | 2720 |
| Porosity, n | 0.45 |
| Particle radius, rp (m) | 0.004 |
| Damping coefficient, γ | 0.7 |
| Ball-wall friction coefficient, fpw | 0.3 |
| Coefficient of sliding friction, fps | 0.9 |
| Coefficient of rolling friction, fpr | 0.3 |
| Particle effective modulus, E* (Pa) | 5 × 10⁷ |
| Normal-to-shear stiffness ratio, K* | 1.0 |
| Gravity, g (m/s²) | 1.625 |

### Table 3: Design space with coarse intervals for MARS model construction
| Category | Design parameter | Design space |
| :--- | :--- | :--- |
| Drill geometry | Anchor height, H (m) | 2r, 2.5r, 3r, 3.5r, 4r, 4.5r, 5r |
| | Anchor shape, b (m) | 3r, 4r, 5r, 6r, 7r, 10r |
| | Cone apex angle, α (°) | 30, 60, 90, 120, 150, 180 |
| Controlling strategies | Downward velocity, VD (m/s) | 0.01, 0.02, 0.03, 0.04 |
| | Rotation velocity, VR (rpm) | 0, 100, 200, 300, 400 |
| | Expansion velocity, VE | 0.01, 0.02, 0.03, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 2r, 3r, 4r, 5r |
*Note: "r" is denoted as the shaft radius of the drill.*

## 4 Design optimization results
The MARS models for all updates yield high R² (>0.9) and low RMSE, indicating accurate predictions of power consumption, effectiveness, and efficiency. 

### Final Optimal Design Results
- **Geometry:** H = 2r, b = 3r, and α = 63°
- **Control Strategies:** VD = 0.01 m/s, VR = 0 rpm, VE = 0.01, L = 1r

## 6 Conclusion
1. The design objectives in two stages (construction cost, power, effectiveness, efficiency) are accurately predicted by MARS with very high R² and low RMSE.
2. MARS significantly reduces the number of design combinations required, resulting in a more efficient design process.
3. MARS yields more accurate optimal designs by identifying non-dominant designs closer to the Utopia Design.
4. Feature relative importance analysis identifies critical parameters, such as the cone apex angle (α), as the most critical factor for power consumption in geometry design.