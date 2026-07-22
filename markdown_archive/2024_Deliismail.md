# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker  
**Journal:** Advances in Space Research 73 (2024) 2674–2684  
**Publisher:** Elsevier / COSPAR  
**DOI:** 10.1016/j.asr.2023.12.028

## Abstract
A main shift in the competitive landscape of technology development is in 3D printing of complex articles made of variety of materials due to faster manufacturing and less human error in the production. HDPE is commonly used in the projects, such as a prototype manufacturing or pipes or damp-proof membrane. This study initially focused on the preliminary design of the self-sustaining mini ethylene production plant from Martian atmosphere with scale-out architecture. UniSIM® was integrated with MATLAB® via CAPE-OPEN extension to design mini-ethylene production plant at low gravity. Ethylene capacity was found as 17.71 tons/year for 100 modules.

## 1. Introduction
Space exploration and colonization necessitate certain chemicals being produced during the voyage because it is not feasible to take all the supplies from Earth. Constructing 3D printed habitats on Mars necessitates the use of planet-made polymers, like high-density polyethylene (HDPE). The atmosphere of Mars, primarily composed of carbon dioxide, presents a favorable opportunity for on-site production of HDPE.

## 2. Process Design & Modeling
The plant design integrates reactor and purification units in a modular "scale-out" approach. One mini-plant module fits in a 2.83 m x 1.44 m x 1.62 m container.

### 2.1 Key Components
- **Dust Removal (ESP-100):** Wire-cylinder electrostatic precipitator to remove Martian dust (0.2 to 2.4 μm range).
- **Methanation Reactor (R-100):** Sabatier reaction converting CO2 and H2 into CH4 and H2O.
- **Ethylene Production Reactor (R-101):** Oxidative coupling of methane (OCM) to produce ethylene.
- **Separators (CS-100/101):** Helical two-phase separators designed for low-gravity performance.

## 3. Results and Discussion

### Table 1: Inlet specifications of methanation reactor (R-100)
| Parameter | Value |
| :--- | :--- |
| Temperature (°C) | 400 |
| Pressure (atm) | 12.56 |
| Mass Flow (kg/h) | 6.566 |

### Table 2: Module Dimensions and Power
| Specification | Value |
| :--- | :--- |
| Module Size | 2.83 m x 1.44 m x 1.62 m |
| Net Power Requirement | 4.47 kW |
| Ethylene Capacity (100 modules) | 17.71 tons/year |
| Methane Storage Capacity | 288.192 tons/year |

### 3.1 Gravity Impacts
The study utilized MATLAB to customize UniSIM unit operations for Martian gravity (3.71 m/s²). It was found that gravity significantly impacts pressure drops in reactors and the efficiency of two-phase separators.

## 4. Conclusion
The proposed system provides a feasible pathway for ISRU-based polymer production. Beyond ethylene for HDPE (construction material), the plant produces oxygen and liquid propellant (methane), supporting both habitat construction and life support systems.