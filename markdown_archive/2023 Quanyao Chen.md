# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen; Yuyue Gao; Lieyun Ding; Cheng Zhou; Wenbin Han; Yan Zhou; and Yusheng Shi

**Abstract:** The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure. Three kinds of genetic algorithm–based multiobjective optimization methods were used and compared to optimize the structural parameters. The optimized Pareto solution set containing multiple solutions based on the hypervolume index are obtained. Finite-model analysis was performed on the structures of the Pareto solution set and the optimal structure was determined based on the results of maximum stress and displacement. Finally, partially scaled-down physical models were produced through additive manufacturing to demonstrate the optimized double-shell habitat structure.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar exploration. Additive manufacturing offers advantages such as fast construction speed and high forming accuracy. This study applies parametric design and genetic algorithm (GA)–based multiobjective optimization (MOPT) to a 3D printable double-shell lunar habitat named "Lunar Ampullae."

## Methodology

### Model Parameters
The proposed lunar habitat structure includes four parts: inner shell, middle rib, outer shell, and catenary roof. The boundary contours are determined by ellipse equations defined by nine design parameters.

**Table 1. Structural optimization parameters and constraint ranges**
| Parameters | Symbol | Description | Range (m) |
| :--- | :--- | :--- | :--- |
| Surface major axis | A | Major axis of the surface elliptic curve forms the shell structure | [12,14] |
| Surface minor axis | B | Minor axis of the surface elliptic curve forms the shell structure | [4,6] |
| Cross section major axis | a | Major axis of the cross-sectional elliptic curve forming the shell structure | [1,3] |
| Cross section minor axis | b | Minor axis of the cross-sectional elliptic curve forms the shell structure | [1,3] |
| Distance | d | Distance between the inner shell and outer shell | [0.4,0.6] |
| Height of the bottom endpoint | Hb | Cut end height of the lower part of the shell surface curve | [0.2A, 0.4A] |
| Height of the top endpoint | Ht | Cut end height of the upper part of the shell surface curve | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of the inner shell in a double shell structure | [0.2,0.3] |
| Outer shell thickness | to | Thickness of the outer shell in a double shell structure | [0.2,0.3] |

### Design Objectives
1. **Maximize Available Volume (V):** To ensure habitable space for astronauts (at least 12 m³ per crew).
2. **Minimize Mass (W):** To reduce material consumption and transportation costs.
3. **Maximize Thermal Insulation (T):** To resist the extreme temperature fluctuations on the lunar surface.

## Results and Discussion
The study compared three algorithms: NSGA-II, PESA-II, and SPEA2. NSGA-II demonstrated the best performance in terms of convergence and diversity (highest Hypervolume index) and the smallest computational time cost. 

Finite-element analysis (FEA) using the "Karamba 3D" plug-in identified solution No. 25 as the optimal configuration, exhibiting the smallest maximum tensile stress (3.33 MPa) and displacement (2.72 x 10⁻² cm) under internal pressurization (0.1 MPa) and lunar gravity.

## Conclusion
The study successfully integrated parametric design with GA-based optimization to produce structural designs for lunar habitats that balance volume, mass, and thermal performance. A scaled-down physical model was 3D printed using concrete to demonstrate the feasibility of the optimized design for additive manufacturing.