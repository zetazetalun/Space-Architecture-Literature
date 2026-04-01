# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini; Sam Wald; Caitlin Mueller; Claudio Chesi; and Olivier L. de Weck

## Abstract
Much like their Earth-based counterparts, the requirements of future space habitat structures can be defined by their ability to protect their occupants and provide usable space to live and work in an extreme, isolated environment. Due to the high cost of transporting resources off of Earth’s surface, recent efforts focus on developing increasingly Earth-independent structural designs. These new designs use local regolith-based materials as a possible solution for long-term extraterrestrial sustainability. With a focus on an Earth-independent habitat, this research looks at architectures that use spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The research approach is to formulate the structural design problem as a multi-objective optimization of the habitat shell. The objectives that apply to the shell geometry and cross section include the minimization of transportation and construction costs, and the minimization of the probability of loss due to radiation and micrometeorite events. Direct trade-offs arise. The multi-objective optimization applies Pareto optimization to determine which design elements or options afford the greatest effectiveness or efficiency. The authors examine candidate design solutions based on priorities and performance thresholds which indicate that ISRU-based reinforced concrete may be a valuable future investment. While the cases presented here are limited to lunar surface systems, both the general architectures and the methodology for analysis and design are applicable to future Mars settlements.

## Introduction
Designing a structure for construction on the lunar surface includes several topics, such as the relationships between severe lunar temperature cycles and structural and material fatigue; structural sensitivity to temperature differentials; and the very low-temperature effects and possibility of brittle fractures. Moreover, due to the virtual absence of atmosphere and magnetic field, space radiation on the Moon is far higher than on Earth. In order to protect the inner core of the outpost from solar wind, solar flares and Galactic Cosmic Rays (GCR), a regolith shelter is considered the most meaningful solution.

## Concepts and Materials

### Lunar Concrete for Habitats
The establishment of a manned human colony on the Moon (or on Mars) will need some form of infrastructure to shelter the astronauts and scientific instrumentations from a very harsh environment. Building a robotic fabricated habitat would reduce the risk of radiation exposure for construction workers.

### Material Properties
Based on potential materials of interest in the family of ceramics, the expected material strength for the regolith is assumed to be between 10 and 100 MPa with a density between 1000 to 3000 kg/m³.

**Table 1. Material properties**

| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10^6 |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10^6 |

## Methodology
Each of the spherical geometries is defined by a set of three variables:
1. **Interior Radius (X_1):** Overall size of the habitat.
2. **Tensile Layer Thickness (X_2):** Effective thickness of the CFRP reinforcing members.
3. **Concrete Layer Thickness (X_3):** Depth of the regolith concrete from interior to exterior.

### Objectives Used for Evaluation
1. **Pressurized Volume:** Maximizing usable space.
2. **Terrestrial Material Mass:** Minimizing mass brought from Earth (CFRP and cement additives).
3. **Lunar Material Mass:** Proxies for complexity of processing and construction in-situ.
4. **Impact Protection:** Goal to afford 0.993 "Probability of No Penetration" (PMP) over 5 years.
5. **Radiation Protection:** Minimizing GCR dose using equivalent shielding depth.

## Results
The results show that reinforced concrete habitats significantly increase meteoroid and radiation protection compared to the aluminum case. While the minimum dose from GCR in an aluminum habitat is approximately 7.5 cSv, the concrete case minimum is reduced to 5.8 cSv at 0.3 meters thickness. More importantly, reinforced concrete can stop micrometeoroids of masses orders of magnitude greater than what is possible with aluminum shells within analyzed ranges.

**Table 2. Possible habitat configurations for aluminum and concrete typologies**

| Variable/Objective | Aluminum | Concrete | Unit |
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
Space habitat structures must serve multiple functions. Pareto optimization allows decision makers to understand the trade-offs between these functions. Reinforced concrete is indicated as a valuable material for further investigation, as it provides a path to satisfying all mission performance goals (volume, mass, and protection) where baseline aluminum structures may fall short.