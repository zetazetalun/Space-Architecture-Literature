# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Published in:** Journal of Aerospace Engineering (ASCE), 2023

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. The optimization objectives were determined considering material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environments. Three kinds of genetic algorithm-based multiobjective optimization methods (NSGA-II, SPEA2, PESA-II) were used and compared. Finite-element analysis (FEA) was performed on the structures, and the optimal structure was determined. Finally, scaled-down physical models were produced through additive manufacturing.

## Introduction
Robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way to establish lunar habitats. Additive manufacturing offers advantages including fast construction speed and high forming accuracy. Structural design must focus on effects like low gravity, high vacuum, large temperature variations, radiation, and micrometeorite impacts.

## Methodology
### "Lunar Ampullae" Design
A conceptual double-shell structure is proposed. It consists of:
- **Inner Shell:** Provides pressurized volume.
- **Middle Rib:** Connects shells and provides structural integrity.
- **Outer Shell:** Provides protection against the external environment.
- **Catenary Roof:** Optimized shape for loading.

### Optimization Framework
- **Parameters:** 9 design parameters (Major/minor axes, heights, thicknesses, distances).
- **Objectives:** 
  1. Maximize habitable volume ($V$)
  2. Minimize mass ($W$)
  3. Maximize thermal insulation performance ($T$)
- **Algorithms:** NSGA-II, SPEA2, and PESA-II were compared.

## Results and Discussion
- **Algorithm Performance:** NSGA-II demonstrated the best diversity and convergence performance with the largest hypervolume (HV) index (0.8022).
- **Optimal Solution:** Solution No. 25 was selected from the Pareto set based on FEA results. 
  - **Max Tensile Stress:** 3.33 MPa
  - **Max Displacement:** $2.72 \times 10^{-2}$ cm
- **Physical Model:** A scaled-down model was successfully 3D printed using putty/concrete-based material to demonstrate printability without internal support structures.

## Conclusion
The study provides a scientific basis for early-stage lunar habitat design. NSGA-II is identified as a highly efficient tool for balancing competing objectives in space architecture. Future work will include seismic analysis and broader environmental factor considerations.