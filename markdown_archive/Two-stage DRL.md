# Two-stage DRL with hybrid perception of vision and force feedback for lunar construction robotic assembly control

**Authors:** Li Boxin, Wang Zhaokui  
**Journal:** Acta Astronautica 229 (2025) 357–373  
**DOI:** [10.1016/j.actaastro.2025.01.017](https://doi.org/10.1016/j.actaastro.2025.01.017)

## Abstract
Lunar construction is necessary for long-term deep space exploration and resource utilization. This paper proposes a two-stage Deep Reinforcement Learning (DRL) control method with hybrid perception of visual and force feedback for lunar construction robots to perform assembly operations end-to-end. A staged reward function based on visual pose norm and force feedback is designed. The method was verified via a 1:1 simulation scenario and a ground real-robot prototype using a sim-to-real pipeline with multi-Aruco visual calibration.

## Mission Overview
The mission scenario consists of Lunar Construction Smart Robots (LCSR), assembly objects, and the lunar environment. The LCSR includes an omnidirectional mobile chassis, a lifting mechanism, and a 6-DOF end effector equipped with a 6D force sensor and RGB-D cameras.

## Methodology
### Two-Stage DRL Control Strategy
1.  **First Stage (Free Spatial Posture Exploration):** Uses Vision-TD3 network to adjust the pose of the assembly part based on RGB-D images to align with a virtual target point.
2.  **Second Stage (Constrained Contact Interaction and Locking):** Uses Force-TD3 network for precise fine-tuning based on force-proprioception to complete the locking of the assembly mechanism.

### Reward Functions
- **Stage 1 Reward:** Based on visual pose norms (position and orientation differences).
- **Stage 2 Reward:** Based on the first-order derivative of piecewise force to handle contact interactions safely.

## Technical Data

### Table 1: Parameters of the Lunar Construction Robot and Components
| Parameters | Value |
| :--- | :--- |
| Chassis movement accuracy | 5 cm |
| Lifting-Z range | 0 m ~ 2.5 m |
| Lifting-Z accuracy | 3 mm |
| Longitudinal movement-X/Y range | ±60 mm |
| Pitch/Roll range | ±6° |
| Yaw range | ±180° |
| Assembly part weight | 200 kg |
| Insertion depth of locking mechanism | 60 mm |

### Table 2: Physical Sensor Parameters
| Parameters | Value |
| :--- | :--- |
| Visual resolution | 640 × 480 |
| Force sensor range | ±30 kN |
| Force sensor accuracy | 1 N |

## Results and Experiments
- **Simulation:** Networks converged after 250k–350k steps. Relative position error approached 5 mm and orientation angle error approached 2°.
- **Ground Experiment:** A sim-to-real pipeline using multi-Aruco calibration was implemented. The system achieved a **80% success rate** (24 out of 30 experiments) in autonomous assembly.

## Conclusion
The application of DRL and cross-disciplinary integration allows lunar robotic systems to perform complex assembly operations autonomously in open environments, bridging the gap between simulation and reality.
