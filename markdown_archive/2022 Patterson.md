# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris  
**Conference:** Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)  
**Date:** October 19-20, 2022, Lisbon, Portugal  
**DOI:** 10.1115/IAM2022-93884

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in areas including space exploration and extraterrestrial habitat construction. This article extracts information about major components, subsystems, and interfaces from published literature to propose a quasi-general system architecture for extrusion-based autonomous construction systems (EBACSs). These models drive research efforts toward agile implementation and improved design of large-scale 3D printing systems.

## 1. Introduction
EBACSs utilize additive manufacturing principles where material (concrete, foam, polymers) is extruded in layers to produce structures. The resulting shell can serve as a building, bridge, or extraterrestrial habitat. Current technologies include contour crafting, cable-driven systems, and mobile robotic platforms. This work adopts a systems engineering approach to develop a high-level general system architecture.

## 2. Methodology
The study defines five research questions focusing on major functions, components, interfaces, and design parameters of identified EBACSs. Data was collected from 23 sources across different EBACS types.

### Table 1: Study assumptions and their potential risk
| Assumption | Impact | Risk |
| :--- | :--- | :--- |
| Collected materials represent state-of-the-art | Missed information | Low |
| No major EBACS types missed | Missed information | Low |
| Architecture accurately described in papers | Inaccurate understanding | Low |
| Sampling of papers was sufficient | Missing small variants | Low |

## 3. Collected Data
### Table 2: EBACS Design and Architecture Data (Selection)
| Ref | EBACS Type | Build Type | Material Type |
| :--- | :--- | :--- | :--- |
| [15] | Gantry-based contour crafting | Ceramic shells | Ceramic paste |
| [16] | Cable-driven contour crafting | Medium/large walls | Concrete |
| [2] | Robotic arm | Medium/large walls | Fiber-reinforced concrete |
| [18] | Digital Construction Platform (DCP) | Poured concrete forms | PU foam |
| [39] | Minibuilders (Mobile robots) | Small/medium structures | Fiber-reinforced concrete |

### 3.3 Fundamental System Tasks
1. Collect and mix raw materials.
2. Transport materials to the nozzle.
3. Selectively place material for walls/geometry.
4. Adjust/tune placement via guides or trowels.
5. Monitor and control the process.

### 3.4 Subsystems
1. **Subsystem 1:** Frame or support (Gantry, robotic arm, etc.).
2. **Subsystem 2:** Preparation software (Modeling, slicing).
3. **Subsystem 3:** Material mixing and transport system.
4. **Subsystem 4:** Extruder.
5. **Subsystem 5:** Extruder orientation system.
6. **Subsystem 6:** Forming or troweling tool.
7. **Subsystem 7:** Control software and firmware.
8. **Subsystem 8:** Control hardware (Sensors, cameras).

## 4. EBACS System Architecture
The proposed architecture (Figure 4 in original) maps mechanical, data/information, and control interfaces between the subsystems. It serves as a starting point for developing future complex construction systems.

## 5. Analysis and Discussion
Key design parameters for exploration include:
- **Degree of integration:** Modular vs. fully integrated systems.
- **Extruder design:** Refining for new material types.
- **Forming/trowel design:** Opportunities for independent optimization.
- **Improved autonomy:** Reducing the need for direct human interaction.
- **Safety and security:** Addressing safety threats posed by large-scale printers.

## 6. Conclusions
This study provides a top-down modeling and analysis tool to guide the assembly and application of autonomous construction machines. Future work will fill gaps in control hardware and forming operations to refine the general EBACS architecture.