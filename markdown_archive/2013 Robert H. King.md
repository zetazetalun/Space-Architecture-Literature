# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer
**Journal:** Journal of Aerospace Engineering, Vol. 26, No. 1
**Date:** January 1, 2013
**DOI:** 10.1061/(ASCE)AS.1943-5525.0000224

## Abstract
Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure.

## Introduction
Outpost development on extraterrestrial bodies requires robotic machines to build berms, grade and compact roads, excavate foundations, and smooth landing pads. Precise design is required to minimize launch costs while ensuring structural integrity. This study measures non-uniform pressures on laboratory-scale blades to improve finite-element analysis (FEA) for extraterrestrial excavator design.

## Measurements
Pressure was measured on straight and V-shaped blades using the Colorado School of Mines (CSM) soil excavation measurement apparatus. A Tekscan I-Scan system with thin-film resistive sensors was used to map distributed pressure.

### Table 1. Base Configuration and Range for Test Sets by Variable
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

### Table 2. Base Configuration and Range for Additional Curved Blade Test Sets
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | — |
| Cutting depth (cm) | 0.635 cm | 0.127–0.635 (0.127 increments) |
| Rake angle | — | — |
| Blade angle (degrees) | 0 | — |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Curved | — |

## Soil Properties
Two materials were used: **Ottawa Sand** (pure silicate, uniform grain) and **JSC-1A Lunar Soil Simulant** (crushed basalt, angular particles, mimics lunar regolith). JSC-1A properties include an internal angle of friction of 37° and a cohesion of 1.793 kPa.

## Key Results
- **Blade Shape:** V-shaped blades divert soil to either side, minimizing the load during excavation. A 30-degree V-blade was found to be the most favorable shape.
- **Operational Strategy:** The average load versus cut depth results suggest that lightweight machines should excavate using thin cuts and multiple passes rather than deep single cuts to maintain low power/force requirements.
- **Pressure Distribution:** Non-uniform load distribution is typical. The middle of the blade pushes the most soil, and pressures decrease toward the top and outward from the middle, though they may increase near the outer edges due to surcharge spillover.
- **Modeling:** Quadratic and exponential models were developed to describe surcharge pressure distribution for FEA input.

### Table 5. Square Rod Force Result Comparison in Ottawa Sand
| Depth (cm) | Test | Average force (N) | Difference (N) | Std Deviation (N) |
| :--- | :--- | :--- | :--- | :--- |
| 0.6350 | Brewer | 0.1266 | 0.1573 | 0.2223 |
| | Gefreh | 0.2839 | | 0.0237 |
| 3.8100 | Brewer | 3.5295 | 0.1846 | 0.3432 |
| | Gefreh | 3.3449 | | 0.1331 |

## Conclusions
To minimize cutting forces and machine weight, a curved, V-shaped blade with a 30° angle is recommended. Distributed pressure models (point-pressure, quadratic, and exponential) are provided for use in FEA software to optimize structural design for lunar excavation tasks.