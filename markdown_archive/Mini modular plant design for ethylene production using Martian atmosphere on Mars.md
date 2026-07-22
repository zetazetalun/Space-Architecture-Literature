# Mini modular plant design for ethylene production using Martian atmosphere on Mars

**Authors:** Ozgun Deliismail, Erol Seker
**Journal:** Advances in Space Research 73 (2024) 2674–2684
**Available online:** 15 December 2023

## Abstract
A main shift in the competitive landscape of technology development is in 3D printing of complex articles made of variety of materials due to faster manufacturing and less human error in the production. In fact, it seems to be a viable candidate for the construction of structures for terrestrial and extraterrestrial life in future. Thus, new or damaged equipment in space explorations could be replaced instantly, and habitats could be manufactured using 3D printing in varying gravitational fields in the solar system. Among 3D printing materials, HDPE is commonly used in the projects, such as a prototype manufacturing or pipes or damp-proof membrane. This study initially focused on the preliminary design of the self-sustaining mini ethylene production plant from Martian atmosphere with scale-out architecture. UniSIM was integrated with MATLAB via CAPE-OPEN extension to design mini-ethylene production plant at low gravity. Ethylene capacity was found as 17.71 tons/year for 100 modules.

## 1. Introduction
Space exploration and colonization necessitates certain chemicals being produced during the voyage because it is not feasible to take all the supplies from Earth. Key chemicals must be produced under micro-gravity environment. Constructing 3D printed habitats on Mars necessitates the use of planet-made polymers, like high-density polyethylene (HDPE). The atmosphere of Mars, primarily composed of CO2, presents a favorable opportunity for on-site production of HDPE through ethylene synthesis and subsequent polymerization.

## 2. Modelling and Process Flow
The self-sustaining mini ethylene production plant was designed to integrate reactor and purification units in one module. A scale-out approach was adopted, where 100 modules produce 17.71 tons/year of ethylene.

### Primary Process Units:
- **ESP-100:** Electrostatic Precipitator for Martian dust removal.
- **R-100:** Methanation (Sabatier) reactor producing methane.
- **C-100:** Condenser for water removal (water is recycled for electrolysis).
- **CS-100/101:** Helical two-phase separators for liquid/gas separation under low gravity.
- **R-101:** Oxidative methane coupling reactor producing ethylene.

## 3. Results and Discussion

### 3.1. Martian Dust Removal
- Approximately 165.89 kg/s Martian dust exists in the inlet of 6 kg/h CO2 fed to a module.
- Wire-cylinder electrostatic precipitator was designed to collect dust (0.2–2.4 μm).
- Electric field: 0.37 kV/cm; Migration velocity: 248.52 m/s.

### 3.2. Methanation Reactor (R-100)
- Temperature: 400 °C; Pressure: 12.56 atm.
- Catalyst: Ni/MgAl2O4.
- Methane production capacity: 92.48 tons/year (for 100 modules).

### 3.3. Ethylene Production Reactor (R-101)
- Operating conditions: 850 °C and 9.59 atm.
- Catalyst: Li/MgO.
- Ethylene capacity: 17.71 tons/year (for 100 modules).

### 3.4. Power and Cost
- Net power requirement per module: 4.47 kW.
- 76.50% of power covered by Static Feed Electrolysis Module.
- Anticipated reactor (R-100) cost: $130,981 (stainless-steel).
- Anticipated condenser (C-100) cost: $86,100 (titanium).

## 4. Conclusion
The study successfully integrated UniSIM and MATLAB to simulate a mini-ethylene production plant under Martian gravity. The modular design allows for flexibility and scalability in supporting Mars colonization efforts, providing feedstock for 3D printing, fuel, and life support systems.