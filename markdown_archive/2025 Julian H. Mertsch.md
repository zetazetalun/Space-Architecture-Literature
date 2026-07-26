# A Compact Concrete Mixing System for High Quality Specimen Production in Space: Automated MASON Concrete Mixer

**Authors:** Julian H. Mertsch, Julian T. I. Müller, Stefan Kleszczynski, Bernd Rattenbacher, and Martina Schnellenbach-Held

**Published:** 24 October 2025  
**Journal:** Aerospace (MDPI)  
**DOI:** 10.3390/aerospace12110954

## Abstract
Establishing a sustainable human presence on the Moon and Mars requires utilizing local resources for construction. Concrete-like binders are promising, but their performance under reduced gravity must be understood. This study presents an automated prototype of the MASON Concrete Mixer (MCM), which integrates motorized mixing and programmable control. The automated MCM (AMCM) enables reproducible specimen production, eliminates operator-dependent variability, and reduces astronaut workload, providing a scalable path for future extraterrestrial construction technologies.

## 1. Introduction
Building habitats on the Moon or Mars requires regolith-based binders similar to concrete. Understanding the mixing and solidification process in microgravity is critical. Previous experiments like NASA's ConCIM (1994) or ESA's manual MCM (2022) faced limitations regarding specimen quality or high astronaut time requirements. The AMCM addresses these by automating the mixing cycle.

## 2. Development of the Automated Prototype

### 2.1. Requirements
*   Standardization of cylindrical concrete sample production.
*   Integration with existing approved space hardware (MCM).
*   Modular structure for subsequent hardware adjustments.
*   Precise control of rotation and linear movement of the mixer blade.

### 2.2. Torque Tests
Torque tests were conducted to determine drive requirements for various mixtures (see Table 1 and 2).

**Table 1. Mixtures in the torque tests.**
| Mixture | Aggregate | Mass of Cement | Mass Aggregate | Mass of Water |
| :--- | :--- | :--- | :--- | :--- |
| R | None | 54 g | - | 21.5 g |
| R-SS | CEN standard sand | 17 g | 51 g | 11.5 g |
| R-R | Regolith EAC-1A | 22 g | 44 g | 15.5 g |

**Table 2. Maximum determined torques.**
| Mixture | Dry Mixing | Mixing with Water |
| :--- | :--- | :--- |
| R | 84.0 cNm | 101.8 cNm |
| R-SS | 111.0 cNm | 112.4 cNm |
| R-R | 44.4 cNm | 90.4 cNm |

### 2.3. System Architecture
The system utilizes NEMA 17 stepper motors for both linear and rotary movements, controlled by an Arduino-based system. A worm gear is used to achieve the required 2 Nm torque for mixing. The frame is constructed from aluminum profiles for modularity.

## 3. Results and Discussion
Ten concrete samples were produced to validate the prototype. Initial tests identified the need for precise microswitch positioning to ensure the blade reaches the bottom of the chamber. 

**Key Observations:**
*   **Uniformity:** AMCM-produced samples showed reduced variability in bulk density and porosity compared to manual samples.
*   **Adhesion:** Some material residue adhered to the mixer blade, which could be mitigated by redesigning blade geometry or materials.
*   **Durability:** Carbon mixer blades were damaged when torques reached approximately 2.3 Nm, suggesting the need for torque monitoring or stronger materials.

## 4. Conclusions
The automated MCM prototype successfully demonstrates the feasibility of autonomous material preparation for space. While currently tested under terrestrial conditions, its modular and robust design is intended for future deployment on the ISS or the Moon. Future development will focus on automatic water injection and compaction mechanisms (e.g., vibrators).