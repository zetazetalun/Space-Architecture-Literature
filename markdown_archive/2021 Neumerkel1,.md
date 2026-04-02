# Design of an Autonomously Deployable Mars Habitat

**Conference Paper**  July 2021
**Authors:** Rudolf Walther Erdem Neumerkel, Miruna Vecerdi, Sandra Huplik-Meusburger
**Affiliation:** TU Wien, 1040, Austria

## Abstract
This paper presents a proposal for the design of an autonomously deployable habitat for a long-duration manned mission on Mars. Key drivers in the design were the payload and volume constraints of Starship, the heavy launch vehicle developed by SpaceX and addressing habitability challenges implied by Martian conditions. The habitat is conceived to be transported in compacted form and to expand to a habitable volume by autonomously deploying after being placed on the Martian surface. For this, the integration of several different kinetic structures is proposed: a protective casing, a vertically sliding core, radially expanding girders and an inflatable membrane. A digital parametric model was made with the Rhinoceros3D Grasshopper Plugin and used to compose and analyze the kinematic behavior of the structures. The form-finding and deployment process of the membrane was developed using the Kangaroo physics engine.

## Nomenclature
a = area
CAD = Computer Aided Design
g = dead load
i = index
ISRU = in situ resource utilization
ISS = International Space Station
MMOD = micrometeoroid / orbital debris
NASA = National Aeronautics and Space Administration
P = pressure
Rhino = Rhinoceros3D by Robert McNeel & Associates
t = thickness
TransHab = Transit Habitat
̑ = density

## I. Introduction
The Martian environment offers a challenging and unusual bed for the creation of a human enclosure. It is characterized by extremely low atmospheric pressure with no breathable air, low gravity, extreme temperatures, micrometeoroid and orbital debris (MMOD) impacts and permanent heavy energy radiation. A solution for dealing with the restricted fairing dimensions of the currently developing vehicles is making use of a deployable habitat architecture. We propose a design that has to fit within the fairing of the rocket and withstand launch, ascend and landing loads. On the other hand, once placed on the Martian surface, it has to autonomously expand to a habitable volume.

## II. Design Method
This paper focuses on the development of an integrated deployment mechanism that fulfils transportation constraints. For this, several different elements were integrated:
1.  **Casing:** A protective rigid shell divided into 3 identical parts that interlock during transportation. Each casing part has a docking interface and 1m deep windows.
2.  **Telescopic Core:** The primary rigid structure with a hexagonal base carrying waste and water management. It doubles in height through a vertically sliding inner frame.
3.  **Expanding Girders:** Radially oriented foldable girders connect the core to the casing elements. They initiate deployment using torsional and compressive springs.
4.  **Inflatable Membrane:** A multi-layered structure adapted from TransHab. It includes an interior Nomex layer, air bladders (CepacHD200), Kevlar restraint belts, and a fillable outer chamber for regolith.

### Membrane Pressure Calculations
Atmospheric and dead weight pressure are only 7.8% of the internal pressure (1 bar). Calculations show:
- P_regolith ≈ 7107.11 Pa
- P_atmosphere = 651.8 Pa
- P_deadweight,membrane = 10.98 Pa
- ̓ P_i = 7769.1 Pa
- P_internal = 100000 Pa

## III. Arrival and Deployment Choreography
The design allows two units to be stacked within a SpaceX Starship fairing. 
- **Total Weight:** Approx. 28t per unit.
- **Volume Expansion:** 180m (stowed) to 921m (habitable pressurized volume).
- **Expandability Factor:** Approx. 5.

## IV. Architectural Quality and Benefits
The habitat is designed for a 4-6 person crew for a 2-year mission. The core contains sanitary units and hydroponic greenhouses. Natural light is provided by a cupola containing a water tank (for radiation protection) and side windows in the casing.

## V. Conclusion
The design addresses transportation constraints and the harsh Martian environment through a deployable hybrid structure. Future work should focus on refined simulation of transportation loads and testing the choreography of deployment actuation.