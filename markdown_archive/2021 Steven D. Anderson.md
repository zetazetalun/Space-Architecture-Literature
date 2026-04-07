# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson, Jekan Thangavelautham
**Affiliation:** Space and Terrestrial Robotic Exploration Laboratory, Univ. of Arizona, Tucson, AZ
**Conference:** Earth and Space 2021
**Publisher:** ASCE

## ABSTRACT
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. Due to the high costs inherent in transporting resources from the Earth’s surface to these locations, new methods of material extraction and construction are necessary. This paper proposes the development of solar additive manufacturing printers for melting and use of sand for construction. The system replaces the laser in the Selective Laser Sintering (SLS) process with a large Fresnel lens to focus sunlight, relying fully on renewable solar energy.

## INTRODUCTION
As commercial and government agencies plan long-duration missions, a new economy requires infrastructure (refueling depots, habitats, etc.) on the Moon, Mars, and asteroids. High export costs make in-situ resource utilization (ISRU) paramount. 3D printing is a leading candidate for autonomous, pre-deployment construction.

## CHALLENGES TO EXTREME ENVIRONMENT ADDITIVE MANUFACTURING
- **Material Availability:** Importing materials is too costly; ISRU is necessary but requires extraction and refinement.
- **Power Systems:** Energy-intensive operations (gathering, refinement, heating) must be accounted for in remote locations.

## OBJECTIVE
To develop an additive manufacturing method that is:
1. Low-cost and low-energy.
2. Adaptable to various extraterrestrial environments.
3. Adherent to ISRU concepts.
4. Suitable for autonomous operation.

## DESIGN METHOD
While Fused Deposition Modeling (FDM) is common, it is energy-intensive. Selective Laser Sintering (SLS) is promising because it requires minimal material pre-processing and lower energy (sintering vs. melting). By replacing the CO2 laser with a Fresnel lens, energy requirements can be almost eliminated by using renewable solar energy.

### Energy Comparison
| Process | Material | Specific Energy Consumption |
| :--- | :--- | :--- |
| SLS | Polymeric | ~40 kWh/kg |
| FDM | Polymeric | 115 kWh/kg |

## FEASIBILITY AND CALCULATIONS
Solar irradiance varies by location (Figure 6). The study calculates lens power using a conservative 50% efficiency estimate for a 1 m² Fresnel lens.

### Figure 6: Solar Irradiance (W/m²)
| Object | Mean Sun Distance (AU) | Max Irradiance | Min Irradiance | Mean Irradiance |
| :--- | :--- | :--- | :--- | :--- |
| Earth/Moon | 0.995 | 1438 | 1354 | 1395 |
| Mars | 1.520 | 725.3 | 501.3 | 597.9 |
| Asteroid Belt | 2.700 | 285.4 | 134.9 | 189.5 |

### Figure 8: Achievable Lens Power (W) for 1 m² Lens
- Earth Surface: 393 W
- Moon: 548 W
- Mars: 235 W

### Figure 9: Power Requirements and Feed Rates for Sintering
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## EMPLOYMENT OF TECHNOLOGY
The technology is best suited for an autonomous robotic fleet. A rover equipped with a Fresnel lens and a leveling blade (grader) would sinter regolith directly onto the surface to build foundations, roads, and structural components.

## EXPERIMENTAL DESIGN
The researchers are building a mid-scale prototype (75cm x 75cm) for testing in vacuum chambers. It uses an Arduino Mega and Ramps 1.4 for Gcode-based movement control of the print bed and solar tracking for the lens.

## CONCLUSION
Solar sintering offers a practical, low-energy alternative to FDM for extraterrestrial construction. By tuning print parameters like travel rates and focal points, the system can adapt to different materials and solar environments, enabling autonomous infrastructure development.