# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Authors:** Robert H. King and Andrew T. Brewer  
**Publication:** Journal of Aerospace Engineering © ASCE / January 2013  
**DOI:** 10.1061/(ASCE)AS.1943-5525.0000224

## Abstract
Extraterrestrial excavator blade design for in situ resource utilization (ISRU) requires high precision due to low-weight and high-reliability requirements. This project measured pressure distribution on laboratory-scale blades using JSC-1A lunar simulant. The study concluded that a V-shaped blade with a tapered curve is the optimal configuration and that multiple passes of small-depth cuts provide the best excavation operating procedure.

## Introduction
Outpost development on the moon requires soil handling for roads, landing sites, berms, and foundations. Robotic excavators must be lightweight to reduce launch costs, necessitating precise design via Finite Element Analysis (FEA). Previous models often used uniform pressure distributions; this study provides non-uniform load data to improve design accuracy.

## Experimental Setup
### Materials
- **JSC-1A Lunar Soil Simulant:** Mimics crushed basalt, highly angular, prone to settling and compaction.
- **Ottawa Sand:** Used as a baseline for comparison.

### Measurement System
- **Tekscan I-Scan:** A thin-film resistive sensor mapping system used to measure distributed pressure across the blade face.
- **Soil Excavation Measurement Apparatus:** Measures velocity and horizontal/vertical forces.

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
- **Blade Geometry:** V-shaped blades minimize loads by diverting soil to either side. A 30° angle was found to be the most favorable for minimizing force while maintaining width.
- **Depth of Cut:** Average load versus cut depth follows a second-order polynomial. Excavating thin cuts in multiple passes is recommended for lightweight robotic platforms.
- **Pressure Modeling:** Three models were developed: an array of point pressures, a quadratic function, and an exponential function for use in FEA and design software.

## Conclusions and Recommendations
1. **Optimal Design:** V-shaped blade with a 30° angle and curved face.
2. **Operating Procedure:** Multiple small-depth cuts to maintain low force and power consumption.
3. **Weight Reduction:** Blade weight can be minimized by employing tapered curves and removing excess support material.