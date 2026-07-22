# Soil Mechanics in Vacuum Chamber

**Authors:** G. H. Go, J. Lee, H. S. Shin, B. H. Rhu, and H. W. Jin
**Conference:** Earth and Space 2018, ASCE

## ABSTRACT
The dust vacuum chamber is an essential infrastructure for the verification of space exploration equipment, especially extraterrestrial missions for in situ resource utilization (ISRU). This study presents a new approach in soil mechanics that is particularly applicable to the dust vacuum chamber. One of the main issues in operating the dust vacuum chamber is soil disturbance problems during the evacuation. Thus, the appropriate vacuum rate was suggested to minimize the soil disturbance in the dust vacuum chamber using theoretical and numerical approaches. Firstly, the simple analytical solutions were used to provide approximate maximum discharge velocity and evacuation time to finish air flow through a soil specimen at a given vacuum pressure. Then, a two-dimensional finite element model was developed which simulates the hydro-mechanical behavior of the soil specimen in a vacuum chamber with respect to different vacuum rates. From the numerical analysis results, optimum guidelines have been proposed to ensure that soil disturbance is minimized.

## INTRODUCTION
Recently, the trend in space exploration has been shifting from remote exploration using orbiters to surface missions using rovers and landers. Verification of equipment used in lunar surface missions requires performance tests in a dirty vacuum chamber (DVC) that simulates lunar surface conditions. A major issue in operating a DVC is soil disturbance caused by depressurization, which complicates maintaining the initial condition of soil bins.

## POROELASTICITY THEORY
Biot’s (1941) poroelasticity theory was applied to evaluate the hydro-mechanical behavior of soil specimens under depressurization. The constitutive equation relates stress, strain, and pore air pressure:

$$\sigma = C\epsilon - \alpha_B u_a I$$

Where:
- $\sigma$ is total stress
- $\epsilon$ is strain tensor
- $u_a$ is pore air pressure
- $\alpha_B$ is Biot-Willis coefficient

The air velocity $q_a$ is calculated by Darcy’s law:

$$q_a = -\frac{K}{\mu} \frac{\partial u_a}{\partial y}$$

Soil disturbance occurs when the seepage force exceeds the soil's dead load ($j = W_d$).

## MATERIAL PROPERTIES

### Table 1. Material properties used in finite element model.
| Property | Name | Value | Unit | Note |
| :--- | :--- | :--- | :--- | :--- |
| Young’s Modulus | E | 10 | MPa | constant |
| Biot-Willis coefficient | αB | 1 | - | constant |
| Particle density | ρd | 2750 | kg/m³ | constant |
| Air density | ρa | (ω u_a) / RT | kg/m³ | variable |
| Porosity | n | 0.418 | - | constant |
| Dynamic viscosity of air | μ | 1.814E-05 | Pa·s | constant |
| Storage | S | n / u_a | 1/Pa | variable |
| Poisson’s ratio | ν | 0.25 | - | constant |
| Intrinsic permeability | K | 2.55E-13 | m² | constant |

## FINITE ELEMENT MODEL
A 2D FE model coupled fluid flow and geomechanics. The specimen depth was 0.047m. Initial pressure was set to atmospheric. Depressurization proceeded from the top, with the bottom and sides defined as undrained.

## RESULTS AND DISCUSSION
Air velocity increases rapidly as the chamber approaches vacuum due to exponential pressure gradients. Soil disturbance occurs when effective stress becomes zero. For the given properties, the maximum air velocity ($q_{max}$) was 0.000235 m/s. With a vacuum rate of -0.33 kPa/sec, disturbance occurred at 282.5 seconds (vacuum pressure ≈ -94 kPa).

## SUMMARY AND CONCLUSION
1. New theoretical approaches provide insight into soil behavior in DVCs.
2. The FE model provides appropriate vacuum rates to prevent disturbance.
3. Vacuum rates should be reduced before air flow reaches the maximum velocity limit.
4. Initial conditions should be maintained until vacuum reaches maximum allowable values (e.g., 2.5 Torr).