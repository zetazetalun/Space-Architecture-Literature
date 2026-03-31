# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini**; **Sam Wald**; **Caitlin Mueller**; **Claudio Chesi**; and **Olivier L. de Weck**

## ABSTRACT
Much like their Earth-based counterparts, the requirements of future space habitat structures can be defined by their ability to protect their occupants and provide usable space to live and work in an extreme, isolated environment. Due to the high cost of transporting resources off of Earth’s surface, recent efforts focus on developing increasingly Earth-independent structural designs. These new designs use local regolith-based materials as a possible solution for long-term extraterrestrial sustainability. With a focus on an Earth-independent habitat, this research looks at architectures that use spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The research approach is to formulate the structural design problem as a multi-objective optimization of the habitat shell. The objectives that apply to the shell geometry and cross section include the minimization of transportation and construction costs, and the minimization of the probability of loss due to radiation and micrometeorite events. Direct trade-offs arise. The multi-objective optimization applies Pareto optimization to determine which design elements or options afford the greatest effectiveness or efficiency. The authors examine candidate design solutions based on priorities and performance thresholds which indicate that ISRU-based reinforced concrete may be a valuable future investment. While the cases presented here are limited to lunar surface systems, both the general architectures and the methodology for analysis and design are applicable to future Mars settlements.

## INTRODUCTION
Humans have relied on structures to house and protect them and their valuables for many thousands of years. These structures may be found in the local environment (e.g. caves), constructed from improved local materials (e.g. igloos), or made mobile and moved from place to place. ... In the potential futures of the human species, it may prove desirable, or even necessary, to move beyond Earth to other bodies in the solar system.

## LUNAR HABITATS: CONCEPTS AND MATERIALS

### Lunar Concrete for Habitats
The idea of Moon colonization originated long before the age of actual space exploration... However the establishment of a manned human colony on the Moon (or on Mars) will need some form of infrastructure to shelter the astronauts and scientific instrumentations from a very harsh environment.

### Material properties
This project aims to identify optimum structural shell geometries for habitat structures built on site with local material. Material strengths for regolith are assumed to be between 10 and 100 MPa with a density between 1000 to 3000 kg/m³.

#### Table 1. Material properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## METHODOLOGY
Each of the spherical geometries is defined by a set of three variables:
1. **Interior Radius X_1**: Measured from the center to the internal wall.
2. **Tensile Layer Thickness X_2**: Cross-sectional area of tensile material (CFRP).
3. **Concrete Layer Thickness X_3**: Depth of the concrete measured from interior to exterior.

### Evaluation Objectives
1. Pressurized Volume (Minimize $-V_{press}$)
2. Terrestrial Material Mass (Minimize $M_{terr}$)
3. Lunar Material Mass (Minimize $M_{lunar}$)
4. Impact Protection (Minimize $-M_{impact}$)
5. Radiation Protection (Minimize $D_{rad}$)

## RESULTS
The variable ranges were restricted to: $X_1 = [2,6]m$, $X_2 = [0.01,0.1]m$, $X_3 = [0,0.3]m$. Results show that the increase in lunar mass required for the concrete habitat greatly increases both the meteoroid and radiation protection over the aluminum case. 

## DISCUSSION
Performance Goals: The pressurized volume required for 4 crew on the surface for 180 days is recommended at 226 m³. The maximum possible payload to the surface is approximately 5,500 kg for a single launch and lander.

#### Table 2. Possible habitat configurations with design variables and objectives for aluminum and concrete typologies.
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

## CONCLUSION
Pareto optimization allows decision makers to understand trade-offs without applying priority weighting. Reinforced concrete is a valuable material to investigate further for lunar habitat structures as it offers superior shielding capabilities.