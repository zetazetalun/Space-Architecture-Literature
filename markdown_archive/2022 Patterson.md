# SYSTEM ARCHITECTURE AND DESIGN PARAMETERS FOR EXTRUSION-BASED AUTONOMOUS CONSTRUCTION SYSTEMS

**Albert E. Patterson, Bhaskar Vajipeyajula, and William R. Norris**  
*Proceedings of the ASME 2022 International Additive Manufacturing Conference (IAM2022)*  
*October 19-20, 2022, Lisbon, Portugal*

## ABSTRACT
Autonomous construction systems (ACSs) have become a topic of great interest in recent years in a variety of areas, including design, materials science, architecture, space exploration, natural disaster recovery, military operations, and others. This article extracts information about the major components, subsystems, and interfaces in these systems from a broad sampling of published literature and uses this information to propose a quasi-general system architecture and identify design opportunities. This work is a first step in the development of a reliable general system architecture similar to those used in the design of large-scale military and aerospace systems.

## 1 INTRODUCTION
Autonomous construction systems (ACSs) have become a topic of great interest, with the most promising approach being large-scale extrusion-based additive manufacturing (EBACS). Typical materials include concrete, asphalt, and ceramic or polymer foams. The resulting structures can be basic shells for extraterrestrial habitats or full buildings. This paper takes a systems engineering approach to develop a high-level general architecture to assist designers in decision-making and efficient implementation.

## 2 METHODOLOGY
The study identifies system components and interfaces through a review of 23 representative sources. Research questions focused on major functions, subsystems, interfaces, and design parameters that can be tuned for specific construction problems.

### Table 1: Study assumptions and their potential risk
| Assumption | Impact | Risk |
|---|---|---|
| Collected materials represent state-of-the-art | Missed information | Low |
| No major EBACS types missed | Missed information | Low |
| Architecture accurately described in papers | Inaccurate understanding | Low |

## 3 COLLECTED DATA

### 3.3 Fundamental System Tasks
1. Collect and mix raw materials (concrete, foam mixtures).
2. Transport materials to a nozzle/applicator.
3. Selectively place material to build geometry.
4. Adjust/tune placement via guide or trowel.
5. Monitor and control the process.

### 3.4 Subsystems
The paper divides a general EBACS into eight subsystems:
1. **Subsystem 1:** Frame or support (gantry, robotic arm, or mobile robots).
2. **Subsystem 2:** Preparation software (modeling, slicing).
3. **Subsystem 3:** Material mixing and transport.
4. **Subsystem 4:** The extruder.
5. **Subsystem 5:** Extruder orientation system.
6. **Subsystem 6:** Forming or troweling tool.
7. **Subsystem 7:** Control software and firmware.
8. **Subsystem 8:** Control hardware (sensors, cameras).

### 3.5 System Interfaces
- **Mechanical Interfaces:** Direct hardware connections.
- **Data/Information Interfaces:** Communication between subsystems.
- **Control Interfaces:** Hardware/software controlling position, rate, and pattern.

### Table 3: Frame and positioning systems on existing EBACSs
| Frame and Positioning System | References |
|---|---|
| XYZ Gantry | [15, 27, 40-42] |
| Cable-driven system | [16, 35] |
| Delta robot/printer | [2, 3, 30] |
| 6 DoF robotic arm | [2, 13, 18, 31-33, 36-38] |
| Fixed or mounted boom | [14, 34] |
| Team of small printing robots | [17, 39] |

## 5 ANALYSIS AND DISCUSSION
Key design parameters identified for exploration include:
1. **Degree of Integration:** Range from modular to fully integrated.
2. **Elimination of Interfaces:** Increasing reliability by reducing connections.
3. **Extruder Design:** Refining for new material varieties.
4. **Control Hardware:** Developing open-source options.
5. **Forming/Trowel Design:** Independent optimization of finish tools.
6. **Process Monitoring:** Feedback loops for defect detection.
7. **Dynamic System Optimization:** Managing vibration and friction.
8. **Improved Autonomy:** Reducing the need for direct human interaction.
9. **Human-System Interface:** Developing effective interfaces for supervision.
10. **Autonomous-Manual Mode Switch:** For varying work conditions.
11. **Safety and Security:** Addressing larger safety threats compared to standard 3D printers.

## 6 CONCLUSIONS
This study provides a top-down modeling and analysis tool to guide the assembly and application of autonomous construction machines. Future work will focus on a comprehensive state-of-the-art review and filling identified gaps in the general EBACS architecture.