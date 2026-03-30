# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson and Jekan Thangavelautham  
**Publication:** Earth and Space 2021 (ASCE)

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. This paper proposes the development of solar additive manufacturing printers that utilize a Fresnel lens to focus sunlight for sintering material (sand/regolith) into solid shapes, relying fully on renewable solar energy.

## Introduction
Sustainable construction methods are required to support long-duration missions. While Fused Deposition Modeling (FDM) is common, it is energy-intensive and requires significant material refinement. Selective Laser Sintering (SLS) adapted for solar energy offers a low-cost, efficient alternative for autonomous construction.

## Objectives
1. Be low-cost and low-energy.
2. Be adaptable to a variety of extraterrestrial environments.
3. Adhere to the concept of In-Situ Resource Utilization (ISRU).
4. Be suitable for an autonomous printing operation.

## Design Method: Solar SLS
The proposed method replaces the CO2 laser in a traditional SLS printer with a Fresnel lens. 
- **SLS Energy Advantage:** SLS specific energy consumption is approximately 40 kWh/kg, compared to 115 kWh/kg for FDM.
- **Fresnel Lens:** Reduces weight while preserving optical performance to reach sintering temperatures (~1100°C for sand).

## Technical Data and Calculations

### Figure 6: Solar Irradiance at Various Locations
| Object | Mean Distance (AU) | Mean Solar Irradiance (W/m²) |
| :--- | :--- | :--- |
| Mercury | 0.387 | 9247 |
| Venus | 0.723 | 2643 |
| Earth/Moon | 0.995 | 1395 |
| Mars | 1.520 | 597.9 |
| Asteroid Belt | 2.700 | 189.5 |
| Jupiter | 5.205 | 50.99 |

### Figure 8: Achievable Lens Power (1 m² lens, 50% efficiency)
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 |
| Moon | 548 |
| Mars | 235 |

### Figure 9: Power Requirements for Sintering ISRU Materials
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Employment and Challenges
The technology is best suited for robotic fleets performing autonomous construction of foundations, road networks, and structural components directly on the surface. Challenges include inconsistencies in solar beam due to atmospheres (on Mars), the lack of ambient temperature control, and the need for precision sun tracking.

## Experimental Design
- **Scale:** Mid-scale prototype (75cm x 75cm) for vacuum chamber testing.
- **Control:** Arduino Mega and Ramps 1.4 board using standard Gcode for X, Y, and Z axis movement.
- **Source:** 1 m² Fresnel lens on a rotating platform for sun tracking.

## Conclusion
Solar sintering provides a practical, low-energy option for extraterrestrial construction where power conservation is a priority. By adjusting print parameters (feed rates, focal points), the system can be tailored to various planetary environments and materials.