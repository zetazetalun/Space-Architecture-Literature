# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon and carry out scientific work. Constructing lunar habitats through additive manufacturing using lunar in situ resource is a promising solution. This study proposed a parametric design and multiobjective optimization approach based on genetic algorithms for the structure of lunar habitats. Structural shape was translated into design parameters, which were optimized during the design phase. The optimization objectives were determined considering the material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environment of the structure. Three kinds of genetic algorithm–based multiobjective optimization methods (NSGA-II, PESA-II, and SPEA2) were used and compared to optimize the structural parameters. Finite-model analysis was performed on the structures of the Pareto solution set and the optimal structure was determined based on the results of maximum stress and displacement. Finally, partially scaled-down physical models were produced through additive manufacturing to demonstrate the optimized double-shell habitat structure.

## Introduction
To realize the exploration project on the Moon and on distant planets, humans need to establish a habitat that enables them to live and work. With the high cost and difficulty of transportation between Earth and the Moon, robotic construction based on in situ resource utilization (ISRU) appears to be the most feasible way. Construction through additive manufacturing has certain advantages, including fast construction speed and high forming accuracy.

## Methodology
### The "Lunar Ampullae" Concept
The proposed lunar habitation structure is a 3D printable double-shell structure that mainly includes four parts:
1. Inner shell
2. Middle rib
3. Outer shell
4. Catenary roof

The double-shell structure allows for independent layers: in case of damage to one shell, the other provides protection. The space between shells can be filled with insulation and radiation protection materials.

### Optimization Framework
The study utilized the parametric design tool **Grasshopper** and the plugin **Karamba 3D**. Nine design parameters were established, including:
- Surface major/minor axes (A, B)
- Cross section major/minor axes (a, b)
- Distance between shells (d)
- Heights of bottom/top endpoints (Hb, Ht)
- Shell thicknesses (ti, to)

### Optimization Objectives
1. **Maximize Available Volume**: Aiming for habitable volume between 33.9–75.3 m³.
2. **Minimize Mass**: To reduce material consumption.
3. **Maximize Thermal Insulation**: Represented by heat transfer thermal resistance.

## Comparison of Algorithms
The study compared three algorithms: **NSGA-II**, **PESA-II**, and **SPEA2**. 
- **NSGA-II** was found to have the best Pareto solution set diversity and convergence performance.
- Under the parameter combination of Crossover Probability (PC) = 0.9 and Mutation Probability (PM) = 0.06, NSGA-II showed the highest Hypervolume (HV) index.

## Finite-Element Analysis (FEA)
FEA was performed using Karamba 3D to evaluate the Pareto solution set. The structural model was subjected to:
- Internal pressure: 0.1 MPa (one standard atmosphere).
- Gravity: One-sixth of Earth’s gravity.
- Evaluation metrics: Smallest maximum tensile stress and displacement.
- Result: The 25th structure model was selected, showing a maximum tensile stress of 3.33 MPa and max displacement of 2.72 × 10⁻² cm.

## Conclusion
This paper demonstrated that parametric design and GA-based optimization can effectively resolve contradictions between volume, mass, and insulation for lunar habitats. The physical 3D printing of a scaled-down model using putty powder confirmed the design's printability and structural potential.