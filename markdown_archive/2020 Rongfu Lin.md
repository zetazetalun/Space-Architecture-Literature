# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Date:** Available online 19 February 2020

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases.

## 1. Introduction
Space exploration is moving beyond "Circling" and "Landing" toward "Returning" and "Base construction." Existing landers are stationary (LSLs), limiting exploration range and ability to adjust pose for ascent or construction. Legged Mobile Landers (LMLs) are proposed to overcome these limitations by combining the stability and payload capacity of landers with the mobility of rovers.

## 2. Truss-Mechanism Transformation (TMT) Method
The core challenge is the Degree of Freedom (DoF) contradiction: landing requires a rigid truss (0 DoF) to withstand impact, while walking requires a multi-DoF mechanism. 

### Synthesis Procedure:
1. **Stage 1: Motion requirements** - Extracting motions from required tasks.
2. **Stage 2: Truss design** - Using Euler's polyhedron formula ($V - E + F = 2$) to design a stable base truss.
3. **Stage 3: Motion design** - Allocating motions into the truss nodes and links using Lie group theory and intersection rules.
4. **Stage 4: Type evaluation** - Evaluating structures based on overconstraints and the number of actuators on the base.

## 3. Technical Data and Tables

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| – | {E} | Rigid connection without relative motion |
| Line with dot | {R(N, u)} | 1-D rotation about axis u through point N |
| Circle with axis | {R(u)} | 1-D rotation around any axis parallel to u |
| Sphere | {S(N)} | 3-D rotation about point N |
| Arrow | {T(u)} | 1-D translation parallel to u |
| Parallelogram | {T(Pvw)} | 2-D translations within plane Pvw |
| Cylinder | {C(N, u)} | Cylindrical motion about axis (N, u) |
| Cube | {D} | 6 rigid body motion |

### Table 2: Distribution of DoF
| Cases | C1 | C2 | C3 |
| :--- | :--- | :--- | :--- |
| Case 1 | 3 | 6 | 6 |
| Case 2 | 4 | 5 | 6 |
| Case 3 | 5 | 5 | 5 |

### Table 4: Typical configurations of legs
| Main backbones | Auxiliary backbones | Transmission limbs |
| :--- | :--- | :--- |
| UR | 2-RUS, 2-PUS, 2-PU*S | RRR, PRR |
| UP | 2-RUS, 2-PUS, 2-PU*S | RSS, PSS |
| RU | 2-RUS, 2-PUS, 2-PU*S | - |

## 4. Key Findings
- **TMT Method Effectiveness:** The Truss-Mechanism Transformation method successfully synthesizes structures that function as rigid trusses for landing and mobile mechanisms for surface operations.
- **Chang'e-based Design:** The study applied TMT to the structure of the Chang'e lander, resulting in novel LML leg designs including (UP&2-RUS)-S and (RU&2-RUS)-S.
- **Functional Versatility:** These LMLs support five critical functions: deployability, landing buffering, walking, orientation adjustment, and terrain adaptability, essential for future base construction logistics.