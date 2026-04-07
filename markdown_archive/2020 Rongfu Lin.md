# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Affiliation:** Shanghai Jiao Tong University, China

## Abstract
To meet the needs of the 'Returning' and 'Base construction' missions of extraterrestrial exploration, it is necessary to enable legged stationary landers (LSL) to walk, creating legged mobile landers (LMLs). This paper proposes a novel synthesis method based on Truss-Mechanism Transformation (TMT) for LMLs. The method allows the structure to act as a truss during landing (to bear high impact) and a multi-DOF mechanism during walking. Using the Chang’e lander structure as a base, several LML leg structures are synthesized and evaluated.

## 1. Introduction
Deep space exploration involves 'Circling', 'Landing', and 'Returning', with 'Base construction' as a future goal. Existing landers (LSLs) are stationary, which limits exploration range and pose adjustment for ascent or construction. LMLs overcome these limits by combining the stability of landers with the mobility of rovers.

## 2. Truss-Mechanism Transformation (TMT) Method
### 2.1 Task Requirements
LMLs must perform five functions: 
1. Being deployable 
2. Landing buffer 
3. Walking 
4. Orientation adjustment 
5. Terrain adaptability

### 2.2 Design Concept
The TMT method addresses the Degree of Freedom (DoF) contradiction: a lander needs 0 DoF (truss) during landing but multiple DoFs (mechanism) for walking. 

### 2.3 Procedure
- **Stage 1:** Extract motion requirements from tasks.
- **Stage 2:** Design space trusses based on polyhedrons (Euler’s formula: V - E + F = 2).
- **Stage 3:** Allocate motions into the truss using intersection operations and Lie group theory.
- **Stage 4:** Type evaluation (overconstraints and actuator placement).

## 3. Technical Tables

### Table 1: Symbols definition and explanation
| Symbol | Subgroup | Motion |
| :--- | :--- | :--- |
| - | {E} | Rigid connection without relative motion |
| Line/Dot | {R(N, u)} | 1-D rotation about axis parallel to u through N |
| Circle/Axis | {R(u)} | 1-D rotation around any axis parallel to u |
| Sphere | {S(N)} | 3-D rotation about point N |
| Arrow | {T(u)} | 1-D translation parallel to u |
| Plate | {T(Pvw)} | 2-D translations within plane Pvw |
| Box | 3T | 3-D translations in space |
| Cylinder | {C(N, u)} | Cylindrical motion about axis (N, u) |
| Sphere/Cross | {D} | 6 rigid body motion |

### Table 4: Typical configurations of legs
| Main backbones | Auxiliary backbones | Transmission limbs |
| :--- | :--- | :--- |
| **UR** | 2-RUS, 2-PUS, 2-PU*S | **RRR**, PRR |
| **UP** | 2-RUS, 2-PUS, 2-PU*S | **RSS**, PSS |
| **RU** | 2-RUS, 2-PUS, 2-PU*S | - |

## 4. Key Results
- **Type I (UP&2-RUS)-S:** Uses RRR transmission limbs. In landing position, auxiliary backbone links are collinear to reach the Dead Point (TPM-DPB), protecting actuators from impact forces.
- **Type III (RU&2-RUS)-S:** Uses electronic bolts to fix joints during landing (TPM-FJB). 
- **Mobility:** Both types achieve 6-D motions in walking mode, allowing flexible surface traversal and orientation adjustment for base construction modules.

## 5. Conclusion
The TMT method provides a universal framework for designing robots that transform between truss and mechanism. The resulting LMLs support larger exploration ranges and provide technical support for future extraterrestrial base construction.