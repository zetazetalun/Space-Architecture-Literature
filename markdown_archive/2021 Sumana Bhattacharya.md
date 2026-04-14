# Understanding the Soil Bearing Resistance in a Different Gravity Environment via Particle Density Scaling

**Authors:** Sumana Bhattacharya, Seung Jae Lee
**Affiliation:** Dept. of Civil and Environmental Engineering, Florida International Univ., Miami, FL
**Published in:** Earth and Space 2021

## Abstract
Understanding the bearing resistance of planetary regolith is essential to establish a long-term presence on the planets, e.g., extraterrestrial human habitat construction. Despite its importance, our understanding of the bearing resistance remains at best incomplete due to the dearth of data collected from the planetary surface missions as well as the limited amount of planetary soil samples available for the study. Moreover, it is hard to experimentally test the bearing resistance in a different gravity condition that can be obtained through parabolic flight, but which is expensive and can simulate a relatively short duration of different gravities. This study hypothesizes a new approach to investigate the soil bearing resistance in a different gravity environment by simply scaling the particle density instead of reproducing the different gravity conditions. To this end, Terzaghi’s bearing capacity theory is tweaked and used to develop the hypothesis. This study performs a set of discrete element simulations to test the hypothesis and demonstrate the feasibility of the proposed approach.

## Introduction
Extraterrestrial soil research is at the core of planetary missions to understand the geomechanical properties including the soil bearing resistance against surface loading. This effort is vital to enable successful future surface activities such as the human habitat construction. Understanding is limited due to accessibility issues. Seven Surveyor spacecraft have been sent from 1966 to 1968 to investigate the geotechnical properties of the lunar surface. A limited quantity of lunar soil was brought back to Earth, but not enough for extensive experiments. Simulants like JSC-1A have been developed for experiments, but simulating different gravities in a lab is challenging.

## Terzaghi’s Bearing Capacity Theory
Terzaghi’s formula to estimate soil bearing capacity ($q_d$):
$$q_d = cN_c + \gamma D_f N_q + 0.5\gamma B N_\gamma = cN_c + \gamma (D_f N_q + 0.5 B N_\gamma)$$

Where:
- $q_d$: bearing capacity
- $c$: cohesion intercept
- $\gamma$: unit weight of soil
- $D_f, B$: depth and width of footing
- $N_c, N_q, N_\gamma$: bearing capacity factors

Since lunar soil cohesion is relatively low, the effect of the first term ($cN_c$) is negligible. Because $\gamma = \rho g$ (where $\rho$ is soil density and $g$ is gravity), the formula for partial gravity ($g/n$) can be presented as:
$$q_d = \rho(g/n)(D_f N_q + 0.5 B N_\gamma)$$
Which can be rewritten for Earth gravity ($g$) with partial density ($\rho/n$):
$$q_d = (\rho/n)g(D_f N_q + 0.5 B N_\gamma)$$

## Discrete Element Modeling (DEM)
- **Code:** LIGGGHTS (Open source DEM code).
- **Soil Type:** Toyoura sand (60% relative density, void ratio ~ 0.76).
- **Scaling:** Original particle size enlarged by 30 times to reduce computational burden, approximated to spheres of 8 mm diameter.
- **Simulation Count:** ~6770 particles.
- **Contact Model:** Hertz contact model.

### Table 1: DEM modeling parameters and values
| DEM modeling parameter | Value |
|---|---|
| Gravity ($g = 9.8 \text{ m/s}^2$) | $1/6g, 1/2g, 1g$ for $1\rho$ particle density |
| Particle density ($\rho = 2650 \text{ kg/m}^3$) | $1/6ho, 1/2ho$ for $1g$ gravity condition |
| Young's modulus of particle | $1 \times 10^{10} \text{ Pa}$ |
| Poisson's Ratio | $0.3$ |
| Coefficient of friction | $0.5$ (~ tan 27°) |
| Coefficient of rolling friction | $0.3$ |

## Results and Discussions
- The DEM simulation result in $1g$ gravity was calibrated with experiment data from Kobayashi et al. (2009).
- Overall good agreement was shown between the simulation results of soil with $1/2\rho$ density in $1g$ gravity and $1\rho$ density in $1/2g$ gravity.
- Similarly, the bearing resistance of soil with $1/6\rho$ density in $1g$ gravity condition was comparable to the result with $1\rho$ density in $1/6g$ gravity.

## Concluding Remarks
This study leverages Terzaghi’s bearing capacity theory to demonstrate that the gravity effect on soil bearing resistance can be reproduced by adopting a synthetic soil with proportionally scaled particle density. This approach facilitates understanding extraterrestrial soil behavior in a general laboratory setting, potentially using 3D-printed synthetic particles with controlled density.