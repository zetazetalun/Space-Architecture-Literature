# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi

**Journal:** Journal of Aerospace Engineering (ASCE)
**DOI:** 10.1061/JAEEEZ.ASENG-4755
**Year:** 2023

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar exploration. Additive manufacturing (AM) using regolith composites offers advantages like fast construction speed and high forming accuracy. This study proposes 'Lunar Ampullae,' a 3D-printable double-shell habitat structure optimized for performance in the lunar environment.

## Methodology
The research framework consists of three parts:
1.  **Parametric Model Creation:** Using Rhino and Grasshopper (GH) with the plug-in 'Karamba 3D.' The structure is defined by nine parameters (Table 1).
2.  **Optimization Methods:** Three GA-based multiobjective optimization (MOPT) methods—NSGA-II, SPEA2, and PESA-II—were compared.
3.  **FEA and 3D Printing:** Finite-element analysis (FEA) was used to select the optimal solution from the Pareto set, which was then validated through a scaled-down 3D-printed concrete model.

### Model Parameters (Table 1)
| Parameters | Symbol | Range (m) |
| :--- | :--- | :--- |
| Surface major axis | A | [12, 14] |
| Surface minor axis | B | [4, 6] |
| Cross section major axis | a | [1, 3] |
| Cross section minor axis | b | [1, 3] |
| Distance (inner/outer shell) | d | [0.4, 0.6] |
| Height of bottom endpoint | Hb | [0.2A, 0.4A] |
| Height of top endpoint | Ht | [0.8A, 0.95A] |
| Inner shell thickness | ti | [0.2, 0.3] |
| Outer shell thickness | to | [0.2, 0.3] |

## Results and Discussion
- **Algorithm Comparison:** NSGA-II showed the best Pareto solution set diversity and convergence performance compared to SPEA2 and PESA-II. The optimal parameter combination for NSGA-II was found with a Crossover Probability (PC) of 0.9 and Mutation Probability (PM) of 0.06.
- **Structural Performance:** The optimal solution (Solution 25) exhibited a maximum tensile stress of 3.33 MPa and a maximum displacement of 0.0272 cm under internal pressure and 1/6 gravity loads.
- **Additive Manufacturing:** A partially scaled-down physical model was successfully produced using additive manufacturing to demonstrate the potential of the optimized double-shell design.

## Conclusion
The study successfully combined parametric design with GA-based optimization for space architecture. The double-shell 'Lunar Ampullae' design provides thermal insulation, radiation shielding, and structural stability. Future work will include more environmental factors like cosmic radiation and high-frequency moonquakes into the optimization goals.