# Understanding the Soil Bearing Resistance in a Different Gravity Environment via Particle Density Scaling

**Authors:** Sumana Bhattacharya and Seung Jae Lee  
**Affiliation:** Dept. of Civil and Environmental Engineering, Florida International Univ., Miami, FL.  
**Publication:** Earth and Space 2021, pp. 757-766, © ASCE.

## ABSTRACT
Understanding the bearing resistance of planetary regolith is essential to establish a long-term presence on the planets, e.g., extraterrestrial human habitat construction. Despite its importance, our understanding of the bearing resistance remains at best incomplete due to the dearth of data collected from the planetary surface missions as well as the limited amount of planetary soil samples available for the study. Moreover, it is hard to experimentally test the bearing resistance in a different gravity condition that can be obtained through parabolic flight, but which is expensive and can simulate a relatively short duration of different gravities. On the other hand, numerical studies using the discrete element method typically require high computational cost. This study hypothesizes a new approach to investigate the soil bearing resistance in a different gravity environment by simply scaling the particle density instead of reproducing the different gravity conditions. To this end, Terzaghi’s bearing capacity theory is tweaked and used to develop the hypothesis. This study performs a set of discrete element simulations to test the hypothesis and demonstrate the feasibility of the proposed approach.

## INTRODUCTION
Extraterrestrial soil research is at the core of planetary missions to understand the geomechanical properties including the soil bearing resistance against surface loading. This effort is vital to enable successful future surface activities such as the human habitat construction (Lim et al. 2017). In spite of the importance of the space mission-related geomechanics study, our understanding is still limited due to the accessibility issues.

## Terzaghi’s Bearing Capacity Theory
Terzaghi’s formula to estimate the soil bearing capacity is shown in Equation (1):

$$q_d = cN_c + \gamma D_f N_q + 0.5\gamma BN_\gamma = cN_c + \gamma(D_f N_q + 0.5BN_\gamma)$$ (1)

where:  
- $q_d$: bearing capacity of a soil mass located above water table  
- $c$: cohesion intercept  
- $\gamma$: unit weight of soil  
- $D_f, B$: depth and width of footing  
- $N_c, N_q, N_\gamma$: bearing capacity factors  

Considering the cohesion of lunar soil is relatively low, the effect of the first term ($cN_c$) is negligible. Because unit weight $\gamma = \rho g$ (where $\rho$ is density and $g$ is gravity), the formula can be expressed for partial gravity ($g/n$):

$$q_d = \rho(g/n)(D_f N_q + 0.5BN_\gamma)$$ (2)

This leads to the hypothesis that the soil bearing resistance of a planet may be reproduced in Earth gravity condition ($g$) by proportionally scaling the particle density to $(\rho/n)$:

$$q_d = (\rho/n)g(D_f N_q + 0.5BN_\gamma)$$ (3)

## Discrete Element Modeling
An open source DEM code, LIGGGHTS, is used. Toyoura sand with 60% relative density (void ratio ~ 0.76) is selected for modeling. To manage computational cost, particle sizes were enlarged by 30 times (8 mm diameter spheres).

**Table 1. DEM modeling parameters and values used for the simulations**

| DEM modeling parameter | Value |
| :--- | :--- |
| Gravity ($g = 9.8$ m/s²) | $1/6g, 1/2g, 1g$ for $1\rho$ particle density |
| Particle density ($\rho = 2650$ kg/m³) | $1/6\rho, 1/2\rho$ for $1g$ gravity condition |
| $E$ Young's modulus of particle | $1 \times 10^{10}$ Pa |
| $\nu$ Poisson's Ratio | 0.3 |
| $\mu$ Coefficient of friction | 0.5 (~ tan 27°) |
| $\mu_r$ Coefficient of rolling friction | 0.3 |

## RESULTS AND DISCUSSIONS
Simulation results for soil bearing resistance with $1/2\rho$ particle density in $1g$ gravity condition showed overall good agreement with simulations of $1\rho$ particle density in $1/2g$ gravity. Similarly, $1/6\rho$ density at $1g$ was comparable to $1\rho$ density at $1/6g$. This demonstrates that Terzaghi’s formula holds true for the developed hypothesis.

## CONCLUDING REMARKS
This study demonstrates that gravity effects on soil bearing resistance can be reproduced by adopting synthetic soil (e.g., 3D-printed particles) with proportionally scaled density. This provides an inexpensive alternative for laboratory testing of extraterrestrial soil behavior.