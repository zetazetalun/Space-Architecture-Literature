# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker
**Journal:** Advances in Space Research 73 (2024) 2674–2684
**Received:** 19 December 2022; **Accepted:** 11 December 2023

## Abstract
A main shift in technology development is 3D printing of complex articles from a variety of materials, making it a viable candidate for constructing structures for extraterrestrial life. This study focuses on the preliminary design of a self-sustaining mini ethylene production plant from the Martian atmosphere using a scale-out architecture. UniSIM was integrated with MATLAB to design the plant at low gravity. The ethylene capacity was found to be 17.71 tons/year for 100 modules.

## 1. Introduction
Space exploration and colonization necessitate chemicals being produced in-situ as it is not feasible to transport all supplies from Earth. Key chemicals must be produced under micro-gravity or partial gravity environments. On Mars, the atmosphere (primarily CO2) provides an opportunity for on-site production of HDPE, which is a significant material for robotic extrusion of inflatable structures and 3D printing habitats.

## 2. Modeling
The design integrates reactors and purification units into a single module. A scale-out approach is used where one mini-plant module fits in a 2.83 m x 1.44 m x 1.62 m container. Honeywell UniSIM Design R460 was used for simulation, integrated with MATLAB via CAPE-OPEN to account for Martian gravitational acceleration (3.71 m/s²).

### 2.1. Process Components
- **Dust Removal (ESP-100):** Uses screen roll filters and electrostatic precipitators to remove Martian dust (0.2 to 6 microns).
- **Methanation Reactor (R-100):** Sabatier reaction and RWGS using Ni/MgAl2O4 catalyst to produce methane.
- **Condenser (C-100):** Separates water from the gas mixture using convective condensation.
- **Two-phase Separators (CS-100, CS-101):** Helical separators designed for lower gravity to separate liquid and gas phases.
- **Ethylene Production Reactor (R-101):** Oxidative methane coupling (OCM) over Li/MgO catalyst to produce ethylene.

## 3. Results and Discussion
- **Ethylene Capacity:** 17.71 tons/year for a system of 100 modules.
- **Power Requirement:** 4.47 kW per module, with 76.50% covered by the Static Feed Electrolysis Module.
- **Reactor Dimensions:** The R-100 reactor has a length of 140 cm and a diameter of 31.6 cm.
- **Mass Flow:** Ethylene production requires a Martian atmosphere feed containing 6 kg/h CO2 per module.

## 4. Conclusion
The study demonstrates the feasibility of a modular, self-sustaining plant for ethylene production on Mars. The system integrates methane production and oxidative coupling to generate ethylene for HDPE manufacturing, alongside oxygen and liquid propellant as byproducts.