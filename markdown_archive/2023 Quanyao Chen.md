# Genetic Algorithm–Based Multiobjective Optimization for 3D Printable Design of a Double-Shell Lunar Habitat Structure

**Authors:** Quanyao Chen, Yuyue Gao, Lieyun Ding, Cheng Zhou, Wenbin Han, Yan Zhou, and Yusheng Shi
**Published in:** Journal of Aerospace Engineering (ASCE), Vol. 36, No. 6, 2023.
**DOI:** 10.1061/JAEEEZ.ASENG-4755

## Abstract
The establishment of lunar habitats is significant for humans to explore the Moon. This study proposes a parametric design and multiobjective optimization approach based on genetic algorithms (GAs) for lunar habitats. The optimization objectives considered material mass consumption, space efficiency, and resistance ability for extreme extraterrestrial environments. Three kinds of GA-based multiobjective optimization methods (NSGA-II, SPEA2, and PESA-II) were compared. The optimal structure was determined based on finite-element analysis (FEA) results of maximum stress and displacement. A scaled-down physical model was produced through additive manufacturing.

## Methodology
### 1. Parametric Modeling: 'Lunar Ampullae'
The structure is a double-shell egg-shaped habitat. It consists of an inner shell, middle rib, outer shell, and catenary roof. The design is governed by nine parameters:
- Surface major/minor axes ($A, B$)
- Cross section major/minor axes ($a, b$)
- Distance between shells ($d$)
- Height of bottom/top endpoints ($H_b, H_t$)
- Inner/outer shell thickness ($t_i, t_o$)

### 2. Optimization Objectives
- **Maximize Volume ($V$):** Internal living space.
- **Minimize Mass ($W$):** Reducing transportation and construction costs.
- **Maximize Thermal Insulation ($T$):** Heat transfer thermal resistance calculation.

### 3. Algorithm Comparison
The study compared three algorithms: 
- **NSGA-II** (Non-dominated Sorting Genetic Algorithm II)
- **SPEA2** (Strength Pareto Evolutionary Algorithm 2)
- **PESA-II** (Pareto Envelope-based Selection Algorithm II)

## Results and Analysis
### Optimization Performance
NSGA-II demonstrated the best performance in terms of convergence and diversity (Hypervolume index of 0.8022).

### FEA and Optimal Solution
Finite Element Analysis was performed with a load of 0.1 MPa (internal pressure) and 1/6 Earth gravity. 

**Solution No. 25 Characteristics:**
- **Tensile Stress:** 3.33 MPa (0.333 $kN/cm^2$)
- **Displacement:** 0.0273 cm
- **Status:** Selected as the optimal model due to minimal stress and displacement.

### Physical Demonstration
A scaled-down model (120 cm height) was printed using a robotic arm with an arm span of 2.6 m. The process simulated concrete additive manufacturing using a putty powder mixture.

## Conclusion
The research provides a framework for the digital design and automated construction of lunar outposts. The double-shell structure offers safety redundancy and the potential to fill the cavity with radiation-shielding regolith or insulation.

### Key Data Tables

| Parameter | Range (m) |
|---|---|
| Surface major axis (A) | [12, 14] |
| Distance (d) | [0.4, 0.6] |
| Inner/Outer thickness ($t_i, t_o$) | [0.2, 0.3] |

| Method | Mutation Probability | Mean Hypervolume | Mean Time (s) |
|---|---|---|---|
| NSGA-II | 0.06 | 0.8022 | 77.685 |
| SPEA2 | 0.06 | 0.7485 | 477.476 |
| PESA-II | 0.06 | 0.4987 | 598.439 |