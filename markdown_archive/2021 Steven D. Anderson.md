# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson, Jekan Thangavelautham
**Affiliation:** Space and Terrestrial Robotic Exploration Laboratory, Dept. of Aerospace and Mechanical Engineering, Univ. of Arizona, Tucson, AZ
**Publisher:** Earth and Space 2021 (ASCE)

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources. To reduce the high costs of transporting resources from Earth, new methods of material extraction and construction are necessary. We propose the development of solar additive manufacturing printers that replace the laser in the Selective Laser Sintering (SLS) process with a large Fresnel lens to focus sunlight for sintering material. This system fully relies on renewable solar energy for operation. The paper analyzes conceptualization, design, and prototype construction of a solar 3D printer, supported by simulations to determine operating parameters.

## Introduction
Long-duration missions require infrastructure strategically located on the Moon, Mars, and asteroids. Additive manufacturing (AM) has risen as a primary candidate for constructing these structures economically and autonomously.

## Challenges to Extreme Environment Additive Manufacturing
- **Material Availability:** Importing materials is cost-prohibitive; ISRU is essential.
- **Refinement:** Materials must be refined into printable forms (e.g., pelletizing for FDM).
- **Power Systems:** Power must be allocated for electrical, communication, and heating systems; gathering and heating material are energy-intensive.

## Objective
To develop a method of additive manufacturing that is:
1. Low-cost and low-energy.
2. Adaptable to various extraterrestrial environments.
3. Based on ISRU.
4. Suitable for autonomous operation.

## Design Method
Selective Laser Sintering (SLS) is promising because it requires minimal material pre-processing and has lower energy consumption than Fused Deposition Modeling (FDM). Replacing the CO2 laser with a Fresnel lens allows the system to harness renewable solar energy directly.

### Comparison of Energy Consumption
| Process | Specific Energy Consumption (kWh/kg) |
| :--- | :--- |
| SLS | ~40 |
| FDM | 115 |

## Feasibility and Calculations

### Table 1: Solar Irradiance available at various locations (Figure 6)
| Object | Mean Distance (AU) | Mean Solar Irradiance (W/m²) |
| :--- | :--- | :--- |
| Earth/Moon | 0.995 | 1395 |
| Mars | 1.520 | 597.9 |
| Asteroid Belt | 2.700 | 189.5 |
| Deimos (Jupiter mean used as proxy) | 5.205 | 50.99 |

### Table 2: Achievable Lens Power (W) at several locations (1m² lens, 50% efficiency)
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 |
| Moon | 548 |
| Mars | 235 |

### Table 3: Power requirements and feed rates for sintering (Figure 9)
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Experimental Objective and Design
Prototype testing involved a small 8.5" x 11" Fresnel lens reaching ~1100°C to sinter quartzite sand. The mid-scale design (75cm x 75cm) is designed for vacuum chamber testing to simulate extraterrestrial conditions (low pressure/low temperature). The system uses an Arduino Mega and RAMPS 1.4 board for Gcode-based control of the print bed and lens tracking.

## Conclusion
Solar sintering offers a practical, low-energy option for constructing infrastructure in locations with sufficient solar exposure. By adjusting print parameters (feed rates, focal points), the technology can be tailored to various environments and raw in-situ materials.