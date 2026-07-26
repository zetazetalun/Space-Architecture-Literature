# Simulation and experimental validation of workspace computation for mobile cable-driven parallel robots in terrestrial and lunar environments

**Journal:** Journal of Mechanical Science and Technology 40 (3) 2026
**Authors:** Byeong-Geon Kim and Kyoung-Su Park
**DOI:** 10.1007/s12206-026-0205-1

## Abstract
This study aims to quantitatively analyze the workspace characteristics of a mobile cable-driven parallel robot (MCDPR) under varying gravitational conditions and to evaluate its applicability. To this end, we propose a workspace computation algorithm that comprehensively considers tension constraints, tipping prevention, and rotation prevention based on the static equilibrium conditions of the MCDPR. The validity of the proposed algorithm was verified through simulations and experiments, demonstrating strong agreement with theoretical predictions. Subsequently, simulations incorporating lunar gravity and friction conditions were conducted to analyze workspace variations in extraterrestrial environments. The results revealed how reduced gravitational force and friction affected the configuration of the workspace. This study suggests that autonomous construction technology based on MCDPR is feasible for lunar applications and provides foundational data for the design of future space construction platforms.

## 1. Introduction
With the growing interest in space exploration and the potential for planetary habitation, the demand for automated construction technologies in extreme environments such as the Moon is rapidly increasing. In response to these challenges, 3D additive construction has emerged as a promising approach for building infrastructure using in-situ resources. Currently, articulated robotic arms and gantry systems are the primary platforms used for 3D additive construction, but they face challenges regarding transportation costs (exceeding $4000/kg) and limited workspaces. As an alternative, the mobile cable-driven parallel robot (MCDPR) is proposed due to its simple structure, lightweight design, and high payload capacity.

## 2. Structure of the MCDPR
In this study, eight cables were adopted to control all six degrees of freedom of the end-effector. Four mobile platforms (differential drive robots) were employed to expand the workspace in the XY plane. 

## 3. Workspace computation algorithm
The workspace is defined as the spatial region where the end-effector can be positioned and controlled. Key criteria include:
- **Tension condition:** Tmin < T < Tmax.
- **Tipping condition:** Prevents the mobile platforms from tilting due to cable tension exceeding gravity-induced stability.
- **Rotating condition:** Prevents the robot from rotating around an axis perpendicular to the contact plane due to wheel slippage.

## 5. Workspace of the MCDPR in lunar environment
To investigate feasibility, the theoretical workspace under lunar conditions (one-sixth Earth's gravity, friction coefficient µ_moon = 0.6) was computed. Results show that while the tension-only workspace remains identical, the inclusion of tipping and rotating constraints significantly reduces the feasible operational space under reduced gravity.

## 6. Conclusion
The proposed algorithm achieved over 87% similarity with simulation and experimental results. Applying the algorithm to lunar conditions confirmed that the resulting workspace was reduced by approximately 34% compared to Earth. These findings provide practical data for designing MCDPR platforms for autonomous additive construction in lunar environments.