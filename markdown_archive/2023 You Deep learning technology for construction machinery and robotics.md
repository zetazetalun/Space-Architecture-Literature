# Deep learning technology for construction machinery and robotics

**Authors:** Ke You, Cheng Zhou, Lieyun Ding
**Journal:** Automation in Construction 150 (2023) 104852
**DOI:** https://doi.org/10.1016/j.autcon.2023.104852

## Abstract
Construction machinery and robots are essential equipment for major infrastructure. The application of deep learning technology can improve construction quality and alleviate labor shortages. This systematic review analyzes deep learning technology from four perspectives: (1) perception; (2) navigation and planning; (3) control; and (4) human-robot interaction. Challenges identified include dataset limitation, lack of interpretability, and insufficient autonomous intelligence. Future outlooks include generative deep learning and extraterrestrial construction.

## 1. Introduction
Autonomous control of unmanned construction machinery has broad application prospects for upcoming lunar and Mars construction due to the difficulty of long-distance real-time communication. Deep learning (DL) algorithms such as DCNN, ResNets, LSTM, and DRL are robust and adaptable, making them suitable for unstructured and unpredictable construction scenarios.

## 2. Research Approach and Scientometric Analysis
The review identifies application hotspots using keyword co-concurrence and cluster-based topic analysis. Key machinery types include excavators, loaders, shield machines (TBM), and 3D printer extruders.

### Table 1: Five high-frequency countries/regions
| No. | Count | Percentage (%) | Countries/Regions |
|---|---|---|---|
| 1 | 46 | 33.6 | USA |
| 2 | 41 | 19.1 | China |
| 3 | 12 | 13.6 | England |
| 4 | 9 | 11.8 | Australia |
| 5 | 8 | 7.3 | Switzerland |

## 3. Perception
- **Vision-based:** Uses CNNs for object detection and semantic segmentation. Mentions crater and boulder detection on the lunar surface (Hashimoto et al.).
- **LiDAR-based:** High-precision 3D construction maps and object detection from point clouds.
- **Fusion method:** Combining image and point cloud data for improved accuracy and distance sensing.

## 4. Navigation and Planning
- **Localization/Pose Estimation:** Uses RTK-GPS, IMU, depth cameras, and LiDAR.
- **Autonomous Navigation:** Fusing heterogeneous sensors to predict machine attitude (e.g., shield machines) and avoid obstacles.
- **Motion Planning:** Learning from demonstration (LfD) and Deep Reinforcement Learning (DRL) for path optimization.

## 5. Control
- **Classical Schemes:** Hierarchical optimization but weak generalization.
- **Data-driven:** Using CNNs to predict environmental parameters and LSTMs for time-series control.
- **Deep Reinforcement Learning (DRL):** Enables machines to learn driving and bucket control autonomously without manual modeling of nonlinear dynamics.

## 6. Human-Robot Interaction (HRI)
- **Teleoperation:** Enhanced by 5G, VR, and force feedback. Mentions Brain-Computer Interfaces (BCI) for hands-free control.
- **Imitation Learning:** Reusing expert knowledge to train autonomous models.
- **Collective Construction:** Swarm robotics and aerial additive manufacturing (AM) inspired by biological nests (termites/bees).

## 7. Discussion
### 7.1 Challenges Applied to Practice
- **Dataset Limitation:** High-quality, multidimensional heterogeneous data is scarce.
- **Interpretability:** DL models are often "black boxes," hindering optimization and safety verification.
- **Autonomous Intelligence:** Difficulty in designing reward functions and low sample efficiency.

### 7.2 Future Outlook: Extraterrestrial Construction
Planetary exploration requires in-situ construction under different gravity, atmospheric, and radiation conditions. Deep learning will play a major role in reconstructing machinery dynamics and control methods for Lunar and Martian environments.

## 8. Conclusions
Deep learning is robust for unstructured environments. Future developments focus on expert knowledge datasets, trustworthy AI, and extraterrestrial construction (e.g., Xuanwu lunar habitation).