# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)**
October 19-20, 2022, Lisbon, Portugal

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, William R. Norris

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in recent years in areas including space exploration and extraterrestrial habitats. This article extracts information about the major components, subsystems, and interfaces from a sampling of published literature and proposes a quasi-general system architecture. These models can be used to drive further research, assist with agile implementation, and improve the design of large-scale 3D printing-based systems, specifically extrusion-based autonomous construction systems (EBACSs).

## 1. Introduction
Autonomous construction systems are being developed for applications in sustainability, space exploration, and military operations. The most promising approach is large-scale additive manufacturing using concrete, asphalt, ceramic, or polymer foams. This paper seeks to develop a high-level general system architecture to reduce cost and schedule risks in real-world building problems.

## 2. Methodology
The study objectives were to identify functions, components, and interfaces common to all EBACSs and map them into a quasi-general system architecture. The final dataset included 23 sources representing various EBACS types such as gantry-based, cable-driven, and robotic arms.

### Table 2: Papers and references used to extract EBACS design and architecture data (Selected)
| Ref | Authors | EBACS Type | Build Type | Material Type |
|---|---|---|---|---|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small/Medium ceramic shells | Ceramic paste |
| [27] | J. Zhang et al. | Gantry-based contour crafting | Medium to large walls | Concrete |
| [16] | P. Bosscher et al. | Cable-driven contour crafting | Medium to large walls | Concrete |
| [2] | H. Alhumayani et al. | Robotic arm | Medium to large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small to large scale | Ceramic, clay, concrete |
| [14] | V. Mechtcherine et al. | CONPrint3D (truck boom) | Very large walls | Concrete |
| [18] | S. Keating et al. | Digital Construction Platform | Forms for concrete/insulation | PU foam |
| [17] | X. Zhang et al. | Minibuilders (robot team) | Small to medium structures | Fiber-reinforced concrete |

## 3. Collected Data
### 3.3 Fundamental System Tasks
1. Collect and mix raw materials (concrete, foams).
2. Transport materials to nozzle.
3. Selectively place material for geometry.
4. Adjust/tune placement via guide/trowel.
5. Monitor and control the process.

### 3.4 Subsystems
1. **Subsystem 1:** Frame or support (gantry, robotic arm, mobile robots).
2. **Subsystem 2:** Preparation software (modeling, slicing).
3. **Subsystem 3:** Material mixing and transport.
4. **Subsystem 4:** Extruder.
5. **Subsystem 5:** Extruder orientation system.
6. **Subsystem 6:** Forming or troweling tool.
7. **Subsystem 7:** Control software and firmware.
8. **Subsystem 8:** Control hardware (sensors, cameras).

### 3.5 System Interfaces
- **Mechanical:** Direct hardware connections.
- **Data/Information:** Communication between subsystems.
- **Control:** Interfaces managing position, extrusion rate, and defect monitoring.

## 4. EBACS System Architecture
The proposed quasi-general architecture integrates the 8 subsystems. Key observations include that extruder systems and positioning systems (gantries/robotic arms) are relatively mature, while forming/trowel design and human-system interfaces remain less developed.

## 5. Analysis and Discussion
The study identifies several design parameters for exploration:
- Degree of integration (modular vs. integrated).
- Dynamic system optimization (predicting vibration/friction).
- Improved autonomy and human-system interfaces.
- Safety and security protocols for large-scale machines.

## 6. Conclusions
This work provides a top-down modeling and analysis tool to guide the assembly and integration of autonomous construction machines. Future work will fill gaps in control hardware and human interaction models.