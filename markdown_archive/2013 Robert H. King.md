# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer

**Published in:** Journal of Aerospace Engineering (ASCE), Vol. 26, No. 1, January 1, 2013.

## Abstract
Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The models include: an array of point pressures, a quadratic function, and an exponential function. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure.

## Introduction
Outpost development on the Moon requires robotic machines for soil handling tasks such as creating roads, landing sites, berms, and excavating foundations. Precise design is necessary to reduce launch costs and avoid equipment failure. Traditional models often provide only average uniform pressure distributions, which do not accurately simulate the nonuniform load distribution typical of excavation practice. This project measured nonuniform pressures on laboratory-scale blades to improve the accuracy of extraterrestrial excavator blade design.

## Measurements and Methodology
Tests were conducted using a suite of laboratory-scale straight and V-shaped blades in the Colorado School of Mines (CSM) soil excavation measurement apparatus. Soils tested included Ottawa Sand and JSC-1A Lunar Soil Simulant. A Tekscan I-Scan system with thin-film resistive sensors was used to map distributed pressure over the tool surface.

### Table 1: Base Configuration and Range for Test Sets by Variable
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

## Results and Discussion
- **Load Comparison:** Average load versus cut depth for flat and curved blades can be approximated with a second-order polynomial. 
- **Blade Geometry:** V-shaped blades with an angle of 30° are favored because they divert soil efficiently and prevent surcharge buildup in the center.
- **Operational Strategy:** Multiple passes of small-depth cuts are recommended to maintain low force and power requirements for lightweight machines.
- **Rake Angle:** Higher rake angles reduce excavation forces.
- **Pressure Models:** Three types of distributed pressure models were developed: an array of point pressures, a quadratic model, and an exponential model.

### Empirical Models for 30.48-cm Flat Blade in JSC-1A
**Quadratic Pressure Model:**
- $P_{surcharge} = 0.42796 - 0.06647x^2 + 0.25170x - 0.00854xy - 0.00194y + 0.00187y^2$
- $P_{cut} = 0.46$

**Exponential Pressure Model:**
- $P_{surcharge} = 0.00082 e^{0.00289[(x-49.701)^2 + (y-5.9187)^2]}$
- $P_{cut} = 0.46$

## Conclusions and Recommendations
- A V-shaped blade (30° angle) with a curved face is the optimal configuration.
- Small-depth, multi-pass excavation is the best strategy for lunar robotic explorers.
- These distributed pressure models can be used in FEA software to optimize future excavator designs for lunar outposts.