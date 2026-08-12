# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker  
**Journal:** Advances in Space Research 73 (2024) 2674–2684  
**DOI:** 10.1016/j.asr.2023.12.028

## Abstract
A main shift in the competitive landscape of technology development is in 3D printing of complex articles made of variety of materials due to faster manufacturing and less human error in the production. In fact, it seems to be a viable candidate for the construction of structures for terrestrial and extraterrestrial life in future. Thus, new or damaged equipment in space explorations could be replaced instantly, and habitats could be manufactured using 3D printing in varying gravitational fields in the solar system. Among 3D printing materials, HDPE is commonly used in the projects, such as a prototype manufacturing or pipes or damp-proof membrane. This study initially focused on the preliminary design of the self-sustaining mini ethylene production plant from Martian atmosphere with scale-out architecture. UniSIM® was integrated with MATLAB® via CAPE-OPEN extension to design mini-ethylene production plant at low gravity. Ethylene capacity was found as 17.71 tons/year for 100 modules.

## 1. Introduction
Space exploration and colonization necessitates certain chemicals being produced during the voyage or on-site, as it is not feasible to take all supplies from Earth. Constructing 3D printed habitats on Mars necessitates the use of planet-made polymers, like high-density polyethylene (HDPE). The Martian atmosphere, primarily composed of CO2, provides a favorable opportunity for on-site production of HDPE through ethylene synthesis.

## 2. Methodology & Modeling
The study utilizes Honeywell UniSIM® Design R460 integrated with MATLAB® via CAPE-OPEN to model chemical process units under Martian gravity (0.38g). 

### Key Components of the Plant:
- **Dust Removal (ESP-100):** Electrostatic precipitator to remove Martian dust (0.2 to 2.4 μm).
- **Methanation Reactor (R-100):** Sabatier reaction to produce methane from CO2 and H2.
- **Condenser (C-100):** Separates water for reuse in electrolysis.
- **Two-phase separators (CS-100, CS-101):** Helical separators designed for lower gravity (6g centrifugal acceleration).
- **Ethylene Production Reactor (R-101):** Oxidative methane coupling to produce ethylene.

## 3. Results and Discussion

### Plant Capacity and Logistics:
- **Module Size:** 2.83 m x 1.44 m x 1.62 m.
- **Production Capacity:** 17.71 tons/year of ethylene using 100 modules.
- **Feedstock:** 6 kg/h CO2 per module.
- **Power Requirement:** 4.47 kW per module (76.5% covered by Static Feed Electrolysis Module).

### Material Application:
Ethylene produced is intended as feedstock for HDPE. HDPE can be used in robotic extrusion of inflatable structures or as a binding agent for regolith-based concretes (polymeric concretes).

## 4. Conclusion
The study successfully demonstrates a conceptual design for a modular, self-sustaining ethylene plant on Mars. The modular architecture (scale-out) allows for flexible capacity and high reliability. Produced ethylene supports the long-term goal of autonomous habitat construction using in-situ polymer production.

### Table: Module Specifications
| Parameter | Value |
| :--- | :--- |
| Ethylene Capacity (100 modules) | 17.71 tons/year |
| Methane Production (100 modules) | 92.48 tons/year |
| Power Requirement per module | 4.47 kW |
| Dust Removal Efficiency (MPPS) | 0.2 - 2.4 μm |