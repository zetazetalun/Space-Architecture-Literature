# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris
**Conference:** Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)
**Date:** October 19-20, 2022
**Location:** Lisbon, Portugal

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest for architecture, space exploration, and other fields. This article extracts information about major components, subsystems, and interfaces from published literature to propose a quasi-general system architecture for extrusion-based autonomous construction systems (EBACSs). These models assist in agile implementation and improved design for large-scale 3-D printing-based systems, specifically targeting extraterrestrial habitats and infrastructure.

## 1 Introduction
EBACSs rely on large-scale additive manufacturing principles, extruding concrete, asphalt, ceramic, or polymer foam in layers. Applications include buildings, shelters, and extraterrestrial habitats. The development of a general system architecture is essential for decision-making, reducing cost, and schedule risks.

## 2 Methodology
The study defines five research questions regarding major functions, components, interfaces, and design parameters of EBACSs. The scope is limited to 23 high-quality sources that specifically discuss system architecture and major components rather than small technical improvements.

## 3 Collected Data
### 3.3 Fundamental System Tasks
1. Collect and mix raw materials (concrete, foam mixtures).
2. Transport materials to a nozzle.
3. Selectively place material for walls and geometry.
4. Adjust or ensure proper placement via guides/trowels.
5. Monitor and control the process.

### 3.4 Subsystems
1. **Subsystem 1 (Frame/Support):** Varies from gantries to robotic arms or mobile robots.
2. **Subsystem 2 (Prep Software):** Modeling, slicing, and print preparation.
3. **Subsystem 3 (Material Prep):** Mixing and transport.
4. **Subsystem 4 (Extruder):** The deposition head.
5. **Subsystem 5 (Extruder Orientation):** Essential for multi-DOF systems.
6. **Subsystem 6 (Forming/Troweling):** For surface finishing and placement control.
7. **Subsystem 7 (Control Software/Firmware):** Positioner and extruder control.
8. **Subsystem 8 (Control Hardware):** Sensors, cameras, and computers.

### 3.5 System Interfaces
1. **Mechanical Interfaces:** Direct hardware connections.
2. **Data/Information Interfaces:** Communication between subsystems.
3. **Control Interfaces:** Hardware/software interfaces for process regulation.

### Table 2: Papers and References Used
| Ref | Authors | EBACS Type | Build Type | Material Type |
|-----|---------|------------|------------|---------------|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small/medium ceramic shells | Ceramic paste |
| [27] | J. Zhang, et al. | Gantry-based contour crafting | Medium/large walls | Concrete |
| [16] | P. Bosscher, et al. | Cable-driven contour crafting | Medium/large walls | Concrete |
| [2] | H. Alhumayani, et al.| Robotic arm | Medium/large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small/large printing | Ceramic, clay, concrete |
| [34] | APIS-COR | Adjustable boom | Large walls | Concrete |
| [18] | S. Keating, et al. | Digital Construction Platform (DCP) | Forms for concrete/insulation | PU foam |
| [39] | S. Jokic, et al. | Minibuilders (team) | Small/medium structures | Fiber-reinforced concrete |

## 5 Analysis and Discussion
Key design parameters identified include:
1. Degree of integration (modular vs. fully integrated).
2. Elimination of interfaces to increase reliability.
3. Extruder design refinement.
4. Control hardware open-source options.
5. Forming/trowel design (a major research gap).
6. Process monitoring and defect detection.
7. Dynamic system optimization (vibration control).
8. Improved autonomy and human-system interfaces.

## 6 Conclusions
This study provides a top-down modeling and analysis tool to guide the assembly and application of EBACSs. Future work will fill gaps in forming/troweling subsystems and human-machine interaction to refine the general architecture for complex real-world (and extraterrestrial) environments.