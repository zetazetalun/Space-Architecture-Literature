# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Published in:** Journal of Aerospace Engineering, ASCE (2023)
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. The optimization objectives considered material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environments. Three kinds of genetic algorithm–based multiobjective optimization methods (NSGA-II, SPEA2, PESA-II) were compared. Finite-element analysis (FEA) was performed to determine the optimal structure, and partially scaled-down physical models were produced through additive manufacturing.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar habitation. Construction through additive manufacturing (3D printing) offers fast construction speeds and high forming accuracy. This study focuses on the 'Lunar Ampullae,' a double-shell habitat structure determined by nine design parameters including shell curve axes, heights, thicknesses, and cavity distances.

### Optimization Framework
1. **Parametric Model Creation:** Developed in Rhino and Grasshopper.
2. **Optimization Methods:** Using NSGA-II to find the Pareto solution set.
3. **Additive Manufacturing:** Demonstrating construction via 3D printing with a scaled concrete model.

### Table 1: Structural Optimization Parameters and Constraint Ranges
| Parameters | Symbol | Description | Range (m) |
| :--- | :--- | :--- | :--- |
| Surface major axis | A | Major axis of surface elliptic curve | [12, 14] |
| Surface minor axis | B | Minor axis of surface elliptic curve | [4, 6] |
| Cross section major axis | a | Major axis of cross-sectional elliptic curve | [1, 3] |
| Cross section minor axis | b | Minor axis of cross-sectional elliptic curve | [1, 3] |
| Distance | d | Distance between inner and outer shell | [0.4, 0.6] |
| Height of bottom endpoint | Hb | Cut end height (lower) | [0.2A, 0.4A] |
| Height of top endpoint | Ht | Cut end height (upper) | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of the inner shell | [0.2, 0.3] |
| Outer shell thickness | to | Thickness of the outer shell | [0.2, 0.3] |

## Results and Discussion
- **Algorithm Comparison:** NSGA-II yielded larger volumes and better thermal insulation performance, while SPEA2 yielded smaller quality (mass). NSGA-II had the largest Hypervolume (HV) index (0.8022), implying the best convergence and diversity.
- **Optimal Solution:** Solution No. 25 was identified as optimal through FEA, exhibiting the smallest maximum stress (0.333 kN/cm²) and displacement (0.0273 cm) under internal pressure loads (0.1 MPa).
- **3D Printing:** A scaled model (1.2m height) was successfully printed using a robotic arm and concrete-based additive manufacturing.

## Conclusion
The study successfully demonstrates that a double-shell structure optimized via genetic algorithms provides a balance between structural efficiency and environmental protection for lunar exploration. Future work will consider cosmic radiation and seismic performance under moonquakes.