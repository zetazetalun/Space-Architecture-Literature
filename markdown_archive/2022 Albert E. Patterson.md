# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris
**Conference:** Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)
**Date:** October 19-20, 2022, Lisbon, Portugal
**DOI:** 10.1115/IAM2022-93884

## Abstract
Autonomous construction systems (ACSs) have become a topic of great interest in areas including space exploration and extraterrestrial habitats. This article extracts information regarding major components, subsystems, and interfaces from published literature to propose a quasi-general system architecture and identify design opportunities for extrusion-based autonomous construction systems (EBACSs).

## 1. Introduction
Several approaches to ACSs have been proposed, with the most promising being large-scale systems based on extrusion-based additive manufacturing (3-D printing) using concrete, asphalt, or ceramic/polymer foams. These systems are vital for building shells for bridges or extraterrestrial habitats. Examples include contour crafting, cable-driven systems, and mobile robotic teams.

## 2. Fundamental System Tasks
1. Collect and mix raw materials (concrete, foam mixtures).
2. Transport materials to a nozzle/applicator.
3. Selectively place material for geometry.
4. Adjust or tune placement via a guide or trowel.
5. Monitor and control the process.

## 3. Subsystem Breakdown
- **Subsystem 1:** Frame or support (Gantry, robotic arm, or mobile robots).
- **Subsystem 2:** Preparation software (modeling, slicing, G-code).
- **Subsystem 3:** Material mixing and transport system.
- **Subsystem 4:** Extruder.
- **Subsystem 5:** Orientation system for the extruder.
- **Subsystem 6:** Forming or troweling tool.
- **Subsystem 7:** Control software and firmware.
- **Subsystem 8:** Control hardware (sensors, cameras).

## 4. Key Tables
### TABLE 3: Frame and positioning systems on existing EBACSs.
| Frame and Positioning System | References |
|---|---|
| XYZ Gantry | [15, 27, 40–42] |
| Cable-driven system | [16, 35] |
| Delta robot/printer | [2, 3, 30] |
| 6 DoF robotic arm | [2, 13, 18, 31–33, 36–38] |
| Fixed or mounted boom | [14, 34] |
| Team of small printing robots | [17, 39] |

## 5. Conclusions
The study identifies a high-level general system architecture consisting of eight subsystems and three interface types (mechanical, data, control). This framework serves as a tool for decision-making and agile implementation of additive manufacturing in complex environments like space.