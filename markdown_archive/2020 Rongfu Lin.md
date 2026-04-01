# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**DOI:** 10.1016/j.mechmachtheory.2020.103787

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper addresses a novel synthesis method based on Truss-Mechanism Transformation (TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. 

## 1. Introduction
Deep space exploration mainly includes three missions: “Circling,” “Landing,” and “Returning”, while “Base construction” is a mission for the future. Legged Stationary Landers (LSLs) have limitations in exploration range and pose adjustment. Legged Mobile Landers (LMLs) are proposed to satisfy the requirement of large area exploration and base construction.

## 2. TMT Method Concept
A novel LML should accomplish five functions:
1. Being deployable
2. Landing buffer
3. Walking
4. Orientation adjustment
5. Terrain adaptability

During the landing phase, the LML is considered a truss (zero DoF); during the walking phase, it is a multi-DoF robot. The TMT method manages this transformation.

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| – | {E} | Rigid connection without relative motion |
| Line with dot | {R(N, u)} | 1-D rotation about axis parallel to u through N |
| Circle/Axis | {R(u)} | 1-D rotation with infinite axis |
| Sphere | {S(N)} | 3-D rotation about point N |
| Arrow | {T(u)} | 1-D translation parallel to u |

## 3. Kinematic Synthesis
The degree of freedom (DoF) is established by the modified G-K criterion:
$$M_{DoF} = d(n - g - 1) + \sum f_i + v - \xi$$

## 4. Key Configurations
The paper evaluates structures based on the Chang’e lander, identifying two typical LML legs using either transmission limbs or electronic bolts to maintain Truss Position of Mechanism (TPM). 

### Typical leg configurations (Table 4 summary):
- **Main backbones:** UR, UP, RU
- **Auxiliary backbones:** 2-RUS, 2-URS, 2-PUS, 2-UPS, 2-PU*S, 2-U*PS
- **Transmission limbs:** RRR, PRR, RSS, PSS

## 5. Conclusion
LMLs provide technical support for deep space exploration by extending the range of exploration and allowing for base construction through flexible orientation and mobility. The TMT method allows for mechanisms that bear high impact (truss mode) and perform complex tasks (mechanism mode).