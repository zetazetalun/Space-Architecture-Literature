# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Affiliation:** State Key Laboratory of Mechanical Systems and Vibration, School of Mechanical Engineering, Shanghai Jiao Tong University, China

## Abstract
To support extraterrestrial base construction, legged stationary landers (LSLs) need to be evolved into legged mobile landers (LMLs). This study proposes the Truss-Mechanism Transformation (TMT) method, which allows structures to behave as rigid trusses for landing and as mobile mechanisms for walking. Using intersection operations and motion requirements, various LML structures are synthesized and evaluated.

## 1. Introduction
Space exploration missions are transitioning from 'Circling' and 'Landing' to 'Base construction'. Current landers are stationary, limiting exploration range. LMLs combine the stability of landers with the mobility of rovers, which is critical for future large-scale base infrastructure development.

## 2. Overall topological design concept and procedure
LMLs must achieve five functions: deployability, landing buffering, walking, orientation adjustment, and terrain adaptability. The core challenge is the Degree of Freedom (DoF) contradiction: a lander needs 0 DoF during landing to act as a truss but multiple DoFs to walk.

## 3. TMT method for topological design
- **Stage 1:** Extract motion requirements from tasks.
- **Stage 2:** Design trusses based on polyhedral units (Euler’s formula: V - E + F = 2).
- **Stage 3:** Allocate motions into the truss using Lie group theory and intersection rules.
- **Stage 4:** Evaluate types based on overconstraints and actuator placement.

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| – | {E} | Rigid connection without relative motion |
| Line with dot | {R(N, u)} | 1-D rotation about axis parallel to unit vector u through point N |
| Circle with axis | {R(u)} | 1-D rotation with infinite axis |
| Sphere | {S(N)} | 3-D rotation about point N |
| Arrow | {T(u)} | 1-D translation parallel to unit vector u |
| Parallelogram | {T(Pvw)} | 2-D translations within plane Pvw |
| Cube | 3T | 3-D translations in space |
| Cylinder | {C(N, u)} | Cylindrical motion about axis (N, u) |
| Crossed Circle | {D} | 6 rigid body motion |

## 4. Innovative design of legs for LMLs
The structure of the Chang’e lander serves as a basis, consisting of one main backbone and two auxiliary backbones per leg. The TMT method is applied to allow these legs to transform between truss and walking configurations.

### Table 2: Distribution of DoF
| Cases | Ci (C1) | Ci (C2) | Ci (C3) |
| :--- | :--- | :--- | :--- |
| Case 1 | 3 | 6 | 6 |
| Case 2 | 4 | 5 | 6 |
| Case 3 | 5 | 5 | 5 |

### Table 3: Backbones with {D}
| Joints | Limbs |
| :--- | :--- |
| P U S | UPS, PUS, PSU, SPU |
| R U S | RUS, RSU, URS, SRU |
| Pa U U* S | UPaS, PaUS, PU*S, PaU*S |

## 5. Two typical LMLs analyses
Analysis verifies configurations for stowed, landing, walking, and orientation phases. Case studies demonstrate how joints are protected from impact using electromagnetic bolts or specific singularity positions (Dead Points).

## 6. Conclusion
The TMT method effectively designs robots with dual truss-mechanism capabilities. This provides technical support for deep space exploration and the expansion of detection ranges through mobile base-building assets.