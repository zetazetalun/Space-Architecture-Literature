# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson and Jekan Thangavelautham  
**Publication:** Earth and Space 2021, ASCE

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. This paper proposes the development of solar additive manufacturing printers that replace lasers in the Selective Laser Sintering (SLS) process with large Fresnel lenses to focus sunlight for sintering material. This approach aims to minimize energy and material transport costs by utilizing renewable solar energy and in-situ materials.

## Introduction
Sustainable construction methods are essential for long-duration missions. New methods of material extraction and utilization are paramount. Additive manufacturing (AM) has risen to the forefront of techniques suitable for space infrastructure. Current technologies need adaptation for extreme environments to expand capabilities and reduce costs.

## Challenges to Extreme Environment Additive Manufacturing
- **Material Availability:** Importing materials is cost-prohibitive; ISRU is necessary. Materials must be refined into printable forms.
- **Power Systems:** Energy-intensive operations (refinement, heating) require robust power sources. Solar energy is a primary candidate.

## Objective
The research aims to develop an AM method that is:
1. Low-cost and low-energy.
2. Adaptable to variety of environments (Moon, Mars, Asteroids).
3. Focused on ISRU.
4. Suitable for autonomous operation.

## Design Method
The proposed system adapts **Selective Laser Sintering (SLS)**. Standard SLS uses a laser to heat powder just below its melting point. By replacing the CO2 laser with a **Fresnel lens**, the system uses focused solar energy. 

### Advantages of SLS for Space:
- Minimal pre-processing of materials.
- Lower energy consumption compared to Fused Deposition Modeling (FDM). SLS requires ~40 kWh/kg vs FDM's ~115 kWh/kg for polymers.
- Ability to create intricate shapes using the powder bed as support.

## Feasibility and Calculations
To determine feasibility, solar irradiance was analyzed across the solar system.

### Solar Irradiance and Lens Power
| Object | Mean Irradiance (W/m^2) | Achievable Lens Power (W)* |
| :--- | :--- | :--- |
| Earth Surface | 1000 | 393 |
| Moon | 1395 | 548 |
| Mars | 597.9 | 235 |

*Assumes 50% efficiency and a 1 m² lens.*

### Sintering Requirements
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Employment of Technology
The technology is best suited for an autonomous robotic fleet. A mobile platform (rover) with a Fresnel lens could sinter material directly onto the surface to build foundations, road networks, and structural components. A leveling blade on the front of the rover would provide a clean surface for the layer-by-layer process.

## Experimental Design
- **Early Feasibility:** Tested with an 8.5" x 11" Fresnel lens, successfully sintering powder to create 3D structures.
- **Mid-scale Design:** 75cm x 75cm printer for environmental testing in vacuum chambers.
- **Control:** Uses Arduino Mega and RAMPS 1.4 for Gcode-based movement; include sun-tracking for lens positioning.

## Conclusion
Solar sintering offers a practical, low-energy alternative for ISRU-based construction. By tuning print parameters (travel rate, aperture, focal points), the process can be optimized for specific materials and local solar conditions. This technology supports the development of critical infrastructure like habitats and landing pads without the high energy costs of imported binders or lasers.