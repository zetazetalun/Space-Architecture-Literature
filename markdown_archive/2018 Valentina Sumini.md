# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck  
**Publication:** Earth and Space 2018, ASCE

## Abstract
Future space habitat structures must protect occupants in extreme environments. Due to high transportation costs from Earth, recent efforts focus on Earth-independent designs using local regolith-based materials. This research investigates spherical regolith-based concrete shells with carbon fiber polymer reinforcement. A multi-objective optimization approach (Pareto optimization) is used to minimize transportation and construction costs and minimize the probability of loss due to radiation and micrometeorites. Results indicate that ISRU-based reinforced concrete is a valuable future investment for lunar and Martian surface habitats.

## Introduction
Habitat design is driven by resource availability and transportation capacity. On the Moon, habitats must shelter occupants from severe temperature cycles, high vacuum, micrometeorites, and high radiation (solar wind, solar flares, and Galactic Cosmic Rays). A regolith shelter is considered a meaningful solution to these challenges.

## Concepts and Materials
### Lunar Concrete
ISRU exploits lunar resources to reduce fuel requirements for take-off. Structural design must account for brittle fracture, out-gassing, and thermal fatigue. Literature examples include Foster + Partners' inflatable/regolith combination and D-Shape 3D printing technology.

### Structural Options
- **Aluminum Shell:** Represents the typical system used for the International Space Station (ISS) modules.
- **Reinforced Concrete Shell:** A spherical dome structure using regolith with an inner bladder layer for airtightness and carbon fiber reinforced polymers (CFRP) to resist tension and impact.

### Material Properties (Table 1)
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8 * 10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280 * 10⁶ |

## Methodology
The optimization defines three variables: interior radius ($X_1$), tensile layer thickness ($X_2$), and concrete layer thickness ($X_3$). Feasible geometries are evaluated against five objectives:
1. **Pressurized Volume ($J_1$):** Maximizing usable space.
2. **Terrestrial Material Mass ($J_2$):** Minimizing mass transported from Earth (CFRP, additives).
3. **Lunar Material Mass ($J_3$):** Proxy for in-situ construction complexity.
4. **Impact Protection ($J_4$):** Maximizing resistance to micrometeoroids (Fish-Summers and Petry formulas).
5. **Radiation Protection ($J_5$):** Minimizing annual dose equivalent from GCR.

## Results and Discussion
Results for a 180-day mission show that CFRP-reinforced concrete reduces payload from Earth while greatly increasing protection. While the aluminum habitat is limited by tensile thickness, the concrete case reduces GCR doses more effectively (down to 5.8 cSv compared to 7.5 cSv for aluminum).

### Possible Habitat Configurations (Table 2)
| Variable/Objective | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload | 5435 | 3059 | kg |
| Concrete | 0 | 36283 | kg |
| Meteoroid | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Pareto optimization allows designers to understand trade-offs without arbitrary weighting. Reinforced concrete is a viable material for investigation, providing superior protection and reduced Earth-reliance.