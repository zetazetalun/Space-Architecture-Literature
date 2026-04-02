# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787

**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The overall topological design concept and procedure of TMT method are proposed. Based on the extract rules and intersection operations of the motions, the motion requirements for TMT method are obtained. The number condition, the relationship among motions and the methods for allocating the motions in the truss for TMT method are proposed. Some qualitative evaluations are also proposed. By means of this method, numerous structures of LMLs based on the structure of Chang’e lander are synthesized. Finally, after type evaluation, two typical LMLs’ legs with transmission limbs or electronic bolts are taken as examples to analyze the properties and abilities of LMLs during different phases. The TMT method is universal and effective for topological design of robots which can transform between truss and mechanism.

## 1. Introduction
The project of landing on and exploring extraterrestrial bodies, such as the Moon, Mars, and other asteroids, is an important strategy for some nations to develop the project of deep space exploration. Deep space exploration mainly includes three missions: “Circling,” “Landing,” and “Returning”, while “Base construction” is a mission for the future. LSLs (Legged Stationary Landers) have the advantages on landing stability and payload capacity. However, for base construction, it is necessary to let the LSL walk to widen the exploration area. The proposal of LMLs (Legged Mobile Landers) can meet the requirements of large area exploration and future construction.

## 2. Overall topological design concept and procedure of TMT method for LMLs

### 2.1. Task requirements of LMLs
A novel LML should accomplish five functions: being deployable, landing buffer, walking, orientation adjustment, and terrain adaptability. During landing, it acts as a truss; during walking, it acts as a multi-DoF robot.

### 2.2. Novel design concept of TMT method
(1) The topological arrangements of a truss and the corresponding mechanism without motion can be the same.
(2) The positions or configurations can be transferred.
(3) Truss nodes and links determine joint positions.

## 3. TMT method for topological design of LMLs

### 3.1. Motion requirements for TMT method
Extraction rules define rotation (R-motion) and translation (T-motion) requirements. Intersection rules (Lie subgroups) are used to integrate these motions.

**Table 1: Symbols definition and explanation [27]**
| Symbol | Subgroup | Motion |
|---|---|---|
| – | {E} | Rigid connection without relative motion |
| —○— | {R(N, u)} | 1-D rotation about axis parallel to unit vector u through point N |
| —□— | {R(u)} | 1-D rotation around any axis parallel to u (infinite axis) |
| (Sphere) | {S(N)} | 3-D rotation about point N |
| —→— | {T(u)} | 1-D translation parallel to u |
| —||— | {T(Pvw)} | 2-D translations within plane Pvw |
| (Box) | 3T | 3-D translations in space |
| (Cylinder) | {C(N, u)} | Cylindrical motion about axis (N, u) |
| (Double Sphere) | {D} | 6 rigid body motion |

### 3.2. Truss design for TMT method
Trusses are designed based on Euler’s polyhedron formula: $V - E + F = 2$.

### 3.3. Motion design for TMT method
#### 3.3.1 Number condition
The DoF of a mechanism ($M_{DoF}$) is established using the modified G-K criterion:
$M_{DoF} = d(n - g - 1) + \sum f_i + v - \xi$

#### 3.3.3 Allocating motions in the truss
- **Dead Point Based TPM (TPM-DPB):** Singularity positions used to lock limbs during landing.
- **Fixed Joint Based TPM (TPM-FJB):** Limiting positions or locking devices (e.g., electronic bolts) used to lock limbs.

## 4. Innovative design of legs for LMLs based on TMT method
Using the Chang’e lander structure (one main backbone, two auxiliary backbones) as a base, new leg structures are synthesized.

**Table 4: Typical configurations of legs**
| Main backbones | Auxiliary backbones | Transmission limbs |
|---|---|---|
| UR | 2-RUS, 2-PUS, 2-PU*S | RRR, PRR |
| UP | 2-RUS, 2-PUS, 2-PU*S | RSS, PSS |
| RU | 2-RUS, 2-PUS, 2-PU*S | - |

## 5. Two typical LMLs analyses
- **Case I:** UP&2-RUS with RRR transmission limbs. In the stowed position, the leg rotates around U joints. In landing, auxiliary backbones reach TPM-DPB (dead point) to bear impact.
- **Case III:** RU&2-RUS with electromagnetic bolts. Electronic bolts fix auxiliary backbones during landing to bearing large impact.

## 6. Conclusion
TMT method provides a systematic approach for designing robots that transform between truss and mechanism structures. This allows landers to survive high-impact landings while retaining high mobility for exploration and extraterrestrial base construction.