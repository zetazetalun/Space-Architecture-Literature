# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5

## Abstract
In recent years, many nations have launched lunar exploration missions. Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. However, due to many challenges faced in the drilling operation on the Moon (e.g., high cost, low gravity, and other lunar environment conditions), there is a need to develop efficient drilling tools for in situ characterization of lunar regolith. Seeking an optimal lunar drill design with effective and efficient controlling strategies has become a matter of urgency. This paper presents a two-stage multi-objective optimization design framework for the clam-inspired drill design into the lunar regolith.

## 1 Introduction
The recent Artemis mission has highlighted the necessity for utilizing the in situ resources on the Moon for NASA’s long-term strategy to build technologies for further space exploration. With limited resources on the Moon, the lunar regolith has great prospects in the construction and habituation on the Moon. Drilling, as one of the most effective and straightforward approaches to characterizing the lunar regolith, is crucial for studies on the lunar regolith.

## 2 Two-stage multi-objective optimization framework

### 2.1 Numerical modeling of the clam-inspired drilling process
The razor clam consists of a slender rigid shell, two convex shell valves, and a stretchable foot. The drilling process can be divided into three phases: 
1. **Phase I:** Cone penetration.
2. **Phase II:** Anchor expansion.
3. **Phase III:** Self-penetration.

The 3D DEM-based program Particle Flow Code (PFC3D) version 7.0 is adopted for the numerical simulations. The lunar regolith is represented using the lunar highlands simulant (LHS-1).

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

## 3 Results of multi-objective optimization
- **Geometry Optimization:** The shortest anchor height (H=3r) is identified as the most preferable design because it causes minimal difference on candidates while contributing to more stress relaxation. A cone apex angle of α = 60° reaches an optimal trade-off between construction cost and total power consumption.
- **Control Strategy Optimization:** The final optimal design of the controlling strategies is determined as VD = 0.01 m/s (downward velocity), VR = 0 (rotation velocity), VE = 0.01 (expansion velocity), and L = 3r (anchor-cone distance).

## 5 Concluding remarks
1. Cylinder-shaped anchors and sharp tips are effective in the reduction of penetration resistance.
2. Optimal drill geometry is determined as an arc-shaped anchor with the smallest height and moderate cone apex angle (H = 3r, b = 5r, and α = 60°).
3. Low downward velocity and low expansion velocity contribute to the decrease of penetration resistance by allowing regolith particles time to transfer load and adjust stress states.