# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer  
**Publication:** Journal of Aerospace Engineering, Vol. 26, No. 1, January 1, 2013  
**DOI:** 10.1061/(ASCE)AS.1943-5525.0000224

## Abstract
Extraterrestrial excavator blade design for in situ resource utilization (ISRU) requires high precision due to reliability and weight constraints. This project measured pressure distribution on laboratory-scale blades using JSC-1A lunar simulant. The study developed empirical pressure distribution models including point pressure arrays, quadratic functions, and exponential functions. Findings suggest a V-shaped blade with a tapered curve is the optimal configuration, and multiple shallow-depth passes constitute the best excavation procedure.

## Introduction
Developing outposts on extraterrestrial bodies requires soil handling tasks such as creating roads, landing sites, berms, foundations, and utility trenches. Robotic excavators must be designed to withstand excavation stresses without the prohibitive weight of terrestrial design factors. Precise design requires understanding the pressure distribution on blades to enable finite-element analysis (FEA) for sizing motors and structural components.

## Methodology
### Materials
- **JSC-1A Lunar Soil Simulant:** Mimics lunar regolith properties (crushed basalt, angular particles, prone to settling/compaction).
- **Ottawa Sand:** Used as a base for comparison (pure silicate, uniform grain size).

### Measurement Apparatus
Blades were mounted in the Colorado School of Mines (CSM) soil excavation apparatus. A **Tekscan I-Scan** thin-film resistive sensor (Model 6300) was used to measure distributed pressure across the blade surface, complemented by load cells for total force measurement.

### Test Variables
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

## Key Results
- **Blade Shape:** V-shaped blades minimize loads by diverting soil to either side and cancel out transverse horizontal pressure distributions.
- **Depth vs. Load:** The relationship between average load and cut depth can be approximated with a second-order polynomial. Shallow cuts reduce power and machine weight requirements.
- **Rake Angle:** Higher rake angles (achieved with curved blades) reduce excavation forces.
- **Optimal Configuration:** A 30-degree V-blade angle provides the widest cut while maintaining efficient force distribution.

## Conclusions
- V-shaped blades with a 30° angle and a curved face are recommended.
- Excavation should be performed in multiple small-depth passes to accommodate lightweight robotic platforms.
- Distributed pressure models (point-pressure, quadratic, and exponential) were developed to assist in future FEA of full-scale lunar excavators.