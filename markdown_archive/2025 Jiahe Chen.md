# 2D construction planning for swarms of simple earthmover robots

**Authors:** Jiahe Chen, Kirstin Petersen
**Journal:** Autonomous Robots (2025) 49:37
**DOI:** https://doi.org/10.1007/s10514-025-10226-3

## Abstract
New settlements in remote environments require terrain modification, a task well suited for autonomous multi-robot systems. Simple, robust earthmover robots offer an inexpensive and scalable alternative to sophisticated construction robots. We present a mathematical model for such robots modifying continuous granular structures in 2D and develop both centralized and decentralized planning algorithms to achieve user-defined construction goals. These algorithms decompose long-horizon tasks into subtasks solvable using optimal transport theory and Wasserstein geodesics. Simulations show that a centralized controller achieves 85-92% construction progress. Multiple robots reduce overall travel distance by 70%. The distributed algorithm matches centralized performance on traversable terrain, reaching 93% progress. These results indicate promise for extraterrestrial habitat preparation.

## 1 Introduction
Robotics is envisioned to prepare hostile landscapes for colonization in the Arctic, deep sea, or outer space. NASA and private investors planning a return to the Moon and missions to Mars require robots capable of using in-situ materials to build landing pads, roads, foundations, and berms. Extreme conditions make long-term resilience and autonomy essential. This paper introduces a mathematical model and multi-robot planning algorithms based on minimalist robot mechanisms (single-actuator wave mechanism).

## 2 Abstract Model
The construction problem involves designing robot motion and action strategies to transform an initial granular structure into a target goal structure. The robot operates in two modes: one stationary mode for material movement and one for simultaneous locomotion and manipulation. The model incorporates height functions $h(x)$ and slope constraints $K=0.42$ for granular materials.

## 3 Planning Algorithm
Planning is formulated based on optimal transport theory and Wasserstein metrics. The 2-Wasserstein distance ($W_2$) is used to measure distance between structures and generate intermediate goal structures along a geodesic path.

### Table 1: Time complexity of distance metrics
| Dimension | $D_{L2}$ (Euclidean) | $D_{W2}$ (2-Wasserstein) |
|---|---|---|
| 1D | $O(L)$ | $O(L + M \log(L))$ |
| 2D | $O(L^2)$ | $O(KL^2 \log L)$ |
*L: sampling points, M: inverse CDF sampling, K: Sinkhorn iterations.*

## 4 Centralized Multi-robot Algorithm
The centralized algorithm (Algorithm 3) mitigates individual robot motion constraints and reduces travel distance by assigning tasks across multiple robots. It includes a flattening phase to expand traversable areas before the main construction phase.

## 5 Distributed Multi-robot Algorithm
The distributed algorithm (Algorithm 4) uses local sensing and limited interaction. Each robot follows a sense-plan-act loop, inferring local terrain shape and computing subgoals using local Wasserstein geodesics.

## 6 Evaluation and Results
- **Centralized Performance:** Average progress of 85% (untraversable) and 92% (traversable) terrains.
- **Efficiency:** 10 robots reduced total travel distance by 70% compared to a single robot (116m reduced to 35m).
- **Distributed Performance:** Reached 93% progress on traversable terrains with 7+ robots.
- **Failure Modes:** Distributed algorithms can create untraversable structures if local 'bad actions' occur, though increased robot numbers reduce these errors by 32%.

## 7 Conclusion
The framework demonstrates that geometry-aware planning using Wasserstein geodesics allows simple robot swarms to achieve complex terrain modification. This approach offers a scalable, resilient, and low-cost solution for extraterrestrial site preparation.