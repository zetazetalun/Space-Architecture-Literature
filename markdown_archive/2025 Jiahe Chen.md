# 2D construction planning for swarms of simple earthmover robots

**Authors:** Jiahe Chen, Kirstin Petersen
**Published:** Autonomous Robots (2025) 49:37
**DOI:** https://doi.org/10.1007/s10514-025-10226-3

## Abstract
New settlements in remote environments require terrain modification, a task well suited for autonomous multi-robot systems. Simple, robust earthmover robots offer an inexpensive and scalable alternative to sophisticated construction robots. We present a mathematical model for such robots modifying continuous granular structures in 2D and develop both centralized and decentralized planning algorithms to achieve user-defined construction goals. These algorithms decompose long-horizon tasks into subtasks solvable using optimal transport theory and Wasserstein geodesics. Simulations across 100 randomly generated tasks show that a centralized controller with global information achieves on average 85% and 92% construction progress on untraversable and traversable terrains respectively, even with action noise. Multiple robots reduce overall travel distance by 70%, important because motion over the structure also disturbs it. The distributed algorithm—without global information—matches centralized performance on traversable terrain, reaching 93% progress. Increasing robot numbers accelerates convergence, lowers moved material, and raises convergence rates, though congestion can increase total travel distance. These results indicate that simple earthmover robots hold promise for construction tasks ranging from extraterrestrial habitat preparation to coastal protective berms.

## 1 Introduction
Robotics is often envisioned as a means to prepare remote, hostile landscapes for colonization, whether in the Arctic, the deep sea, or outer space. Government agencies and private investors planning an imminent return to the moon and future missions to Mars are driving innovations that call for robots capable of using in-situ materials to build landing pads, roads, foundations, and berms (Desai et al., 2022; Moses & Mueller, 2021). Current approaches typically rely on advanced actuation, high-speed communication, and sophisticated sensors. Yet the extreme conditions of extraterrestrial terrain modification create high risks of clogged mechanisms, dust-covered or saturated sensors, and robot entrapment; long-term resilience and autonomy are therefore essential. A promising alternative is to deploy swarms of simpler, more robust robots that can continue working even when individual units fail.

## 2 Abstract model
The construction problem is formulated as follows: Given initial and user-defined goal structures, how can we design a robot motion and action strategy such that the shape of the final structure is as close to the goal structure as possible? The model focuses on non-additive construction: agents cannot carry material from elsewhere but must push existing material to form a target shape.

### 2.1 Continuous structure modeling
The construction area $Q$ is set as an area with length $L$. The height function is a continuous, bounded, non-negative function $h: Q \rightarrow R^+$. The maximum steepness cannot exceed a constant $K = 0.42$, informed by real robot experiments (Huang et al., 2022).

## 6 Evaluation
To evaluate algorithmic performance, 100 random construction tasks were generated based on a mixed Gaussian model. 

### 6.2 Centralized multi-robot algorithm
As more robots are added, the algorithm achieves higher progress. The highest average progress is 85 ± 13% for ten robots, a 23% increase from the single-robot case. The average traveling distance drops from 116 ± 25m for one robot to 35 ± 5m for ten robots, a 70% decrease.

### 6.3 Distributed multi-robot algorithm
For traversable terrains, deploying 7 robots increases average construction progress from 62 ± 37% to 93 ± 17% (50% increase), and reduces construction time and volume of moved material from 1731 ± 786m to 1019 ± 367m (70% decrease) and 42 ± 21 to 21 ± 6 (50% decrease), respectively.

## 7 Conclusion
This paper introduced a novel framework for collective terrain modification by minimalistic earthmover robots using Wasserstein-based planning. Simulations demonstrated more reliable and scalable performance than the greedy baseline. Key results include: 1) for the centralized algorithm, deploying more robots can increase the average progress by 23% and reduce the traveling distance by 70%, and 2) for the distributed algorithm, deploying more robots can increase the average progress by 50% and reduce the construction time and volume of moved material by 70% and 50%, respectively.