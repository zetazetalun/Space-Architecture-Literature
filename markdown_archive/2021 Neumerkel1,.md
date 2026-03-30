# Design of an Autonomously Deployable Mars Habitat

**Conference Paper** · July 2021  
**Authors:** Rudolf Walther Erdem Neumerkel, Miruna Vecerdi, Sandra Häuplik-Meusburger  
**Affiliation:** TU Wien, 1040, Austria  
**Publication:** 50th International Conference on Environmental Systems (ICES-2021-398)

## Abstract
This paper presents a proposal for the design of an autonomously deployable habitat for a long-duration manned mission on Mars. Key drivers in the design were the payload and volume constraints of Starship and addressing habitability challenges implied by Martian conditions. The habitat is conceived to be transported in compacted form and to expand to a habitable volume by autonomously deploying after being placed on the Martian surface. For this, the integration of several different kinetic structures is proposed: a protective casing, a vertically sliding core, radially expanding girders and an inflatable membrane. 

## I. Introduction
The Martian environment is characterized by extremely low atmospheric pressure, low gravity, extreme temperatures, micrometeoroid and orbital debris (MMOD) impacts, and heavy radiation. A solution for dealing with the restricted fairing dimensions of current launch vehicles is making use of a deployable habitat architecture. Once placed on the Martian surface, the habitat must autonomously expand to a habitable volume, providing a pressurized enclosure, thermal management, and radiation protection.

## II. Design Method
The design integrates several elements:
1.  **Protective Casing:** A rigid shell divided into 3 identical parts that interlock during transportation. It includes docking interfaces for egress/ingress and windows for psychological wellbeing.
2.  **Telescopic Core:** The primary rigid structure with a hexagonal base, containing technical units (sanitary, kitchen, hydroponics) and a water tank at the top for radiation protection and natural light (cupola).
3.  **Expanding Girders:** Radially oriented foldable girders that push the casing elements outward using torsional and compressive springs.
4.  **Inflatable Membrane:** A multi-layered system (Nomex, CepacHD200, Kevlar) that creates the pressurized environment. The outermost layer is a fillable chamber for loose regolith (up to 100cm thickness) for radiation and MMOD protection.

### II.D. Regolith Calculations
Atmospheric and dead weight pressure are calculated as only 7.8% of the internal pressure (1 bar). Thus, the internal pressure can easily support the regolith layer.
- $P_{regolith} = 7107.11 \text{ Pa}$
- $P_{internal} = 100,000 \text{ Pa}$

## III. Arrival and Deployment Choreography
The design allows for two units to be transported within the SpaceX Starship cargo space (100t capacity). Total weight of one habitat is approximately 28t. 
- **Step 1:** Habitat placed at location.
- **Step 2:** Casing elements unlock; girders push outwards.
- **Step 3:** Membrane begins inflation, causing the core to slide vertically.
- **Step 4:** Robotic filling of the outer membrane with regolith.
- **Expansion Factor:** From 180m³ (compacted) to 921m³ (pressurized volume).

## Table 1. Listing of Components

| Component | Material | Volume [m³] | Density [kg/m³] | Mass [kg] |
| :--- | :--- | :--- | :--- | :--- |
| core frame | aluminium | 0.26 | 2740 | 712.40 |
| cupola structure | aluminium | 0.13 | 2740 | 356.20 |
| cupola glass | glass | 0.15 | 2500 | 375.00 |
| base | aluminium | 0.42 | 2740 | 1150.80 |
| watertank | PE | 0.16 | 940 | 150.40 |
| technical units | GF r. polymer | 0.80 | 1800 | 1440.00 |
| girders | titanium | 0.25 | 4506 | 1126.50 |
| floor | PE | 3.05 | 940 | 2867.00 |
| casing shell | aluminium | 1.82 | 2740 | 4986.80 |
| membrane struct. layer | kevlar | 2.34 | 1400 | 3279.50 |
| membrane ext. layer | kevlar | 1.76 | 1400 | 2459.10 |
| **TOTAL** | | | | **27988.53** |

## IV. Architectural Quality
The floorplan is divided into two zones: social interaction (facing the kitchen/atrium) and quiet areas (crew quarters). The core acts as a vertical and horizontal circulation hub. Natural light is provided through the cupola and casing windows.

## V. Conclusion
The study proposes a hybrid deployable system that addresses transportation constraints and environmental challenges on Mars. The automated regolith-filling method is presented as a faster and lower-risk alternative to 3D sintering for shielding.