# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker
**Published in:** Advances in Space Research 73 (2024) 2674–2684
**DOI:** 10.1016/j.asr.2023.12.028

## Abstract
A main shift in the competitive landscape of technology development is in 3D printing of complex articles made of variety of materials due to faster manufacturing and less human error in the production. In fact, it seems to be a viable candidate for the construction of structures for terrestrial and extraterrestrial life in future. Thus, new or damaged equipment in space explorations could be replaced instantly, and habitats could be manufactured using 3D printing in varying gravitational fields in the solar system. Among 3D printing materials, HDPE is commonly used in the projects, such as a prototype manufacturing or pipes or damp-proof membrane. This study initially focused on the preliminary design of the self-sustaining mini ethylene production plant from Martian atmosphere with scale-out architecture. UniSIM was integrated with MATLAB via CAPE-OPEN extension to design mini-ethylene production plant at low gravity. Ethylene capacity was found as 17.71 tons/year for 100 modules.

## 1. Introduction
Space exploration and colonization necessitates certain chemicals being produced during the voyage because it is not feasible to take all the supplies from Earth to the space station or other planets. In the realm of space exploration studies centered on the Moon, Mars emerges as a compelling candidate for future missions focused on exploring the potential exploitation of planetary resources. Constructing 3D printed habitats on Mars necessitates the use of planet-made polymers, like high-density polyethylene (HDPE).

Naser (2019) featured the polymeric concretes as a first choice for Lunar and Martian construction applications since they have promising durability characteristics, reduced water requirement and the ability to directly utilize surface regolith. In addition to the polymers, such as polyester, epoxy, polypropylene and polyimide, high density polyethylene (HDPE) has gained great attention because it can be used in robotic extrusion of inflatable structures in the Martian environment or as a binding agent especially in the production of concretes for future habitats.

## 2. Modelling
The self-sustaining mini ethylene production plant was designed to integrate reactor and purification units in one module. One mini-plant module could fit in 2.83 m × 1.44 m × 1.62 m container. The process involves:
1. Martian Dust Removal (ESP-100)
2. Methanation Reactor (R-100) using Sabatier reaction.
3. Condenser (C-100) to remove water.
4. Two-phase separators (CS-100, CS-101).
5. Ethylene Production Reactor (R-101) via oxidative methane coupling.

### Table 1: Inlet specifications of methanation reactor (R-100)
| Parameter | Value |
| :--- | :--- |
| Temperature (°C) | 400 |
| Pressure (atm) | 12.56 |
| Mass Flow (kg/h) | 6.566 |

### Table 4: Specifications of ethylene production reactor (R-101)
| Parameter | Value |
| :--- | :--- |
| Temperature (°C) | 850 |
| Pressure (atm) | 9.59 |
| Mass Flow (kg/h) | 0.3682 |

## 3. Results and Discussion
- **Ethylene Production:** Total ethylene production capacity was found as 17.71 tons/year using 100 modules from Martian atmosphere feed containing 6 kg/h carbon dioxide for each module.
- **Power Requirement:** For one module, net power requirement was calculated to be 4.47 kW, 76.50% of which was covered by the Static Feed Electrolysis Module.
- **Co-products:** The system provides additional oxygen, liquid propellant (methane), and water for electrolysis.

## 4. Conclusion
Honeywell UniSIM Design R460 was used to simulate the preliminary design of a self-sustaining mini ethylene production plant from Martian atmosphere. The main units were modelled under lower gravity. The system contains integrated methane and ethylene production and gas purification units embedded in a module to produce 17.71 tons ethylene per year using 100 modules. The module could easily be adapted for possible feedstock to produce other chemicals under such a low gravity.