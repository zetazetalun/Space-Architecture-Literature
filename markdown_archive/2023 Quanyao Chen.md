# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Journal:** Journal of Aerospace Engineering (ASCE)
**Volume/Issue:** 36(6): 04023069
**Year:** 2023
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment. Three kinds of genetic algorithm–based multiobjective optimization methods (NSGA-II, SPEA2, PESA-II) were compared. Finally, partially scaled-down physical models were produced through additive manufacturing to demonstrate the optimized double-shell habitat structure.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way for lunar habitation. Sintered lunar soil brick assembly and additive manufacturing are two ISRU construction methods. This paper proposes a three-dimensional (3D) printable double-shell lunar habitat named "Lunar Ampullae."

## Methodology

### Model Parameters
The structure is determined by nine design parameters including surface major/minor axes, cross-section axes, shell thicknesses, and distances between shells.

### Table 1: Structural optimization parameters and constraint ranges
| Parameters | Symbol | Description | Range (m) |
|---|---|---|---|
| Surface major axis | A | Major axis of the surface elliptic curve | [12, 14] |
| Surface minor axis | B | Minor axis of the surface elliptic curve | [4, 6] |
| Cross section major axis | a | Major axis of cross-sectional elliptic curve | [1, 3] |
| Cross section minor axis | b | Minor axis of cross-sectional elliptic curve | [1, 3] |
| Distance | d | Distance between inner and outer shell | [0.4, 0.6] |
| Height of bottom endpoint | Hb | Cut end height of lower shell surface | [0.2A, 0.4A] |
| Height of top endpoint | Ht | Cut end height of upper shell surface | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of the inner shell | [0.2, 0.3] |
| Outer shell thickness | to | Thickness of the outer shell | [0.2, 0.3] |

### Optimization Objectives
1. **Maximize Available Volume (V)**: Integrating cross-sectional areas between Hb and Ht.
2. **Minimize Mass (W)**: Based on lunar regolith density and shell surface area.
3. **Maximize Thermal Insulation (T)**: Represented by heat transfer thermal resistance.

## Results and Discussion

### Algorithm Comparison
Three algorithms were compared: NSGA-II, PESA-II, and SPEA2. NSGA-II generally performed better in terms of diversity and convergence. Under the parameter combination of PC = 0.9 and PM = 0.06, the average value of Hypervolume (HV) was the largest (0.8022).

### Finite-Model Analysis (FEA)
FEA was performed using the Karamba 3D plugin for Grasshopper. The structure was subjected to 0.1 MPa internal pressure and 1/6th Earth gravity. The 25th structure model from the Pareto solution set was selected as optimal, exhibiting the smallest maximum stress (3.33 MPa) and displacement (2.72 × 10⁻² cm).

## Conclusion
The study successfully combined parametric design with GA-based optimization for lunar habitats. The optimized double-shell structure provides better performance in mass, volume, and thermal insulation. Additive manufacturing of scaled models verified the feasibility of the structural design for robotic construction on the Moon.