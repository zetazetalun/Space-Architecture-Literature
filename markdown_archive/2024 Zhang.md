# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Published:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5

## Abstract
In recent years, many nations have launched lunar exploration missions. Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for the clam-inspired drill design into the lunar regolith. The process is analyzed using the discrete element method (DEM) based on parameters for lunar highlands simulant (LHS-1). The first stage optimizes drill geometry (anchor height, shape, and cone apex angle) regarding construction cost and power consumption. The second stage optimizes controlling strategies (velocities and distances) for drilling effectiveness and efficiency. The framework provides a guide for bio-inspired tools for extraterrestrial bodies.

## 1. Introduction
Artemis missions highlight the necessity of utilizing in situ resources (ISRU) on the Moon. Lunar regolith has great prospects in construction and habitation. However, lunar drilling faces challenges such as low gravity, high transportation costs, and specific regolith properties. Bio-inspired strategies, such as clam-inspired drilling, offer highly efficient, low-cost, and sustainable solutions. This study uses a DEM-based numerical model to evaluate geometry and mechanisms.

## 2. Numerical Modeling
The clam-inspired drill consists of a rigid shell, convex shell valves, and a stretchable foot. The process involves three phases:
1. **Phase I (Cone penetration):** Downward movement with constant velocity and rotation.
2. **Phase II (Anchor expansion):** Radial expansion to change soil stress states.
3. **Phase III (Self-penetration):** Continued penetration while the anchor moves upward relative to the shaft.

### Table 1: Input parameters for numerical simulations
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
| Wall normal stiffness, kn (N/m³) | 1.5 × 10⁷ |
| Wall shear stiffness, ks (N/m³) | 1.5 × 10⁷ |

## 3. Results and Optimization

### 3.1 Drill Geometry Optimization
- **Anchor Shape:** Cylinder-shaped anchors are more effective in penetration reduction than arc-shaped anchors.
- **Anchor Height:** Shorter anchor heights are more advantageous for reducing cone resistance (Qc) due to localized stress relaxation.
- **Cone Angle:** A 60° cone apex angle provides an optimal trade-off between penetration resistance and surface area (cost).

### 3.2 Controlling Strategy Optimization
- **Downward Velocity (VD):** Smaller VD values are advantageous as they allow regolith particles more time to transfer loads and adjust stress states.
- **Rotation Velocity (VR):** Low rotation or no rotation (VR = 0) was found to be more efficient in certain phases to minimize power consumption relative to effectiveness gain.

### Table 2: Design space for the clam-inspired drill design
| Category | Design parameter | Design space |
| :--- | :--- | :--- |
| Drill geometry | Anchor height, H (m) | 3r, 4r, 5r |
| | Anchor shape, b (m) | 3r, 5r, ∞ |
| | Cone apex angle, α (°) | 30, 60, 90 |
| Controlling strategies | Downward velocity, VD (m/s) | 0.01, 0.02, 0.04 |
| | Rotation velocity, VR (rpm) | 0, 100, 400 |
| | Expansion velocity, VE | 0.01, 0.02, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 3r, 5r |

## 4. Concluding Remarks
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. The optimal drill geometry is identified as H = 3r, b = 5r, and α = 60°.
3. Lower downward velocities and closer anchor-cone distances significantly contribute to decreasing penetration resistance.
4. The optimal controlling strategy identified was VD = 0.01 m/s, VR = 0, VE = 0.01, and L = 3r.