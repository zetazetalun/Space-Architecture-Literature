# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer  
**Publication:** Journal of Aerospace Engineering, Vol. 26, No. 1, January 1, 2013  
**DOI:** 10.1061/(ASCE)AS.1943-5525.0000224

## Abstract
Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure.

## Introduction
If outposts are developed on extraterrestrial bodies, such as the moon, several soil handling tasks are required, such as creating roads and landing sites. Outpost development requires robotic machines to build berms, grade and compact roads, excavate foundations, smooth landing pads, and excavate trenches for utilities. Precision design begins with analysis of the pressures on the blade. If excavation pressures are known, finite-element and discrete-element models can be used to calculate stresses and displacement in the frame and joints.

## Measurements
Pressure was measured on a suite of laboratory-scale straight and V-shaped blades. The straight blade simulates the LANCE-type blade. The V-shaped blade design may be better for extraterrestrial application because it minimizes the load during excavation by diverting the soil to either side of the blade.

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

## Results
- **Blade Shape:** V-shaped blades with an angle of 30° were found to be optimal. Curved blade faces minimize cutting forces.
- **Depth of Cut:** The average load versus cut depth results for flat and curved blades can be approximated with a second-order polynomial. Lightweight machines should excavate thin cuts and take multiple passes.
- **Width:** Wider blades are preferred because the increase in force is non-linear (smallest increase from 25.40-cm to 30.48-cm width).
- **Pressure Models:** Three types of distributed pressure models were developed: an array of point pressures, a quadratic model, and an exponential model.

### Table 3. Summary of Calibration Relationships
| Relationship | First calibration | Third calibration |
| :--- | :--- | :--- |
| Horizontal calibration (N) | F = 36.532V - 27.224 | F = 38.433V - 37.429 |
| Vertical calibration (N) | F = -66.767V + 394.18 | F = -76.737V + 424.63 |

## Conclusions and Recommendations
The measurements showed that a V-shaped blade with an angle of 30° is the best choice, and the blade face should be curved to minimize cutting forces. Multiple passes of small-depth cuts are the best excavation operating procedure to maintain low force and low power for lightweight machines.