# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**DOI:** https://doi.org/10.1016/j.mechmachtheory.2020.103787

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The TMT method is universal and effective for topological design of robots which can transform between truss and mechanism.

## 1. Introduction
Deep space exploration involves missions including "Circling," "Landing," "Returning," and "Base construction." Current modes use a combination of a Legged Stationary Lander (LSL) and a rover. LMLs are proposed to overcome limitations in exploration range and pose adjustment, facilitating future base construction tasks.

## 2. Overall topological design concept and procedure of TMT method for LMLs
### 2.1. Task requirements of LMLs
A novel LML should accomplish five functions: 
1. Being deployable
2. Landing buffer
3. Walking
4. Orientation adjustment
5. Terrain adaptability

### 2.2. Novel design concept of TMT method
A truss is considered a mechanism in a particular position without motions (Truss Position of Mechanism, TPM), while a mechanism is a truss with added motions in its nodes and links.

## 3. TMT method for topological design of LMLs
The process involves four stages:
1. **Motion Requirements:** Extracting motions from tasks (Rotation/Translation rules).
2. **Truss Design:** Using Euler's polyhedron formula (V - E + F = 2) to design candidate space trusses.
3. **Motion Design:** Satisfying DOF conditions (Modified G-K criterion) and distributing motions into the truss links/nodes.
4. **Type Evaluation:** Using indexes like number of overconstraints and number of base-located actuators.

## 4. Innovative design of legs for LMLs based on TMT method
Structures were synthesized based on the Chang’e lander configuration. Four specific motion distributions suitable for legs were identified. The upper part is a parallel mechanism for 3D translation, while the lower part provides terrain adaptability via a spherical joint.

## 5. Two typical LMLs analyses
Two configurations were analyzed:
- **Case I:** UP&2-RUS with transmission limbs (actuators protected from landing impact).
- **Case III:** RU&2-RUS with electronic bolts (locking mechanisms to maintain truss rigidity during landing).

## 6. Conclusion
The TMT method provides a systematic approach for designing robots with dual capabilities (truss/mechanism). LMLs using this method can enhance exploration range and support base construction by providing orientation adjustment and terrain adaptability.

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| – | {E} | Rigid connection without relative motion |
| Line/Point | {R(N, u)} | 1-D rotation about axis parallel to unit vector u |
| Sphere | {S(N)} | 3-D rotation about point N |
| Arrow | {T(u)} | 1-D translation parallel to unit vector u |
| Box | {C(N, u)} | Cylindrical motion about the axis (N, u) |