# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Robert H. King¹ and Andrew T. Brewer²**

**Abstract:** Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The models include: an array of point pressures, a quadratic function, and an exponential function. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure. DOI: 10.1061/(ASCE)AS.1943-5525.0000224. © 2013 American Society of Civil Engineers.

**CE Database subject headings:** Lunar materials; Excavation; Space construction; Load factors; Measurement; Simulation.

**Author keywords:** Lunar materials; Excavation; Space construction; Soil-blade interaction; Blade-distributed pressure measurement; Extraterrestrial excavation.

---

## Introduction
If outposts are developed on extraterrestrial bodies, such as the moon, several soil handling tasks are required, such as creating roads and landing sites. Outpost development requires a robotic machine to build berms, grade and compact roads, excavate foundations, smooth landing pads, and excavate trenches for utilities. Robotic excavators must be designed to withstand the stresses of excavation without failing. 

Launch costs of large equipment are prohibitive, and therefore precise design must take the place of high design factors used terrestrially. Precise design begins with analysis of the pressures on the blade. If excavation pressures are known, finite-element and discrete-element models can be used to calculate stresses and displacement in the frame and joints, determine tractive requirements, size motors, and provide data for trade studies.

## Measurements
Pressure was measured on a suite of laboratory-scale straight and V-shaped blades. Two sets of straight blades compare blade widths (20.32, 25.40, and 30.48 cm) and face curvature, while the V-blades compare the blade shapes as well as angles (15°, 30°, and 45°).

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
Two soils were tested: Ottawa Sand and JSC-1A Lunar Soil Simulant. JSC-1A mimics the material properties of lunar regolith. It is made from crushed basalt; particles are very angular, and the particle size distribution is more dispersed than Ottawa Sand. JSC-1A has an internal angle of friction of 37°, 1.793 kPa cohesion, 23° external angle of friction, and 39 Pa adhesion.

## Results
The average load versus cut depth results for flat and curved blades can be approximated with a second-order polynomial. Because high loads mean a stronger and heavier machine, lightweight machines for extraterrestrial application should excavate thin cuts and take multiple passes if necessary.

Key findings regarding blade geometry include:
- Wider blades are generally preferred to minimize force increases relative to width, but must be balanced against machine weight and stress on supports.
- Higher rake angles reduce excavation forces, which can be achieved with a curved blade.
- V-shaped blades are favorable because the transverse horizontal pressure distributions cancel out, facilitating a lighter machine.

## Conclusions and Recommendations
The measurements showed that a V-shaped blade with an angle of 30° is the best choice, and the blade face of the excavator should be curved to minimize the cutting forces. These tests also suggest that multiple passes of small-depth cuts are the best excavation operating procedure to maintain low force and low power with a lightweight machine. The weight of the excavator blade can be minimized by employing a tapered curve along the blade and removing excess material from the support members.

Three types of distributed pressure models were developed: an array of point pressures, a quadratic model, and an exponential model. These models can be used to analyze small-scale blade designs with FEA software.