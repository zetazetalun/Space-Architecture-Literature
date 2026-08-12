# Design of an Autonomously Deployable Mars Habitat

**Authors:** Rudolf Walther Erdem Neumerkel, Miruna Vecerdi, Sandra Häuplik-Meusburger
**Source:** 50th International Conference on Environmental Systems (ICES-2021-398), 12-15 July 2021

## Abstract
This paper proposes an autonomously deployable habitat for long-duration manned missions on Mars. The design is optimized for the payload constraints of SpaceX's Starship and addresses habitability challenges such as low pressure, radiation, and extreme temperatures. The system integrates a rigid casing, a telescopic core, expanding girders, and an inflatable multi-layered membrane.

## 1. Introduction
The Martian environment presents hazards including low atmospheric pressure, radiation, and MMOD impacts. Transportation is a primary constraint; hence, the design utilizes a deployable architecture to maximize habitable volume from a compact launch state.

## 2. Design Method
The habitat consists of four main integrated systems:
- **A. Casing:** A rigid shell divided into three parts that protect internal components during transport and provide docking interfaces.
- **B. Telescopic Core:** The primary rigid structure housing life support, sanitary units, and a water tank for radiation protection. It doubles in height during deployment.
- **C. Expanding Girders:** Foldable elements that push the casing outward and provide structural support for floors.
- **D. Inflatable Membrane:** A multi-layered structure adapted from TransHab technology, featuring layers for airtightness, structural restraint, and radiation shielding.
- **E. Design Workflow:** Developed using Rhino/Grasshopper and the Kangaroo physics engine to simulate kinematic behavior and avoid collisions during deployment.

## 3. Arrival and Deployment Choreography
Two units can fit within a single Starship fairing. Deployment is initiated by releasing girder springs, followed by membrane inflation and the vertical extension of the core. Robotic systems then fill outer membrane chambers with loose regolith for shielding.

## 4. Key Data and Findings
| Component | Material | Volume (m3) | Density (kg/m3) | Mass (kg) |
| :--- | :--- | :--- | :--- | :--- |
| Core Frame | Aluminium | 0.26 | 2740 | 712.40 |
| Water Tank | PE | 0.16 | 940 | 150.40 |
| Inflatable Membrane | Kevlar/Nomex | ~5.0 | Varies | 7335.00 |
| **Total Habitat Mass** | - | - | - | **27,988.53** |

- **Stowed Volume:** ~180 m3
- **Deployed Volume:** 921 m3
- **Expansion Factor:** ~5
- **Internal Pressure:** 100,000 Pa (1 bar)

## 5. Conclusion
The design offers a flexible, modular layout that provides a safe environment for 4-6 crew members. The use of loose regolith infill is presented as a lower-risk ISRU strategy compared to 3D sintering.