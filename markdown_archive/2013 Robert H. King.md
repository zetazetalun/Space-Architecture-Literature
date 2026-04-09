# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer
**Publication:** Journal of Aerospace Engineering (ASCE), Vol. 26, No. 1, January 1, 2013.
**DOI:** 10.1061/(ASCE)AS.1943-5525.0000224

## Abstract
Extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be precise due to high reliability and low weight requirements. This project measured the pressure distribution on laboratory-scale blades using JSC-1A lunar simulant and created empirical distribution models (quadratic and exponential). Findings suggest V-shaped blades with tapered curves are optimal, and small-depth cuts minimize excavation forces.

## Introduction
Developing extraterrestrial outposts requires soil handling tasks like creating roads, landing sites, and excavating foundations. Precise design of robotic excavators is necessary to reduce launch mass while ensuring structural integrity. Traditional 2D models often fail to account for non-uniform 3D pressure distributions across the blade.

## Experimental Setup
### Materials
- **Ottawa Sand:** Pure silicate, uniform grain size, used for comparison.
- **JSC-1A Lunar Soil Simulant:** Mimics lunar regolith (crushed basalt, angular particles, dispersed size distribution).

### Equipment
- **Colorado School of Mines (CSM) soil excavation apparatus:** Controlled tray movement.
- **Tekscan I-Scan System:** Thin-film resistive sensor (Model 6300) to map distributed pressure.
- **National Instruments PXI DAQ:** For velocity and total force measurement.

### Table 1: Base Configuration and Range for Test Sets
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

## Results and Findings
- **Blade Shape:** V-shaped blades (especially at 30 degrees) reduce excavation forces by diverting soil and preventing surcharge buildup in the center.
- **Curvature:** Curved blades allow for higher rake angles, which significantly reduce excavation forces.
- **Depth:** Cutting forces follow a second-order polynomial relationship with cut depth; thin cuts in multiple passes are recommended for lightweight machines.
- **Force Distribution:** Pressure is non-uniform; higher in the middle and decreasing toward the top and sides, though increases were noted near the outer edges due to surcharge shape.

## Conclusions
- A V-shaped blade with a 30-degree angle and tapered curve is the recommended configuration.
- Multiple small-depth passes are the most efficient excavation procedure to maintain low power and force.
- The developed quadratic and exponential models can be used in FEA software for small-scale lunar excavator design.