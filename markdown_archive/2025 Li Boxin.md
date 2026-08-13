# Two-stage DRL with hybrid perception of vision and force feedback for lunar construction robotic assembly control

**Authors:** Li Boxin, Wang Zhaokui  
**Affiliation:** School of Aerospace Engineering, Tsinghua University, Beijing, 100084, China  
**Published in:** Acta Astronautica 229 (2025) 357–373  
**DOI:** [10.1016/j.actaastro.2025.01.017](https://doi.org/10.1016/j.actaastro.2025.01.017)

## Abstract
Lunar construction is necessary for long-term deep space exploration and resource utilization. This paper proposes a two-stage Deep Reinforcement Learning (DRL) control method using hybrid perception (vision and force feedback) for lunar construction robots to perform assembly operations end-to-end. The method utilizes a Vision-TD3 network for free spatial alignment and a Force-TD3 network for constrained contact interaction and locking. Effectiveness is verified through a 1:1 simulation scenario and ground real-robot experiments, achieving an 80% success rate.

## 1. Introduction
Robotic assembly is critical for lunar surface exploration (e.g., Artemis program, China's manned lunar exploration). Unlike industrial settings, lunar construction occurs in open, unstructured environments with large communication delays, requiring autonomous intelligence. This research addresses the challenges of irregular shapes, unknown contact models, and the need for proprioceptive sensing.

## 2. Mission Overview
### 2.1 Lunar Construction Smart Robot (LCSR)
- **Components:** Omnidirectional mobile chassis, lifting mechanism, 6-DOF high-precision end effector.
- **Sensors:** 6-dimensional force sensor, two RGB-D eye-in-hand cameras.
- **Assembly Task:** Two-point docking with locking/release mechanisms.

## 3. Control Method
### 3.1 Two-Stage DRL Strategy
1.  **Stage 1: Free Spatial Posture Exploration:** Uses `Vision-TD3` to align the assembly part with a virtual target point using RGB-D data.
2.  **Stage 2: Constrained Contact Interaction:** Uses `Force-TD3` for fine-tuning and locking based on 6D force and torque feedback.

### 3.2 Reward Functions
- **Stage 1 Reward:** Based on visual pose norm difference between the current part pose and the virtual target point.
- **Stage 2 Reward:** Based on the first-order derivative of piecewise force to detect contact and successful locking while preventing part damage.

## 4. Technical Data and Specifications

### Table 1: Parameters of the Lunar Construction Robot and Components
| Parameters | Value |
| :--- | :--- |
| Chassis movement accuracy | 5 cm |
| Lifting-Z range | 0 m ~ 2.5 m |
| Lifting-Z accuracy | 3 mm |
| Pitch/Roll accuracy | 0.2° |
| Yaw accuracy | 0.5° |
| Assembly part weight | 200 kg |
| Insertion depth | 60 mm |

### Table 2: Physical Sensor Parameters
| Parameters | Value |
| :--- | :--- |
| Observation space | RGB-D Image |
| Visual resolution | 640 × 480 |
| Force sensor range | ±30 kN |
| Force sensor accuracy | 1 N |

### Table 3: Network Configuration
| Parameters | Value |
| :--- | :--- |
| Batch size | 8 |
| Reward discount (γ) | 0.99 |
| Actor learning rate | 3 × 10⁻⁴ |
| Critic learning rate | 3 × 10⁻⁴ |

## 5. Results and Analysis
### 5.1 Simulation Experiments
- **Vision-TD3:** Converged after ~250k steps. Successfully reduced relative distance to <5 mm and orientation error to <2°.
- **Force-TD3:** Converged after ~350k steps. Force feedback $N_p$ threshold was set at 4000 N.

### 5.2 Ground Experiments
- **Sim-to-Real Pipeline:** Utilized multi-Aruco visual calibration to bridge the reality gap.
- **Success Rate:** 80% (24 out of 30 experiments completed successfully).

## 6. Conclusion
The two-stage DRL method successfully enables autonomous assembly in unstructured environments. Future work focuses on embodied intelligence and parallel intelligence for ground-moon synchronous verification.