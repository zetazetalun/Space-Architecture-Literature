# Understanding the Soil Bearing Resistance in a Different Gravity Environment via Particle Density Scaling

**Authors:** Sumana Bhattacharya and Seung Jae Lee  
**Publication:** Earth and Space 2021 (ASCE)

## Abstract
Understanding the bearing resistance of planetary regolith is essential to establish a long-term presence on the planets, e.g., extraterrestrial human habitat construction. This study hypothesizes a new approach to investigate the soil bearing resistance in a different gravity environment by simply scaling the particle density instead of reproducing the different gravity conditions. Terzaghi’s bearing capacity theory is tweaked and used to develop the hypothesis. This study performs a set of discrete element simulations to test the hypothesis and demonstrate the feasibility of the proposed approach.

## Introduction
Extraterrestrial soil research is vital to enable successful future surface activities such as human habitat construction. Challenges include the high cost of parabolic flights and the high computational cost of numerical studies (DEM). The authors propose scaling particle density as a surrogate for scaling gravity to observe bearing resistance.

## Terzaghi’s Bearing Capacity Theory
Terzaghi’s formula to estimate soil bearing capacity ($q_d$) is shown in Equation (1):

$$q_d = cN_c + \gamma D_f N_q + 0.5\gamma B N_\gamma$$

Where:
- $c$: cohesion intercept
- $\gamma$: unit weight of soil
- $D_f, B$: depth and width of footing
- $N_c, N_q, N_\gamma$: bearing capacity factors

Because cohesion in lunar soil is relatively low, the formula is simplified. Since $\gamma = \rho g$ (density $\times$ gravity), the study hypothesizes that bearing resistance in partial gravity ($g/n$) can be reproduced in Earth gravity ($g$) by scaling density to $\rho/n$.

## Methodology: Discrete Element Modeling (DEM)
- **Software:** LIGGGHTS (Open source DEM code).
- **Material:** Toyoura sand (60% relative density).
- **Scaling:** To manage computational load, particle sizes were enlarged 30 times (8 mm spheres).
- **Parameters:**

| DEM modeling parameter | Value |
| :--- | :--- |
| Gravity ($g$) | $1/6g$, $1/2g$, $1g$ |
| Particle density ($\rho$) | $2650\,kg/m^3$; $1/6\rho$, $1/2\rho$ for $1g$ simulations |
| Young's modulus | $1 \times 10^{10}\,Pa$ |
| Poisson's Ratio | 0.3 |
| Coefficient of friction | 0.5 |

## Results and Discussion
- The DEM simulation results in $1g$ gravity were first validated against experimental data from Kobayashi et al. (2009).
- Simulations confirmed that soil with $1/2\rho$ density in $1g$ gravity showed bearing resistance comparable to soil with $1\rho$ density in $1/2g$ gravity.
- Similarly, $1/6\rho$ density in $1g$ gravity matched $1\rho$ in $1/6g$ gravity.

## Concluding Remarks
The study demonstrates that gravity effects on soil bearing resistance can be reproduced by adopting synthetic soil (such as 3D-printed particles) with proportionally scaled particle density. This provides an inexpensive alternative to parabolic flights for space exploration research and education.