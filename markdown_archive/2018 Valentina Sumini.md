# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Published in:** Earth and Space 2018 (ASCE)

## Abstract
Future space habitat structures must protect occupants in extreme environments. Due to high transport costs from Earth, research focuses on Earth-independent designs using local regolith-based materials. This study explores architectures using spherical regolith-based concrete shells reinforced with carbon fiber polymers. A multi-objective optimization (Pareto optimization) is used to minimize transportation/construction costs and minimize risk from radiation and micrometeorites. Results indicate that ISRU-based reinforced concrete is a valuable investment for lunar and potentially Martian settlements.

## Introduction
Habitat design is driven by resource availability, transportation capacity, and the need for protection from harsh environments. The high cost of Earth-to-Moon transport (estimated at US$ 2 million per brick) necessitates In Situ Resource Utilization (ISRU).

## Concepts and Materials
- **Aluminum Shell:** Baseline case representing ISS-style habitation modules.
- **Reinforced Concrete Shell:** Spherical dome structure using regolith as the primary material, reinforced with Carbon Fiber Reinforced Polymers (CFRP) to handle tension from internal pressurization.

### Material Properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
The study uses five objectives for evaluation:
1. **Pressurized Volume (J1):** Maximizing usable space.
2. **Terrestrial Material Mass (J2):** Minimizing mass launched from Earth (reinforcement, additives).
3. **Lunar Material Mass (J3):** Proxy for ISRU processing costs.
4. **Impact Protection (J4):** Resistance to micrometeoroids (Probability of No Penetration over 5 years).
5. **Radiation Protection (J5):** Shielding from Galactic Cosmic Rays (GCR).

## Results
The analysis compared aluminum and reinforced concrete designs across variable ranges: Radius (2-6m), Tensile Thickness (0.01-0.1m), and Concrete Thickness (0-0.3m).

### Comparison Table
| Variable/Objective | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (from Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Meteoroid (Mass limit) | 2.94e-6 | 1.04e-5 | kg |
| Radiation Dose | 15.3 | 9.7 | cSv |

## Conclusion
Pareto optimization reveals that reinforced concrete shells can satisfy habitat performance goals (radiation/micrometeoroid protection and volume) more efficiently than aluminum shells under single-lander payload constraints. Reinforced concrete should be prioritized for further investigation in lunar habitat construction.