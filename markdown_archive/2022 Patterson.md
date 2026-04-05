# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris
**Conference:** Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)
**Date:** October 19-20, 2022
**Location:** Lisbon, Portugal
**DOI:** 10.1115/IAM2022-93884

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in recent years in a variety of areas, including design, materials science, architecture, space exploration, and others. This article extracts information about the major components, subsystems, and interfaces from a broad sampling of published literature and uses this information to propose a quasi-general system architecture and identify design opportunities. These models can be used to drive further research efforts, assist with agile implementation, and improve the design of large-scale 3-D printing-based systems.

## 1. Introduction
Several different approaches to ACS have been proposed, notably large-scale systems based on extrusion-based additive manufacturing (EBACS). Typical materials include concrete, asphalt, and ceramic or polymer foams. The resulting structures can be basic shells for shelters, bridges, or extraterrestrial habitats. This work aims to develop a high-level general system architecture using a systems engineering approach to reduce cost and schedule risks.

## 2. Methodology
### 2.1 Research Questions
1. What are the major functions completed by identified EBACSs?
2. What are the major system components or subsystems?
3. What are the major interfaces within the system?
4. What is the general or quasi-general architecture?
5. What are the major design parameters?

### 2.2 Scope and Limitations
The study collected data from 23 sources specifically discussing system architecture and major components/interfaces, rather than small technology improvements.

## 3. Collected Data
### 3.1 Reference Set
Table 2 summarizes the 23 final references by EBACS type, build type, and material type.

| Ref | Authors | EBACS Type | Build Type | Material Type |
|---|---|---|---|---|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small to medium ceramic shells | Ceramic paste |
| [27] | J. Zhang et al. | Gantry-based contour crafting | Medium to large walls | Concrete |
| [16] | P. Bosscher et al. | Cable-driven contour crafting | Medium to large walls | Concrete |
| [2] | H. Alhumayani et al. | Robotic arm | Medium to large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small to large scale printing | Ceramic/Clay/Concrete |
| [34] | APIS-COR | Adjustable boom | Large walls and structures | Concrete |
| [35] | E. Barnett et al. | Cable-suspended foam extrusion | Small to medium structures | PU foam |
| [14] | V. Mechtcherine et al.| CONPrint3D (truck-mounted) | Very large walls/monoliths | Concrete |
| [17] | X. Zhang et al. | Minibuilders (robot team) | Small to medium structures | Fiber-reinforced concrete |

### 3.3 Fundamental System Tasks
1. Collect and mix raw materials.
2. Transport materials to nozzle.
3. Selectively place material (build geometry).
4. Adjust/tune placement via guide or trowel.
5. Monitor and control the process.

### 3.4 Subsystems
1. **Subsystem 1:** Frame or support (Gantry, robotic arm, etc.).
2. **Subsystem 2:** Preparation software (modeling/slicing).
3. **Subsystem 3:** Material mixing and transport.
4. **Subsystem 4:** Extruder.
5. **Subsystem 5:** Extruder orientation system.
6. **Subsystem 6:** Forming or troweling tool.
7. **Subsystem 7:** Control software and firmware.
8. **Subsystem 8:** Control hardware (sensors/cameras).

### 3.5 System Interfaces
1. **Mechanical interfaces:** Direct hardware connections.
2. **Data/information interfaces:** Communication between software and subsystems.
3. **Control interfaces:** Software/hardware that manages position, rate, and monitoring.

## 4. EBACS System Architecture
A quasi-general architecture was generated (Figure 4) illustrating the flow from model/build job input and raw material input to the final product output, mapping all identified subsystems and their interfaces.

## 5. Analysis and Discussion
Key design parameters include:
- **Degree of integration:** Modular vs. fully integrated.
- **Extruder design:** Refined for different materials.
- **Process monitoring:** Feedback loops for defect detection.
- **Autonomy:** Improved human-system interfaces and manual/autonomous mode switching.
- **Safety and security:** Protecting both intellectual property and human bystanders.

## 6. Conclusions and Future Work
The resulting data provides a top-down modeling and analysis tool to guide the assembly and integration of ACS. Future work will focus on a comprehensive state-of-the-art review and filling gaps in the identified architecture.