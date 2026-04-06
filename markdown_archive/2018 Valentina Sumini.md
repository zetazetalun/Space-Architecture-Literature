# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini¹; Sam Wald²; Caitlin Mueller³; Claudio Chesi⁴; and Olivier L. de Weck⁵**

¹Digital Structures Research Group, Dept. of Civil and Environmental Engineering, Massachusetts Institute of Technology, 77 Massachusetts Ave., Cambridge, MA, U.S. E-mail: vsumini@mit.edu
²Dept. of Aeronautics and Astronautics, Massachusetts Institute of Technology, 77 Massachusetts Ave., Cambridge, MA, U.S. E-mail: swald@mit.edu
³Digital Structures Research Group, Dept. of Civil and Environmental Engineering, Massachusetts Institute of Technology, 77 Massachusetts Ave., Cambridge, MA, U.S. E-mail: caitlinm@mit.edu
⁴Dept. of Architecture, Built Environment and Construction Engineering, Politecnico di Milano, Piazza Leonardo da Vinci, 32, 20133 Milano, Italy. E-mail: claudio.chesi@polimi.it
⁵Dept. of Aeronautics and Astronautics, Massachusetts Institute of Technology, 77 Massachusetts Ave., Cambridge, MA, U.S. E-mail: deweck@mit.edu

## ABSTRACT
Much like their Earth-based counterparts, the requirements of future space habitat structures can be defined by their ability to protect their occupants and provide usable space to live and work in an extreme, isolated environment. Due to the high cost of transporting resources off of Earth’s surface, recent efforts focus on developing increasingly Earth-independent structural designs. These new designs use local regolith-based materials as a possible solution for long-term extraterrestrial sustainability. With a focus on an Earth-independent habitat, this research looks at architectures that use spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The research approach is to formulate the structural design problem as a multi-objective optimization of the habitat shell. The objectives that apply to the shell geometry and cross section include the minimization of transportation and construction costs, and the minimization of the probability of loss due to radiation and micrometeorite events. Direct trade-offs arise. The multi-objective optimization applies Pareto optimization to determine which design elements or options afford the greatest effectiveness or efficiency. The authors examine candidate design solutions based on priorities and performance thresholds which indicate that ISRU-based reinforced concrete may be a valuable future investment. While the cases presented here are limited to lunar surface systems, both the general architectures and the methodology for analysis and design are applicable to future Mars settlements.

## INTRODUCTION
Humans have relied on structures to house and protect them and their valuables for many thousands of years. The establish of a manned human colony on the Moon (or on Mars) will need some form of infrastructure to shelter the astronauts and scientific instrumentations from a very harsh environment.

## LUNAR HABITATS: CONCEPTS AND MATERIALS

### Material properties
This project aims to identify optimum structural shell geometries for habitat structures built on site with local material. The authors have limited the trade-space to represent likely materials that can be created with lunar regolith. These include cast regolith, sintered regolith, and lunar concrete.

**Table 1. Material properties**
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## METHODOLOGY

### Primary Structure Generation and Evaluation Process
Each of the spherical geometries is defined by a set of three variables:
1. **Interior Radius X_1**: Defines the overall size of the habitat.
2. **Tensile Layer Thickness X_2**: Represents the effective thickness of the reinforcement (CFRP).
3. **Concrete Layer Thickness X_3**: The depth of the regolith concrete layer.

### Objectives
1. **Pressurized Volume**: To be maximized.
2. **Terrestrial Material Mass**: To be minimized (mass brought from Earth).
3. **Lunar Material Mass**: To be minimized (processed ISRU mass).
4. **Impact Protection**: To afford a 0.993 "Probability of No Penetration" (PMP) over 5 years.
5. **Radiation Protection**: To minimize the annual dose equivalent from Galactic Cosmic Rays (GCR).

## RESULTS
The results show that the maximum payload from Earth is reduced due to the increased strength and reduced density of the CFRP compared to aluminum for a given volume. Furthermore, the increase in lunar mass required to build the concrete habitat greatly increases both the meteoroid and radiation protection over the aluminum case.

**Table 2. Possible habitat configurations with design variables and objectives for aluminum and concrete typologies.**
| Property | Aluminum | Concrete | Units |
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
Pareto optimization allows decision makers to understand the trade-offs between performances and to make informed decisions. Reinforced concrete could be a valuable material to investigate further as it provides better protection and satisfied all mission goals in the optimization model, whereas aluminum did not.