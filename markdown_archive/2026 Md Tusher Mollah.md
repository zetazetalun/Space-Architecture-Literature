# A virtual 3D printing framework for off-Earth construction

**Authors:** Md Tusher Mollah, Berin Šeta, Jon Spangenberg  
**Journal:** Acta Astronautica 244 (2026) 524–538  
**DOI:** https://doi.org/10.1016/j.actaastro.2026.02.001

## Abstract
3D printing offers a practical approach to autonomous off-Earth construction by utilizing local materials (ISRU). Implementing large-scale printing in extraterrestrial environments poses challenges due to altered gravity, vacuum, and thermal variations. This paper presents a computational fluid dynamics (CFD) model, validated through experimental 3D printing of lunar regolith simulant-based geopolymer on Earth. The model simulates printing under altered gravity, providing insights into geometrical precision and deformation across different celestial bodies. The results highlight ways to control curing kinetics to enable fast and large-scale printing.

## 1. Methodology

### 1.1 Materials and Rheology
The study uses lunar regolith simulant JSC-1A mixed with water, NaOH, and urea to create a viscoplastic mortar. The rheological behavior is predicted using a Bingham model: 
- **Bingham Model:** Until shear stress exceeds yield stress (τ₀), the material remains solid.
- **Wet-on-solidifying strategy:** Curing is modeled as a material age-dependent yield stress increase (τᵦ(Tc) = αTc + τ₀).

### 1.2 Computational Fluid Dynamics (CFD)
The model uses FLOW-3D software. The regolith simulant is assumed to be transient, isothermal, and incompressible. The Volume-of-Fluid (VOF) technique tracks the free surface, and the FAVOR method represents solid obstacles like the nozzle.

### Table 1: Rheological properties of samples (obtained from Momi et al.)
| Cases | JSC-1A regolith (g) | Water (g) | Regolith content (wt%) | Density ρ (kg/m³) | Dynamic yield stress τ₀ (Pa) | Plastic viscosity ηₚ (Pa.s) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 60 | 20.4 | 74.6 | 1970 | 9.5 | 0.6 |
| 2 | 60 | 19.4 | 75.8 | 1995 | 18.0 | 1.3 |
| 3 | 60 | 18.6 | 76.3 | 2015 | 26.0 | 2.4 |
| 4 | 60 | 18.0 | 76.9 | 2031 | 36.0 | 3.4 |
| 5 | 60 | 17.6 | 77.3 | 2042 | 41.0 | 4.4 |

## 2. Experimental Validation
An experimental campaign using a HYREL 3D printer and LMS-1 lunar simulant geopolymer validated the CFD model. Results showed cross-sectional area errors below 6% and height errors within 5%.

## 3. Results and Discussion

### 3.1 Impact of Gravity
Simulations across Phobos (0.0057 m/s²), the Moon (1.62 m/s²), Mars (3.71 m/s²), Earth (9.81 m/s²), and Ross 128b (10.95 m/s²) showed:
- Higher gravity leads to greater penetration of deposited layers and significant deformation due to hydrostatic pressure (P_H = ρghN).
- The same material provides high precision on low-gravity bodies but unstable prints on Earth.

### 3.2 Printing Scale and Curing
For large-scale printing (e.g., 50 mm nozzle), "wet-on-wet" strategies often fail due to hydrostatic pressure exceeding yield stress. The "wet-on-solidifying" strategy, where the material builds yield stress during the printing process, is shown to stabilize large-scale prints, keeping deformation below 5%.

## 4. Conclusions
- CFD modeling is crucial for predicting printing behavior in inaccessible gravity environments.
- Increasing regolith content improves stability but increases required extrusion pressure.
- Controlling curing kinetics (yield stress buildup) is essential for large-scale ISRU construction to mitigate deformation induced by layer weight.