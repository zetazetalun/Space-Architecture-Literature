# A modified Prandtl’s model for predicting the bearing capacity of lunar soil ground under extraterrestrial gravitational environment

**Journal:** Acta Astronautica 234 (2025) 59–72
**Authors:** Banglu Xi, Mingjing Jiang, Lin Qi, Jiaqiang Yang, Mingliang Chen

## Abstract
The prediction of bearing capacity of regolith on the Moon plays an important role in the design and construction of the future lunar base. Classical analytical methods developed on Earth may be unable to predict the bearing capacity on the Moon since the gravity effect is excluded. This paper examines Prandtl’s bearing capacity theory assumptions based on DEM simulations of plate loading tests. A modified Prandtl’s model considering gravity effects was developed and verified with experimental data. The results show the model predicts bearing capacities within 50% error, capturing the gravity effect on lunar soil simulants.

## Introduction
Establishing permanent research stations on the Moon or Mars requires careful foundation design. Structures proposed include inflatable, concrete, and deployable systems. Foundations must transfer structural loads safely to lunar soil. Existing theories like Prandtl (1921) and Terzaghi (1943) assume Earth gravity (9.8 m/s²), which does not scale linearly to the Moon (1.63 m/s²).

## Modified Prandtl’s Model

### Soil Parameters and Simulation
DEM simulations utilized a grain size distribution (GSD) of 0.5 mm to 2 mm. Parameters were calibrated to capture lunar soil properties (apparent cohesion and high peak friction).

**Table 1: Parameters for lunar soil bin in DEM simulations.**
| Name | Value |
|---|---|
| Void ratio | 0.22 |
| Dry density (kg/m³) | 2600 |
| Normal stiffness (N/m) | 7.5 x 10⁷ |
| Tangential stiffness (N/m) | 5.0 x 10⁷ |
| Frictional coefficient | 1.0 |
| Rolling resistance coefficient | 1.3 |
| Thickness of absorbed molecular layer (m) | 1.5 x 10⁻⁸ |
| Damping coefficient (kg/s) | 0.4 |

### Key Modifications
1. **Soil Weight:** Soil weight is introduced directly into the limit equilibrium analysis.
2. **Active Earth Pressure:** Replaced with the sum of earth pressure at rest (Pr) and additional pressure due to applied load (Padd).
3. **Passive Earth Pressure:** Introduced a gravity-dependent coefficient (k^ng_p) to replace the constant terrestrial value.
4. **Failure Surface:** Internal friction angle (φ) is modeled as stress-dependent, increasing as gravity decreases.

## Findings and Verification
The model was verified against experimental data from aircraft parabolic flights, drop towers, and centrifuges. 

**Table 2: Equations for the bearing capacity factors.**
| Factors | Equation Source |
|---|---|
| Nq | Prandtl Theory |
| Nc | Prandtl Theory / Terzaghi Theory |
| Ny | Various (Hansen, Vesic, Meyerhof, etc.) |

### Conclusions
1. Sum of earth pressure at rest and additional load pressure is more accurate for lunar scenarios than active earth pressure.
2. Horizontal earth pressure increases non-linearly with gravity.
3. The modified Prandtl model captures the gravity effect on bearing capacity with errors <50%.

## References
1. Herzig et al. (2022) - PneumoPlanet inflatable lunar habitat.
2. Troemner et al. (2022) - 3D-printing centered approach to Mars habitats.
3. Duke et al. (1989) - Strategies for a permanent lunar base.
4. Ellery (2021) - Leveraging ISRU for lunar base construction.