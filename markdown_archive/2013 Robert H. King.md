# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Robert H. King** and **Andrew T. Brewer**

**Abstract:** Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The models include: an array of point pressures, a quadratic function, and an exponential function. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure.

## Introduction
Outpost development requires a robotic machine to build berms, grade and compact roads, excavate foundations, smooth landing pads, and excavate trenches for utilities. Robotic excavators must be designed to withstand the stresses of excavation without failing. High launch costs necessitate precise design rather than terrestrial over-design strategies. Nonuniform load distribution is typical of excavation practice, because soil doesn’t press against the upper corners, the surcharge shape is curved, and the middle of the blade pushes the most soil.

## Measurements
Pressure was measured on a suite of laboratory-scale straight and V-shaped blades. The straight blade simulates the LANCE-type blade. The V-shaped blade design minimizes the load by diverting soil to either side.

### Table 1: Base Configuration and Range for Test Sets by Variable
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

## Soil Properties
Two soils were tested: Ottawa Sand and **JSC-1A Lunar Soil Simulant**. JSC-1A mimics the material properties of lunar regolith, made from crushed basalt. Its characteristics (internal angle of friction 37°, cohesion 1.793 kPa) make it highly prone to settling and compaction, requiring strict soil preparation protocols.

## Results
*   **Load vs Depth:** The average load versus cut depth results for flat and curved blades can be approximated with a second-order polynomial.
*   **Blade Width:** Wider blades are preferred because the increase in force is smallest when moving from 25.40-cm to 30.48-cm widths.
*   **Rake Angle:** Higher rake angles reduce excavation forces.
*   **V-Blades:** The V-blade became the most favorable shape when considering transverse horizontal pressure distribution, as pressures for the two halves are equal and opposite, cancelling out transverse loads on the frame. The optimal angle was found to be between 30° and 45°.

### Distributed Pressure Models
Three types of distributed pressure models were developed for use in FEA software:
1.  **Point-Pressure Model:** An array of pressures for each sensel (0.08 x 0.51 cm area).
2.  **Quadratic Model:** $P_{surcharge} = 0.42796 - 0.06647x^2 + 0.25170x - 0.00854xy - 0.00194y + 0.00187y^2$; $P_{cut} = 0.46$.
3.  **Exponential Model:** $P_{surcharge} = 0.00082 e^{0.00289[(x - 49.701)^2 + (y - 5.9187)^2]}$; $P_{cut} = 0.46$.

## Conclusions
*   A V-shaped blade with an angle of 30° is the best choice.
*   The blade face should be curved to minimize cutting forces.
*   Multiple passes of small-depth cuts is the best operating procedure for maintaining low force/power for lightweight machines.
*   Weight can be minimized by employing a tapered curve along the blade and removing excess support material.