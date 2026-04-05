# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson, Jekan Thangavelautham
**Affiliations:** Space and Terrestrial Robotic Exploration Laboratory, Dept. of Aerospace and Mechanical Engineering, Univ. of Arizona, Tucson, AZ
**Publication:** Earth and Space 2021 (ASCE), pp. 732-744

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. Due to the high costs inherent in transporting resources, new methods of material extraction and construction are necessary. This paper proposes the development of solar additive manufacturing printers using the principles of selective laser sintering (SLS), replacing the laser with a large Fresnel lens to focus sunlight for sintering in-situ materials.

## Introduction
As commercial and government organizations plan long-duration missions, a vast spectrum of infrastructure is required. Additive manufacturing (AM) has risen to the forefront of construction methods due to its ability to be sent in advance and build structures autonomously. Two distinct challenges exist: the need for material supply and the high energy requirement for processing.

## Challenges to Extreme Environment Additive Manufacturing
*   **Material Availability:** Importing materials is cost-prohibitive. ISRU is essential.
*   **Material Versatility:** Printing techniques must be able to work with a wide variety of unrefined or minimally refined materials.
*   **Power Systems:** Gathering and heating material are energy-intensive operations. Designing power sources for these tasks in remote locations is a significant challenge.

## Design Method
While Fused Deposition Modeling (FDM) is common, it is energy-intensive due to pre-processing requirements. Selective Laser Sintering (SLS) is proposed as a more adaptable technique. 

### Selective Laser Sintering (SLS) Advantages:
*   Lower specific energy consumption (~40 kWh/kg for SLS vs ~115 kWh/kg for FDM in polymers).
*   Material only needs to reach sinter temperature (hundreds of degrees below melting point).
*   Minimal pre-processing of raw materials.

### The Solar Sinter Concept:
Replacing the CO2 laser with a Fresnel lens allows the system to rely on renewable solar energy. A Fresnel lens reduces weight while preserving optical performance.

## Feasibility and Calculations

### Solar Irradiance Data
| Object | Closest Dist (AU) | Mean Dist (AU) | Max Irradiance (W/m²) | Min Irradiance (W/m²) | Mean Irradiance (W/m²) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Earth/Moon | 0.980 | 0.995 | 1438 | 1354 | 1395 |
| Mars | 1.380 | 1.520 | 725.3 | 501.3 | 597.9 |
| Asteroid Belt | 2.200 | 2.700 | 285.4 | 134.9 | 189.5 |

### Achievable Lens Power
Based on a 1 m² Fresnel lens with 50% efficiency:
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 |
| Moon | 548 |
| Mars | 235 |

### Power Requirements for Sintering In-Situ Materials
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Experimental Design
*   **Feasibility Test:** Used a small 8.5” x 11” Fresnel lens to reach 1100°C and create rough 3D structures from sand.
*   **Mid-Scale Design:** A 75cm x 75cm printer for environmental testing in vacuum chambers.
*   **Full-Scale Design:** Will utilize a 1 m² Fresnel lens.
*   **Control System:** Arduino Mega with RAMPS 1.4 board using standard G-code for X-Y-Z translation of the print bed relative to a fixed solar focal point.

## Conclusion
Solar sintering is a practical, low-energy option for constructing infrastructure in locations with high solar exposure. By adjusting parameters like feed rates and focal points, the system can be tuned for different materials and environments, reducing the reliance on Earth-shipped materials and complex power systems.