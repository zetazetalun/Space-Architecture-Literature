# Safe Distributed Control of Multi-Robot Systems With Communication Delays

## Abstract
Safe operation of multi-robot systems is critical, especially in communication-degraded environments such as underwater for seabed mapping, underground caves for navigation, and in extraterrestrial missions for assembly and construction. We address safety of networked autonomous systems where the information exchanged between robots incurs communication delays. We formalize a notion of distributed control barrier function for multi-robot systems, a safety certificate amenable to a distributed implementation, which provides formal ground to using graph neural networks to learn safe distributed controllers. Further, we observe that learning a distributed controller ignoring delays can severely degrade safety. We finally propose a predictor-based framework to train a safe distributed controller under communication delays, where the current state of nearby robots is predicted from received data and age-of-information. Numerical experiments on multi-robot collision avoidance show that our predictor-based approach can significantly improve the safety of a learned distributed controller under communication delays.

## Introduction
Mobile autonomous robot networked systems are increasingly being conceived to aid humans in oceanbed mapping, underground navigation, search-and-rescue, and space exploration. Safe and coordinated operation is critical, but operational environments often induce communication outages and delays. This paper addresses safety via Control Barrier Functions (CBFs) in a distributed, networked context.

## Methodology
1. **Distributed Control Barrier Functions (CBFs):** The authors define a safe set where robots are individually safe based on their neighbors' states, ensuring global safety through local forward invariance.
2. **Learning Safe Controllers:** Graph Neural Networks (GNNs) are used to implement the distributed controller, allowing for scalability to large robot teams and minimizing global computation needs.
3. **Predictor-based Framework:** To handle communication delays, a predictor (implemented as an LSTM) estimates the current relative states of neighbors based on received data and Age-of-Information (AoI).

## Experimental Results
- **Perfect Communication:** The GNN-based controller maintains a 100% safety rate for single integrator models and >80% for the complex Dubins car model even as robot density doubles.
- **Realistic Information Exchange (Delays):** Controllers that ignore delays show significant safety degradation. The proposed predictor-based controller restores safety performance, significantly outperforming standard GNN controllers under high delay coefficients (cdel).
- **Scalability:** The approach generalizes well to robot densities higher than those seen during training.

## Conclusion
The study provides a principled approach to solving control problems with delays in multi-robot systems, emphasizing that predicting neighbor states using information freshness (AoI) is critical for autonomous assembly and construction tasks in space.