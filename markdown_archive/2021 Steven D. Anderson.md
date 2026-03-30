# Solar-Powered Additive Manufacturing in Extraterrestrial Environments

**Authors:** Steven D. Anderson, Jekan Thangavelautham  
**Publication:** Earth and Space 2021, ASCE  
**Pages:** 732-744

## Abstract
Kickstarting a space economy will require building communication relays, refueling depots, repair depots, habitats, and mining bases from in-situ resources in strategic locations between Earth, Moon, and Mars. Due to the high costs inherent in transporting resources from the Earth’s surface, new methods of material extraction and construction are necessary. This paper proposes the development of solar additive manufacturing printers for melting and use of sand for construction, utilizing a large Fresnel lens to focus sunlight for sintering material (Selective Laser Sintering - SLS). This approach reduces power consumption and relies on renewable solar energy.

## Introduction
As commercial and government organizations plan long-duration missions, a new economy requires a spectrum of infrastructures. Infrastructure needs to be strategically located on the Moon, Mars, asteroids, and other moons. Additive manufacturing (AM) has risen as a key technology for habitat construction, demonstrated by NASA's 3D Printed Habitat Challenge.

## Challenges to Extreme Environment Additive Manufacturing
- **Material Availability:** Feasibility of importing materials for large-scale infrastructure is low; ISRU is essential.
- **Refinement:** Materials must be refined into printable forms (e.g., pelletizing for FDM).
- **Power Systems:** AM is energy-intensive; gathering and heating material requires significant power allocation.

## Objective
To develop an AM method tailored to off-world environments that is:
1. Low-cost and low-energy.
2. Adaptable to various environments.
3. Based on ISRU.
4. Suitable for autonomous operation.

## Design Method: Solar Sintering
The researchers propose replacing the laser in a standard SLS system with a Fresnel lens. 
- **Energy Comparison:** FDM (115 kWh/kg) vs. SLS (40 kWh/kg). SLS is more energy-efficient as it only needs to reach sinter temperature, not the full melting point.
- **Optical Quality:** A Fresnel lens reduces weight while preserving optical performance.

## Feasibility and Calculations
### Solar Irradiance available at various locations (Figure 6)
| Object | Closest (AU) | Farthest (AU) | Mean (AU) | Max Irradiance (W/m²) | Min Irradiance (W/m²) | Mean Irradiance (W/m²) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Mercury | 0.307 | 0.466 | 0.387 | 14656 | 6361 | 9247 |
| Venus | 0.718 | 0.728 | 0.723 | 2679 | 2606 | 2643 |
| Earth/Moon | 0.980 | 1.010 | 0.995 | 1438 | 1354 | 1395 |
| Mars | 1.380 | 1.660 | 1.520 | 725.3 | 501.3 | 597.9 |
| Asteroid Belt | 2.200 | 3.200 | 2.700 | 285.4 | 134.9 | 189.5 |
| Jupiter | 4.950 | 5.460 | 5.205 | 56.38 | 46.34 | 50.99 |

### Achievable Lens Power (Figure 8)
Calculations based on a 1 m² lens with 50% efficiency:
| Location | Achievable Lens Power (W) |
| :--- | :--- |
| Earth Surface | 393 (assumes 1000 W/m² irradiance) |
| Moon | 548 |
| Mars | 235 |

### Power requirements for sintering in-situ materials (Figure 9)
| Location | Material | Required Sinter Power (W) | Feed Rate (mm/s) |
| :--- | :--- | :--- | :--- |
| Earth Surface | Sand | 351 | 2.50 |
| Moon | Regolith | 450 | 1.00 |
| Mars | Basalt | 236 | 4.50 |
| Deimos | Carbonaceous Chondrite | 97 | 5.00 |

## Technical Considerations and Robotic Fleets
Solar sintering technology may be best employed by a robotic fleet. A mobile platform with a Fresnel lens could sinter material directly onto the terrain, preceded by a leveling blade. This is ideal for building foundations, roads, and structural components.

## Experimental Design
- **Prototype:** Mid-scale design (75cm x 75cm) using a 1 m² lens.
- **Control System:** Arduino Mega with Ramps 1.4 board, using G-code from standard slicer programs.
- **Mechanism:** The print bed moves in X, Y, and negative Z directions while the focused beam remains stationary at the focal point.

## Conclusion
Solar sintering offers a practical, low-energy alternative to FDM for extraterrestrial construction. By tuning print parameters like feed rates and lens apertures, the system can adapt to different irradiance levels across the solar system, making it a viable candidate for autonomous ISRU infrastructure development.