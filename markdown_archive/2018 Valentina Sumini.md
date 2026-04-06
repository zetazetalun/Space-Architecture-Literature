# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck**

## Abstract
Much like their Earth-based counterparts, the requirements of future space habitat structures can be defined by their ability to protect their occupants and provide usable space to live and work in an extreme, isolated environment. Due to the high cost of transporting resources off of Earth’s surface, recent efforts focus on developing increasingly Earth-independent structural designs. These new designs use local regolith-based materials as a possible solution for long-term extraterrestrial sustainability. This research looks at architectures that use spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The research approach is to formulate the structural design problem as a multi-objective optimization of the habitat shell. The objectives include the minimization of transportation and construction costs, and the minimization of the probability of loss due to radiation and micrometeorite events.

## Introduction
Humans have relied on structures to house and protect them for thousands of years. Designing a structure for construction on the lunar surface includes several topics, such as relationships between severe lunar temperature cycles and structural and material fatigue, out-gassing in high vacuum, and the lack of magnetic fields resulting in high space radiation. A regolith shelter is considered the most meaningful solution to protect against solar wind and Galactic Cosmic Rays (GCR).

## Lunar Habitats: Concepts and Materials
- **Aluminum Shell:** Baseline case representing the typical system used for ISS modules.
- **Reinforced Concrete Shell:** Spherical dome structure using regolith. An inner bladder layer is in contact with the concrete shell to resist internal pressure. Reinforcement is provided by carbon fiber reinforced polymers (CFRP).

### Table 1: Material Properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
Each spherical geometry is defined by three variables:
1. **Interior Radius (X_1)**: Defines the overall size.
2. **Tensile Layer Thickness (X_2)**: Reinforcement material per linear length.
3. **Concrete Layer Thickness (X_3)**: Depth of concrete from interior to exterior.

### Evaluation Objectives
- **Pressurized Volume (J1)**: Maximizing usable space.
- **Terrestrial Material Mass (J2)**: Minimizing mass brought from Earth (CFRP and cement additives).
- **Lunar Material Mass (J3)**: Proxy for ISRU processing costs.
- **Impact Protection (J4)**: Resistance to micrometeoroid penetration (0.993 Probability of No Penetration over 5 years).
- **Radiation Protection (J5)**: Minimizing the Radiation Dose Equivalent from GCR.

## Results
The results demonstrate that reinforced concrete habitats can satisfy mission requirements for a 180-day mission where aluminum shells might fail specific safety thresholds. Reinforced concrete significantly increases protection against meteoroids and radiation compared to the aluminum baseline.

### Table 2: Possible habitat configurations for aluminum and concrete typologies
| Parameter | Aluminum | Concrete | Unit |
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
Pareto optimization allows decision-makers to understand trade-offs between performance functions. Reinforced concrete is a valuable material for lunar habitats, offering superior protection and larger habitable volumes within terrestrial mass constraints.