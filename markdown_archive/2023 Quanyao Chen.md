# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Published in:** Journal of Aerospace Engineering, ASCE (2023)
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure. Three kinds of genetic algorithm–based multiobjective optimization methods were used and compared to optimize the structural parameters. The optimized Pareto solution set containing multiple solutions based on the hypervolume index are obtained. Finite-model analysis was performed on the structures of the Pareto solution set and the optimal structure was determined based on the results of maximum stress and displacement. Finally, partially scaled-down physical models were produced through additive manufacturing to demonstrate the optimized double-shell habitat structure.

## Introduction
To realize exploration projects on the Moon and distant planets, humans need to establish a habitat that enables them to live and work. robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way. Additive manufacturing has certain advantages, including fast construction speed and high forming accuracy.

## Methodology
This paper proposes a conceptual design named "Lunar Ampullae," a double-shell structure intended for additive manufacturing. The inner and outer layers are independent to provide redundancy; in case of damage to one shell, the other provides protection. The space between shells can be filled with insulation and radiation protection materials.

### Model Parameters
The structure is determined by nine optimization parameters affecting size and contour (Table 1).

**Table 1. Structural optimization parameters and constraint ranges**

| Parameters | Symbol | Description | Range (m) |
| :--- | :--- | :--- | :--- |
| Surface major axis | A | Major axis of the shell structure | [12,14] |
| Surface minor axis | B | Minor axis of the shell structure | [4,6] |
| Cross section major axis | a | Major axis of the cross-sectional curve | [1,3] |
| Cross section minor axis | b | Minor axis of the cross-sectional curve | [1,3] |
| Distance | d | Distance between inner and outer shell | [0.4,0.6] |
| Height of bottom endpoint | Hb | Cut end height of lower part | [0.2A, 0.4A] |
| Height of top endpoint | Ht | Cut end height of upper part | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of the inner shell | [0.2,0.3] |
| Outer shell thickness | to | Thickness of the outer shell | [0.2,0.3] |

### Design Objectives
1.  **Maximize Available Volume:** Calculated via integration of cross-sectional areas.
2.  **Minimize Mass:** Based on the density of lunar regolith and shell surface areas.
3.  **Maximize Thermal Insulation:** Represented by the heat transfer thermal resistance of the structure.

## Optimization and Analysis
Three algorithms were compared: NSGA-II, SPEA2, and PESA-II. NSGA-II yielded the best Pareto solution set diversity and convergence performance. Finite Element Analysis (FEA) was performed using the "Karamba 3D" plugin for Grasshopper to evaluate maximum stress and displacement under 1/6 gravity and internal pressurization (0.1 MPa).

## Experimental Validation
A scaled-down physical model was printed using concrete additive manufacturing to demonstrate the feasibility of the "Lunar Ampullae" design.

## Conclusion
The study successfully demonstrates a parametric framework for optimizing lunar habitats. NSGA-II proved most effective for balancing the conflicting goals of mass reduction, volume maximization, and thermal performance. Future work will include expanded environmental factors such as cosmic radiation and meteorite impact resistance.