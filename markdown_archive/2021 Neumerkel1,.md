# Design of an Autonomously Deployable Mars Habitat

**Authors:** Rudolf Walther Erdem Neumerkel, Miruna Vecerdi, Sandra Häuplik-Meusburger  
**Affiliation:** TU Wien, 1040, Austria  
**Conference:** 50th International Conference on Environmental Systems (ICES-2021-398), 12-15 July 2021

## Abstract
This paper presents a proposal for the design of an autonomously deployable habitat for a long-duration manned mission on Mars. Key drivers in the design were the payload and volume constraints of Starship (SpaceX) and addressing habitability challenges implied by Martian conditions. The habitat is conceived to be transported in compacted form and expand to a habitable volume by autonomously deploying after being placed on the Martian surface.

## I. Introduction
The Martian environment requires enclosures that address low pressure, low gravity, extreme temperatures, MMOD impacts, and radiation. The proposed solution uses a deployable architecture to fit within rocket fairings while expanding to a functional pressurized enclosure on-site.

## II. Design Method
The design integrates four primary systems:
1.  **Casing:** A protective rigid shell divided into 3 identical parts with docking interfaces.
2.  **Telescopic Core:** The primary rigid structure housing technical units, sanitary fittings, and a water-tank-based cupola for radiation protection.
3.  **Expanding Girders:** Radially oriented foldable girders that push the casing elements outward using torsional and compressive springs.
4.  **Inflatable Membrane:** A multi-layered soft structure for pressurization and protection.

### Membrane Layers
- **Interior Layer:** Nomex (flame-resistant), air bladders (CepacHD200), and Kevlar felt.
- **Middle Layer:** Woven Kevlar belts (restraint layer for pressure loads).
- **Outer Layer:** Dust protection and a fillable chamber for loose regolith (up to 100cm thick).

### Pressure Calculations
Atmospheric and dead weight pressure are calculated to be only 7.8% of the internal pressure (1 bar), allowing the regolith layer to be easily supported by the internal atmosphere.

**Equation (1):**
- $P_{regolith} = \rho_{bulk,max} \cdot t_{regolith} \cdot a_{Mars} = 1910 \, kg/m^3 \cdot 1m \cdot 3.721 \, m/s^2 = 7107.11 \, Pa$
- $P_{atmosphere} = 651.8 \, Pa$
- $P_{deadweight,membrane} = 10.98 \, Pa$
- $\sum P_i = 7769.1 \, Pa$
- $P_{internal} = 100000 \, Pa$

## III. Arrival and Deployment Choreography
The design allows two units to be stacked within a Starship fairing. The total weight per habitat is approximately 28t. Deployment involves unlocking casing elements, expanding girders, and inflating the membrane until the core frame has doubled in height and internal pressure reaches 1 bar. Regolith filling is performed robotically post-deployment.

## Table 1. Listing of Components and Mass Estimation

| Component | Material | Volume [m³] | Density [kg/m³] | Mass [kg] |
| :--- | :--- | :--- | :--- | :--- |
| core frame | aluminium | 0.26 | 2740 | 712.40 |
| cupola structure | aluminium | 0.13 | 2740 | 356.20 |
| cupola protection | aluminium | 0.35 | 2740 | 959.00 |
| cupola glass | glass | 0.15 | 2500 | 375.00 |
| base | aluminium | 0.42 | 2740 | 1150.80 |
| technical units | GF r. polymer | 0.80 | 1800 | 1440.00 |
| girders | titanium | 0.25 | 4506 | 1126.50 |
| floor | PE | 3.05 | 940 | 2867.00 |
| casing shell | aluminium | 1.82 | 2740 | 4986.80 |
| membrane struct. layer | kevlar | 2.34 | 1400 | 3279.50 |
| membrane ext. layer | kevlar | 1.76 | 1400 | 2459.10 |
| **TOTAL** | | | | **27988.53** |

## V. Conclusion
The design successfully balances transportation constraints with habitable volume requirements, achieving an expandability factor of 5 (180 m³ to 921 m³). Future work includes refining stowed configurations and testing deployment actuators under realistic transportation loads.