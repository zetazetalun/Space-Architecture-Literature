# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Affiliation:** State Key Laboratory of Mechanical Systems and Vibration, Shanghai Jiao Tong University, China  

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The overall topological design concept and procedure of TMT method are proposed. Based on the extract rules and intersection operations of the motions, the motion requirements for TMT method are obtained. Numerous structures of LMLs based on the structure of Chang’e lander are synthesized.

## 1. Introduction
Deep space exploration mainly includes three missions: “Circling,” “Landing,” and “Returning”, while “Base construction” is a mission for the future. Legged stationary landers (LSLs) are limited in their exploration range and cannot adjust their pose, which is disadvantageous for providing the adequate conditions for the ascent and base construction in the future. The proposal of LMLs can meet the requirement of large area exploration and base construction.

## 2. Novel Design Concept (TMT Method)
The TMT method views a truss as a mechanism in a particular position without motions (Truss Position of Mechanism, TPM). The transformation between landing (truss-like stability) and walking (mechanism-like mobility) is the core challenge. 

### Task Requirements of LMLs
A novel LML should accomplish five functions:
1. Being deployable
2. Landing buffer
3. Walking
4. Orientation adjustment
5. Terrain adaptability

## 3. Technical Tables

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| – | {E} | Rigid connection without relative motion |
| (Line with point) | {R(N, u)} | 1-D rotation about axis parallel to unit vector **u** passing through N |
| (Line/sphere) | {S(N)} | 3-D rotation about point N |
| (Arrow) | {T(u)} | 1-D translation parallel to the unit vector **u** |
| (Block) | 3T | 3-D translations in space |
| (Cylinder) | {C(N, u)} | Cylindrical motion about the axis (N, u) |

### Table 2: Distribution of DoF
| Cases | C1 (Limb 1) | C2 (Limb 2) | C3 (Limb 3) |
| :--- | :--- | :--- | :--- |
| Case 1 | 3 | 6 | 6 |
| Case 2 | 4 | 5 | 6 |
| Case 3 | 5 | 5 | 5 |

### Table 4: Typical configurations of legs
| Main backbones | Auxiliary backbones | Transmission limbs |
| :--- | :--- | :--- |
| **UR** | 2-RUS, 2-PUS, 2-PU*S | **RRR**, PRR |
| **UP** | 2-RUS, 2-PUS, 2-PU*S | **RSS**, PSS |
| **RU** | 2-RUS, 2-PUS, 2-PU*S | - |

## 4. Key Results
The study synthesized four typical novel LMLs based on the Chang'e lander configuration. These landers utilize electromagnetic bolts or transmission limbs to transition between a rigid structure for impact absorption during landing and a multi-degree-of-freedom robot for surface mobility. The results show that 4-{(UP&2-RUS)-S} and 4-{(RU&2-RUS)-S} configurations effectively support 6-D motions for walking and orientation adjustment.

## 5. Conclusion
The TMT method provides a systematic approach for designing multi-functional robots for deep space. LMLs designed this way can extend the range of exploration and provide technical support for base construction and other complex space missions.