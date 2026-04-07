# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer  
**Publication:** Journal of Aerospace Engineering © ASCE / January 2013

### Abstract
Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The models include: an array of point pressures, a quadratic function, and an exponential function. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure.

### Introduction
Outpost development on the moon requires robotic machines to build berms, grade roads, excavate foundations, and dig trenches. Unlike terrestrial excavators, space-bound equipment must be lightweight due to launch costs, requiring high-precision design rather than excessive overdesign factors. Knowing the exact pressure distribution on blades allows for more accurate finite-element analysis (FEA) to size motors and structural frames.

### Measurements and Soil Properties
Two soils were tested: **Ottawa Sand** (for baseline comparison) and **JSC-1A Lunar Soil Simulant**. JSC-1A mimics lunar regolith, being made from crushed basalt and having angular particles prone to settling and compaction.

#### Table 1. Base Configuration and Range for Test Sets by Variable
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

### Results
- **Blade Shape:** V-shaped blades are superior as they minimize loads by diverting soil to the sides. A 30-degree angle provides the widest blade without excessive force increases.
- **Cut Depth:** The relationship between average load and cut depth can be approximated by a second-order polynomial. Small-depth cuts with multiple passes are recommended for lightweight machines.
- **Blade Width:** Force increases are non-linear; wider blades are generally preferred but increase machine weight and stress on frames due to uneven loading.
- **Pressure Models:** Three types of models were developed (point-pressure, quadratic, and exponential) for FEA software integration.

#### Table 5. Square Rod Force Result Comparison in Ottawa Sand
| Depth (cm) | Test | Average force (N) | Difference in force (N) | Std Dev of force (N) |
| :--- | :--- | :--- | :--- | :--- |
| 0.6350 | Brewer | 0.1266 | 0.1573 | 0.2223 |
| 0.6350 | Gefreh | 0.2839 | - | 0.0237 |
| 3.8100 | Brewer | 3.5295 | 0.1846 | 0.3432 |

### Conclusions and Recommendations
- A **V-shaped blade with a 30-degree angle** is the optimal choice for lunar excavation.
- Excavator blades should have a **curved face** to minimize cutting forces.
- **Multiple small-depth cuts** should be used to maintain low force and power requirements.
- The weight of the blade can be reduced by using a tapered curve and removing excess material from support members.