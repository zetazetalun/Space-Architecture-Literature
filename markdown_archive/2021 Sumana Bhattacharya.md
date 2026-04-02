# Understanding the Soil Bearing Resistance in a Different Gravity Environment via Particle Density Scaling

**Sumana Bhattacharya**¹ and **Seung Jae Lee**²
¹Dept. of Civil and Environmental Engineering, Florida International Univ., Miami, FL. Email: sbhat014@fiu.edu
²Dept. of Civil and Environmental Engineering, Florida International Univ., Miami, FL. Email: sjlee@fiu.edu

## ABSTRACT

Understanding the bearing resistance of planetary regolith is essential to establish a long-term presence on the planets, e.g., extraterrestrial human habitat construction. Despite its importance, our understanding of the bearing resistance remains at best incomplete due to the dearth of data collected from the planetary surface missions as well as the limited amount of planetary soil samples available for the study. Moreover, it is hard to experimentally test the bearing resistance in a different gravity condition that can be obtained through parabolic flight, but which is expensive and can simulate a relatively short duration of different gravities. On the other hand, numerical studies using the discrete element method typically require high computational cost. This study hypothesizes a new approach to investigate the soil bearing resistance in a different gravity environment by simply scaling the particle density instead of reproducing the different gravity conditions. To this end, Terzaghi’s bearing capacity theory is tweaked and used to develop the hypothesis. This study performs a set of discrete element simulations to test the hypothesis and demonstrate the feasibility of the proposed approach.

## INTRODUCTION

Extraterrestrial soil research is at the core of planetary missions to understand the geomechanical properties including the soil bearing resistance against surface loading. This effort is vital to enable successful future surface activities such as the human habitat construction (Lim et al. 2017). In spite of the importance of the space mission-related geomechanics study, our understanding is still limited due to the accessibility issues.

## Terzaghi’s Bearing Capacity Theory

Terzaghi’s formula to estimate the soil bearing capacity is shown in Equation (1):

$q_d = cN_c + \gamma D_f N_q + 0.5 \gamma B N_\gamma = cN_c + \gamma (D_f N_q + 0.5 B N_\gamma)$ (1)

where:
- $q_d$: bearing capacity of a soil mass
- $c$: cohesion intercept
- $\gamma$: unit weight of soil
- $D_f, B$: depth and width of footing
- $N_c, N_q, N_\gamma$: bearing capacity factors

Equation (2) for a partial gravity condition (g/n):
$q_d = \rho(g/n)(D_f N_q + 0.5 B N_\gamma)$ (2)

Equation (3) considers partial density (\rho/n) in Earth gravity g:
$q_d = (\rho/n)g(D_f N_q + 0.5 B N_\gamma)$ (3)

## DISCRETE ELEMENT MODELING

An open source DEM code, LIGGGHTS, is used for numerical study. Toyoura sand with 60% relative density (void ratio ~ 0.76) is selected for modeling. Particle sizes were enlarged 30 times to keep computational costs manageable, resulting in particles approximated to spheres of 8 mm diameter.

### Table 1. DEM modeling parameters and values used for the simulations

| DEM modeling parameter | Value |
| :--- | :--- |
| Gravity ($g = 9.8$ m/s²) | $1/6g, 1/2g, 1g$ for $1\rho$ particle density |
| Particle density ($\rho = 2650$ kg/m³) | $1/6\rho, 1/2\rho$ for $1g$ gravity condition |
| Young's modulus of particle | $1 \times 10^{10}$ Pa |
| Poisson's Ratio | 0.3 |
| Coefficient of friction | 0.5 (~ tan 27°) |
| Coefficient of rolling friction | 0.3 |

## CONCLUDING REMARKS

This study leverages Terzaghi’s bearing capacity theory to demonstrate that the gravity effect on the soil bearing resistance can be reproduced by adopting a synthetic soil with proportionally scaled particle density. This approach is an alternative to existing experimental methods and facilitates the understanding of extraterrestrial soil behavior in a general laboratory setting using 3D-printed synthetic particles with controlled density.