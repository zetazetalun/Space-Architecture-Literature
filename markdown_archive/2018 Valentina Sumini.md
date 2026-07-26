# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Publication:** Earth and Space 2018, ASCE

## Abstract
Future space habitat structures must protect occupants in extreme environments. This research focuses on Earth-independent habitats using spherical regolith-based concrete shells with carbon fiber polymer (CFRP) reinforcement. A multi-objective optimization approach is used to minimize transportation/construction costs and minimize loss due to radiation and micrometeorites. Results indicate that ISRU-based reinforced concrete is a valuable future investment for Lunar and Martian settlements.

## Introduction
Resource availability and transportation capacity drive space habitat design. To reduce the high cost of shipping materials (up to $2 million per brick), ISRU-based designs are necessary. The paper explores regolith shelters as solutions for radiation (GCR, SPE) and micrometeoroid protection.

## Lunar Habitats: Concepts and Materials
- **Lunar Concrete:** Exploits local regolith and potentially polar water. Challenges include temperature cycles and high vacuum effects.
- **Aluminum Shell:** Represents the baseline (ISS-style modules).
- **Reinforced Concrete Shell:** Uses a spherical dome of regolith with an inner bladder and CFRP reinforcement to resist tension from internal pressurization.

### Table 1. Material properties
| Property | Units | Value |
|---|---|---|
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
The study uses five objectives for Pareto optimization:
1. Pressurized Volume (Maximize)
2. Terrestrial Material Mass (Minimize)
3. Lunar Material Mass (Minimize)
4. Impact Protection (Maximize M_impact resisted)
5. Radiation Protection (Minimize Dose)

**Design Variables:**
- X1: Interior Radius (2-6m)
- X2: Tensile Layer Thickness (0.01-0.1m)
- X3: Concrete Layer Thickness (0-0.3m)

## Results and Discussion
Parallel coordinates plots demonstrate trade-offs. Reinforced concrete shells significantly increase protection over aluminum. While aluminum habitats are limited to a minimum GCR dose of ~7.5 cSv, the concrete case (0.3m thickness) reduces this to 5.8 cSv and provides vastly superior micrometeoroid stopping power.

### Table 2. Possible habitat configurations (Optimized)
| Parameter | Aluminum | Concrete | Unit |
|---|---|---|---|
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload | 5435 | 3059 | kg |
| Concrete | 0 | 36283 | kg |
| Meteoroid (mass resisted) | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Pareto optimization allows decision-makers to understand trade-offs. Reinforced concrete is a superior material for lunar habitats when considering long-term safety and Earth-independence.