# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson, Jekan Thangavelautham
**Institution:** Space and Terrestrial Robotic Exploration Laboratory, Dept. of Aerospace and Mechanical Engineering, Univ. of Arizona, Tucson, AZ
**Published in:** Earth and Space 2021 (ASCE)

## Abstract
Kickstarting a space economy requires building habitats and infrastructure from in-situ resources. This paper proposes an additive manufacturing process based on selective laser sintering (SLS), replacing the laser with a Fresnel lens to focus sunlight. This system relies on renewable solar energy to sinter materials like sand and regolith. The study analyzes conceptual design, prototype development, and simulations to determine operating parameters for lunar and planetary construction.

## Introduction
Long-duration missions require sustainable construction methods for refueling depots, repair depots, and human/robotic habitats. Due to high transport costs from Earth, material extraction and utilization (ISRU) are paramount. 3D printing is a leading candidate for autonomous, pre-deployment construction.

## Challenges to Extreme Environment Additive Manufacturing
- **Material Availability:** In-situ resources are the only feasible option to cut costs, requiring extraction and refinement.
- **Power Systems:** AM is energy-intensive. Heating processed material and operating electrical systems require significant power allocation in remote locations.

## Design Method: Solar SLS
Selective Laser Sintering (SLS) is identified as more energy-efficient than Fused Deposition Modeling (FDM). 
- **Energy Comparison:** A study found SLS consumed ~40 kWh/kg while FDM consumed ~115 kWh/kg for polymeric materials.
- **Fresnel Lens:** Replaces the CO2 laser. It reduces weight while preserving optical performance to focus solar thermal energy directly onto the powder bed.

## Feasibility and Calculations

### Table 1: Solar Irradiance at Various Locations
| Object | Mean Distance (AU) | Mean Solar Irradiance (W/m²) |
| :--- | :--- | :--- |
| Mercury | 0.387 | 9247 |
| Venus | 0.723 | 2643 |
| Earth/Moon | 0.995 | 1395 |
| Mars | 1.520 | 597.9 |
| Asteroid Belt | 2.700 | 189.5 |
| Jupiter | 5.205 | 50.99 |
| Saturn | 9.585 | 15.04 |
| Uranus | 19.250 | 3.728 |
| Neptune | 30.100 | 1.525 |
| Pluto | 39.500 | 0.885 |

### Table 2: Achievable Lens Power (W)
Calculated using a 1 m² lens at 50% efficiency.
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 |
| Moon | 548 |
| Mars | 235 |

### Table 3: Power Requirements and Feed Rates
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Employment of Technology
Solar sinter technology is best suited for a robotic fleet tasked with autonomous construction prior to human arrival. Concepts include a mobile rover equipped with a Fresnel lens and a leveling blade (similar to a road grader) to sinter foundations, roads, and structural components directly onto the surface.

## Experimental Design
- **Objective:** Reach ~1100°C to sinter quartzite sand.
- **Scale:** Mid-scale design (75cm x 75cm) for vacuum chamber testing.
- **Control:** Arduino Mega and Ramps 1.4 board using Gcode; X-Y motion for the print bed while the focused beam remains fixed.

## Conclusion
Solar sintering offers a low-energy, ISRU-based alternative for extraterrestrial construction. By tuning parameters like travel rates and lens aperture, it provides high versatility for building essential infrastructure in power-constrained environments.