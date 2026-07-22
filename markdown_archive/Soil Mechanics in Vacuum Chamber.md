## Soil Mechanics in Vacuum Chamber

Downloaded from ascelibrary.org by University of Liverpool on 07/22/25. Copyright ASCE. For personal use only; all rights reserved.

G. H. Go<sup>1</sup>; J. Lee<sup>2</sup>; H. S. Shin<sup>3</sup>; B. H. Rhu<sup>4</sup>; and H. W. Jin<sup>5</sup>

# ABSTRACT

The dust vacuum chamber is an essential infrastructure for the verification of space exploration equipment, especially extraterrestrial missions for in situ resource utilization (ISRU). This study presents a new approach in soil mechanics that is particularly applicable to the dust vacuum chamber. One of the main issues in operating the dust vacuum chamber is soil disturbance problems during the evacuation. Thus, the appropriate vacuum rate was suggested to minimize the soil disturbance in the dust vacuum chamber using theoretical and numerical approaches. Firstly, the simple analytical solutions were used to provide approximate maximum discharge velocity and evacuation time to finish air flow through a soil specimen at a given vacuum pressure. Then, a two dimensional finite element model was developed which simulates the hydro-mechanical behavior of the soil specimen in a vacuum chamber with respect to different vacuum rates. From the numerical analysis results, optimum guidelines have been proposed to ensure that soil disturbance is minimized.

# INTRODUCTION

Recently, the trend in space exploration has been shifting from a remote exploration using orbiters to a surface mission using rover and lander. The analysis results of “LCROSS impact mission” performed by NASA in 2009 showed a key indicator that water ice is present in the floor of the crater (Colaprete et al. 2010). Since then, studies on the technology for lunar surface exploration are gradually being extended. Among them, developing and verifying the exploration equipment that will be mounted on the rover or lander are the most essential parts. For the verification of the equipment used in the lunar surface mission, thorough performance tests in dirty vacuum chamber (DVC) that simulates lunar surface conditions are required.

# POROELASTICITY THEORY

During depletion of air pressure in the soil specimen, the stress is altered due to the change in pore air pressure. In this study, a “poroelasticity theory” proposed by Biot (1941) was applied to evaluate the hydro-mechanical behavior of soil specimen under depressurization conditions. 

# FINITE ELEMENT MODEL

For the investigation of the poroelastic effects on the soil specimen during the depressurization, a two dimensional finite element model was set up which couples the behavior of fluid flow and geomechanics. 

### Table 1. Material properties used in finite element model.

| Property | Name | Value | Unit | Note |
| :--- | :--- | :--- | :--- | :--- |
| Young’s Modulus | E | 10 | MPa | constant |
| Biot-Willis coefficient | αB | 1 | | constant |
| Particle density | ρd | 2750 | kg/m3 | constant |
| Air density | ρa | (ωb ua) / RT | kg/m3 | variable |
| Porosity | n | 0.418 | | constant |
| Dynamic viscosity of air | μ | 1.814E-05 | Pa·s | constant |
| Storage | S | n/ua | 1/Pa | variable |
| Poisson’s ratio | ν | 0.25 | | constant |
| Intrinsic permeability | K | 2.55E-13 | m2 | constant |

# RESULTS AND DISCUSSION

Figure 2 shows the air velocity distribution at the middle point of the soil specimen when the vacuum rate was applied at -0.33 kPa/sec in the chamber. As the absolute pressure approaches the state of vacuum, the air velocity increases rapidly. This phenomenon results from the pressure gradient that goes up exponentially in the state of vacuum, and it induces a high drag force inside the soil specimen.

Meanwhile, the soil disturbance phenomenon occurs when the effective stress becomes zero due to seepage stress. Based on a theoretical approach established in this study, the maximum air velocity (qmax) causing the soil disturbance was calculated. At given properties, the calculated qmax was about 0.000235 m/s. Theoretically, this means that the soil disturbance occurs 282.5 sec after the beginning of depressurization. 

# SUMMARY AND CONCLUSION

1. New theoretical approach provided the insight of the hydro-mechanical behavior of the soil in DVC during depressurization process.
2. The finite element model used in this study can be used to provide an appropriate vacuum rate during depressurization.
3. During the depressurization, the vacuum rate should be controlled adequately to maintain the initial condition of soil specimen until the vacuum pressure reaches a maximum allowable value.