# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Journal:** Journal of Aerospace Engineering (ASCE)
**Volume/Issue:** 36(6): 04023069
**Year:** 2023
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. This study proposes a parametric design and multiobjective optimization approach based on genetic algorithms for lunar habitats. Structural shape was translated into design parameters optimized for material consumption, space efficiency, and resistance to extreme environments. Three genetic algorithm–based optimization methods (NSGA-II, SPEA2, PESA-II) were compared. Finite-element analysis (FEA) was performed on the Pareto solution set, and a scaled-down 3D-printed model was produced to demonstrate the construction process.

## Methodology
The "Lunar Ampullae" is a double-shell structure designed using Grasshopper (GH) and Karamba 3D. The optimization used nine design parameters (axes, heights, thicknesses, and distance between shells).

### Table 1: Structural optimization parameters and constraint ranges
| Parameters | Symbol | Description | Range (m) |
|---|---|---|---|
| Surface major axis | A | Major axis of shell elliptic curve | [12, 14] |
| Surface minor axis | B | Minor axis of shell elliptic curve | [4, 6] |
| Cross section major axis | a | Major axis of cross-sectional curve | [1, 3] |
| Cross section minor axis | b | Minor axis of cross-sectional curve | [1, 3] |
| Distance | d | Distance between inner/outer shell | [0.4, 0.6] |
| Height of bottom endpoint | Hb | Cut end height (lower) | [0.2A, 0.4A] |
| Height of top endpoint | Ht | Cut end height (upper) | [0.8A, 0.95A] |
| Inner shell thickness | ti | Thickness of inner shell | [0.2, 0.3] |
| Outer shell thickness | to | Thickness of outer shell | [0.2, 0.3] |

## Optimization Results
NSGA-II proved most effective for convergence and diversity. The optimal parameter combination found was PC = 0.9 (Crossover Probability) and PM = 0.06 (Mutation Probability).

### Table 5: Values of hypervolume and time cost comparison
| Method | Mutation probability | Hypervolume Mean | Time cost (s) Mean |
|---|---|---|---|
| SPEA2 | 0.06 | 0.7485 | 477.476 |
| PESA-II | 0.06 | 0.4987 | 598.439 |
| **NSGA-II** | **0.06** | **0.8022** | **77.685** |

## FEA Analysis and Physical Model
Finite Element Analysis focused on internal pressure (0.1 MPa) and lunar gravity (1/6 g). The 25th solution in the Pareto set was selected as the optimal structure.
- **Maximum Tensile Stress:** 3.33 MPa
- **Maximum Displacement:** 2.72 × 10⁻² cm

A partially scaled-down physical model was printed using putty powder and concrete additive manufacturing to prove constructability.

## Conclusion
The study successfully combined parametric design with GA-based multiobjective optimization. Limitations included the exclusion of cosmic radiation and thermal stress from the primary optimization objectives, which are suggested for future work.