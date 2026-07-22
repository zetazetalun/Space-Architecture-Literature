# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris  
**Conference:** Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)  
**Date:** October 19-20, 2022, Lisbon, Portugal  
**DOI:** 10.1115/IAM2022-93884

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in areas including space exploration and extraterrestrial habitats. This article extracts information from published literature to propose a quasi-general system architecture for extrusion-based autonomous construction systems (EBACSs), identifying major components, subsystems, and interfaces. This model serves as a tool for decision-making and agile implementation of large-scale 3-D printing-based systems.

## 1. Introduction
EBACSs use additive manufacturing principles to extrude materials (concrete, asphalt, ceramic/polymer foams) in layers to produce structures like shells or full buildings. The study aims to understand commonalities between diverse technologies like contour crafting, cable-driven systems, and mobile robot teams to create a high-level general system architecture.

## 2. Methodology
The study reviewed 23 sources to answer five research questions regarding major functions, components, interfaces, general architecture, and design parameters of EBACSs.

### Table 2: EBACS Types and Materials (Sample)
| Ref | Authors | EBACS Type | Build Type | Material Type |
|---|---|---|---|---|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small/med ceramic shells | Ceramic paste |
| [16] | P. Bosscher, et al. | Cable-driven contour crafting | Medium to large walls | Concrete |
| [2] | H. Alhumayani, et al. | Robotic arm | Medium to large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small to large scale | Clay, concrete, fiber |
| [14] | V. Mechtcherine, et al. | CONPrint3D (truck-mounted) | Very large monolithic | Concrete |
| [17] | X. Zhang, et al. | Minibuilders (robot team) | Small to medium | Fiber-reinforced concrete |

## 3. System Architecture
### 3.1 Fundamental Tasks
1. Collect raw materials and mix them appropriately.
2. Transport materials to a nozzle or applicator.
3. Selectively place material to build geometry.
4. Adjust/tune placement via guide or trowel.
5. Monitor and control the process.

### 3.2 Subsystems
1. **Frame or Support with Positioner:** Holds and moves the extruder (Gantry, Cable, Delta, 6-DoF Arm, Boom, or Mobile Robots).
2. **Prep Software:** Modeling, slicing, and toolpath generation.
3. **Material Prep/Mixing and Transport:** Pump and mixing system.
4. **Extruder System:** The nozzle and holding chamber.
5. **Extruder Orientation System:** Vital for effective placement (rotational DoF).
6. **Forming or Trowel:** Controls and polishes the extruded material.
7. **Control Software/Firmware:** Firmware for positioners and extruders.
8. **Control Hardware:** Sensors, cameras, and control computers.

### 3.3 Interfaces
* **Mechanical Interfaces:** Direct hardware connections.
* **Data/Information Interfaces:** Communication between software/subsystems.
* **Control Interfaces:** Hardware/software interfaces managing position, rate, and monitoring.

## 4. Key Design Parameters
1. Degree of integration (modular vs. integrated).
2. Elimination of interfaces for reliability.
3. Extruder design for new materials.
4. Control hardware (moving toward open source).
5. Forming/trowel design for surface quality.
6. Process monitoring (defect detection).
7. Dynamic system optimization (vibration control).
8. Improved autonomy (reducing human interaction).

## 5. Conclusions
The proposed architecture provides a top-down modeling and analysis tool for complex construction jobs. Future work will focus on filling gaps in control hardware and forming/troweling operations to refine the general EBACS architecture.