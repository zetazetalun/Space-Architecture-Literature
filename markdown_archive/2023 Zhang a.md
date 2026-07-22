# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen
**Published:** Acta Geotechnica (2024) 19:1379–1396
**DOI:** https://doi.org/10.1007/s11440-023-02119-5

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill into lunar regolith. Using the discrete element method (DEM) based on calibrated parameters for lunar highlands simulant (LHS-1), the study optimizes drill geometry (anchor height, shape, and cone apex angle) and controlling strategies (velocity, rotation, expansion) to minimize construction cost and power consumption while maximizing drilling effectiveness.

## 1. Introduction
Recent Artemis missions highlight the necessity of utilizing in situ resources (ISRU) on the Moon. Limited resources and high transportation costs necessitate advanced drilling tools for characterization and construction. Bio-inspired strategies, such as clam-inspired drilling, offer highly efficient, low-cost solutions for extraterrestrial geotechnical challenges.

## 2. Methodology
### 2.1 Numerical Modeling
The 3D DEM-based program Particle Flow Code (PFC3D) was used. The lunar regolith was modeled using LHS-1 simulant properties with a low gravity of 1.625 m/s².

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

### 2.2 Design Optimization Framework
- **Stage 1:** Drill Geometry (Anchor height H, Anchor shape b, Cone apex angle α).
- **Stage 2:** Controlling Strategies (Downward velocity VD, Rotation velocity VR, Expansion velocity VE, Anchor-cone distance L).

### Table 2: Design space for the clam-inspired drill design
| Category | Design parameter | Design space |
| :--- | :--- | :--- |
| Drill geometry | Anchor height, H (m) | 3r*, 4r, 5r |
| | Anchor shape, b (m) | 3r, 5r, ∞ |
| | Cone apex angle, α (°) | 30, 60, 90 |
| Controlling strategies | Downward velocity, VD (m/s) | 0.01, 0.02, 0.04 |
| | Rotation velocity, VR (rpm) | 0, 100, 400 |
| | Expansion velocity, VE | 0.01, 0.02, 0.04 |
| | Anchor-cone distance, L (m) | 1r, 3r, 5r |
*"r" denotes the shaft radius of the drill.

## 5. Concluding remarks
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. Optimal geometry identified: H = 3r, b = 5r, and α = 60°.
3. Low downward/expansion velocity and minimized rotation contribute to higher efficiency.
4. Optimal controlling strategies: VD = 0.01 m/s, VR = 0, VE = 0.01, L = 3r.