# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson and Jekan Thangavelautham  
**Publication:** Earth and Space 2021 (ASCE)

## Abstract
Developing a space economy requires infrastructure such as refueling depots and habitats built from in-situ resources. This paper proposes a solar-powered additive manufacturing process based on Selective Laser Sintering (SLS), replacing the laser with a Fresnel lens to focus sunlight for sintering regolith. The system aims for low-cost, low-energy, and autonomous operation to facilitate lunar and planetary base construction.

## Challenges to Extreme Environment Additive Manufacturing
- **Material Availability:** Importing materials from Earth is cost-prohibitive; ISRU is mandatory.
- **Refinement:** FDM-style printing requires complex pelletizing/refinement, whereas sintering requires minimal pre-processing.
- **Power Systems:** Additive manufacturing is energy-intensive. Traditional FDM consumes ~115 kWh/kg, whereas SLS consumes ~40 kWh/kg.

## Design Method: Solar Sintering
The proposed method uses a Fresnel lens to harness renewable solar energy to reach the sintering temperature of regolith (~1100°C). Unlike FDM, which requires liquefaction, sintering only requires heating the material to a point where particles fuse, significantly reducing power demand.

### Solar Irradiance Data (Figure 6)
| Object | Mean Distance (AU) | Max Irradiance (W/m²) | Min Irradiance (W/m²) | Mean Irradiance (W/m²) |
| :--- | :---: | :---: | :---: | :---: |
| Mercury | 0.387 | 14656 | 6361 | 9247 |
| Earth/Moon | 0.995 | 1438 | 1354 | 1395 |
| Mars | 1.520 | 725.3 | 501.3 | 597.9 |
| Asteroid Belt | 2.700 | 285.4 | 134.9 | 189.5 |

### Power Feasibility (Figure 8 & 9)
Calculations based on a 1m² lens with 50% efficiency:
| Location | Material | Achievable Lens Power (W) | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :---: | :---: | :---: |
| Earth Surface | Sand | 393 | 351 | 2.50 |
| Moon | Regolith | 548 | 450 | 1.00 |
| Mars | Basalt | 235 | 236 | 4.50 |
| Deimos | C. Chondrite | - | 97 | 5.00 |

## Implementation
The technology is envisioned as part of a robotic fleet. Mobile rovers equipped with Fresnel lenses and leveling blades (similar to road graders) would sinter infrastructure like foundations and roads directly onto the planetary surface.

## Conclusion
Solar sintering offers a practical, low-energy alternative to FDM for extraterrestrial construction. By tuning parameters like lens aperture and focal points, the system can adapt to different environments and in-situ materials to autonomously build the necessary infrastructure for human exploration.