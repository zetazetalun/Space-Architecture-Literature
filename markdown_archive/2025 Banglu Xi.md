# A modified Prandtl’s model for predicting the bearing capacity of lunar soil ground under extraterrestrial gravitational environment

**Journal:** Acta Astronautica 234 (2025) 59–72  
**DOI:** https://doi.org/10.1016/j.actaastro.2025.04.054  

## Abstract
The prediction on bearing capacity of regolith on the Moon plays an important role in the design and construction of the future lunar base. Classical analytical methods developed on Earth may be unable to predict the bearing capacity of lunar soil on the Moon since the gravity effect is excluded. This study examines assumptions in Prandtl’s theory and proposes a modified model considering gravity effects, verified against experimental data under different gravity fields. Results show the model predicts bearing capacities within 50% error, capturing the gravity effect on lunar soil simulants.

## 1. Introduction
The setup of permanent research stations on the Moon or Mars requires careful foundation design to transfer structure loads safely to lunar soil. Proposed designs include inflatable, concrete, and deployable structures, as well as lava tubes. Classical theories (Prandtl, Terzaghi) assume weightless soil or Earth-standard gravity, leading to potential inaccuracies in low-gravity environments like the Moon (1.63 m/s²).

## 2. Methodology
- **DEM Simulations:** Discrete element method simulations of plate loading tests under gravity fields from 0.01g to 10g.
- **Modified Parameters:** Introduction of soil weight, additional pressure due to applied load, and gravity-dependent passive earth pressure coefficients.
- **Stress-Dependency:** Consideration of internal friction angle (φ) dependency on confining pressure (stress level).

## 3. Results & Findings
### 3.1 Soil Weight and Earth Pressure
- Earth pressure acting on the foundation includes initial pressure at rest ($P_r$) and additional pressure ($P_{add}$) due to applied load.
- Passive earth pressure increases non-linearly with decreasing gravity.

### 3.2 Model Verification
- Comparison with experimental data from centrifuge tests and parabolic flights.
- The modified Prandtl’s model predicts values within 50% error, significantly improving upon classical models which predict a purely linear relationship between gravity and bearing capacity.

## 4. Conclusions
1. Active earth pressure assumptions in classical Prandtl theory should be replaced by the sum of earth pressure at rest and additional pressure.
2. Passive earth pressure increases non-linearly with gravity levels.
3. The proposed model serves as an effective tool for the design and construction of future lunar bases.

### Table 1: Parameters for lunar soil bin in DEM simulations
| Name | Value |
|---|---|
| Void ratio | 0.22 |
| Dry density (kg/m³) | 2600 |
| Frictional coefficient | 1.0 |
| Rolling resistance coefficient | 1.3 |
| Normal stiffness (N/m) | 7.5 x 10⁷ |

### Table 2: Bearing Capacity Factor Equations (Summary)
- **Nq:** Modified for gravity and additional pressure coefficient.
- **Nc:** Adjusted based on Nq and friction angle.
- **Ny:** Derived from limit equilibrium including soil weight integrals.