# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Affiliations:** Massachusetts Institute of Technology (MIT), Politecnico di Milano
**Source:** Earth and Space 2018, ASCE

## Abstract
Future space habitat structures must protect occupants and provide usable space in extreme environments. Due to high transportation costs, research focuses on Earth-independent structural designs using local regolith-based materials. This study explores spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The structural design problem is formulated as a multi-objective optimization (Pareto optimization) to minimize transportation and construction costs while minimizing the probability of loss due to radiation and micrometeorite events. Results indicate that ISRU-based reinforced concrete is a valuable investment for lunar surface systems and applicable to Mars.

## Introduction
Habitat design is driven by resource availability and transportation capacity. The high cost of Earth-based resources necessitates the use of local regolith-based materials for sustainability. This research investigates the impact of material and geometrical variables on reinforced concrete shells compared to a baseline aluminum shell.

## Lunar Habitats: Concepts and Materials
- **Lunar Concrete:** Exploiting lunar bases reduces fuel requirements due to lower gravity. Infrastructure is needed to shelter against harsh environments (temperature cycles, vacuum, radiation, micrometeorites).
- **Structural Concepts:** Literature mentions inflatable structures inside protective regolith shells (Foster + Partners) and 3D printing technologies (D-Shape, Contour Crafting).
- **Material Comparison:**
    - **Aluminum Shell:** Baseline system based on ISS habitation modules.
    - **Reinforced Concrete Shell:** Spherical dome using regolith with an inner bladder and Carbon Fiber Reinforced Polymers (CFRP) to resist tension and impacts.

### Table 1: Material properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
Each geometry is defined by interior radius ($X_1$), tensile layer thickness ($X_2$), and concrete layer thickness ($X_3$). Feasible geometries are evaluated on five objectives:
1. **Pressurized Volume ($J_1$):** Maximized for crew and hardware.
2. **Terrestrial Material Mass ($J_2$):** Minimized to reduce launch costs.
3. **Lunar Material Mass ($J_3$):** Proxy for ISRU processing costs.
4. **Impact Protection ($J_4$):** Maximized to resist micrometeoroid hazards (0.993 Probability of No Penetration).
5. **Radiation Protection ($J_5$):** Minimized dose equivalent from GCR.

## Results
The optimization identified Pareto optimal solutions. For a given volume, ISRU habitats increase lunar mass but significantly improve radiation and meteoroid protection compared to aluminum. Aluminum habitats are limited to ~7.5 cSv dose equivalent, while concrete can reduce this to 5.8 cSv at 0.3m thickness.

### Table 2: Possible habitat configurations
| Parameter | Aluminum | Concrete | Units |
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
Reinforced concrete is a viable material for lunar habitats. Pareto optimization allows designers to understand trade-offs between construction effort and human safety. ISRU-based designs can satisfy performance goals that aluminum shells cannot, particularly regarding mass-to-volume efficiency and protection levels.