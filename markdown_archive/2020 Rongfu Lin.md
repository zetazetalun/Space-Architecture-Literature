# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Affiliation:** State Key Laboratory of Mechanical Systems and Vibration, School of Mechanical Engineering, Shanghai Jiao Tong University, Shanghai, China

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The TMT method is universal and effective for topological design of robots which can transform between truss and mechanism.

## 1. Introduction
Deep space exploration mainly includes three missions: “Circling,” “Landing,” and “Returning”, while “Base construction” is a mission for the future. Legged stationary landers (LSLs) have advantages in stability and payload but limit exploration range. Legged mobile landers (LMLs) can meet the requirements of large area exploration and base construction. A significant challenge is the degree of freedom (DoF) contradiction: a lander must be a rigid truss (0 DoF) during landing to survive impact, but a multi-DoF mechanism for walking.

## 2. TMT Method for LMLs
### 2.1 Task Requirements
A novel LML should accomplish five functions:
1. Being deployable
2. Landing buffer
3. Walking
4. Orientation adjustment
5. Terrain adaptability

### 2.2 Novel Design Concept
A truss is considered a mechanism in a particular position without motion (Truss Position of Mechanism, TPM). The TMT method involves four stages:
- **Stage 1:** Motion requirements extraction.
- **Stage 2:** Truss design (using Euler’s polyhedron formula: $V - E + F = 2$).
- **Stage 3:** Motion design (allocating DoFs into the truss).
- **Stage 4:** Type evaluation (overconstraints and actuator location).

## 3. Design of Legs for LMLs
Based on the Chang’e lander structure (one main backbone and two auxiliary backbones), the following parameters were used:
- **Truss Topology:** $V=6, E=9, F=5$.
- **Upper Part:** Parallel mechanism for 3D translation (Mid-platform).
- **Lower Part:** Spherical joint ($S_M$) for terrain adaptability.

### Table 2: Distribution of DoF
| Cases | $C_1$ | $C_2$ | $C_3$ |
| :--- | :--- | :--- | :--- |
| Case 1 | 3 | 6 | 6 |
| Case 2 | 4 | 5 | 6 |
| Case 3 | 5 | 5 | 5 |

### Table 4: Typical configurations of legs
| Main backbones | Auxiliary backbones | Transmission limbs |
| :--- | :--- | :--- |
| **UR** | 2-RUS, 2-PUS, 2-PU*S | **RRR** |
| **UP** | 2-RUS, 2-PUS, 2-PU*S | **RSS** |
| **RU** | 2-RUS, 2-PUS, 2-PU*S | **PSS** |

## 4. Results and Analysis
Two typical LML legs were analyzed:
- **Type I (UP&2-RUS):** Uses RRR transmission limbs. During landing, links are collinear (TPM-DPB) to protect actuators from impact. Provides 6-DOF walking mobility after landing.
- **Type III (RU&2-RUS):** Uses electronic bolts to fix links during landing (TPM-FJB). Protects actuators by ensuring impact forces do not pass through the RU links.

## 5. Conclusion
The TMT method provides a systematic way to design robots that transform kinematics from a truss to a mechanism. Four typical novel LMLs were obtained, providing technical support for deep space exploration and base construction.