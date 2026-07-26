# A virtual 3D printing framework for off-Earth construction

**Authors:** Md Tusher Mollah, Berin Šeta, Jon Spangenberg
**Journal:** Acta Astronautica 244 (2026) 524–538
**Publisher:** Elsevier

## Abstract
3D printing offers a practical approach to autonomous off-Earth construction by utilizing local materials (ISRU). This paper presents a computational fluid dynamics (CFD) model, validated through experimental 3D printing of lunar regolith simulant-based geopolymer on Earth. The model simulates 3D printing under altered gravity (Phobos, Moon, Mars, Earth, Ross 128b). The results provide insights into geometrical precision and deformation, highlighting ways to control curing kinetics for large-scale printing.

## 1. Introduction
Building infrastructure like bases and habitats on the Moon or Mars requires protective measures against radiation and thermal extremes. Transporting materials from Earth is impractical, underscoring the imperative of In-Situ Resource Utilization (ISRU). Lunar regolith serves as a raw material for binders and geopolymers. Challenges arise from altered gravity, vacuum, and thermal variations affecting the extrusion-based 3D printing process.

## 2. Methodology
### 2.1. Materials and Rheology
The study uses lunar regolith simulant **JSC-1A** and **LMS-1**. The rheological behavior is modeled using the Bingham viscoplastic model.
- **Viscosity Equation:** $\mu(\dot{\gamma}) = \eta_p + \frac{\tau_0}{\dot{\gamma}}$ for $\tau \ge \tau_0$.
- **Curing Model:** $\tau_B(T_c) = \alpha T_c + \tau_0$, where $\alpha$ is the curing factor.

### 2.2. CFD Simulation
Simulations were performed using FLOW-3D® with a Volume-of-Fluid (VOF) technique for free surface tracking. Two models were tested: 
- **Model 1:** Wet-on-wet printing (zero curing).
- **Model 2:** Wet-on-solidifying (active curing).

### 2.3. Experimental Validation
A geopolymer mortar (LMS-1 regolith + alkaline activator) was printed using a HYREL 3D printer. Cross-sectional shapes were compared with simulations, showing errors below 6% for area and 8% for width.

## 3. Results and Discussion
### 3.1. Impact of Gravity
Gravity levels tested: Phobos (0.0057 m/s²), Moon (1.62 m/s²), Mars (3.71 m/s²), Earth (9.81 m/s²), and Ross 128b (10.95 m/s²).
- **Findings:** Higher gravity increases hydrostatic pressure ($P_H = \rho g h N$), leading to significant deformation. On the Moon, hydrostatic pressure for 3 layers is ~121.2 Pa, whereas on Earth it is ~751.2 Pa.
- **Stability Zone:** Defined where material yield stress $\tau_0 > P_H$.

### 3.2. Curing Kinetics for Large-Scale Printing
For a 50mm nozzle on the Moon:
- Without curing, the bottom layer deforms over 25%.
- With a curing factor $\alpha = 4.59$ Pa/s, deformation was restricted to under 5%.

## 4. Conclusions
- CFD modeling is crucial for understanding off-Earth construction where physical testing is difficult.
- Lower gravity environments allow for more stable prints with the same material.
- Curing kinetics must be utilized for large-scale printing to build yield stress faster than the increase in hydrostatic pressure from additional layers.

## Data Tables

### Table 1: Sample Rheological Properties
| Case | JSC-1A (g) | Water (g) | Density (kg/m³) | Yield Stress $\tau_0$ (Pa) | Plastic Viscosity (Pa.s) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 60 | 20.4 | 1970 | 9.5 | 0.6 |
| 5 | 60 | 17.6 | 2042 | 41.0 | 4.4 |

### Table 4: CFD vs Experimental Comparison (3 layers)
| Quantity | Experimental (Avg) | CFD | % Error |
| :--- | :--- | :--- | :--- |
| Area (mm²) | 81.362 | 80.630 | 0.899% |
| Width (mm) | 9.061 | 9.680 | 6.828% |
| Height (mm) | 11.923 | 11.403 | 4.364% |