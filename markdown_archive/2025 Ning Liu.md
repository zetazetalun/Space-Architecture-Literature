# Multi-scale modeling of hydrogel-based concrete formed under the ambient environment and the extremely harsh environment of Mars

**Journal:** Journal of the Mechanics and Physics of Solids  
**DOI:** [10.1016/j.jmps.2024.105969](https://doi.org/10.1016/j.jmps.2024.105969)  
**Authors:** Ning Liu, Tianju Xue, Jishen Qiu  

## Abstract
Hydrogel-based concretes (HBCs) are load-bearing composite materials consisting of inert particles joined by micro-hydrogel joints. They are suitable for extraterrestrial construction as they harden via sol-gel processes under freezing temperatures and vacuum. This study presents a multi-scale model predicting mechanical properties of HBC under Martian conditions. On the micro-scale, four joint microstructures (tubular, foamy, honeycomb, tube-cased-foam) are studied. On the macro-scale, a discrete element method (DEM) model using a linear parallel bond model (LPM) and Weibull distribution quantifies interparticle relationships.

## 1. Introduction
HBC offers two advantages over traditional cement-based concrete:
1. Supports living microorganisms for engineered functionalities.
2. Functions at sub-zero temperatures and low pressure where cement hydration fails.

Previous work demonstrated HBC compressive strength of 5 MPa with minimal polymer (20 kg/m³) under Martian conditions (-55 °C, 0.01% atm).

## 3. Mechanical Behavior of Interparticle Hydrogel Joint

### 3.1 Experimental Methodology
Joints were tested under "Air-Drying (AD)" (23 °C, 1 atm) and "Freeze-Drying (FD)" (-55 °C, 10 Pa) regimes.

**Table 2: Geometric properties of the tube/foam formed in the hydrogel joint (unit: mm)**
| Curing regime | Joint type | Max diameter (d_max) | Min diameter (d_min) | Wall height (h) | Wall thickness (t) | Skin thickness (t') |
|---|---|---|---|---|---|---|
| AD | Tubular | 12.18 ± 0.78 | 9.67 ± 0.22 | 1.56 ± 0.11 | 0.41 ± 0.08 | 0.26 ± 0.03 |
| FD | Foamy | 12.77 ± 0.12 | 12.77 ± 0.12 | 5.40 ± 0.62 | - | - |

### 3.4 Parameter Calibration
**Table 3: Summary of parameters for analytical equations**
* Elastic modulus of gel material (E_s): 2 GPa
* Shear modulus (G_s): 1 GPa
* Poisson’s ratio (v): 0.26
* Tensile strength (σ_f): 55.4 MPa
* Material porosity (ϕ_foam): 0.79

## 4. Mechanical Behavior of Hydrogel-Based Concrete (HBC)

### 4.3 Validation of the Multi-scale DEM Model
* Simulation used 7963 particles and 31,853 joints in a 40mm cube.
* Weibull distribution (homogeneity index m=6) was essential to capture compressive strength accurately.

**Table 6: Input joint properties in DEM**
| Curing | s/a | Type | Tension K_neq (N/mm) | Tension F' (N) | Shear K_seq (N/mm) | Shear F' (N) |
|---|---|---|---|---|---|---|
| AD | 0.05 | Tubular | 8.72 | 0.83 | 5.45 | 0.42 |
| AD | 0.1 | Tubular | 10.71 | 1.69 | 6.68 | 1.35 |
| AD | 0.2 | Honeycomb | 10.18 | 3.05 | 6.43 | 2.38 |
| FD | 0.05 | Tube-Foam | 6.71 | 0.51 | 2.21 | 0.42 |
| FD | 0.1 | Tube-Foam | 7.79 | 0.71 | 2.61 | 0.55 |
| FD | 0.2 | Foam | 6.99 | 0.78 | 1.28 | 0.61 |

## 5. Summary
* HBC can be produced with low energy input compared to laser/microwave sintering.
* The model captures effects of sol-to-sand (s/a) ratios and environmental curing conditions.
* Air-dried HBC has higher elastic modulus/strength; freeze-dried HBC (Martian) exhibits higher ductility and multiple random crack patterns.