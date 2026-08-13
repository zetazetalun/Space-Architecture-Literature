# Growing fast and steady in space: Distributed rapid self-reconfiguration motion planning optimization methods for swarm intelligent space modular self-reconfigurable satellites

## Authors
Lei Chen, Naiming Qi, Mingying Huo, Qiufan Yuan, Ze Yu, Wenyu Feng

## Abstract
The large-scale self-reconfiguration of Space Modular Self-Reconfigurable Satellites (SMSRS) faces critical challenges in computational complexity and efficiency. This study proposes a Rapid Self-Reconfiguration Motion Planning Optimization (RSRMPO) method based on a distributed framework for pivoting cube modular systems. The framework includes a Virtual Connection technique, Degeneration-Growth Assignment (DGA), real-time Feasible Space map (FS_map) generation, and an energy-cost-optimized A* path planning algorithm. Simulation experiments with up to 1,200 modules demonstrate significant improvements in planning time, energy consumption, and completion rates compared to traditional graph-based searches.

## 1. Introduction
Spacecraft missions are becoming increasingly complex, leading to higher costs and longer launch cycles. Space Modular Self-Reconfigurable Satellites (SMSRS) offer reusability, interchangeability, and robustness. These systems can self-assemble into various structures like large-aperture telescopes or deployable configurations for maneuvering and orbital capture.

## 2. Methodology
### Distributed Strategy
The strategy is divided into:
1. **High-level tasks:** Assignment planning (mapping modules to target positions) and map generation.
2. **Low-level tasks:** Path planning, motion execution, and collision avoidance.

### Assignment Optimization
- **Virtual Connection Technique (VCT):** Uses magnetic link sensors and a distributed framework to rapidly identify connection states.
- **Degeneration-Growth Assignment (DGA):** An improved fractal method based on L-systems to topologically describe the reconfiguration process, preventing hollow structures.

### Motion Planning
- **FS_map:** A real-time generation technique for finite feasible space maps based on connectable surfaces of immovable modules.
- **Enhanced A* Algorithm:** Incorporates a transfer gradient heuristic function (including Euclidean distance and motion steps) to minimize total transfer steps.

## 3. Results and Discussion
Simulation of reconfigurations spanning 10 to 1,200 modules showed:
- **Computational Efficiency:** VCT reduces computation time for movable modules by 51.2% in 1,000-module scenarios.
- **Path Planning:** The MPO algorithm decreases reconfiguration planning time by an average of 67.2%.
- **Performance Metrics:** For 1,000 modules with 50% overlap, RSRMPO achieved a 93.3% reduction in planning time and 85.3% reduction in energy consumption compared to GBCS.
- **Completion Rate:** RSRMPO reached a completion rate of 89.85% for 1,000 modules, which is 11.7% higher than centralized methods.

## 4. Conclusion
The RSRMPO framework provides near-optimal solutions for large-scale reconfiguration (10-1,200 modules). It effectively prevents the formation of hollow structures and ensures structural robustness for orbital assembly and deep-space missions.