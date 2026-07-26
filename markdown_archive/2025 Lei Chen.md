# Growing fast and steady in space: Distributed rapid self-reconfiguration motion planning optimization methods for swarm intelligent space modular self-reconfigurable satellites

**Authors:** Lei Chen, Naiming Qi, Mingying Huo, Qiufan Yuan, Ze Yu, Wenyu Feng  
**Publication:** Aerospace Science and Technology 166 (2025) 110536  
**Keywords:** Large-scale reconfiguration, Assignment optimization, Reconfiguration planning, Space modular self-reconfigurable satellite, On-orbit service  

## Abstract
The large-scale self-reconfiguration of Space Modular Self-Reconfigurable Satellites (SMSRS) faces critical challenges in computational complexity, low efficiency, and low completion rates associated with hollow structures, limiting their application in extraterrestrial infrastructure construction. This study proposes a Rapid Self-Reconfiguration Motion Planning Optimization (RSRMPO) method based on a distributed framework. It utilizes a decoupled optimization strategy: assignment optimization at the high-level to ensure structural integrity and motion planning at the execution layer for collision-free coordination. Simulation experiments with 10-1,200 modules confirm near-optimal solutions, improved computational efficiency, and structural robustness for orbital assembly and deep-space missions.

## Introduction
Space Modular Self-Reconfigurable Satellites (SMSRS) offer reusability, interchangeability, and reduced launch costs by forming target spacecraft structures in orbit. Key challenges include task allocation (NP-complete problem) and path searching, especially for large-scale swarms (over 1,000 modules).

## Methodology
The RSRMPO framework involves several techniques:
1. **Virtual Connection Technique (VCT):** Facilitates rapid identification of connection states using magnetic link sensors and a distributed framework.
2. **Degeneration-Growth Assignment (DGA):** An improved fractal method based on L-systems to topologically describe the reconfiguration process and prevent hollow structures.
3. **Feasible Space map (FS_map):** A real-time generation technique for identifying connectable surface positions of immovable modules.
4. **Energy-cost-optimized A* algorithm:** Enhanced path planning with parallelization and priority-based collision avoidance.

## Results and Findings
- **Efficiency:** VCT reduces the computation time of generating movable modules by 51.2% compared to graph-link methods for 1,000 modules.
- **Path Planning:** The MPO algorithm decreases reconfiguration planning time per module by an average of 67.2% for 1,200 modules.
- **Total Performance:** Compared to the Graph-Based Configuration Search (GBCS), RSRMPO achieves a 93.3% reduction in planning time and an 85.3% reduction in energy consumption for 1,000-module random configurations.
- **Completion Rate:** RSRMPO achieved a completion rate of 89.85% in large-scale configurations (1,000 modules), which is 11.7% higher than GBCS.

## Conclusion
The RSRMPO framework provides a scalable and efficient solution for large-scale space orbital assembly. It effectively prevents the formation of deadlocking hollow structures during the reconfiguration process, though further research into decentralized growth trends for existing hollow structures is suggested.