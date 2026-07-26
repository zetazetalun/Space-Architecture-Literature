# Growing fast and steady in space: Distributed rapid self-reconfiguration motion planning optimization methods for swarm intelligent space modular self-reconfigurable satellites

**Authors:** Lei Chen, Naiming Qi, Mingying Huo, Qiufan Yuan, Ze Yu, Wenyu Feng  
**Publication:** Aerospace Science and Technology 166 (2025) 110536  
**DOI:** 10.1016/j.ast.2025.110536

## Abstract
The large-scale self-reconfiguration of Space Modular Self-Reconfigurable Satellites (SMSRS) faces critical challenges in the computational complexity of global assignment and motion space problems, low efficiency, as well as the low completion rate associated with the hollow structure, severely limiting their application in extraterrestrial infrastructure construction. In this study, we propose a Rapid Self-Reconfiguration Motion Planning Optimization (RSRMPO) method based on the distributed framework, specifically designed for pivoting cube modular systems. The proposed framework resolves the dual bottlenecks of near-optimal NP-complete problem computational demands and hollow structure formation through a decoupled optimization strategy. Simulation experiments confirm that RSRMPO framework provides near-optimal solutions to the NP-complete reconfiguration problem, effectively improving computational efficiency and structural robustness.

## Introduction
Modular satellites offer advantages such as reusability, interchangeability, and robust data interfaces. SMSRS systems have emerged as versatile platforms for large-scale space missions, including on-orbit maintenance, debris removal, and assembly of large-scale structures like space telescope frames and manipulator arms. 

## Methodology
The study introduces the **Rapid Self-Reconfiguration Motion Planning Optimization (RSRMPO)** framework consisting of:
1.  **Virtual Connection Technique (VCT):** Uses magnetic link sensors and a distributed framework for rapid identification of connection states.
2.  **Degeneration-Growth Assignment (DGA):** An improved fractal method based on L-systems to topologically describe the reconfiguration process and prevent hollow structures.
3.  **Feasible Space Map (FS_map):** A real-time generation technique for finite feasible space maps based on connectable surfaces.
4.  **Energy-cost-optimized A* path planning:** Minimizes transfer steps to reduce energy consumption.
5.  **Collision Avoidance:** A priority-based technique to prevent agent deadlocks.

## Results and Experiments
The methods were evaluated using configurations ranging from 10 to 1,200 modules.
- **Computational Efficiency:** VCT reduces computation time by 51.2% compared to graph-link methods for 1,000 modules.
- **Path Planning:** The MPO algorithm decreases reconfiguration planning time for each module by an average of 67.2% when configured with 1,200 modules.
- **Completion Rate:** RSRMPO achieved a completion rate of 89.85% in 1,000-module random configurations with 50% overlap, significantly higher than the 78.14% achieved by the GBCS method.
- **Energy/Time Savings:** Compared to GBCS, RSRMPO achieved a 93.3% reduction in planning time and an 85.3% decrease in energy consumption (measured by transfer steps).

## Conclusion
The RSRMPO framework demonstrates scalability and efficiency for large-scale space applications, preventing the formation of hollow structures and providing a robust solution for the assembly of modular spacecraft and infrastructure in microgravity environments.