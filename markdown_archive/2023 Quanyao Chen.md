# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Published in:** Journal of Aerospace Engineering (ASCE), Vol. 36, No. 6, 2023
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure. Three kinds of genetic algorithm–based multiobjective optimization methods were used and compared to optimize the structural parameters. The optimized Pareto solution set containing multiple solutions based on the hypervolume index are obtained. Finite-model analysis was performed on the structures of the Pareto solution set and the optimal structure was determined based on the results of maximum stress and displacement. Finally, partially scaled-down physical models were produced through additive manufacturing to demonstrate the optimized double-shell habitat structure.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar habitation. Construction through additive manufacturing has certain advantages, including fast construction speed and high forming accuracy. Utilization of minimally processed regolith for construction can be more effective than foreign materials. 

## Methodology
The study proposes a conceptual lunar habitat named "Lunar Ampullae." It is a double-shell structure built by additive manufacturing using lunar ISRU on the outside and a pressurized module on the inside. 

### Optimization Framework
1.  **Parametric Model Creation:** Using Rhino/Grasshopper and Karamba 3D.
2.  **Optimization Methods:** Genetic Algorithm-based Multiobjective Optimization (MOPT). Three algorithms were compared: NSGA-II, SPEA2, and PESA-II.
3.  **3D Printing:** Using the Pareto solution set to select the optimal solution for physical demonstration.

| Parameters | Symbol | Description | Range (m) |
| :--- | :--- | :--- | :--- |
| Surface major axis | A | Major axis of the surface elliptic curve | [12, 14] |
| Surface minor axis | B | Minor axis of the surface elliptic curve | [4, 6] |
| Cross section major axis | a | Major axis of the cross-sectional elliptic curve | [1, 3] |
| Cross section minor axis | b | Minor axis of the cross-sectional elliptic curve | [1, 3] |
| Distance | d | Distance between the inner and outer shell | [0.4, 0.6] |
| Bottom endpoint height | Hb | Cut end height of the lower part | [0.2A, 0.4A] |
| Top endpoint height | Ht | Cut end height of the upper part | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of the inner shell | [0.2, 0.3] |
| Outer shell thickness | to | Thickness of the outer shell | [0.2, 0.3] |

## Results and Discussion
- **Algorithm Performance:** NSGA-II demonstrated the best convergence and diversity (highest hypervolume index) compared to SPEA2 and PESA-II for this optimization problem.
- **Structural Analysis:** Model 25 was selected as the optimal structure from the Pareto set. Finite Element Analysis (FEA) showed a maximum tensile stress of 3.33 MPa and maximum displacement of 2.73 × 10⁻² cm under 0.1 MPa internal pressure and 1/6 Earth's gravity.
- **Physical Validation:** A scaled-down physical model was printed using putty powder additive manufacturing to demonstrate structural printability.

## Conclusion
The study successfully combined parametric design with GA-based optimization to create a 3D-printable lunar habitat. The double-shell design provides potential for radiation and thermal insulation while maintaining structural integrity. Future work will include thermal stress analysis under extreme temperature cycles and further material simulations.