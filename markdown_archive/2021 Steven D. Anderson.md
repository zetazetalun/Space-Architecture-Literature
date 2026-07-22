# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson and Jekan Thangavelautham  
**Publication:** Earth and Space 2021, ASCE

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. This paper proposes the development of solar additive manufacturing printers that utilize a large Fresnel lens to focus sunlight, replacing the traditional laser in Selective Laser Sintering (SLS). This system relies on renewable solar energy to sinter in-situ materials into solid shapes for autonomous construction.

## Introduction
Long-duration missions require sustainable, low-cost construction methods. Additive manufacturing (AM) is a frontrunner for space infrastructure, but current methods like FDM require significant energy for material refinement. The authors propose adapting SLS to use concentrated solar energy instead of CO2 lasers to reduce mission power requirements.

## Challenges to Extreme Environment Additive Manufacturing
1.  **Material Availability:** Importing materials is cost-prohibitive; ISRU is mandatory.
2.  **Material Range:** Processes must work with varied in-situ materials.
3.  **Power Systems:** Electrical, heating, and processing operations are energy-intensive.

## Design Method: Solar Sintering
Typical SLS technology uses a laser to heat powder substrate to its sinter temperature. By replacing the laser with a Fresnel lens, energy requirements for the printer are drastically reduced by utilizing ambient solar irradiance. SLS is more energy-efficient than FDM (40 kWh/kg vs 115 kWh/kg for polymers) and requires less pre-processing of raw materials.

## Feasibility and Calculations
To determine feasibility, solar irradiance and achievable lens power were calculated for various locations.

### Table 1: Solar Irradiance available at various locations
| Object | Closest (AU) | Farthest (AU) | Mean (AU) | Max (W/m²) | Min (W/m²) | Mean (W/m²) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Mercury | 0.307 | 0.466 | 0.387 | 14656 | 6361 | 9247 |
| Earth/Moon | 0.980 | 1.010 | 0.995 | 1438 | 1354 | 1395 |
| Mars | 1.380 | 1.660 | 1.520 | 725.3 | 501.3 | 597.9 |
| Asteroid Belt | 2.200 | 3.200 | 2.700 | 285.4 | 134.9 | 189.5 |

### Table 2: Achievable Lens Power (W) assuming a 1m² Fresnel lens at 50% efficiency
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 |
| Moon | 548 |
| Mars | 235 |

### Table 3: Power requirements and feed rates for sintering in-situ materials
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Experimental Design
The researchers are developing a mid-scale prototype (75cm x 75cm) using an Arduino Mega and RAMPS 1.4 for control. The printer moves the print bed in X, Y, and Z axes while the solar beam remains fixed. Preliminary tests with an 8.5” x 11” Fresnel lens successfully sintered powder to create 3D structures.

## Conclusion
Solar sintering offers a practical, low-energy alternative to FDM for extraterrestrial environments. By tuning print parameters such as feed rates and lens focus, the technology can provide a versatile platform for autonomous infrastructure development, including road networks and foundations, using only in-situ resources.