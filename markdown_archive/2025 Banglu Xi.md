# A modified Prandtl’s model for predicting the bearing capacity of lunar soil ground under extraterrestrial gravitational environment

**Journal:** Acta Astronautica 234 (2025) 59–72  
**DOI:** [10.1016/j.actaastro.2025.04.054](https://doi.org/10.1016/j.actaastro.2025.04.054)

## Abstract
The prediction on bearing capacity of regolith on the Moon plays an important role in the design and construction of the future lunar base. However, the classical analytical methods are developed on Earth for terrestrial soils, which may be unable to predict the bearing capacity of lunar soil on the Moon since the gravity effect on the bearing behavior is excluded. Therefore, a modified Prandtl’s model considering the gravity effect was developed and verified with experimental data under different gravity fields. The modified model predicts bearing capacities within 50% error of experimental data, capturing the gravity effect on lunar soil bearing capacity.

## 1. Introduction
The setup of permanent research stations on the Moon and Mars requires foundation systems designed to transfer structure loads safely to the regolith. Most lunar habitations (inflatable, concrete, deployable, or lava-tube based) are designed for the lunar surface, requiring shallow foundation analysis. Classical theories (Prandtl, Terzaghi) often assume weightless soil or Earth-gravity conditions, which do not scale linearly to the 1.63 m/s² lunar environment.

## 2. Modified Prandtl’s Model
The authors examined the failure mechanisms of lunar soil using the Discrete Element Method (DEM) under gravity fields ranging from 0.01 g to 10 g. 

### Table 1: Parameters for lunar soil bin in DEM simulations
| Name | Value |
|---|---|
| Void ratio | 0.22 |
| Dry density (kg/m³) | 2600 |
| Normal stiffness (N/m) | 7.5 × 10⁷ |
| Tangential stiffness (N/m) | 5.0 × 10⁷ |
| Frictional coefficient | 1.0 |
| Rolling resistance coefficient | 1.3 |
| Thickness of absorbed molecular layer (m) | 1.5 × 10⁻⁸ |
| Damping coefficient cₙ, cₛ (kg/s) | 0.4 |

### Hypotheses and Examination
- **Soil weight:** Introduced into the limit equilibrium analysis via integral calculus.
- **Earth Pressure:** Replaced the active earth pressure assumption with a combination of initial earth pressure at rest and additional pressure due to the applied load.
- **Gravity Effect:** The passive earth pressure coefficient was found to increase non-linearly as gravity decreases.

## 3. Calculation Results and Bearing Capacity Factors

### Table 2: Equations for the bearing capacity factors
| Factors | Equations / Source |
|---|---|
| Nq | tan²(45+φ)e^(π tan φ) (Prandtl Theory) |
| Nc | (Nq - 1) cot φ (Prandtl/Terzaghi) |
| Nγ | Various models: Liao et al., Salgado, Meyerhof, Hansen, Vesic |

## 4. Conclusions
1. The modified Prandtl's model introduces gravity-dependent soil weight and stress-dependent soil strength.
2. The predicted bearing capacities are within 50% error of experimental data (centrifuge and parabolic flight tests).
3. The model serves as a more effective tool for the design and construction of future lunar bases compared to classical terrestrial models.