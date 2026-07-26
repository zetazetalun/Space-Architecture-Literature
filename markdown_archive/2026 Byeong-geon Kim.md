# Simulation and experimental validation of workspace computation for mobile cable-driven parallel robots in terrestrial and lunar environments

**Journal of Mechanical Science and Technology 40 (3) 2026**

**Authors:** Byeong-Geon Kim and Kyoung-Su Park
**Department:** Mechanical Engineering, Gachon University, Korea
**DOI:** 10.1007/s12206-026-0205-1

## Abstract
This study aims to quantitatively analyze the workspace characteristics of a mobile cable-driven parallel robot (MCDPR) under varying gravitational conditions and to evaluate its applicability. To this end, we propose a workspace computation algorithm that comprehensively considers tension constraints, tipping prevention, and rotation prevention based on the static equilibrium conditions of the MCDPR. The validity of the proposed algorithm was verified through simulations and experiments, demonstrating strong agreement with theoretical predictions. Subsequently, simulations incorporating lunar gravity and friction conditions were conducted to analyze workspace variations in extraterrestrial environments. The results revealed how reduced gravitational force and friction affected the configuration of the workspace. This study suggests that autonomous construction technology based on MCDPR is feasible for lunar applications and provides foundational data for the design of future space construction platforms.

## 1. Introduction
With the growing interest in space exploration and the potential for planetary habitation, the demand for automated construction technologies in extreme environments such as the Moon is rapidly increasing. In such settings, the difficulty of human involvement and the limitations in resource utilization necessitate autonomous and efficient construction methods. In response to these challenges, 3D additive construction has emerged as a promising approach for building infrastructure using in-situ resources.

As an alternative to conventional articulated robotic arms and gantry systems (which weigh over 3 tons and face high transportation costs), the mobile cable-driven parallel robot (MCDPR) has been proposed. MCDPR utilizes multiple cables to fix and control an end-effector, offering a lightweight design, high payload capacity, and a wide workspace suitable for additive construction at various scales.

## 2. Structure of the MCDPR
In this study, eight cables were adopted to control all six degrees of freedom of the end-effector. To expand the workspace in the XY plane, four mobile platforms were employed. Each mobile platform is a differential drive robot equipped with two drive motors and one caster wheel.

## 3. Workspace Computation Algorithm
The workspace of the MCDPR refers to the spatial region where the end-effector can be positioned and controlled. The algorithm considers three key conditions:
1. **Tension Condition:** Ensures cables remain taut ($T_{min} < T < T_{max}$).
2. **Tipping Condition:** Prevents the mobile platforms from tilting when cable tension moments exceed gravity moments.
3. **Rotating Condition:** Prevents wheel slippage and rotational instability of the mobile units.

## 4. Results and Validation

### Table 1. 3D positions of the pulleys used in the MCDPR prototype.
| | a1 | a2 | a3 | a4 | a5 | a6 | a7 | a8 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| x [mm] | 348.3 | -350.4 | -354.0 | 349.3 | 376.6 | -376.9 | -376.9 | 376.6 |
| y [mm] | 285.8 | 286.7 | -287.1 | -285.8 | 313.6 | 313.7 | 313.4 | 313.6 |
| z [mm] | 274.0 | 274.0 | 273.7 | 274.0 | 1034.3 | 1035.7 | 1035.0 | 1035.6 |

### Table 2. Comparison of workspaces.
| Workspace | Overlap (%) | Relative area (%) |
| :--- | :---: | :---: |
| Theory-based vs Simulation-based | 91.5 | 92.2 |
| Theory-based vs Experiment-based | 87.4 | 93.4 |

## 5. Workspace of the MCDPR in lunar environment
Simulation under lunar conditions (one-sixth Earth gravity, $\mu_{moon}=0.6$) showed that the workspace defined solely by tension remained unchanged. However, when tipping and rotating conditions were included, the overall workspace decreased by 34%. This reduction is attributed to the lower gravity weakening resistance against tipping moments and reducing frictional force at the wheels.

## 6. Conclusion
The proposed algorithm allows for precise estimation of a robot's feasible operational space. Notably, the lunar workspace was constrained along diagonal directions due to tipping and front-rear directions due to rotating conditions. These findings provide practical data for designing MCDPR platforms for autonomous additive construction on the Moon.