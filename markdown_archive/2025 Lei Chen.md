# Growing fast and steady in space: Distributed rapid self-reconfiguration motion planning optimization methods for swarm intelligent space modular self-reconfigurable satellites

**Authors:** Lei Chen, Naiming Qi, Mingying Huo, Qiufan Yuan, Ze Yu, Wenyu Feng
**Journal:** Aerospace Science and Technology 166 (2025) 110536

## Abstract
The large-scale self-reconfiguration of Space Modular Self-Reconfigurable Satellites (SMSRS) faces critical challenges in the computational complexity of global assignment and motion space problems, low efficiency, as well as the low completion rate associated with the hollow structure, severely limiting their application in extraterrestrial infrastructure construction. In this study, we propose a Rapid Self-Reconfiguration Motion Planning Optimization (RSRMPO) method based on the distributed framework, specifically designed for pivoting cube modular systems. The proposed framework resolves the dual bottlenecks of near-optimal NP-complete problem computational demands and hollow structure formation through a decoupled optimization strategy: assignment optimization at the high-level module ensures structural integrity, while motion planning optimization at the execution layer guarantees swarm fast collision-free coordination.

## 1. Introduction
As spacecraft missions become increasingly specialized and complex, the emergence of the Space Modular Self-Reconfigurable Satellite (SMSRS) offers promise. SMSRS systems offer key advantages such as reusability, interchangeability, and robust data interfaces. These systems can self-reconfigure or self-assemble into deployable configurations for high-precision maneuvering, orbital capture, and in-orbit assembly of large aperture space telescopes.

## 2. Problem Formation
The distributed strategy of SR can be divided into:
1. **High-level tasks:** Assignment planning and map generation.
2. **Low-level tasks:** Path planning, motion execution, and collision avoidance.

### Reconfiguration Pivoting Motion
The dynamics of a SMSRS is pivoting (rotating) about the edges they share with other modules. The transfer motion is feasible only if the support module exists and the restriction matrix does not overlap the current configuration.

## 3. Assignment Optimization Algorithm
### Virtual Connection Technique (VCT)
To enhance reconfiguration planning efficiency, a virtual connection technique based on magnetic link sensors and the distributed framework is proposed to facilitate rapid identification of connection states among modules.

### Degeneration-Growth Assignment (DGA) Method
In large-scale SR processes, assignment matching planning is a primary challenge. The DGA method, an improved fractal method, leverages the character-overriding mechanism of enhanced L-systems to topologically describe the SR process.

## 4. Motion Planning Optimization Algorithm
### Real-time Feasible Space map (FS_map) Generation Technique
The FS_map represents the current feasible space that the SMSRS can navigate, generated based on connectable surface positions of immovable modules.

### Path Planning Algorithm
An enhanced A* search algorithm is integrated with the real-time feasible map to minimize transfer steps and energy consumption.

## 5. Experiments and Results
### 5.1. Efficiency Comparison
- **Movable Module Generation:** VCT reduces computation time by 51.2% compared to the graph-link method for 1,000 modules.
- **Path Planning:** The MPO algorithm decreases reconfiguration planning time for each module by an average of 67.2% when configured with 1,200 modules.
- **Overall Performance:** The RSRMPO framework achieves a 93.3% reduction in planning time and an 85.3% decrease in energy consumption compared to the Graph-Based Configuration Search (GBCS) algorithm.
- **Completion Rate:** RSRMPO achieved a completion rate of 89.86% for 1,000 modules, which is 11.7% higher than GBCS.

## 6. Conclusion
The RSRMPO framework provides near-optimal solutions for reconfiguration scales spanning 10–1,200 modules, demonstrating scalability and efficiency for large-scale space applications, including camouflage satellites, space telescope frames, and space manipulator arms.