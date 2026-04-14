# System Architecture and Design Parameters for Extrusion-Based Autonomous Construction Systems

**Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)**  
October 19-20, 2022, Lisbon, Portugal

**Authors:** Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris

## ABSTRACT
Autonomous construction systems (ACSs) have become a topic of great interest in recent years in a variety of areas, including design, materials science, architecture, space exploration, natural disaster recovery, military operations, and others. Several different approaches have been proposed, the most promising (and so far most widely-applied) one being a large-scale system based on additive manufacturing (or 3-D printing) principles, where a concrete- or foam-based material is extruded in layers to produce a structure. This article extracts information about the major components, subsystems, and interfaces in these systems from a broad sampling of published literature and uses this information to propose a quasi-general system architecture and identify design opportunities.

## 1 INTRODUCTION
Autonomous construction systems have become a topic of great interest... including space exploration [6]. The typical materials used include concrete, asphalt, and ceramic and polymer foams. The resulting structure can be a basic shell around which a useful building, shelter, bridge, extraterrestrial habitat, or other infrastructure can be built.

## 2 METHODOLOGY
This study had five major objectives:
1. Identify and collect a representative sample of published papers describing the system architecture of EBACSs.
2. Extract the important features, design parameters, and interfaces.
3. Map common features into a quasi-general system architecture.
4. Examine and discuss gaps and needed research areas.
5. Identify opportunities for improvements.

### TABLE 1: Study assumptions and their potential risk and impact
| Assumption | Impact | Risk |
|---|---|---|
| Collected materials represent state-of-the-art | Missed information | Low |
| No major EBACS types were missed | Missed information | Low |
| Descriptions in papers were accurate | Inaccurate understanding | Low |
| Sampling was enough to understand operation | Missing info on variants | Low |

## 3 COLLECTED DATA

### TABLE 2: Papers and references used to extract EBACS design and architecture data (Selected Items)
| Ref | Authors | EBACS Type | Build Type | Material Type |
|---|---|---|---|---|
| [15] | B. Khoshnevis | Gantry-based contour crafting | Small/medium ceramic shells | Ceramic paste |
| [27] | J. Zhang, B. Khoshnevis | Gantry-based contour crafting | Medium to large walls | Concrete |
| [16] | P. Bosscher, et al. | Cable-driven contour crafting | Medium to large walls | Concrete |
| [2] | H. Alhumayani, et al. | Robotic arm | Medium to large walls | Fiber-reinforced concrete |
| [30] | WASP | Delta printer | Small to large scale | Ceramic paste, clay, concrete |
| [18] | S. Keating, et al. | Digital Construction Platform (DCP) | Forms for concrete/insulation | PU foam |
| [17] | X. Zhang, et al. | Minibuilders: Team of robots | Small to medium structures | Fiber-reinforced concrete |

### 3.3 Fundamental System Tasks
1. Collect raw materials and mix appropriately.
2. Transport materials to a nozzle.
3. Selectively place the raw material.
4. Adjust/tune placement via a guide or trowel.
5. Monitor and control the process.

### 3.4 Subsystems
1. Subsystem 1: Frame or support (gantry, robotic arm, mobile robot).
2. Subsystem 2: Preparation software (modeling, slicing).
3. Subsystem 3: Material mixing and transport system.
4. Subsystem 4: The extruder.
5. Subsystem 5: Orientation system (vital for efficient printing).
6. Subsystem 6: Forming or troweling tool.
7. Subsystem 7: Control software and firmware.
8. Subsystem 8: Control hardware (sensors, cameras).

## 5 ANALYSIS AND DISCUSSION
The study identified major design parameters including:
- Degree of integration (modular vs. fully integrated).
- Elimination of interfaces (to increase reliability).
- Extruder design.
- Control hardware and software (need for ROS-based open systems).
- Improved autonomy and human-system interfaces.
- Safety and security.

## 6 CONCLUSIONS
This work provides a top-down modeling and analysis tool to guide the assembly and application of EBACS in the real world. Future work will focus on filling identified gaps to refine the general architecture.