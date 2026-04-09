# Understanding the Soil Bearing Resistance in a Different Gravity Environment via Particle Density Scaling

**Authors:** Sumana Bhattacharya, Seung Jae Lee
**Affiliation:** Dept. of Civil and Environmental Engineering, Florida International Univ., Miami, FL.
**Source:** Earth and Space 2021, ASCE, pp. 757-766.

## ABSTRACT
Understanding the bearing resistance of planetary regolith is essential to establish a long-term presence on the planets, e.g., extraterrestrial human habitat construction. Despite its importance, our understanding of the bearing resistance remains at best incomplete due to the dearth of data collected from the planetary surface missions as well as the limited amount of planetary soil samples available for the study. Moreover, it is hard to experimentally test the bearing resistance in a different gravity condition that can be obtained through parabolic flight, but which is expensive and can simulate a relatively short duration of different gravities. On the other hand, numerical studies using the discrete element method typically require high computational cost. This study hypothesizes a new approach to investigate the soil bearing resistance in a different gravity environment by simply scaling the particle density instead of reproducing the different gravity conditions. To this end, Terzaghi’s bearing capacity theory is tweaked and used to develop the hypothesis. This study performs a set of discrete element simulations to test the hypothesis and demonstrate the feasibility of the proposed approach.

## INTRODUCTION
Extraterrestrial soil research is at the core of planetary missions to understand the geomechanical properties including the soil bearing resistance against surface loading. This effort is vital to enable successful future surface activities such as the human habitat construction (Lim et al. 2017). In spite of the importance of the space mission-related geomechanics study, our understanding is still limited due to the accessibility issues. Seven Surveyor space crafts have been sent from 1966 to 1968 to investigate the geotechnical properties of the lunar surface... A limited quantity of lunar soil was brought back to Earth, but which was not enough for experiments needed to understand the geomechanical behavior. Therefore, a number of simulants including Johnson Space Center lunar soil simulant (JSC-1A) have been developed for use in experiments (Zeng et al. 2010).

## Terzaghi’s Bearing Capacity Theory
Terzaghi’s formula to estimate the soil bearing capacity is shown in Equation (1) which shows the contribution by cohesion, surcharge, and weight of soil (Terzaghi et al. 1996).

$$q_d = cN_c + \gamma D_f N_q + 0.5 \gamma B N_\gamma = cN_c + \gamma (D_f N_q + 0.5 B N_\gamma)$$

Where:
- $q_d$: bearing capacity of a soil mass located above water table
- $c$: cohesion intercept
- $\gamma$: unit weight of soil
- $D_f, B$: depth and width of footing
- $N_c, N_q, N_\gamma$: bearing capacity factors

Since lunar soil cohesion is relatively low, the controlling parameters are friction angle and unit weight. Unit weight $\gamma$ has gravity dependence ($\gamma = \rho g$). The study hypothesizes that soil bearing resistance of a planet may be reproduced in Earth gravity by proportionally scaling the particle density: $q_d = (\rho/n) g (D_f N_q + 0.5 B N_\gamma)$.

## DISCRETE ELEMENT MODELING
An open source DEM code, LIGGGHTS, is used for numerical study. Toyoura sand with 60% relative density (void ratio ~ 0.76) is selected. To manage computational cost, particle sizes are enlarged 30 times to 8 mm diameter (6770 particles total).

### Table 1. DEM modeling parameters and values used for the simulations
| DEM modeling parameter | Value |
| :--- | :--- |
| Gravity ($g = 9.8 m/s^2$) | $1/6g, 1/2g, 1g$ for $1\rho$ particle density |
| Particle density ($\rho = 2650 kg/m^3$) | $1/6\rho, 1/2\rho$ for $1g$ gravity condition |
| $E$ Young's modulus of particle | $1 \times 10^{10}$ Pa |
| $\nu$ Poisson's Ratio | 0.3 |
| $\mu$ Coefficient of friction | 0.5 (~ tan 27°) |
| $\mu_r$ Coefficient of rolling friction | 0.3 |

## RESULTS AND DISCUSSIONS
Numerical simulations for reduced gravity conditions ($1/2g, 1/6g$) were compared with simulations using Earth gravity but scaled densities ($1/2\rho, 1/6\rho$). Overall good agreement is shown between the simulation results, which demonstrates that Terzaghi's formula holds true for the developed hypothesis.

## CONCLUDING REMARKS
This study leverages Terzaghi’s bearing capacity theory to demonstrate that the gravity effect on the soil bearing resistance can be reproduced by adopting a synthetic soil with proportionally scaled particle density. This approach provides an alternative to expensive parabolic flights and facilitates extraterrestrial soil study in standard laboratory settings using 3D-printed particles with controlled density.