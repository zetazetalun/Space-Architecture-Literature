# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)**  
**October 19-20, 2022, Lisbon, Portugal**

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, William R. Norris

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in areas including space exploration and materials science. This article extracts information about major components, subsystems, and interfaces from published literature to propose a quasi-general system architecture for extrusion-based autonomous construction systems (EBACSs). These models drive research on large-scale 3D printing for buildings and extraterrestrial habitats.

## 1. Introduction
Several approaches to ACS have been proposed, with the most promising being large-scale systems based on additive manufacturing (AM) principles. Typical materials include concrete, asphalt, ceramic, and polymer foams. These systems are used to build basic shells for buildings or extraterrestrial habitats. Examples include contour crafting, cable-driven systems, and the Digital Construction Platform (DCP).

## 2. Methodology
The study objectives were to identify functions, components, and interfaces common to identified EBACSs and map them into a quasi-general system architecture. A final set of 23 sources was used to collect data.

## 3. Collected Data
### Table 2: Papers and references used to extract EBACS design and architecture data (Summary)
| Ref | Authors | EBACS Type | Build Type | Material Type |
|-----|---------|------------|------------|---------------|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small/Medium ceramic shells | Ceramic paste |
| [27] | Zhang & Khoshnevis | Gantry-based contour crafting | Large walls | Concrete |
| [2] | Alhumayani et al. | Robotic arm | Large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small to large scale | Ceramic, clay, concrete |
| [34] | APIS-COR | Adjustable boom | Large walls | Concrete |
| [18] | S. Keating et al. | DCP (boom-mounted robotic arm) | Forms for poured concrete | PU foam |

### 3.3 Fundamental System Tasks
1. Collect and mix raw materials.
2. Transport materials to nozzle.
3. Selectively place material.
4. Adjust placement via guide/trowel.
5. Monitor and control the process.

### 3.4 Subsystems
1. **Subsystem 1:** Frame or support (gantry, robotic arm, etc.).
2. **Subsystem 2:** Preparation software (modeling/slicing).
3. **Subsystem 3:** Material mixing and transport.
4. **Subsystem 4:** Extruder.
5. **Subsystem 5:** Orientation system for extruder.
6. **Subsystem 6:** Forming or troweling tool.
7. **Subsystem 7:** Control software/firmware.
8. **Subsystem 8:** Control hardware (sensors/cameras).

## 4. EBACS System Architecture
A quasi-general architecture was generated identifying mechanical, data/information, and control interfaces. The system includes feedback loops for real-time control and correction.

## 5. Analysis and Discussion
Key design parameters identified include:
- Degree of integration (modular vs. fully integrated).
- Extruder design and forming/trowel design.
- Improved autonomy and human-system interfaces.
- Safety and security in large-scale AM.

## 6. Conclusions
This work provides a top-down modeling tool to guide the assembly and integration of autonomous construction machines. Future work will focus on filling gaps in the architecture related to control hardware and material pumping.