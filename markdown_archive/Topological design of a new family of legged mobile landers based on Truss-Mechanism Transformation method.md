# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory  
**Volume:** 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li

## Abstract
To meet the needs of the 'Returning' and 'Base construction' missions of the extraterrestrial body's exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The overall topological design concept and procedure of TMT method are proposed. Based on the extract rules and intersection operations of the motions, the motion requirements for TMT method are obtained. The number condition, the relationship among motions and the methods for allocating the motions in the truss for TMT method are proposed. Some qualitative evaluations are also proposed. By means of this method, numerous structures of LMLs based on the structure of Chang'e lander are synthesized. Finally, after type evaluation, two typical LMLs' legs with transmission limbs or electronic bolts are taken as examples to analyze the properties and abilities of LMLs during different phases. The TMT method is universal and effective for topological design of robots which can transform between truss and mechanism.

## 1. Introduction
The exploration of extraterrestrial bodies (Moon, Mars, asteroids) involves 'Circling', 'Landing', and 'Returning', with 'Base construction' as a future objective. Current modes utilize stationary landers and rovers. Legged stationary landers (LSLs) offer stability but lack mobility, limiting the exploration range. Legged mobile landers (LMLs) are proposed to overcome these limitations, requiring novel kinematic architectures that can serve as rigid trusses during landing and mobile mechanisms during surface operations.

## 2. Overall topological design concept and procedure of TMT method
### 2.1. Task requirements of LMLs
An LML must accomplish five functions:
1. Being deployable
2. Landing buffer
3. Walking
4. Orientation adjustment
5. Terrain adaptability

The configuration during landing needs to be stationary (no DoF), while the walking phase requires multiple DoFs.

### 2.2. Novel design concept
- A truss is considered a mechanism in a specific position without motion.
- A mechanism is a truss with added motions in its nodes and links.
- Transformation between these states is the core of the TMT method.

## 3. TMT method for topological design of LMLs
### 3.1. Motion requirements
- **Rule 1 (Rotation):** {R(N, u)}
- **Rule 2 (Translation):** {T(u)}
- Integration via intersection rules of Lie subgroups or submanifolds.

### 3.2. Truss design
Based on Euler’s polyhedron formula: $V - E + F = 2$.
1. Determine vertices (V), edges (E), and faces (F).
2. Select a base platform face; edges represent mechanism limbs ($EL = n_{TL}$).

### 3.3. Motion design
Satisfies the modified G-K criterion for Degree of Freedom ($M_{DoF}$):
$M_{DoF} = d(n - g - 1) + \sum f_i + v - \xi$

Methods to maintain the Truss Position of Mechanism (TPM):
- **TPM-DPB:** Dead Point Based (singularity position).
- **TPM-FJB:** Fixed Joint Based (locking devices/electronic bolts).

## 4. Innovative design of legs based on Chang'e structure
The Chang'e-3 structure is used as a baseline ($V=6, E=9, F=5$). The upper part is a parallel mechanism; the lower part is a passive spherical joint (S) for terrain adaptability.

| Typical Leg Configurations | Main Backbones | Auxiliary Backbones | Transmission Limbs |
|---|---|---|---| 
| Case I | UP | 2-RUS | RRR |
| Case II | UP | 2-RUS | Electronic bolt |
| Case III | RU | 2-RUS | Electronic bolt |

## 5. Typical LMLs analyses
- **Type I:** Uses RRR transmission limbs to protect actuators from high-impact forces during landing.
- **Type III:** Uses electronic bolts to fix the RU link of the main backbone and US links of auxiliary backbones during landing.
- Both designs demonstrate 6-DoF flexible walking and orientation adjustment capabilities.

## 6. Conclusion
The TMT method provides a systematic approach for designing robots that transition between truss and mechanism states. This is critical for deep space exploration where robots must endure high landing impacts and then perform complex mobility tasks for base construction.