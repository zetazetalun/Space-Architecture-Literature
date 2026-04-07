# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck  
**Publication:** Earth and Space 2018, ASCE

## Abstract
Future space habitat requirements are defined by the ability to protect occupants in extreme environments. Due to high transportation costs, research focuses on Earth-independent structural designs using local regolith-based materials. This study explores architectures using spherical regolith-based concrete shells with carbon fiber polymer (CFRP) reinforcement. A multi-objective optimization approach (Pareto optimization) is used to minimize transportation and construction costs while maximizing protection against radiation and micrometeorite events. Results indicate that ISRU-based reinforced concrete is a viable investment for lunar and Martian settlements.

## Introduction
Habitat design is driven by resource availability and transportation capacity. For extraterrestrial sustainability, local materials are essential. This research builds on prior studies of pressurized aluminum domes and inflatable structures by applying multi-objective evaluation to regolith-based concrete habitats.

## Materials and Concepts
### Lunar Concrete
Lunar concrete is proposed to shelter astronauts from harsh temperature cycles, high vacuum, and radiation. The research considers a spherical dome structure made of regolith with an inner bladder layer for airtightness and CFRP reinforcement to resist tension from internal pressure.

### Material Properties

| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8 * 10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280 * 10⁶ |

## Methodology
The evaluation uses five primary objectives:
1. **Pressurized Volume:** Maximize usable internal space.
2. **Terrestrial Material Mass:** Minimize mass launched from Earth (CFRP reinforcement, additives).
3. **Lunar Material Mass:** Minimize processed lunar material (proxy for construction cost/complexity).
4. **Impact Protection:** Maximize resistance to micrometeoroids (Probability of No Penetration over 5 years).
5. **Radiation Protection:** Minimize annual dose equivalent from Galactic Cosmic Rays (GCR).

## Results
Pareto optimal solutions show that while concrete habitats require more lunar mass, they drastically reduce the mass required from Earth for a given volume and provide superior protection. 

### Comparison of Habitat Configurations

| Variable/Objective | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (from Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Meteoroid Resistance | 2.94e-6 | 1.04e-5 | kg |
| Radiation Dose | 15.3 | 9.7 | cSv |

## Discussion and Conclusion
Reinforced concrete habitats can satisfy mission performance goals (e.g., volume for 4 crew, 180 days) within the payload limits of launch vehicles like the SLS. While aluminum shells struggle to meet all protection and volume goals simultaneously in the analyzed scenario, the concrete designer has multiple options that satisfy all constraints. Future work will refine the quantification of costs and include alternative geometries.