# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi

**Publication:** *Journal of Aerospace Engineering*, Vol. 36, No. 6, 2023.
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure. Three kinds of genetic algorithm–based multiobjective optimization methods (NSGA-II, SPEA2, and PESA-II) were used and compared. Finite-element analysis (FEA) was performed on the structures of the Pareto solution set. Finally, partially scaled-down physical models were produced through additive manufacturing.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar habitation. Additive manufacturing (AM) using lunar regolith offers advantages including fast construction speed and high forming accuracy. This paper introduces "Lunar Ampullae," a 3D-printable double-shell lunar habitat structure designed through parametric modeling and genetic algorithm-based multiobjective optimization (MOPT).

## Methodology

### Parametric Modeling
The structure is defined by nine parameters that influence its size and contour:
1. **A**: Surface major axis [12, 14] m
2. **B**: Surface minor axis [4, 6] m
3. **a**: Cross section major axis [1, 3] m
4. **b**: Cross section minor axis [1, 3] m
5. **d**: Distance between inner and outer shell [0.4, 0.6] m
6. **Hb**: Height of the bottom endpoint [0.2A, 0.4A]
7. **Ht**: Height of the top endpoint [0.8A, 0.95A]
8. **ti**: Inner shell thickness [0.2, 0.3] m
9. **to**: Outer shell thickness [0.2, 0.3] m

### Optimization Objectives
*   **Maximize Habitable Volume (V)**
*   **Minimize Material Mass (W)**
*   **Maximize Thermal Insulation Performance (T)**

## Results and Analysis

### Algorithm Comparison
The study compared NSGA-II, SPEA2, and PESA-II. NSGA-II yielded the best performance in terms of convergence and diversity (highest Hypervolume index of 0.8022).

### FEA Validation
The structures were subjected to internal pressure (0.1 MPa) and lunar gravity (1/6 G). The optimal solution (Solution No. 25) demonstrated:
*   **Maximum Tensile Stress:** 0.333 kN/cm² (3.33 MPa)
*   **Maximum Displacement:** 0.0273 cm

### Additive Manufacturing Experiment
A 1:20 scaled model (120 cm height) was printed using concrete additive manufacturing technology to demonstrate the feasibility of the double-shell geometry and the robotic construction process.

## Conclusions
1. Parametric design combined with genetic algorithms provides a robust workflow for optimizing space habitat geometry.
2. NSGA-II outperformed other algorithms in balancing mass, volume, and insulation.
3. The double-shell "Lunar Ampullae" structure provides a feasible, structurally sound design for lunar 3D printing with ISRU materials.