# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Publication:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. However, due to challenges such as high cost and low gravity, there is a need for efficient drilling tools. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill. Using the discrete element method (DEM) and lunar highlands simulant (LHS-1) parameters, the study optimizes both drill geometry and controlling strategies to minimize construction cost and power consumption while maximizing drilling effectiveness and efficiency.

## 1. Introduction
The Artemis mission highlights the necessity for utilizing in situ resources on the Moon for NASA’s long-term strategy. Lunar regolith has great prospects in construction and habituation. Drilling is crucial for site investigation and characterization. Bio-inspired strategies, such as clam-inspired drilling, offer potential for high efficiency and low cost in geotechnical engineering on extraterrestrial bodies.

## 2. Numerical Modeling
The razor clam drill consists of a slender rigid shell, two convex shell valves, and a stretchable foot. The process includes three phases:
1. **Phase I: Cone penetration**
2. **Phase II: Anchor expansion**
3. **Phase III: Self-penetration**

### Table 1: Input parameters adopted for the numerical simulations
| Parameter | Value |
| :--- | :--- |
| Particle density, ρ (kg/m³) | 2720 |
| Porosity, n | 0.45 |
| Particle radius, rp (m) | 0.004 |
| Damping coefficient, γ (kg/s) | 0.7 |
| Ball-wall friction coefficient, fpw | 0.3 |
| Coefficient of sliding friction, fps | 0.9 |
| Coefficient of rolling friction, fpr | 0.3 |
| Particle effective modulus, E* (Pa) | 5 × 10⁷ |
| Normal-to-shear stiffness ratio, K* | 1.0 |
| Wall normal stiffness, kn (N/m³) | 1.5 × 10⁷ |
| Wall shear stiffness, ks (N/m³) | 1.5 × 10⁷ |

## 3. Design Space and Optimization
The study utilizes a Pareto front approach with a non-dominated sorting algorithm to identify the "knee point"—the most preferred design.

### Table 2: Design space for the clam-inspired drill design
| Category | Design parameter | Design space |
| :--- | :--- | :--- |
| **Drill geometry** | Anchor height, H (m) | 3r*, 4r, 5r |
| | Anchor shape, b (m) | 3r, 5r, ∞ |
| | Cone apex angle, α (°) | 30, 60, 90 |
| **Controlling strategies** | Downward velocity, VD (m/s) | 0.01, 0.02, 0.04 |
| | Rotation velocity, VR (rpm) | 0, 100, 400 |
| | Expansion velocity, VE | 0.01, 0.02, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 3r, 5r |

## 4. Key Findings
1. **Optimal Geometry:** The shortest anchor height (H=3r), cylinder-shaped anchor (b=∞), and a moderate cone apex angle (α=60°) were identified as the optimal configuration.
2. **Optimal Strategy:** Minimal downward velocity (0.01 m/s), minimal rotation (0 rpm), and a short anchor-cone distance (L=3r) maximize effectiveness.
3. **Efficiency:** Cylinder-shaped anchors are more effective in reducing penetration resistance than arc-shaped anchors due to higher expansion ratios.

## 5. Concluding Remarks
The proposed framework provides an efficient solution for designing bio-inspired tools for the Moon and other extraterrestrial bodies like Mars. Future work will include imposing vertical reaction force constraints as model parameters.