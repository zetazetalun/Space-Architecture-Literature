# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker
**Journal:** Advances in Space Research 73 (2024) 2674–2684

## Abstract
A main shift in the competitive landscape of technology development is in 3D printing of complex articles made of variety of materials due to faster manufacturing and less human error in the production. In fact, it seems to be a viable candidate for the construction of structures for terrestrial and extraterrestrial life in future. This study focused on the preliminary design of a self-sustaining mini ethylene production plant from Martian atmosphere with scale-out architecture. UniSIM was integrated with MATLAB to design the plant at low gravity. Ethylene capacity was found as 17.71 tons/year for 100 modules.

## 1. Introduction
Humanity aims to build self-sustaining civilizations beyond Earth. Key chemicals must be produced under micro-gravity or low-gravity environments to sustain life and construction. Constructing 3D printed habitats on Mars necessitates the use of planet-made polymers like high-density polyethylene (HDPE).

## 2. Methodology
Honeywell UniSIM Design R460 was used as the simulation environment, integrated with MATLAB via CAPE-OPEN extension to handle low-gravity impacts on unit operations. The process includes:
- **Martian Dust Removal:** Using screen roll filters and electrostatic precipitators.
- **Methanation Reactor (R-100):** Sabatier reaction and reverse water gas shift.
- **Purification:** Using condensers (C-100) and two-phase separators (CS-100/101).
- **Ethylene Production Reactor (R-101):** Oxidative methane coupling.

## 3. Results and Discussion
- **Dust Removal:** Approximately 165.89 kg/s of Martian dust exists in the raw inlet gas. Filters collect particles ranging from 0.2 to 6 microns.
- **Methanation:** Single-pass CO2 conversion reached 32%. Methane production capacity is 92.48 tons/year for 100 modules.
- **Separation:** Helical separators were designed to achieve 6g of acceleration to overcome low Martian gravity.
- **Ethylene Production:** 100 modules produce 17.71 tons/year of ethylene.
- **Power Consumption:** Each module requires 4.47 kW, primarily covered by the Static Feed Electrolysis Module (76.50%).

| Specification | CS-100 | CS-101 |
|---|---|---|
| Length of tube (m) | 1.402 | 0.507 |
| Diameter of tube (m) | 0.01 | 0.006 |
| Diameter of coil (m) | 0.0041 | 0.0018 |
| Number of holes | 2803 | 1268 |

## 4. Conclusion
The study demonstrates the feasibility of a modular, self-sustaining plant on Mars. The system provides ethylene for HDPE production (3D printing material), liquid propellant (methane), oxygen, and water.