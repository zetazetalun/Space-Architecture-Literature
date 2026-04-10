# Topological design of a new family of legged mobile landers based on Truss-Mechanism Transformation method

**Journal:** Mechanism and Machine Theory 149 (2020) 103787  
**Authors:** Rongfu Lin, Weizhong Guo, Changjie Zhao, Youyuan Tang, Chenyao Zhao, Ziyue Li  
**Affiliation:** Shanghai Jiao Tong University, China  

## Abstract
To meet the needs of the “Returning” and “Base construction” missions of the extraterrestrial body’s exploration task, it is necessary to enable the legged stationary lander (LSL) to walk, i.e., it is important and imperative to design novel legged mobile landers (LMLs). This paper aims to address a novel synthesis method based on Truss-Mechanism Transformation (called as TMT method) for LMLs with the capabilities of trusses and mechanisms during different phases. The overall topological design concept and procedure of TMT method are proposed. Numerous structures of LMLs based on the structure of Chang’e lander are synthesized. The TMT method is universal and effective for topological design of robots which can transform between truss and mechanism.

## 1. Introduction
Space exploration missions are evolving from circling and landing to "Base construction." Existing legged stationary landers (LSLs) are limited in their exploration range. Legged mobile landers (LMLs) are proposed to overcome these limitations, providing the capability for large-area exploration and site adjustment for construction. The main challenge is the degree of freedom (DoF) contradiction: a lander must behave as a rigid truss during landing to absorb impacts but as a multi-DoF mechanism for walking.

## 2. Truss-Mechanism Transformation (TMT) Method
The TMT method involves four stages:
1.  **Motion Requirements:** Extracting necessary motions (rotation/translation) from the mission tasks.
2.  **Truss Design:** Using Euler's polyhedron formula ($V - E + F = 2$) to design the initial rigid structure.
3.  **Motion Design:** Allocating joints into the truss edges and nodes while ensuring the structure can return to a "Truss Position of Mechanism" (TPM) during landing.
4.  **Type Evaluation:** Assessing mechanisms based on overconstraints and actuator placement.

## 3. Results and Configurations
The study used the Chang’e lander structure as a basis. The legs consist of an upper parallel mechanism and a lower terrain-adaptability joint.

### Table 4: Typical configurations of legs
| Main backbones | Auxiliary backbones | Transmission limbs |
| :--- | :--- | :--- |
| **UR** | 2-RUS, 2-PUS, 2-PU*S | **RRR**, PRR |
| **UP** | **2-RUS**, 2-PUS, 2-PU*S | **RSS**, PSS |
| **RU** | **2-RUS**, 2-PUS, 2-PU*S | - |

*Note: Bold items represent configurations analyzed as typical examples (Type I-IV).* 

## 4. Conclusion
The TMT method provides a systematic approach to design robots that transform kinematics between a truss and a mechanism. Four novel LML types were obtained, capable of landing, walking, and orientation adjustment, providing technical support for future deep space base construction.