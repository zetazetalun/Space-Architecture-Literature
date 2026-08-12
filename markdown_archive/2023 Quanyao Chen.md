# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, Yusheng Shi
**Published in:** Journal of Aerospace Engineering (ASCE)
**DOI:** 10.1061/JAEEEZ.ASENG-4755
**Year:** 2023

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms (GAs) for the structure of lunar habitats. Optimization objectives included material mass consumption, space efficiency, and thermal insulation. Finite-element analysis (FEA) was performed on the Pareto solution set. A scaled-down physical model was produced through additive manufacturing to demonstrate the optimized double-shell structure.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) is considered a feasible way to build lunar habitats due to high transportation costs. Methods like sintered lunar soil brick assembly and additive manufacturing are emphasized. The study introduces 'Lunar Ampullae,' a double-shell habitat designed to be 3D printed with ISRU-derived materials.

## Methodology
### Parametric Design
The structure is defined by nine parameters:
- Surface major/minor axes (A, B)
- Cross section major/minor axes (a, b)
- Shell distance (d)
- Bottom/top cut heights (Hb, Ht)
- Inner/outer shell thicknesses (ti, to)

### Optimization Framework
- **Algorithm:** Genetic Algorithms (comparing NSGA-II, SPEA2, and PESA-II).
- **Objectives:** Maximize Volume (V), Maximize Thermal Resistance (T), and Minimize Mass (W).
- **Environment:** Loads include internal pressure (0.1 MPa) and one-sixth Earth's gravity.

### Additive Manufacturing Validation
A physical model was 3D printed using a concrete-like putty powder and a robotic arm to verify printability.

## Results and Discussion
- **Algorithm Performance:** NSGA-II demonstrated the best convergence and diversity for this structural optimization problem (Hypervolume index 0.8022).
- **Structural Analysis:** The optimal solution (Solution No. 25) showed a maximum tensile stress of 3.33 MPa and a maximum displacement of 2.72 × 10⁻² cm, which are well within the material's structural failure limits.
- **Design Correlations:** A positive correlation exists between mass, volume, and thermal insulation performance; as mass increases, the other two typically improve.

## Conclusion
The study successfully integrated parametric design with multiobjective optimization to create a feasible lunar habitat. The double-shell configuration provides redundant protection and space for insulation materials. Future work aims to include radiation protection and seismic performance in the optimization model.