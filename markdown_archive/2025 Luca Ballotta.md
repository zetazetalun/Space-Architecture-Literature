# Safe Distributed Control of Multi-Robot Systems With Communication Delays

**Authors:** Luca Ballotta, Rajat Talak
**Journal:** IEEE Transactions on Vehicular Technology, 2025

## Abstract
Safe operation of multi-robot systems is critical, especially in communication-degraded environments such as underwater for seabed mapping, underground caves for navigation, and in **extraterrestrial missions for assembly and construction**. We address safety of networked autonomous systems where the information exchanged between robots incurs communication delays. We formalize a notion of distributed control barrier function (CBF) for multi-robot systems, a safety certificate amenable to a distributed implementation, which provides formal ground to using graph neural networks (GNNs) to learn safe distributed controllers. Further, we observe that learning a distributed controller ignoring delays can severely degrade safety. We finally propose a predictor-based framework to train a safe distributed controller under communication delays, where the current state of nearby robots is predicted from received data and age-of-information (AoI).

## I. Introduction
Mobile autonomous robot networked systems are increasingly being conceived to aid humans in oceanbed mapping, underground subterranean navigation, and **space exploration**. Safe and coordinated operation is critical, but operation environments often induce severe communication outages that make information exchange imperfect and delayed. This work addresses the question of safety in conjunction with imperfect information exchange.

## II. Setup and System Model
- **Robot Dynamics:** Robots fulfill a control task with dynamics $\dot{x}_i(t) = f(x_i(t), u_i(t))$.
- **Information Exchange:** Robots communicate through a wireless channel within a radius $R_c$. Transmissions are subject to delays.
- **Safety Requirements:** Defined via a safe set $S$ where robots must avoid collisions ($d_{coll}$). This is formalized through Control Barrier Functions (CBFs).

## III. Proposed Framework
1. **Distributed CBF:** A safety certificate using only local information available at each robot. 
2. **Learning-based Controller:** Uses Graph Neural Networks (GNNs) to learn safe distributed controllers that can scale to large robot teams.
3. **Predictor-based Training:** To handle communication delays, a predictor (parametrized as an LSTM) estimates the current state of neighbors from delayed measurements using the Age-of-Information (AoI).

## IV. Experimental Results
- **Control Tasks:** Multi-robot navigation for collision avoidance using single integrator and Dubins car models.
- **Safety Rate Performance:** 
  - Under perfect communication, the GNN controller maintains near 100% safety.
  - Under realistic communication delays, safety rates for standard controllers drop significantly.
  - The predictor-based controller restores safety, maintaining high safety rates (e.g., above 95% for single integrator even with delays).
- **Scalability:** The learned controller scales to double the robot density during testing compared to training without significant safety degradation.

## V. Conclusion
Communication delays disrupt safety certification if not accounted for. A predictor-based approach using AoI of exchanged information can effectively handle these delays, enabling safe autonomous construction and assembly in extreme environments like space.