# Safe Distributed Control of Multi-Robot Systems With Communication Delays

**Authors:** Luca Ballotta and Rajat Talak, Member, IEEE
**Status:** Accepted for publication in the IEEE Transactions on Vehicular Technology, 2025.

## Abstract
Safe operation of multi-robot systems is critical, especially in communication-degraded environments such as underwater for seabed mapping, underground caves for navigation, and in extraterrestrial missions for assembly and construction. We address safety of networked autonomous systems where the information exchanged between robots incurs communication delays. We formalize a notion of distributed control barrier function for multi-robot systems, a safety certificate amenable to a distributed implementation, which provides formal ground to using graph neural networks to learn safe distributed controllers. Further, we observe that learning a distributed controller ignoring delays can severely degrade safety. We finally propose a predictor-based framework to train a safe distributed controller under communication delays, where the current state of nearby robots is predicted from received data and age-of-information. Numerical experiments on multi-robot collision avoidance show that our predictor-based approach can significantly improve the safety of a learned distributed controller under communication delays.

## I. Introduction
Mobile autonomous robot networked systems are increasingly being conceived to aid humans in oceanbed mapping, underground subterranean navigation, search-and-rescue missions, and space exploration [1]–[5]. Safe and coordinated operation of multi-robot systems is critical to their successful deployment. However, operation environments often induce severe communication outages that make information exchange between robots imperfect and delayed [2], [6], [7].

## II. System Model and Setup
### Robot Dynamics
We consider a multi-robot system where R robots fulfill a control task. The dynamics of robot i are given by:
$$\dot{x}_i(t) = f(x_i(t), u_i(t))$$
where $x_i(t)$ denotes the state (e.g., position $p_i$) and $u_i(t)$ the control action.

### Information Exchange
Robots communicate through a wireless channel with radius $R_c$. Under realistic conditions, information exchange involves delays. The information received by robot $i$ from robot $j$ until time $t$ is denoted as $\mathcal{I}_{i\leftarrow j}(t)$.

## III. Distributed Control Barrier Functions (CBF)
The paper proposes a **distributed Control Barrier Function** $h(w_i)$ where $w_i$ collects relative state configurations between robot $i$ and its safety-relevant neighbors. A distributed CBF ensures safety if:
1. $h(w_i) \geq 0$ iff the robot is in a safe state.
2. There exists a control action such that the time derivative $\dot{h}$ satisfies a decay condition relative to $h$.

## IV. Learning-Based Architecture
The authors utilize **Graph Neural Networks (GNNs)** to learn safe distributed controllers ($\pi_{\xi}$) and the CBF ($h_{\theta}$). For delayed environments, a **predictor** ($\lambda_{\zeta}$) is introduced to estimate the current state of neighbors based on received past messages and Age-of-Information (AoI).

## V. Experimental Results
The approach was tested using two dynamical models: **Single Integrator** and **Dubins Car**.

### Table I: Parameters and hyperparameters used with single integrator model.
| exp. | $c_{del}$ | $w_S$ | $w_{Su}$ | $w_{der}$ | $\alpha$ | $\epsilon$ | $w_{contr}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| exp. 1 | 0.5 | 1 | 1 | 0.7 | 1 | 0.02 | 0.001 |
| exp. 2 | 0.8 | 0.9 | 1 | 0.7 | 1 | 0.02 | 0.0005 |

### Table II: Parameters and hyperparameters used with Dubins car model.
| $w_S$ | $w_{Su}$ | $w_{der}$ | $\alpha$ | $\epsilon$ | $w_{contr}$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 1.2 | 0.5 | 1 | 0.02 | 0.001 |

## VI. Conclusion
The research demonstrates that communication delays severely disrupt safety in multi-robot systems if not accounted for. The proposed predictor-based GNN architecture restores safety by leveraging Age-of-Information to handle stale data, providing a scalable solution for autonomous coordination in extreme environments.
